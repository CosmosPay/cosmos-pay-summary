# Changelog general — Cosmos Pay

Cambios hechos en toda la organización `CosmosPay` desde el **sábado 12/09/2026 a las 15:00 (hora Argentina)** hasta el **27/09/2026**. Está agrupado por tema y por repositorio. El detalle commit por commit está en el [README](README.md).

## Versiones publicadas

| Repositorio | Primera del período | Última del período | Releases estables |
|---|---|---|---|
| CosmosPay-Wallet | v1.8.0-dev.79 | v1.11.0-dev.97 | v1.8.0, v1.9.0, v1.10.0 |
| CosmosPay-Community-Server | v1.1.1 | v1.3.1 | v1.1.1, v1.2.0, v1.3.0, v1.3.1 |
| CosmosPay-Developer-Platform | v0.2.2 | v0.4.1 | v0.2.2, v0.3.0, v0.4.0, v0.4.1 |
| CosmosJS_SDK | v2.0.0 | v2.0.0 | v2.0.0 (cambio incompatible) |

---

## Autenticación de la wallet, recuperación y passkeys

### Added
- **Wallet:** flujo de inicio de sesión social con verificación por email y código de acceso.
- **Wallet:** nueva interfaz de métodos de inicio de sesión (reemplaza el componente social anterior) y estilos de recuperación de cuenta y onboarding.
- **Wallet:** el backend de inicio de sesión se elige con un flag, sin reescribir el cliente.
- **Wallet:** recuperación de cuenta con tokens de identidad y códigos por email, más manejo del token de sesión en el inicio de sesión y la recuperación.
- **Wallet:** desbloqueo con passkey y comandos para crear, obtener y consultar el estado de las passkeys.
- **Community Server:** el propio servidor sirve el inicio de sesión de la wallet (`wallet-auth`), con Authentik como proveedor OIDC.
- **Community Server:** manejo de emails no verificados y `max_age` en el flujo de Authentik.
- **Community Server:** backups v3 con espacios para contraseña y passkey.
- **Community Server:** esquema de seguridad SEP-30 en las rutas de cuenta del OpenAPI.
- **Developer Platform:** flujo OAuth de inicio de sesión de la wallet, SEP-10 (Stellar Web Authentication) y SEP-30 (recuperación de cuentas).
- **Developer Platform:** endpoint de códigos de recuperación, paginación del listado de cuentas y endpoints de consola de `wallet-auth` bajo `api/wallet/`.

### Changed
- **Community Server:** se corrigió el contrato para que coincida con lo que la wallet envía realmente, se envía el nombre visible al servicio de alta y los endpoints de consola quedan dentro del espacio `wallet`.
- **Developer Platform:** se quitaron los tests viejos de SEP-10 y recuperación y se agregaron tests unitarios de `wallet-auth`.

## Pagos, swaps y rampas (BlindPay)

### Added
- **Wallet:** manejo y validación de comisiones en swaps (PR #73), registro de activos y mejoras del firmante web (PR #74).
- **Community Server:** servicio `SignedTransactionRelay` para retransmitir transacciones firmadas y manejo de envelopes de Stellar guardados.
- **Community Server:** tests end-to-end del `txHash` de payment intents y tests unitarios de los webhooks de BlindPay.
- **Wallet (en revisión):** acciones de rampas BlindPay visibles en la pantalla de inicio, con lenguaje de "fondeo bancario" (PR #78).
- **Community Server (en revisión):** rechazo de cotizaciones de BlindPay vencidas (PR #92) y ejecución de pagos idempotente (PR #93).
- **Community Server (en revisión):** RFQs privadas no custodiales con Sub Rosa (PR #91, contribución externa).

### Changed
- **Community Server:** `$transaction` se reemplazó por `Promise.all` en algunos flujos, por rendimiento.

## Rendimiento (Earn) y DeFindex — en revisión

- **Wallet:** directorio de protocolos de rendimiento en "Ganar" (PR #80), ruta web directa de Earn (PR #79) e integración de bóvedas DeFindex con montos legibles (PR #81).
- **Community Server:** API gateway de DeFindex (PR #94).

## Autorización, receptores y seguridad de la API

### Changed
- **Community Server y Developer Platform:** el modelo de autorización pasó a verificación desde la consola. Se eliminaron las credenciales y secretos de la API de administración y su sección en `.env.example` (Community Server PR #86, Developer Platform PRs #43 y #44).
- **Community Server:** mejor verificación de propiedad de wallets y de su alta; la actualización de receptores exige una clave con permisos elevados.
- **Developer Platform y SDK:** `expected_version` en la aprobación de receptores y campos `dossierVersion` y `reviewedVersion` en el modelo `Receiver`.
- **CosmosJS_SDK v2.0.0 (incompatible):** sigue los cambios del contrato de seguridad de la API de pagos, agrega `SwapManager` y cambia la licencia a Apache-2.0.

### Added
- **Community Server:** mejoras de sesión OAuth y registro de usuarios con Pollar.
- **CosmosJS_SDK:** `AliasManager` y `AssetManager` para alias y registro de activos (en `dev`, sin release todavía).

## Documentación, OpenAPI y herramientas para desarrolladores

### Added
- **Community Server:** tests de Swagger y mejor documentación OpenAPI.
- **Developer Platform:** definiciones de seguridad y rutas públicas en el spec OpenAPI; documentación de `AliasManager`, `AssetManager`, `Client` y `PaymentIntentManager`; descripciones de `wallet-auth` más claras.
- **Wallet:** script de sincronización del OpenAPI y tests de contrato del gateway.
- **Wallet, Community Server y Developer Platform:** archivos `AGENTS.md` con las convenciones de cada repositorio.
- **CosmosPay-Skill:** nuevo repositorio con la skill de integración de Cosmos Pay para agentes (PR #1), también documentada en la Developer Platform (skills.stellar.org).

### Changed
- **Developer Platform:** el buscador de la documentación pasó de Orama a ZBSearch.
- **Developer Platform:** los imports de Zod usan la versión extendida de la librería OpenAPI.

## Rebranding a la nueva identidad de Cosmos

### Changed
- **Wallet:** nueva identidad visual; el nombre en la bienvenida pasó a ser un lockup SVG.
- **Developer Platform:** tokens, tipografía y logo nuevos. El landing se rehízo con los paneles y titulares del deck, pasó por dos rondas de revisión, pone la wallet al frente y ya no tiene restos de la marca vieja.
- **Cosmos-frontend:** paleta, tipografía Open Sauce One y logo SVG; header, buscador, footer y mockup con la marca nueva; landing de siete secciones según el deck; tres rondas de correcciones; sección /06 con la wallet y la plataforma; personaje oficial de la agencia versionado; bandera argentina para el castellano.

## Infraestructura, builds y despliegues

### Added
- **Wallet:** íconos de desarrollo para builds locales en todas las plataformas y paquetes de Android necesarios para que los builds compilen.
- **Wallet:** mejor manejo de errores en el proxy de desarrollo.

### Changed
- **Cosmos-frontend:** nuevo backend `api.cosmosapp.lat` y host `cosmosapp.lat`, con 4 deploys a producción.
- **cosmos-backend:** snapshot-v1 promovido a `main` (PR #3).
- **Wallet:** 3 deploys de la web a GitHub Pages.

### Fixed
- **cosmos-backend:** las URLs de imágenes subidas se generan con https y `multer` se actualizó a 2.3.0 (PR #2).
- **Cosmos-frontend:** un gráfico roto ya no deja `/panel` en blanco.

## Dependencias

- Actualizaciones de Dependabot mergeadas en Wallet (#76), Community Server (#90), Developer Platform (#41, #42) y SDK (#10).
- Pendientes de revisión: `@stellar/stellar-sdk` 16.3.0 → 17.1.0 (Wallet #77), `@astrojs/react` 7.0.0 (Wallet #83), `dotenv` 18.0.3 (Community Server #96) y grupos de actualizaciones menores (Wallet #82, Community Server #95, Developer Platform #50 y #51, SDK #12).

## Estado de CI

- 187 ejecuciones de workflows en el período, entre CI, releases, deploys y Dependabot.
- Fallidas: 20 de CI (Wallet 7, Community Server 6, Developer Platform 7) y 6 de releases (Wallet 3, Developer Platform 2, SDK 1). Hubo 7 cancelaciones. El detalle de cada una está en el README.
