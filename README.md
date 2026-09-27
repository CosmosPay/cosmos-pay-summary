# Cosmos Pay — Resumen de actividad

Registro de todo lo hecho en la organización [`CosmosPay`](https://github.com/CosmosPay) desde el **sábado 12/09/2026 a las 15:00 (hora Argentina, UTC-3)** hasta el **27/09/2026 10:30 (ART)**.

Todas las horas están en hora Argentina (UTC-3). El changelog general, agrupado por tema, está en [CHANGELOG.md](CHANGELOG.md).

## Resumen

| Repositorio | Commits | PRs | Releases | Builds | Deploys |
|---|---:|---:|---:|---:|---:|
| [CosmosPay-Wallet](#cosmospay-wallet) | 35 | 11 | 18 | 65 | 3 |
| [CosmosPay-Community-Server](#cosmospay-community-server) | 38 | 11 | 4 | 42 | 0 |
| [CosmosPay-Developer-Platform](#cosmospay-developer-platform) | 45 | 11 | 4 | 55 | 0 |
| [CosmosJS_SDK](#cosmosjs_sdk) | 9 | 4 | 1 | 21 | 2 |
| [Cosmos-frontend](#cosmos-frontend) | 14 | 0 | 0 | 4 | 4 |
| [cosmos-backend](#cosmos-backend) | 5 | 2 | 0 | 0 | 0 |
| [CosmosPay-Skill](#cosmospay-skill) | 3 | 1 | 0 | 0 | 0 |
| **Total** | **149** | **40** | **27** | **187** | **9** |

> Los builds incluyen CI, releases, deploys y las ejecuciones automáticas de Dependabot. Los commits se cuentan una sola vez aunque estén en varias ramas.

---

## CosmosPay-Wallet

Wallet (extensión, web y apps) — [https://github.com/CosmosPay/CosmosPay-Wallet](https://github.com/CosmosPay/CosmosPay-Wallet)

### Commits (35)

| Fecha | Autor | Commit | Mensaje |
|---|---|---|---|
| 15/09 19:57 | Emanuel250YT | [`c9f4933`](https://github.com/CosmosPay/CosmosPay-Wallet/commit/c9f493323651dc0b88026bd73bb4130792325d39) | feat: implement social login flow with email verification and access code handling |
| 16/09 12:27 | Emanuel250YT | [`ede25aa`](https://github.com/CosmosPay/CosmosPay-Wallet/commit/ede25aa7484915939ed183c791e138219d2981a8) | feat: update Android setup to include necessary packages for successful builds |
| 16/09 12:51 | Emanuel250YT | [`80c1f57`](https://github.com/CosmosPay/CosmosPay-Wallet/commit/80c1f57a6fec664f912221614a5daf10c4a1a015) | Merge pull request #73 from CosmosPay/dev |
| 16/09 12:54 | github-actions[bot] | [`20df981`](https://github.com/CosmosPay/CosmosPay-Wallet/commit/20df9813a615d900f6fd7e1186396c4341386660) | chore(release): v1.8.0 [skip ci] |
| 16/09 12:56 | Emanuel250YT | [`4915101`](https://github.com/CosmosPay/CosmosPay-Wallet/commit/49151015d36bea792a3c7564cd004faa4a0b423e) | Merge pull request #74 from CosmosPay/main |
| 18/09 20:26 | leocagli | [`5b1958a`](https://github.com/CosmosPay/CosmosPay-Wallet/commit/5b1958a567562bd3e751f8387bd276e58cd5d267) | feat(marca): la wallet pasa a la identidad nueva de Cosmos |
| 18/09 20:28 | leocagli | [`1c2f33e`](https://github.com/CosmosPay/CosmosPay-Wallet/commit/1c2f33e9068676d23aeed9e1bfa24545a42f87a0) | feat(marca): el nombre en la bienvenida va como lockup SVG, no tipeado |
| 18/09 21:38 | github-actions[bot] | [`936610e`](https://github.com/CosmosPay/CosmosPay-Wallet/commit/936610e211dcd1eb998bd706a14c6aa7f5d9d4d6) | chore(release): v1.9.0 [skip ci] |
| 19/09 10:38 | Emanuel250YT | [`9c7868b`](https://github.com/CosmosPay/CosmosPay-Wallet/commit/9c7868be1b4f6d6958ac22d35393827d2fe8c402) | Merge pull request #75 from CosmosPay/main |
| 19/09 12:00 | Emanuel250YT | [`cb972dc`](https://github.com/CosmosPay/CosmosPay-Wallet/commit/cb972dc6a58b43cf3a217cfb961ada11d683b09d) | feat(icon): implement dev icon handling for local builds across platforms |
| 19/09 17:13 | dependabot[bot] | [`6fbef9c`](https://github.com/CosmosPay/CosmosPay-Wallet/commit/6fbef9cd4d405ae9c489bb3bf3c0d833edd9ccb3) | chore: bump the minor-and-patch group with 3 updates |
| 19/09 21:19 | Emanuel250YT | [`b0bfe48`](https://github.com/CosmosPay/CosmosPay-Wallet/commit/b0bfe48715ca94e9a2a6ce790fba7e8a4727d298) | feat(social-login): eliminar componente y estilos de inicio de sesión social |
| 19/09 21:19 | Emanuel250YT | [`db9314a`](https://github.com/CosmosPay/CosmosPay-Wallet/commit/db9314ac8454cc9e64e7b1887ff9158b9f49a4a2) | feat: implement sign-in methods UI and functionality |
| 19/09 22:57 | Emanuel250YT | [`930b7e3`](https://github.com/CosmosPay/CosmosPay-Wallet/commit/930b7e3e2e39e79782c6fbd36f6227b8c2d64a25) | Add styles for account recovery and onboarding features |
| 21/09 11:04 | Emanuel250YT | [`e679836`](https://github.com/CosmosPay/CosmosPay-Wallet/commit/e6798366182016fbaefdc3ba04cad558509b7596) | Merge pull request #76 from CosmosPay/dependabot/npm_and_yarn/minor-and-patch-ed7065fa84 |
| 21/09 11:07 | github-actions[bot] | [`0d70e63`](https://github.com/CosmosPay/CosmosPay-Wallet/commit/0d70e63690d31f7badfccb13c3f6dbb3aa9f2c44) | chore(release): v1.10.0 [skip ci] |
| 21/09 11:09 | dependabot[bot] | [`35db486`](https://github.com/CosmosPay/CosmosPay-Wallet/commit/35db486ac3be0a75e02c9032bb0df8337c3cc14b) | chore: bump @stellar/stellar-sdk from 16.3.0 to 17.1.0 |
| 22/09 00:14 | root | [`de6570e`](https://github.com/CosmosPay/CosmosPay-Wallet/commit/de6570e8083a77d6404e5f72d30490c1317ac54f) | feat(wallet): surface BlindPay ramps on home |
| 22/09 00:15 | root | [`2991139`](https://github.com/CosmosPay/CosmosPay-Wallet/commit/2991139f320c1aaa3fc362a17b78fbb9092d108e) | fix(wallet): add explicit ramps action |
| 22/09 00:21 | root | [`c6e3bff`](https://github.com/CosmosPay/CosmosPay-Wallet/commit/c6e3bffba0a9b39fc99fc2964450674e8eadaafc) | fix(wallet): use bank funding language for ramps |
| 22/09 00:23 | root | [`d57d36b`](https://github.com/CosmosPay/CosmosPay-Wallet/commit/d57d36baad364a24a2f523bd952f867d6335f290) | fix(web): add direct earn route |
| 22/09 00:33 | root | [`ce4d470`](https://github.com/CosmosPay/CosmosPay-Wallet/commit/ce4d470b27b00eb8c576b0ba85197f3cdb03820b) | feat: add yield protocol directory |
| 22/09 13:08 | leocagli | [`e3e1a4a`](https://github.com/CosmosPay/CosmosPay-Wallet/commit/e3e1a4aedaa6ee3a4478298c79f0f5021002e15c) | feat: integrate DeFindex vaults in wallet |
| 22/09 13:14 | leocagli | [`4c06df1`](https://github.com/CosmosPay/CosmosPay-Wallet/commit/4c06df19a5581196e3e383dfd1c14d261dac22a4) | fix: accept human-readable DeFindex amounts |
| 24/09 12:30 | Emanuel250YT | [`c4d07e8`](https://github.com/CosmosPay/CosmosPay-Wallet/commit/c4d07e8f0fcc4b908f1a14b4927de31335adec03) | Implement feature X to enhance user experience and fix bug Y in module Z |
| 24/09 16:10 | Emanuel250YT | [`fe7e293`](https://github.com/CosmosPay/CosmosPay-Wallet/commit/fe7e29332a7f04200483d47a26654b29d7dbdb50) | feat(proxy): mejorar manejo de errores en el proxy de desarrollo y optimizar dependencias |
| 24/09 17:15 | Emanuel250YT | [`3006f4e`](https://github.com/CosmosPay/CosmosPay-Wallet/commit/3006f4e8087ee7e676c324f5de94fa875944c03c) | feat: enhance SEP-10 and recovery features |
| 25/09 18:57 | Emanuel250YT | [`fc61913`](https://github.com/CosmosPay/CosmosPay-Wallet/commit/fc61913c3fbf5af0e874e4d298702ff35af10fb6) | feat(signin): switch the sign-in backend with a flag, not a rewrite |
| 25/09 20:44 | Emanuel250YT | [`4151b8b`](https://github.com/CosmosPay/CosmosPay-Wallet/commit/4151b8bdd9abba79dc2c44d2aa829e42262e0862) | feat: implement recovery process with identity tokens and email codes |
| 25/09 21:00 | Emanuel250YT | [`e177362`](https://github.com/CosmosPay/CosmosPay-Wallet/commit/e1773621bdea054b2f1b04856cb5057bff58e1f7) | feat: add OpenAPI sync script and gateway contract tests |
| 26/09 17:13 | dependabot[bot] | [`281320b`](https://github.com/CosmosPay/CosmosPay-Wallet/commit/281320b106fe04a82999665b20f02071bd15480b) | chore: bump the minor-and-patch group with 2 updates |
| 26/09 17:13 | dependabot[bot] | [`fc3c7a8`](https://github.com/CosmosPay/CosmosPay-Wallet/commit/fc3c7a852c43e2e8034856ae4634e46406f41d65) | chore: bump @astrojs/react from 6.0.6 to 7.0.0 |
| 26/09 22:14 | Emanuel250YT | [`16aeff7`](https://github.com/CosmosPay/CosmosPay-Wallet/commit/16aeff77e74b2fee1a445515ae91328a9b2dddd8) | feat: agregar manejo de token de sesión en el proceso de inicio de sesión y recuperación |
| 27/09 00:09 | Emanuel250YT | [`075c23b`](https://github.com/CosmosPay/CosmosPay-Wallet/commit/075c23ba41e0aaa1647a6d8d3d5b478278f833ae) | feat: implement passkey unlock functionality |
| 27/09 09:56 | Emanuel250YT | [`0dc2fcd`](https://github.com/CosmosPay/CosmosPay-Wallet/commit/0dc2fcdc46a6d39b5195b8d7254769c48d42be86) | feat(passkeys): implement passkey creation, retrieval, and status commands |

### Pull requests (11)

| # | Abierto | Mergeado | Estado | Autor | Ramas | Título |
|---|---|---|---|---|---|---|
| [#73](https://github.com/CosmosPay/CosmosPay-Wallet/pull/73) | 13/09 13:21 | 16/09 12:51 | mergeado | Emanuel250YT | `dev` → `main` | Implement commission handling and validation for swaps |
| [#74](https://github.com/CosmosPay/CosmosPay-Wallet/pull/74) | 16/09 12:56 | 16/09 12:56 | mergeado | Emanuel250YT | `main` → `dev` | Enhance web signer, asset registry, and commission handling |
| [#75](https://github.com/CosmosPay/CosmosPay-Wallet/pull/75) | 19/09 10:37 | 19/09 10:38 | mergeado | Emanuel250YT | `main` → `dev` | Leos integration |
| [#76](https://github.com/CosmosPay/CosmosPay-Wallet/pull/76) | 19/09 17:13 | 21/09 11:04 | mergeado | dependabot[bot] | `dependabot/npm_and_yarn/minor-and-patch-ed7065fa84` → `main` | chore: bump the minor-and-patch group with 3 updates |
| [#77](https://github.com/CosmosPay/CosmosPay-Wallet/pull/77) | 19/09 17:13 | — | abierto | dependabot[bot] | `dependabot/npm_and_yarn/stellar/stellar-sdk-17.1.0` → `main` | chore: bump @stellar/stellar-sdk from 16.3.0 to 17.1.0 |
| [#78](https://github.com/CosmosPay/CosmosPay-Wallet/pull/78) | 22/09 00:15 | — | abierto | leocagli | `codex/visible-modular-ramps` → `main` | Surface BlindPay on/off-ramp actions in the wallet |
| [#79](https://github.com/CosmosPay/CosmosPay-Wallet/pull/79) | 22/09 00:23 | — | abierto | leocagli | `codex/web-earn-route` → `main` | Fix the web Earn route |
| [#80](https://github.com/CosmosPay/CosmosPay-Wallet/pull/80) | 22/09 00:34 | — | abierto | leocagli | `codex/earn-protocol-directory` → `main` | feat: mostrar protocolos de rendimiento en Ganar |
| [#81](https://github.com/CosmosPay/CosmosPay-Wallet/pull/81) | 22/09 13:09 | — | abierto | leocagli | `codex/defindex-wallet-integration` → `codex/earn-protocol-directory` | feat: integrate DeFindex vaults in wallet |
| [#82](https://github.com/CosmosPay/CosmosPay-Wallet/pull/82) | 26/09 17:13 | — | abierto | dependabot[bot] | `dependabot/npm_and_yarn/minor-and-patch-522a3e4b7e` → `main` | chore: bump the minor-and-patch group with 2 updates |
| [#83](https://github.com/CosmosPay/CosmosPay-Wallet/pull/83) | 26/09 17:13 | — | abierto | dependabot[bot] | `dependabot/npm_and_yarn/astrojs/react-7.0.0` → `main` | chore: bump @astrojs/react from 6.0.6 to 7.0.0 |

### Releases (18)

| Fecha | Tag | Nombre |
|---|---|---|
| 15/09 19:57 | [`v1.8.0-dev.79`](https://github.com/CosmosPay/CosmosPay-Wallet/releases/tag/v1.8.0-dev.79) | Cosmos Pay v1.8.0-dev.79 |
| 16/09 12:27 | [`v1.8.0-dev.80`](https://github.com/CosmosPay/CosmosPay-Wallet/releases/tag/v1.8.0-dev.80) | Cosmos Pay v1.8.0-dev.80 |
| 16/09 12:54 | [`v1.8.0`](https://github.com/CosmosPay/CosmosPay-Wallet/releases/tag/v1.8.0) | Cosmos Pay v1.8.0 |
| 16/09 12:56 | [`v1.8.1-dev.82`](https://github.com/CosmosPay/CosmosPay-Wallet/releases/tag/v1.8.1-dev.82) | Cosmos Pay v1.8.1-dev.82 |
| 18/09 21:38 | [`v1.9.0`](https://github.com/CosmosPay/CosmosPay-Wallet/releases/tag/v1.9.0) | Cosmos Pay v1.9.0 |
| 19/09 10:38 | [`v1.9.1-dev.84`](https://github.com/CosmosPay/CosmosPay-Wallet/releases/tag/v1.9.1-dev.84) | Cosmos Pay v1.9.1-dev.84 |
| 19/09 12:00 | [`v1.10.0-dev.85`](https://github.com/CosmosPay/CosmosPay-Wallet/releases/tag/v1.10.0-dev.85) | Cosmos Pay v1.10.0-dev.85 |
| 19/09 21:19 | [`v1.10.0-dev.86`](https://github.com/CosmosPay/CosmosPay-Wallet/releases/tag/v1.10.0-dev.86) | Cosmos Pay v1.10.0-dev.86 |
| 19/09 22:57 | [`v1.10.0-dev.87`](https://github.com/CosmosPay/CosmosPay-Wallet/releases/tag/v1.10.0-dev.87) | Cosmos Pay v1.10.0-dev.87 |
| 21/09 11:07 | [`v1.10.0`](https://github.com/CosmosPay/CosmosPay-Wallet/releases/tag/v1.10.0) | Cosmos Pay v1.10.0 |
| 24/09 12:30 | [`v1.11.0-dev.89`](https://github.com/CosmosPay/CosmosPay-Wallet/releases/tag/v1.11.0-dev.89) | Cosmos Pay v1.11.0-dev.89 |
| 24/09 16:10 | [`v1.11.0-dev.90`](https://github.com/CosmosPay/CosmosPay-Wallet/releases/tag/v1.11.0-dev.90) | Cosmos Pay v1.11.0-dev.90 |
| 24/09 17:15 | [`v1.11.0-dev.91`](https://github.com/CosmosPay/CosmosPay-Wallet/releases/tag/v1.11.0-dev.91) | Cosmos Pay v1.11.0-dev.91 |
| 25/09 18:57 | [`v1.11.0-dev.92`](https://github.com/CosmosPay/CosmosPay-Wallet/releases/tag/v1.11.0-dev.92) | Cosmos Pay v1.11.0-dev.92 |
| 25/09 20:44 | [`v1.11.0-dev.93`](https://github.com/CosmosPay/CosmosPay-Wallet/releases/tag/v1.11.0-dev.93) | Cosmos Pay v1.11.0-dev.93 |
| 25/09 21:00 | [`v1.11.0-dev.94`](https://github.com/CosmosPay/CosmosPay-Wallet/releases/tag/v1.11.0-dev.94) | Cosmos Pay v1.11.0-dev.94 |
| 27/09 00:09 | [`v1.11.0-dev.96`](https://github.com/CosmosPay/CosmosPay-Wallet/releases/tag/v1.11.0-dev.96) | Cosmos Pay v1.11.0-dev.96 |
| 27/09 09:56 | [`v1.11.0-dev.97`](https://github.com/CosmosPay/CosmosPay-Wallet/releases/tag/v1.11.0-dev.97) | Cosmos Pay v1.11.0-dev.97 |

### Builds (65: 51 ok, 10 fallidos, 4 cancelados)

| Fecha | Workflow | Rama | Evento | Commit | Resultado |
|---|---|---|---|---|---|
| 13/09 13:22 | [CI](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/34768361256) | `dev` | pull_request | `2957822` | ✅ ok |
| 15/09 19:57 | [CI](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/35033457461) | `dev` | push | `c9f4933` | ❌ falló |
| 15/09 19:57 | [Release (extension + apps)](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/35033457494) | `dev` | push | `c9f4933` | ❌ falló |
| 15/09 19:57 | [CI](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/35033462484) | `dev` | pull_request | `c9f4933` | ❌ falló |
| 16/09 12:27 | [CI](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/35115436434) | `dev` | push | `ede25aa` | ✅ ok |
| 16/09 12:27 | [Release (extension + apps)](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/35115436339) | `dev` | push | `ede25aa` | ✅ ok |
| 16/09 12:27 | [CI](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/35115441257) | `dev` | pull_request | `ede25aa` | ✅ ok |
| 16/09 12:51 | [Deploy web (GitHub Pages)](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/35118154220) | `main` | push | `80c1f57` | ✅ ok |
| 16/09 12:51 | [CI](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/35118154737) | `main` | push | `80c1f57` | ✅ ok |
| 16/09 12:51 | [Release (extension + apps)](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/35118154847) | `main` | push | `80c1f57` | ✅ ok |
| 16/09 12:56 | [CI](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/35118647818) | `dev` | push | `4915101` | ✅ ok |
| 16/09 12:56 | [Release (extension + apps)](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/35118648097) | `dev` | push | `4915101` | ✅ ok |
| 18/09 21:36 | [CI](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/35409929478) | `main` | push | `1c2f33e` | ✅ ok |
| 18/09 21:36 | [Release (extension + apps)](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/35409929462) | `main` | push | `1c2f33e` | ✅ ok |
| 18/09 21:36 | [Deploy web (GitHub Pages)](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/35409929376) | `main` | push | `1c2f33e` | ✅ ok |
| 19/09 10:38 | [CI](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/35446348209) | `dev` | push | `9c7868b` | ✅ ok |
| 19/09 10:38 | [Release (extension + apps)](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/35446348228) | `dev` | push | `9c7868b` | ✅ ok |
| 19/09 12:00 | [CI](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/35450424826) | `dev` | push | `cb972dc` | ✅ ok |
| 19/09 12:00 | [Release (extension + apps)](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/35450425057) | `dev` | push | `cb972dc` | ✅ ok |
| 19/09 17:13 | [CI](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/35466714351) | `dependabot/npm_and_yarn/minor-and-patch-ed7065fa84` | pull_request | `6fbef9c` | ✅ ok |
| 19/09 17:13 | [CI](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/35466720055) | `dependabot/npm_and_yarn/stellar/stellar-sdk-17.1.0` | pull_request | `43f3ccd` | ❌ falló |
| 19/09 21:19 | [CI](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/35478486714) | `dev` | push | `db9314a` | ✅ ok |
| 19/09 21:19 | [Release (extension + apps)](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/35478486750) | `dev` | push | `db9314a` | ✅ ok |
| 19/09 22:57 | [CI](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/35482716226) | `dev` | push | `930b7e3` | ✅ ok |
| 19/09 22:57 | [Release (extension + apps)](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/35482716244) | `dev` | push | `930b7e3` | ✅ ok |
| 21/09 11:04 | [Deploy web (GitHub Pages)](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/35609717191) | `main` | push | `e679836` | ✅ ok |
| 21/09 11:04 | [CI](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/35609717610) | `main` | push | `e679836` | ✅ ok |
| 21/09 11:04 | [Release (extension + apps)](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/35609717871) | `main` | push | `e679836` | ✅ ok |
| 21/09 11:06 | [CI](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/35609963468) | `dependabot/npm_and_yarn/stellar/stellar-sdk-17.1.0` | pull_request | `c5bf56e` | ⚪ cancelado |
| 21/09 11:09 | [CI](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/35610266468) | `dependabot/npm_and_yarn/stellar/stellar-sdk-17.1.0` | pull_request | `35db486` | ❌ falló |
| 22/09 00:15 | [CI](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/35682460155) | `codex/visible-modular-ramps` | pull_request | `de6570e` | ⚪ cancelado |
| 22/09 00:15 | [CI](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/35682502563) | `codex/visible-modular-ramps` | pull_request | `2991139` | ⚪ cancelado |
| 22/09 00:21 | [CI](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/35682856654) | `codex/visible-modular-ramps` | pull_request | `c6e3bff` | ✅ ok |
| 22/09 00:23 | [CI](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/35682969291) | `codex/web-earn-route` | pull_request | `d57d36b` | ✅ ok |
| 22/09 00:34 | [CI](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/35683642849) | `codex/earn-protocol-directory` | pull_request | `ce4d470` | ✅ ok |
| 22/09 13:09 | [CI](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/35752195645) | `codex/defindex-wallet-integration` | pull_request | `e3e1a4a` | ⚪ cancelado |
| 22/09 13:14 | [CI](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/35752774549) | `codex/defindex-wallet-integration` | pull_request | `4c06df1` | ✅ ok |
| 24/09 12:31 | [CI](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/36020764968) | `dev` | push | `c4d07e8` | ✅ ok |
| 24/09 12:31 | [Release (extension + apps)](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/36020764860) | `dev` | push | `c4d07e8` | ✅ ok |
| 24/09 16:10 | [Release (extension + apps)](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/36046371062) | `dev` | push | `fe7e293` | ❌ falló |
| 24/09 16:10 | [CI](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/36046370869) | `dev` | push | `fe7e293` | ✅ ok |
| 24/09 17:15 | [Release (extension + apps)](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/36053632856) | `dev` | push | `3006f4e` | ✅ ok |
| 24/09 17:15 | [CI](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/36053632882) | `dev` | push | `3006f4e` | ✅ ok |
| 25/09 19:27 | [CI](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/36196802639) | `dev` | push | `fc61913` | ✅ ok |
| 25/09 19:27 | [Release (extension + apps)](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/36196802565) | `dev` | push | `fc61913` | ✅ ok |
| 25/09 20:44 | [CI](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/36202173223) | `dev` | push | `4151b8b` | ✅ ok |
| 25/09 20:44 | [Release (extension + apps)](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/36202173213) | `dev` | push | `4151b8b` | ✅ ok |
| 25/09 21:00 | [Release (extension + apps)](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/36203167074) | `dev` | push | `e177362` | ✅ ok |
| 25/09 21:00 | [CI](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/36203167121) | `dev` | push | `e177362` | ✅ ok |
| 26/09 17:13 | [CI](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/36268745659) | `dependabot/npm_and_yarn/minor-and-patch-522a3e4b7e` | pull_request | `281320b` | ✅ ok |
| 26/09 17:13 | [CI](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/36268761669) | `dependabot/npm_and_yarn/astrojs/react-7.0.0` | pull_request | `fc3c7a8` | ✅ ok |
| 26/09 22:14 | [Release (extension + apps)](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/36284918213) | `dev` | push | `16aeff7` | ❌ falló |
| 26/09 22:14 | [CI](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/36284918220) | `dev` | push | `16aeff7` | ❌ falló |
| 27/09 00:09 | [CI](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/36290592203) | `dev` | push | `075c23b` | ❌ falló |
| 27/09 00:09 | [Release (extension + apps)](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/36290592140) | `dev` | push | `075c23b` | ✅ ok |
| 27/09 09:56 | [CI](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/36320686356) | `dev` | push | `0dc2fcd` | ❌ falló |
| 27/09 09:56 | [Release (extension + apps)](https://github.com/CosmosPay/CosmosPay-Wallet/actions/runs/36320686370) | `dev` | push | `0dc2fcd` | ✅ ok |

Además, 8 ejecuciones automáticas de Dependabot (8 ok).

### Deploys (3)

| Fecha | Entorno | Rama | Commit |
|---|---|---|---|
| 16/09 12:51 | github-pages | `main` | `80c1f57` |
| 18/09 21:36 | github-pages | `main` | `1c2f33e` |
| 21/09 11:04 | github-pages | `main` | `e679836` |

---

## CosmosPay-Community-Server

Community Server (API) — [https://github.com/CosmosPay/CosmosPay-Community-Server](https://github.com/CosmosPay/CosmosPay-Community-Server)

### Commits (38)

| Fecha | Autor | Commit | Mensaje |
|---|---|---|---|
| 13/09 13:18 | Emanuel250YT | [`ad028aa`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/ad028aa9e1868bb5055dce3f6a5ee237990631f8) | refactor: remove admin credentials and switch to console-based authorization |
| 13/09 13:46 | Emanuel250YT | [`2ac9abd`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/2ac9abda604b7ce47be1217cfd31cabe1fa8473c) | refactor: remove deprecated admin API credentials section from .env.example |
| 13/09 14:10 | Emanuel250YT | [`428d88a`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/428d88a8f00b3c27b1f47eb3d352a8addb43d345) | Merge pull request #86 from CosmosPay/dev |
| 13/09 14:12 | github-actions[bot] | [`d5e29db`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/d5e29dbd62b5e7f5adf163440a76ab13a11eddab) | chore(release): v1.1.1 [skip ci] |
| 14/09 20:10 | Emanuel250YT | [`dab0dd0`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/dab0dd00414ee44869fa68cd09d6a1a9537c6a54) | refactor: eliminar archivos de evidencia obsoletos relacionados con la lista blanca de URL de redirección KYC |
| 14/09 20:10 | Emanuel250YT | [`8a8e7d5`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/8a8e7d566ac69572fa1fe5bce3f0dc941d93f6a4) | feat(wallets): enhance wallet ownership verification and provisioning logic |
| 15/09 02:09 | Emanuel250YT | [`d28299c`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/d28299c861f1294c927399ff3d7d9cd4b2aea737) | feat: implement SignedTransactionRelay service for relaying signed transactions |
| 15/09 08:35 | Emanuel250YT | [`878ad1e`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/878ad1e3980485fdecec6b8c09062d627a9b2ff7) | refactor: replace $transaction with Promise.all for improved performance and consistency |
| 15/09 08:35 | Emanuel250YT | [`9792312`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/97923122ea911839e1b3e9f0a4841b40640b67e4) | feat: add unit tests for Blindpay webhooks controller |
| 15/09 09:28 | Emanuel250YT | [`e0ca53e`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/e0ca53ed2f03fc8e16043b28dd2956443de3aca4) | Refactor code structure for improved readability and maintainability |
| 15/09 09:34 | Emanuel250YT | [`92bebf4`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/92bebf404ff7010a9a32d262ff79614d68486bca) | Merge pull request #87 from CosmosPay/dev |
| 15/09 09:36 | github-actions[bot] | [`c0f91c5`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/c0f91c5e3856d4a58a2da3b3dbb7a0e180e1b59a) | chore(release): v1.2.0 [skip ci] |
| 15/09 18:03 | Emanuel250YT | [`8013ca0`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/8013ca0a14a8776a3be07e9d864043b7ab0914f1) | feat(tests): add end-to-end tests for payment intents txHash handling |
| 15/09 18:43 | Emanuel250YT | [`04147e5`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/04147e5a7448dcbfec3df1eadcf55e3083ca4c04) | feat: update API documentation for receiver updates with elevated key requirements |
| 15/09 19:59 | Emanuel250YT | [`2b19c55`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/2b19c55fa0d3aba1fc78f8f3e9d7d9c0e1ac0dd6) | feat(pollar): enhance OAuth session handling and user registration |
| 16/09 00:20 | Emanuel250YT | [`876a46b`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/876a46b0334ca318413e23a34a5a1f6a88e6bb11) | feat: implement stored envelope handling for Stellar transactions |
| 16/09 12:49 | Emanuel250YT | [`8815528`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/881552816568b41f795fcacf7e1428c36bab2bb2) | Merge pull request #88 from CosmosPay/dev |
| 16/09 12:51 | github-actions[bot] | [`069be48`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/069be488bce32e7da227c6ca79f4d0bb34c6f268) | chore(release): v1.3.0 [skip ci] |
| 16/09 12:53 | Emanuel250YT | [`daee830`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/daee83049609f872a5d371ec5b90fd0e0fbcd68e) | Merge pull request #89 from CosmosPay/main |
| 17/09 22:13 | Emanuel250YT | [`68cdd89`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/68cdd89a3686f1d4b0392ccd6bd9bd5cbcb80457) | feat: add Swagger tests and enhance OpenAPI documentation |
| 19/09 07:15 | dependabot[bot] | [`f2c8de7`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/f2c8de70db261b7b87b1aced61a6fa3c1f1d6fde) | chore: bump the minor-and-patch group with 12 updates |
| 20/09 10:49 | Emanuel250YT | [`636c956`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/636c9562d000e925cefd810922ff1fc11e8cd017) | Merge pull request #90 from CosmosPay/dependabot/npm_and_yarn/minor-and-patch-6c98efc57f |
| 20/09 10:51 | github-actions[bot] | [`65eae79`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/65eae79c16bb1e5788d08c3ca2a2239d03bd141c) | chore(release): v1.3.1 [skip ci] |
| 22/09 00:09 | root | [`c4ab364`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/c4ab3641700b99c5d3808080449208f17b1ba040) | fix(blindpay): reject expired quotes |
| 22/09 00:10 | root | [`a459067`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/a459067690c157fb5e0b2cb06ed1bf0c238f8564) | fix(blindpay): make payment execution idempotent |
| 22/09 12:56 | leocagli | [`d5559ea`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/d5559eacae352aeaf522fb3b42e6c39c16a210c5) | feat: add DeFindex gateway API |
| 24/09 12:30 | Emanuel250YT | [`afb37ec`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/afb37ecef5a82ed2431c9fb329bb286f703ea810) | feat: add AGENTS.md with repository conventions and guidelines |
| 25/09 18:46 | Emanuel250YT | [`3abb392`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/3abb3923607a56e04eaa9df6243bd19361a17704) | feat(wallet-auth): serve the wallet's own sign-in from the community server |
| 25/09 18:59 | Emanuel250YT | [`ae3ec36`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/ae3ec362c8d8e72da6e2babc3b8c149d3de5a159) | fix(wallet-auth): match the wire contract the wallet actually sends |
| 25/09 19:12 | Emanuel250YT | [`813b069`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/813b06923284457c12361711038c2fecbc1bc895) | refactor(wallet-auth): send the display name to the provisioner |
| 25/09 19:21 | Emanuel250YT | [`1a93099`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/1a93099703bfadd25bd2ce5de589629f6a68502a) | refactor(wallet-auth): keep the console legs inside the wallet namespace |
| 25/09 20:44 | Emanuel250YT | [`c47422a`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/c47422aa8f8043cd3511da100adb09c4ff5cd2e6) | feat: add support for Authentik as an OIDC provider |
| 25/09 21:00 | Emanuel250YT | [`0811412`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/081141216e83d32f6f45425309d5739cc3e7454e) | feat(recovery): implement SEP-30 security scheme for account routes in OpenAPI |
| 26/09 07:14 | dependabot[bot] | [`cb795ec`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/cb795ec2ee9e006b27769415e5e2851723699448) | chore: bump the minor-and-patch group with 15 updates |
| 26/09 07:15 | dependabot[bot] | [`b97c5d8`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/b97c5d87b4ef6e79373d02ab89724b23b1ca9396) | chore: bump dotenv from 17.4.2 to 18.0.3 |
| 26/09 22:13 | Emanuel250YT | [`c9490ad`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/c9490ad8a25587a0e1721b7671ff53a165de07fd) | feat(wallet-auth): handle unverified emails in Authentik sign-in flow |
| 26/09 23:07 | Emanuel250YT | [`8c055bc`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/8c055bcd3d7124287ce767d6b007c66fda69209f) | feat(wallet-auth): implement max_age for Authentik sign-in flow to enhance security |
| 27/09 00:09 | Emanuel250YT | [`d446d02`](https://github.com/CosmosPay/CosmosPay-Community-Server/commit/d446d02b2c9171bc86a5dec76538d1557d21efbd) | feat(wallet-auth): implement v3 backup box structure supporting password and passkey slots |

### Pull requests (11)

| # | Abierto | Mergeado | Estado | Autor | Ramas | Título |
|---|---|---|---|---|---|---|
| [#86](https://github.com/CosmosPay/CosmosPay-Community-Server/pull/86) | 13/09 14:08 | 13/09 14:10 | mergeado | Emanuel250YT | `dev` → `main` | Refactor authorization model to use console-based verification |
| [#87](https://github.com/CosmosPay/CosmosPay-Community-Server/pull/87) | 15/09 09:34 | 15/09 09:34 | mergeado | Emanuel250YT | `dev` → `main` | Refactor and enhance wallet, swap, and webhook functionalities |
| [#88](https://github.com/CosmosPay/CosmosPay-Community-Server/pull/88) | 16/09 12:29 | 16/09 12:49 | mergeado | Emanuel250YT | `dev` → `main` | Enhance tests and API for payment intents, OAuth, and rate limiting |
| [#89](https://github.com/CosmosPay/CosmosPay-Community-Server/pull/89) | 16/09 12:51 | 16/09 12:53 | mergeado | Emanuel250YT | `main` → `dev` | Enhance wallet, authorization, and payment functionalities |
| [#90](https://github.com/CosmosPay/CosmosPay-Community-Server/pull/90) | 19/09 07:15 | 20/09 10:49 | mergeado | dependabot[bot] | `dependabot/npm_and_yarn/minor-and-patch-6c98efc57f` → `main` | chore: bump the minor-and-patch group with 12 updates |
| [#91](https://github.com/CosmosPay/CosmosPay-Community-Server/pull/91) | 20/09 05:39 | — | abierto | karagozemin | `feat/sub-rosa-private-rfqs` → `main` | feat: add non-custodial Sub Rosa private RFQs |
| [#92](https://github.com/CosmosPay/CosmosPay-Community-Server/pull/92) | 22/09 00:09 | — | abierto | leocagli | `codex/blindpay-quote-expiry` → `main` | Reject expired BlindPay quotes |
| [#93](https://github.com/CosmosPay/CosmosPay-Community-Server/pull/93) | 22/09 00:10 | — | abierto | leocagli | `codex/blindpay-execution-idempotency` → `main` | Make BlindPay execution idempotent |
| [#94](https://github.com/CosmosPay/CosmosPay-Community-Server/pull/94) | 22/09 12:56 | — | abierto | leocagli | `codex/defindex-api` → `main` | feat: add DeFindex gateway API |
| [#95](https://github.com/CosmosPay/CosmosPay-Community-Server/pull/95) | 26/09 07:14 | — | abierto | dependabot[bot] | `dependabot/npm_and_yarn/minor-and-patch-bb70154548` → `main` | chore: bump the minor-and-patch group with 15 updates |
| [#96](https://github.com/CosmosPay/CosmosPay-Community-Server/pull/96) | 26/09 07:15 | — | abierto | dependabot[bot] | `dependabot/npm_and_yarn/dotenv-18.0.3` → `main` | chore: bump dotenv from 17.4.2 to 18.0.3 |

### Releases (4)

| Fecha | Tag | Nombre |
|---|---|---|
| 13/09 14:12 | [`v1.1.1`](https://github.com/CosmosPay/CosmosPay-Community-Server/releases/tag/v1.1.1) | Cosmos Pay Community Server v1.1.1 |
| 15/09 09:36 | [`v1.2.0`](https://github.com/CosmosPay/CosmosPay-Community-Server/releases/tag/v1.2.0) | Cosmos Pay Community Server v1.2.0 |
| 16/09 12:51 | [`v1.3.0`](https://github.com/CosmosPay/CosmosPay-Community-Server/releases/tag/v1.3.0) | Cosmos Pay Community Server v1.3.0 |
| 20/09 10:51 | [`v1.3.1`](https://github.com/CosmosPay/CosmosPay-Community-Server/releases/tag/v1.3.1) | Cosmos Pay Community Server v1.3.1 |

### Builds (42: 36 ok, 6 fallidos, 0 cancelados)

| Fecha | Workflow | Rama | Evento | Commit | Resultado |
|---|---|---|---|---|---|
| 13/09 13:18 | [CI](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/34768187181) | `dev` | push | `ad028aa` | ✅ ok |
| 13/09 13:46 | [CI](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/34769612490) | `dev` | push | `2ac9abd` | ✅ ok |
| 13/09 14:08 | [CI](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/34770680144) | `dev` | pull_request | `2ac9abd` | ✅ ok |
| 13/09 14:10 | [CI](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/34770768049) | `main` | push | `428d88a` | ✅ ok |
| 13/09 14:10 | [Release](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/34770768046) | `main` | push | `428d88a` | ✅ ok |
| 14/09 20:10 | [CI](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/34907640851) | `dev` | push | `8a8e7d5` | ✅ ok |
| 15/09 02:10 | [CI](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/34931640883) | `dev` | push | `d28299c` | ✅ ok |
| 15/09 08:35 | [CI](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/34964124998) | `dev` | push | `9792312` | ✅ ok |
| 15/09 09:28 | [CI](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/34969036937) | `dev` | push | `e0ca53e` | ✅ ok |
| 15/09 09:34 | [CI](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/34969618463) | `dev` | pull_request | `e0ca53e` | ✅ ok |
| 15/09 09:34 | [CI](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/34969637360) | `main` | push | `92bebf4` | ✅ ok |
| 15/09 09:34 | [Release](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/34969637384) | `main` | push | `92bebf4` | ✅ ok |
| 15/09 18:04 | [CI](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/35023407109) | `dev` | push | `8013ca0` | ✅ ok |
| 15/09 18:43 | [CI](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/35027245261) | `dev` | push | `04147e5` | ✅ ok |
| 15/09 21:34 | [CI](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/35040540733) | `dev` | push | `2b19c55` | ✅ ok |
| 16/09 00:20 | [CI](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/35051446075) | `dev` | push | `876a46b` | ✅ ok |
| 16/09 12:29 | [CI](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/35115719171) | `dev` | pull_request | `876a46b` | ✅ ok |
| 16/09 12:49 | [Release](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/35117944044) | `main` | push | `8815528` | ✅ ok |
| 16/09 12:49 | [CI](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/35117944095) | `main` | push | `8815528` | ✅ ok |
| 16/09 12:51 | [CI](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/35118088300) | `main` | pull_request | `8815528` | ✅ ok |
| 16/09 12:53 | [CI](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/35118308629) | `dev` | push | `daee830` | ✅ ok |
| 17/09 22:14 | [CI](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/35294484751) | `dev` | push | `68cdd89` | ✅ ok |
| 19/09 07:15 | [CI](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/35436885278) | `dependabot/npm_and_yarn/minor-and-patch-6c98efc57f` | pull_request | `f2c8de7` | ✅ ok |
| 20/09 05:39 | [CI](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/35500174602) | `feat/sub-rosa-private-rfqs` | pull_request | `a315eac` | ✅ ok |
| 20/09 10:49 | [CI](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/35514624337) | `main` | push | `636c956` | ✅ ok |
| 20/09 10:49 | [Release](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/35514624196) | `main` | push | `636c956` | ✅ ok |
| 22/09 00:09 | [CI](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/35682107329) | `codex/blindpay-quote-expiry` | pull_request | `c4ab364` | ❌ falló |
| 22/09 00:10 | [CI](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/35682197765) | `codex/blindpay-execution-idempotency` | pull_request | `a459067` | ❌ falló |
| 22/09 12:56 | [CI](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/35750781578) | `codex/defindex-api` | pull_request | `d5559ea` | ❌ falló |
| 24/09 12:31 | [CI](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/36020774547) | `dev` | push | `afb37ec` | ✅ ok |
| 25/09 19:27 | [CI](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/36196804524) | `dev` | push | `1a93099` | ✅ ok |
| 25/09 20:44 | [CI](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/36202152044) | `dev` | push | `c47422a` | ✅ ok |
| 25/09 21:00 | [CI](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/36203159663) | `dev` | push | `0811412` | ✅ ok |
| 26/09 07:15 | [CI](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/36235213415) | `dependabot/npm_and_yarn/minor-and-patch-bb70154548` | pull_request | `cb795ec` | ✅ ok |
| 26/09 07:15 | [CI](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/36235233785) | `dependabot/npm_and_yarn/dotenv-18.0.3` | pull_request | `b97c5d8` | ✅ ok |
| 26/09 22:13 | [CI](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/36284899056) | `dev` | push | `c9490ad` | ❌ falló |
| 26/09 23:08 | [CI](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/36287614502) | `dev` | push | `8c055bc` | ❌ falló |
| 27/09 00:09 | [CI](https://github.com/CosmosPay/CosmosPay-Community-Server/actions/runs/36290583676) | `dev` | push | `d446d02` | ❌ falló |

Además, 4 ejecuciones automáticas de Dependabot (4 ok).

---

## CosmosPay-Developer-Platform

Developer Platform (consola y docs) — [https://github.com/CosmosPay/CosmosPay-Developer-Platform](https://github.com/CosmosPay/CosmosPay-Developer-Platform)

### Commits (45)

| Fecha | Autor | Commit | Mensaje |
|---|---|---|---|
| 12/09 20:53 | dependabot[bot] | [`9ea9adc`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/9ea9adc80cf0953a2d2e53522a9478980decfbea) | chore: bump @asteasolutions/zod-to-openapi from 8.5.0 to 9.1.0 |
| 12/09 20:54 | dependabot[bot] | [`6b197e3`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/6b197e3e1e037f1a86e8adef8b655a1a61374ace) | chore: bump the minor-and-patch group in /docs with 12 updates |
| 13/09 13:16 | Emanuel250YT | [`6e08f2c`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/6e08f2c95acb166896ec50813d59e633de974034) | refactor: remove deprecated admin API secrets and update proxy handling for Payments API |
| 13/09 13:22 | Emanuel250YT | [`616a129`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/616a129e773776442d961b330591abd3104f9c51) | Merge pull request #43 from CosmosPay/dev |
| 13/09 13:23 | Emanuel250YT | [`419b046`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/419b0460f64e47daf87b9b0e41247c71bdcd9330) | Merge pull request #42 from CosmosPay/dependabot/npm_and_yarn/docs/minor-and-patch-10c7a64163 |
| 13/09 13:24 | Emanuel250YT | [`0d509d7`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/0d509d70c4e6b6d1da3953e19a74144cddc9fe18) | Merge pull request #41 from CosmosPay/dependabot/npm_and_yarn/asteasolutions/zod-to-openapi-9.1.0 |
| 13/09 13:28 | Emanuel250YT | [`08bd1f8`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/08bd1f802b9c1c06ed265aa09c740ae7e5594f21) | Merge pull request #44 from CosmosPay/main |
| 13/09 13:46 | Emanuel250YT | [`46044a0`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/46044a0dce6de47a76310bf3ed0bec21cfb6faf4) | refactor: remove deprecated Payments API admin secrets from environment example |
| 13/09 14:00 | Emanuel250YT | [`cf72b25`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/cf72b25d3f2721af8549b38b85d72876a6725ad9) | refactor: migrate search client from Orama to ZBSearch and update related functions |
| 13/09 14:06 | Emanuel250YT | [`b2a59b3`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/b2a59b336d3e74ca911b4098e042a4133cc80f73) | Merge pull request #45 from CosmosPay/dev |
| 13/09 14:07 | github-actions[bot] | [`c977ba3`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/c977ba350399e7476109eecf779bfb2ec6e1a22d) | chore(release): v0.2.2 [skip ci] |
| 15/09 18:42 | Emanuel250YT | [`f85cc92`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/f85cc92373198ef3eefb519874f862c3fe95fce7) | Refactor code structure for improved readability and maintainability |
| 15/09 19:57 | Emanuel250YT | [`e04de5a`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/e04de5a9fd98fd76bb0f4018f8023f1439d305ce) | feat: implement social login email verification process |
| 16/09 00:55 | Emanuel250YT | [`cf202fb`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/cf202fb3fc0a7613c7b8598b750afdb81b34b6b4) | feat: add expected_version to receiver approval process and update related schemas |
| 16/09 12:27 | Emanuel250YT | [`5aeb5a0`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/5aeb5a0626cd6d74d7367933b64ea5ab9d3f5363) | feat: add dossierVersion and reviewedVersion properties to Receiver documentation |
| 16/09 12:50 | Emanuel250YT | [`e388ed0`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/e388ed04b2f86d197511b1b9d83c15de7b7699cc) | Merge pull request #46 from CosmosPay/dev |
| 16/09 12:52 | github-actions[bot] | [`bcadcc7`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/bcadcc795ee21bcb8a1944708ba2766b02115c25) | chore(release): v0.3.0 [skip ci] |
| 16/09 12:55 | Emanuel250YT | [`234ce46`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/234ce46a964756253e1d25353210aa3aee9cacc5) | Merge pull request #47 from CosmosPay/main |
| 17/09 02:51 | root | [`c169eb2`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/c169eb21434a98ba4ca80c64aab365510c3048b0) | feat(marca): tokens, tipografia y logo de la marca nueva |
| 17/09 19:37 | Emanuel250YT | [`25b156b`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/25b156b0f5c380e8e1240d2bcf0f0714fc878198) | refactor: update Zod imports to use extended version from openapi library |
| 18/09 12:54 | root | [`9c2d0a7`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/9c2d0a73cdb8a80d7c2afd8457c077c0231bc635) | feat(marca): landing con los paneles, los titulares y los motivos del deck |
| 18/09 13:45 | root | [`4b28d9f`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/4b28d9f735512a1561b3749c551b95307eef6f59) | fix(marca): correcciones de la ronda 1 de revision sobre el landing |
| 18/09 14:38 | root | [`d8ad0f7`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/d8ad0f779b4d8091763dbb5610e304f7b96e9890) | Rebrand: arreglos de la ronda 2 de revision en el landing |
| 18/09 15:19 | root | [`f25390e`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/f25390e0bd136a17e504e994463721698a6fa83b) | Rebrand: barrido de los restos de la marca vieja fuera del landing |
| 18/09 18:45 | root | [`75a97e1`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/75a97e12f8e3d2cd57aa1b19aee70463790cdd4a) | Poner la wallet al frente del landing |
| 18/09 19:21 | root | [`c3cad78`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/c3cad786ff61a79ef390f0ffe9e75c8b67d441d7) | fix(marca): la promo cruzada entra en el sistema y el landing en ES pasa a voseo |
| 18/09 21:30 | leocagli | [`b400ba4`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/b400ba48d9043e3d02c2fb086064d736c04821f6) | feat(landing): la wallet primero, y la barra y el idioma que no se veian |
| 18/09 21:38 | github-actions[bot] | [`266e8c3`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/266e8c39cf0c215c57e0040786fe76ef900eff15) | chore(release): v0.4.0 [skip ci] |
| 19/09 13:02 | leocagli | [`4181499`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/41814991c8a3de41e16083b84463820c0bddd43f) | docs(skills): skill de Cosmos Pay para agentes (skills.stellar.org) |
| 19/09 13:03 | github-actions[bot] | [`ef15ee8`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/ef15ee8fc80d0bc8cf0379126bac6a05a5e7edef) | chore(release): v0.4.1 [skip ci] |
| 19/09 21:19 | Emanuel250YT | [`0acb506`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/0acb506febecc002131d208cb7326d67cc27e262) | feat: implement OAuth authentication flow for wallet sign-in |
| 19/09 22:56 | Emanuel250YT | [`7d89383`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/7d893835a672c1f0d736fc7799e778d2cc98cc03) | feat: implement SEP-10 Stellar Web Authentication and SEP-30 account recovery |
| 24/09 12:30 | Emanuel250YT | [`cb372b2`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/cb372b2d47197433ea436b87425f0d268f52ace9) | feat: add AGENTS.md for API documentation and development guidelines |
| 24/09 16:10 | Emanuel250YT | [`b55ad6e`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/b55ad6e008623e0f9ff0b39ccb684e2e106ec545) | Implement feature X to enhance user experience and fix bug Y in module Z |
| 24/09 17:14 | Emanuel250YT | [`94886e2`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/94886e2c635de8b1a1f490258c2a9bcf185f9fc5) | feat: implement pagination for accounts listing and add SEP-30 response handling |
| 24/09 17:15 | Emanuel250YT | [`1c2e72f`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/1c2e72f45c0bb97ea5192e7d6dcda517afa88088) | feat: enhance recovery API with SEP-30 compliance and improve error handling |
| 25/09 19:10 | Emanuel250YT | [`e31d960`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/e31d9605619a957d8e369dbcec355709f7e0c22c) | feat(wallet-auth): serve the two console legs the community server hands back |
| 25/09 19:21 | Emanuel250YT | [`bec268d`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/bec268d54e69d02cdf4a532dd837653124c5f33b) | refactor(wallet-auth): move the console legs under api/wallet/ |
| 25/09 20:43 | Emanuel250YT | [`b8f7b7f`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/b8f7b7f7b8bf8e40ab19856d80e5951a72ee47a4) | Add unit tests for wallet authentication and remove obsolete recovery and SEP-10 tests |
| 25/09 20:43 | Emanuel250YT | [`670267a`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/670267aa932d25b65b978311d178d11c0bf9cac3) | feat: implement recovery code API endpoint and associated schema |
| 25/09 20:59 | Emanuel250YT | [`409455e`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/409455e30641d8bc73240514a101005bc5adc70a) | feat: enhance OpenAPI spec with security definitions and public routes |
| 26/09 20:54 | dependabot[bot] | [`d988ec9`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/d988ec9e47f18edb6bef81d823f0d70f78404dd7) | chore: bump the minor-and-patch group across 1 directory with 8 updates |
| 26/09 20:55 | dependabot[bot] | [`7f04b35`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/7f04b351e5c5b5cd92387540533608ec002b3b3b) | chore: bump the minor-and-patch group across 1 directory with 5 updates |
| 26/09 22:13 | Emanuel250YT | [`284b005`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/284b0054d5cb27747b2736ba53340006f9cc46f5) | feat: add AliasManager and AssetManager documentation; update Client and PaymentIntentManager with new methods |
| 26/09 23:07 | Emanuel250YT | [`f8b1e3b`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/commit/f8b1e3b27b5db557c9c5c1fa2c1526fe9e289032) | feat: update wallet auth API descriptions to clarify session token usage and email verification process |

### Pull requests (11)

| # | Abierto | Mergeado | Estado | Autor | Ramas | Título |
|---|---|---|---|---|---|---|
| [#41](https://github.com/CosmosPay/CosmosPay-Developer-Platform/pull/41) | 12/09 20:53 | 13/09 13:24 | mergeado | dependabot[bot] | `dependabot/npm_and_yarn/asteasolutions/zod-to-openapi-9.1.0` → `main` | chore: bump @asteasolutions/zod-to-openapi from 8.5.0 to 9.1.0 |
| [#42](https://github.com/CosmosPay/CosmosPay-Developer-Platform/pull/42) | 12/09 20:54 | 13/09 13:23 | mergeado | dependabot[bot] | `dependabot/npm_and_yarn/docs/minor-and-patch-10c7a64163` → `main` | chore: bump the minor-and-patch group in /docs with 12 updates |
| [#43](https://github.com/CosmosPay/CosmosPay-Developer-Platform/pull/43) | 13/09 13:22 | 13/09 13:22 | mergeado | Emanuel250YT | `dev` → `main` | refactor: remove deprecated admin API secrets and update proxy handli… |
| [#44](https://github.com/CosmosPay/CosmosPay-Developer-Platform/pull/44) | 13/09 13:25 | 13/09 13:28 | mergeado | Emanuel250YT | `main` → `dev` | Enhance navigation, fix dependencies, and update authentication |
| [#45](https://github.com/CosmosPay/CosmosPay-Developer-Platform/pull/45) | 13/09 14:04 | 13/09 14:06 | mergeado | Emanuel250YT | `dev` → `main` | Enhance navigation, update authentication, and migrate search client |
| [#46](https://github.com/CosmosPay/CosmosPay-Developer-Platform/pull/46) | 16/09 12:30 | 16/09 12:50 | mergeado | Emanuel250YT | `dev` → `main` | Refactor code structure and implement social login email verification |
| [#47](https://github.com/CosmosPay/CosmosPay-Developer-Platform/pull/47) | 16/09 12:54 | 16/09 12:55 | mergeado | Emanuel250YT | `main` → `dev` | Enhance navigation, refactor code, and implement social login |
| [#48](https://github.com/CosmosPay/CosmosPay-Developer-Platform/pull/48) | 19/09 20:54 | — | cerrado sin merge | dependabot[bot] | `dependabot/npm_and_yarn/minor-and-patch-50809c966c` → `main` | chore: bump the minor-and-patch group with 6 updates |
| [#49](https://github.com/CosmosPay/CosmosPay-Developer-Platform/pull/49) | 19/09 20:54 | — | cerrado sin merge | dependabot[bot] | `dependabot/npm_and_yarn/docs/minor-and-patch-6f652f81d4` → `main` | chore: bump the minor-and-patch group in /docs with 9 updates |
| [#50](https://github.com/CosmosPay/CosmosPay-Developer-Platform/pull/50) | 26/09 20:54 | — | abierto | dependabot[bot] | `dependabot/npm_and_yarn/docs/minor-and-patch-dda4a464c6` → `main` | chore: bump the minor-and-patch group across 1 directory with 8 updates |
| [#51](https://github.com/CosmosPay/CosmosPay-Developer-Platform/pull/51) | 26/09 20:55 | — | abierto | dependabot[bot] | `dependabot/npm_and_yarn/minor-and-patch-864ab215d3` → `main` | chore: bump the minor-and-patch group across 1 directory with 5 updates |

### Releases (4)

| Fecha | Tag | Nombre |
|---|---|---|
| 13/09 14:07 | [`v0.2.2`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/releases/tag/v0.2.2) | Cosmos Pay Developer Platform v0.2.2 |
| 16/09 12:52 | [`v0.3.0`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/releases/tag/v0.3.0) | Cosmos Pay Developer Platform v0.3.0 |
| 18/09 21:38 | [`v0.4.0`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/releases/tag/v0.4.0) | Cosmos Pay Developer Platform v0.4.0 |
| 19/09 13:03 | [`v0.4.1`](https://github.com/CosmosPay/CosmosPay-Developer-Platform/releases/tag/v0.4.1) | Cosmos Pay Developer Platform v0.4.1 |

### Builds (55: 43 ok, 9 fallidos, 3 cancelados)

| Fecha | Workflow | Rama | Evento | Commit | Resultado |
|---|---|---|---|---|---|
| 12/09 20:54 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/34726597157) | `dependabot/npm_and_yarn/asteasolutions/zod-to-openapi-9.1.0` | pull_request | `9ea9adc` | ✅ ok |
| 12/09 20:54 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/34726631487) | `dependabot/npm_and_yarn/docs/minor-and-patch-10c7a64163` | pull_request | `6b197e3` | ❌ falló |
| 13/09 13:16 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/34768083295) | `dev` | push | `6e08f2c` | ✅ ok |
| 13/09 13:22 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/34768392964) | `dev` | pull_request | `6e08f2c` | ✅ ok |
| 13/09 13:22 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/34768398116) | `main` | push | `616a129` | ⚪ cancelado |
| 13/09 13:22 | [Release](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/34768398130) | `main` | push | `616a129` | ❌ falló |
| 13/09 13:23 | [Release](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/34768419534) | `main` | push | `419b046` | ⚪ cancelado |
| 13/09 13:23 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/34768419529) | `main` | push | `419b046` | ⚪ cancelado |
| 13/09 13:24 | [Release](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/34768478324) | `main` | push | `0d509d7` | ❌ falló |
| 13/09 13:24 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/34768478329) | `main` | push | `0d509d7` | ❌ falló |
| 13/09 13:26 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/34768559104) | `main` | pull_request | `0d509d7` | ❌ falló |
| 13/09 13:28 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/34768678335) | `dev` | push | `08bd1f8` | ❌ falló |
| 13/09 13:46 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/34769610876) | `dev` | push | `46044a0` | ❌ falló |
| 13/09 14:00 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/34770255554) | `dev` | push | `cf72b25` | ✅ ok |
| 13/09 14:04 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/34770496684) | `dev` | pull_request | `cf72b25` | ✅ ok |
| 13/09 14:06 | [Release](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/34770576331) | `main` | push | `b2a59b3` | ✅ ok |
| 13/09 14:06 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/34770576412) | `main` | push | `b2a59b3` | ✅ ok |
| 15/09 18:42 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/35027139763) | `dev` | push | `f85cc92` | ✅ ok |
| 15/09 19:58 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/35033492136) | `dev` | push | `e04de5a` | ✅ ok |
| 16/09 00:55 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/35053620442) | `dev` | push | `cf202fb` | ✅ ok |
| 16/09 12:27 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/35115423521) | `dev` | push | `5aeb5a0` | ✅ ok |
| 16/09 12:30 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/35115814248) | `dev` | pull_request | `5aeb5a0` | ✅ ok |
| 16/09 12:50 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/35117995420) | `main` | push | `e388ed0` | ✅ ok |
| 16/09 12:50 | [Release](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/35117995338) | `main` | push | `e388ed0` | ✅ ok |
| 16/09 12:55 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/35118545790) | `dev` | push | `234ce46` | ✅ ok |
| 17/09 19:37 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/35282953416) | `dev` | push | `25b156b` | ✅ ok |
| 18/09 21:36 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/35409927229) | `main` | push | `b400ba4` | ✅ ok |
| 18/09 21:36 | [Release](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/35409927228) | `main` | push | `b400ba4` | ✅ ok |
| 19/09 13:02 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/35453655418) | `main` | push | `4181499` | ✅ ok |
| 19/09 13:02 | [Release](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/35453655450) | `main` | push | `4181499` | ✅ ok |
| 19/09 20:54 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/35477348904) | `dependabot/npm_and_yarn/minor-and-patch-50809c966c` | pull_request | `91c8db0` | ✅ ok |
| 19/09 20:54 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/35477376063) | `dependabot/npm_and_yarn/docs/minor-and-patch-6f652f81d4` | pull_request | `f9459c9` | ❌ falló |
| 19/09 21:19 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/35478474531) | `dev` | push | `0acb506` | ✅ ok |
| 19/09 22:56 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/35482663231) | `dev` | push | `7d89383` | ✅ ok |
| 24/09 12:30 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/36020725891) | `dev` | push | `cb372b2` | ✅ ok |
| 24/09 16:10 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/36046330990) | `dev` | push | `b55ad6e` | ✅ ok |
| 24/09 17:15 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/36053616143) | `dev` | push | `1c2e72f` | ✅ ok |
| 25/09 19:27 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/36196804232) | `dev` | push | `bec268d` | ✅ ok |
| 25/09 20:43 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/36202130174) | `dev` | push | `670267a` | ✅ ok |
| 25/09 20:59 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/36203146488) | `dev` | push | `409455e` | ✅ ok |
| 26/09 20:54 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/36280890984) | `dependabot/npm_and_yarn/docs/minor-and-patch-dda4a464c6` | pull_request | `d988ec9` | ❌ falló |
| 26/09 20:55 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/36280912788) | `dependabot/npm_and_yarn/minor-and-patch-864ab215d3` | pull_request | `7f04b35` | ✅ ok |
| 26/09 22:13 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/36284876912) | `dev` | push | `284b005` | ✅ ok |
| 26/09 23:08 | [CI](https://github.com/CosmosPay/CosmosPay-Developer-Platform/actions/runs/36287615977) | `dev` | push | `f8b1e3b` | ✅ ok |

Además, 11 ejecuciones automáticas de Dependabot (11 ok).

---

## CosmosJS_SDK

SDK de JavaScript — [https://github.com/CosmosPay/CosmosJS_SDK](https://github.com/CosmosPay/CosmosJS_SDK)

### Commits (9)

| Fecha | Autor | Commit | Mensaje |
|---|---|---|---|
| 15/09 18:47 | Emanuel250YT | [`0e9ba8b`](https://github.com/CosmosPay/CosmosJS_SDK/commit/0e9ba8b8cab8a2fb3f0b366092e9c87af8f11231) | feat!: follow the payments API security contract changes |
| 16/09 00:21 | Emanuel250YT | [`d80aa11`](https://github.com/CosmosPay/CosmosJS_SDK/commit/d80aa11473e372310bbce151e1644b79b07ae249) | feat: update PollarManager documentation to clarify session handling and user registration requirements |
| 16/09 00:55 | Emanuel250YT | [`14689d1`](https://github.com/CosmosPay/CosmosJS_SDK/commit/14689d13014a090ed9081cdec7283fc6204f1671) | feat: add dossierVersion and reviewedVersion to Receiver class and update approval logic |
| 16/09 12:28 | Emanuel250YT | [`091ef13`](https://github.com/CosmosPay/CosmosJS_SDK/commit/091ef13f00f5de5f2d8fc06f2cc4a5086085048d) | Merge pull request #5 from CosmosPay/dev |
| 16/09 12:29 | Emanuel250YT | [`5fc83cf`](https://github.com/CosmosPay/CosmosJS_SDK/commit/5fc83cfc0c961f63a95ca7c4ac8ab4aec692180b) | Merge pull request #10 from CosmosPay/dependabot/npm_and_yarn/minor-and-patch-ce6036253e |
| 16/09 12:30 | github-actions[bot] | [`65c34e9`](https://github.com/CosmosPay/CosmosJS_SDK/commit/65c34e96f083e4721d1b6593e3ba6ac819e1fed1) | chore(release): v2.0.0 [skip ci] |
| 16/09 12:50 | Emanuel250YT | [`50d35d1`](https://github.com/CosmosPay/CosmosJS_SDK/commit/50d35d19ae902970767e13998b00e39711ce8e70) | Merge pull request #11 from CosmosPay/main |
| 19/09 17:52 | dependabot[bot] | [`e67fafa`](https://github.com/CosmosPay/CosmosJS_SDK/commit/e67fafaae8ed8289c41584e028770f7fe131d0a8) | chore: bump @types/node in the minor-and-patch group |
| 25/09 21:00 | Emanuel250YT | [`74e88b1`](https://github.com/CosmosPay/CosmosJS_SDK/commit/74e88b11fc59033876d6ba7990cfa6300ea124be) | feat: add AliasManager and AssetManager for handling aliases and asset registry |

### Pull requests (4)

| # | Abierto | Mergeado | Estado | Autor | Ramas | Título |
|---|---|---|---|---|---|---|
| [#5](https://github.com/CosmosPay/CosmosJS_SDK/pull/5) | 11/07 17:19 | 16/09 12:28 | mergeado | Emanuel250YT | `dev` → `main` | chore: relicense the SDK to Apache-2.0 |
| [#10](https://github.com/CosmosPay/CosmosJS_SDK/pull/10) | 05/09 17:52 | 16/09 12:29 | mergeado | dependabot[bot] | `dependabot/npm_and_yarn/minor-and-patch-ce6036253e` → `main` | chore: bump @types/node from 26.3.0 to 26.4.1 in the minor-and-patch group |
| [#11](https://github.com/CosmosPay/CosmosJS_SDK/pull/11) | 16/09 12:50 | 16/09 12:50 | mergeado | Emanuel250YT | `main` → `dev` | Implement SwapManager, enhance CI/CD, and update dependencies |
| [#12](https://github.com/CosmosPay/CosmosJS_SDK/pull/12) | 19/09 17:52 | — | abierto | dependabot[bot] | `dependabot/npm_and_yarn/minor-and-patch-febceb97ad` → `main` | chore: bump @types/node from 26.4.1 to 26.6.1 in the minor-and-patch group |

### Releases (1)

| Fecha | Tag | Nombre |
|---|---|---|
| 16/09 12:30 | [`v2.0.0`](https://github.com/CosmosPay/CosmosJS_SDK/releases/tag/v2.0.0) | v2.0.0 |

### Builds (21: 20 ok, 1 fallidos, 0 cancelados)

| Fecha | Workflow | Rama | Evento | Commit | Resultado |
|---|---|---|---|---|---|
| 15/09 18:50 | [CI](https://github.com/CosmosPay/CosmosJS_SDK/actions/runs/35027826657) | `dev` | push | `0e9ba8b` | ✅ ok |
| 15/09 18:50 | [CI](https://github.com/CosmosPay/CosmosJS_SDK/actions/runs/35027830327) | `dev` | pull_request | `0e9ba8b` | ✅ ok |
| 16/09 00:21 | [CI](https://github.com/CosmosPay/CosmosJS_SDK/actions/runs/35051506924) | `dev` | push | `d80aa11` | ✅ ok |
| 16/09 00:21 | [CI](https://github.com/CosmosPay/CosmosJS_SDK/actions/runs/35051510954) | `dev` | pull_request | `d80aa11` | ✅ ok |
| 16/09 00:55 | [CI](https://github.com/CosmosPay/CosmosJS_SDK/actions/runs/35053629831) | `dev` | push | `14689d1` | ✅ ok |
| 16/09 00:55 | [CI](https://github.com/CosmosPay/CosmosJS_SDK/actions/runs/35053632850) | `dev` | pull_request | `14689d1` | ✅ ok |
| 16/09 12:29 | [CI](https://github.com/CosmosPay/CosmosJS_SDK/actions/runs/35115634731) | `main` | push | `091ef13` | ✅ ok |
| 16/09 12:29 | [Release](https://github.com/CosmosPay/CosmosJS_SDK/actions/runs/35115634838) | `main` | push | `091ef13` | ❌ falló |
| 16/09 12:29 | [CI](https://github.com/CosmosPay/CosmosJS_SDK/actions/runs/35115731169) | `main` | push | `5fc83cf` | ✅ ok |
| 16/09 12:29 | [Release](https://github.com/CosmosPay/CosmosJS_SDK/actions/runs/35115731328) | `main` | push | `5fc83cf` | ✅ ok |
| 16/09 12:50 | [CI](https://github.com/CosmosPay/CosmosJS_SDK/actions/runs/35118070462) | `dev` | push | `50d35d1` | ✅ ok |
| 19/09 17:52 | [CI](https://github.com/CosmosPay/CosmosJS_SDK/actions/runs/35468738693) | `dependabot/npm_and_yarn/minor-and-patch-febceb97ad` | pull_request | `e67fafa` | ✅ ok |
| 25/09 21:00 | [CI](https://github.com/CosmosPay/CosmosJS_SDK/actions/runs/36203176770) | `dev` | push | `74e88b1` | ✅ ok |

Además, 8 ejecuciones automáticas de Dependabot (8 ok).

### Deploys (2)

| Fecha | Entorno | Rama | Commit |
|---|---|---|---|
| 16/09 12:29 | release | `main` | `091ef13` |
| 16/09 12:30 | release | `main` | `5fc83cf` |

---

## Cosmos-frontend

Frontend / landing de agencia — [https://github.com/CosmosPay/Cosmos-frontend](https://github.com/CosmosPay/Cosmos-frontend)

### Commits (14)

| Fecha | Autor | Commit | Mensaje |
|---|---|---|---|
| 17/09 02:49 | leocagli | [`b54937e`](https://github.com/CosmosPay/Cosmos-frontend/commit/b54937e16d697904b6d911d71b02245b4f80aeec) | rebrand(tokens): paleta, Open Sauce One y logo SVG de la marca nueva |
| 17/09 12:18 | leocagli | [`61952c3`](https://github.com/CosmosPay/Cosmos-frontend/commit/61952c3e7e1ef1ed7b67f73e6416f146d1bd1907) | rebrand(chrome): header, buscador, footer y mockup con la piel de la marca |
| 17/09 12:18 | leocagli | [`2377218`](https://github.com/CosmosPay/Cosmos-frontend/commit/2377218f9dc54a91fa9dcb5abb2e820ecb066b46) | rebrand(css): paneles con alcance propio, tipografia del deck y cinta |
| 17/09 12:18 | leocagli | [`dae860a`](https://github.com/CosmosPay/Cosmos-frontend/commit/dae860a1d3041fd8ec73d0965920f40fef3bd9df) | rebrand(landing): siete secciones con la estructura del deck |
| 18/09 13:02 | leocagli | [`7463a37`](https://github.com/CosmosPay/Cosmos-frontend/commit/7463a379344415f0a2004d5621e8acee68b8a39d) | rebrand(fix1): los once puntos de la primera revision |
| 18/09 13:51 | leocagli | [`8d2cadf`](https://github.com/CosmosPay/Cosmos-frontend/commit/8d2cadf3d0501922affd2aa5d120db2e0cfd71d5) | rebrand(fix2): los once puntos de la segunda revision |
| 18/09 14:18 | leocagli | [`65cdff1`](https://github.com/CosmosPay/Cosmos-frontend/commit/65cdff19f1b27e07deb8556048b4f53a7a269839) | rebrand(barrido): sacar la marca vieja de las paginas interiores |
| 18/09 18:39 | leocagli | [`f7c43bc`](https://github.com/CosmosPay/Cosmos-frontend/commit/f7c43bca68468e25c0d2d6cb4be1c4c0ea5803a6) | rebrand(landing): seccion /06 con la wallet y la plataforma de Cosmos Pay |
| 18/09 18:40 | leocagli | [`445ce6a`](https://github.com/CosmosPay/Cosmos-frontend/commit/445ce6af16b7bc2fcb84c53344affa6ceab9b41c) | rebrand(activos): versionar el personaje oficial de la agencia |
| 18/09 19:09 | leocagli | [`a21aa0b`](https://github.com/CosmosPay/Cosmos-frontend/commit/a21aa0b16d4628a73be0e089de113c02d2646403) | rebrand(fix3): otro compas para /06 y el personaje oficial en /04 |
| 18/09 19:09 | leocagli | [`a55b067`](https://github.com/CosmosPay/Cosmos-frontend/commit/a55b06757452ff10257f8cce6c2a417bcd71f951) | rebrand(marca): la spec del personaje oficial y el aviso de POI Aeronaut |
| 18/09 21:30 | leocagli | [`23a9835`](https://github.com/CosmosPay/Cosmos-frontend/commit/23a98358094fb9eed89d59bf55ba3ef65cb3eea2) | fix(i18n): bandera argentina para el castellano, no la mexicana |
| 18/09 22:59 | leocagli | [`c28a66a`](https://github.com/CosmosPay/Cosmos-frontend/commit/c28a66ab8a7257e80140626f753232eb4ab0d3ca) | chore(config): backend nuevo api.cosmosapp.lat y host cosmosapp.lat |
| 23/09 23:16 | leocagli | [`60bf7fb`](https://github.com/CosmosPay/Cosmos-frontend/commit/60bf7fbacd8ec375bb353fdb43f1448cfcc4bbaf) | fix(panel): que un grafico roto no deje /panel en blanco |

### Builds (4: 4 ok, 0 fallidos, 0 cancelados)

| Fecha | Workflow | Rama | Evento | Commit | Resultado |
|---|---|---|---|---|---|
| 18/09 21:36 | [Build and deploy](https://github.com/CosmosPay/Cosmos-frontend/actions/runs/35409924950) | `main` | push | `23a9835` | ✅ ok |
| 18/09 22:59 | [Build and deploy](https://github.com/CosmosPay/Cosmos-frontend/actions/runs/35414329683) | `main` | push | `c28a66a` | ✅ ok |
| 18/09 23:02 | [Build and deploy](https://github.com/CosmosPay/Cosmos-frontend/actions/runs/35414502353) | `main` | workflow_dispatch | `c28a66a` | ✅ ok |
| 23/09 23:16 | [Build and deploy](https://github.com/CosmosPay/Cosmos-frontend/actions/runs/35946553910) | `main` | push | `60bf7fb` | ✅ ok |

### Deploys (4)

| Fecha | Entorno | Rama | Commit |
|---|---|---|---|
| 18/09 21:37 | production | `main` | `23a9835` |
| 18/09 23:00 | production | `main` | `c28a66a` |
| 18/09 23:04 | production | `main` | `c28a66a` |
| 23/09 23:17 | production | `main` | `60bf7fb` |

---

## cosmos-backend

Backend de agencia — [https://github.com/CosmosPay/cosmos-backend](https://github.com/CosmosPay/cosmos-backend)

### Commits (5)

| Fecha | Autor | Commit | Mensaje |
|---|---|---|---|
| 09/09 23:50 | leocagli | [`88e9aa4`](https://github.com/CosmosPay/cosmos-backend/commit/88e9aa4df3af6a2883c94f0ef20319c5925f0f39) | fix(upload): build image URLs over https so browsers stop blocking them |
| 10/09 01:05 | leocagli | [`4871b88`](https://github.com/CosmosPay/cosmos-backend/commit/4871b88a4c697a3c81bb6959ab973a5ccfe265ee) | fix(deps): pull multer up to 2.3.0 on the upload path |
| 23/09 23:07 | leocagli | [`c70c6d7`](https://github.com/CosmosPay/cosmos-backend/commit/c70c6d742ee7d35d053e5927164c443fa479182e) | Merge pull request #2 from CosmosPay/fix/https-upload-urls-main |
| 23/09 23:53 | leocagli | [`9ef1738`](https://github.com/CosmosPay/cosmos-backend/commit/9ef17388d1b81f8fb36eeedae4e375dbe31d209a) | merge(snapshot): traer snapshot-v1 a main |
| 23/09 23:57 | leocagli | [`1b792df`](https://github.com/CosmosPay/cosmos-backend/commit/1b792df0b13cb7956cd02b7d9790b7a73d6c8c8d) | Merge pull request #3 from CosmosPay/promote/snapshot-v1 |

### Pull requests (2)

| # | Abierto | Mergeado | Estado | Autor | Ramas | Título |
|---|---|---|---|---|---|---|
| [#2](https://github.com/CosmosPay/cosmos-backend/pull/2) | 23/09 22:35 | 23/09 23:07 | mergeado | leocagli | `fix/https-upload-urls-main` → `main` | fix(upload): URLs de imagen en https (sobre main) |
| [#3](https://github.com/CosmosPay/cosmos-backend/pull/3) | 23/09 23:56 | 23/09 23:57 | mergeado | leocagli | `promote/snapshot-v1` → `main` | merge(snapshot): promover snapshot-v1 a main |

---

## CosmosPay-Skill

Skill para agentes — [https://github.com/CosmosPay/CosmosPay-Skill](https://github.com/CosmosPay/CosmosPay-Skill)

### Commits (3)

| Fecha | Autor | Commit | Mensaje |
|---|---|---|---|
| 22/09 00:44 | root | [`d31b37e`](https://github.com/CosmosPay/CosmosPay-Skill/commit/d31b37e4e682b05bf3ec3c78ec88b2b56080beae) | chore: initialize skill repository |
| 22/09 00:44 | root | [`39f6baf`](https://github.com/CosmosPay/CosmosPay-Skill/commit/39f6bafba0404ccd81fc3af20e01f71bd60cbfe8) | feat: add CosmosPay integration skill |
| 22/09 07:34 | Emanuel250YT | [`429a8d1`](https://github.com/CosmosPay/CosmosPay-Skill/commit/429a8d1c6d68ec65b1c715f8620e0c9a7f8a7263) | Merge pull request #1 from CosmosPay/codex/cosmospay-community-skill |

### Pull requests (1)

| # | Abierto | Mergeado | Estado | Autor | Ramas | Título |
|---|---|---|---|---|---|---|
| [#1](https://github.com/CosmosPay/CosmosPay-Skill/pull/1) | 22/09 00:45 | 22/09 07:34 | mergeado | leocagli | `codex/cosmospay-community-skill` → `main` | feat: publish CosmosPay integration skill |

---

## Repositorios sin actividad en el período

`cosmos-app-bridge`, `cosmos-app-runtime`, `cosmos-wallet-landing`, `paydev`, `CosmosPay`, `cosmos-pay-backend`, `cosmos-pay-frontend`, `.github`.

## Notas

- En `cosmos-backend`, los commits `88e9aa4` y `4871b88` se escribieron el 09/09 pero entraron a `main` el 23/09 con el PR #2, por eso aparecen en este período.
- En `CosmosJS_SDK`, los PRs #5 y #10 se abrieron antes del 12/09 y se mergearon dentro del período.
