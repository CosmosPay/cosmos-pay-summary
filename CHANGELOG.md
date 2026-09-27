# Changelog — Cosmos Pay

Overall changelog for the `CosmosPay` organization, from **Saturday 12/09/2026 at 15:00 (Argentina time, UTC-3)** to **27/09/2026**. Dates use the DD/MM format.

The changelog is ordered by work priority:

1. **Unreleased: on `dev`.** Work integrated into `dev` that has not reached `main` yet.
2. **In progress: working branches and open PRs.** Work that is not merged anywhere yet.
3. **Released: shipped to `main`.** Versions published during the period.

Commit-level detail is in the [README](README.md).

---

## 1. Unreleased — on `dev`

### Wallet sign-in, account recovery and passkeys

#### CosmosPay-Wallet (13 commits on `dev`)
- **Added:** new sign-in methods UI, which replaces the old social login component.
- **Added:** styles for account recovery and onboarding.
- **Added:** SEP-10 authentication and account recovery improvements.
- **Added:** the sign-in backend can be switched with a flag instead of a rewrite.
- **Added:** account recovery with identity tokens and email codes.
- **Added:** session token handling during sign-in and recovery.
- **Added:** passkey unlock, plus commands to create and retrieve passkeys and check their status.
- **Added:** OpenAPI sync script and gateway contract tests.
- **Added:** dev icons for local builds on every platform.
- **Changed:** better error handling in the development proxy, with trimmed dependencies.
- *The work on the `feat/wallet-auth-backend` branch was merged into `dev`.*

#### CosmosPay-Community-Server (11 commits on `dev`)
- **Added:** the community server serves the wallet's own sign-in (`wallet-auth`).
- **Added:** Authentik support as an OIDC provider.
- **Added:** handling of unverified emails in the Authentik sign-in flow.
- **Added:** `max_age` enforcement in the Authentik sign-in flow.
- **Added:** v3 backup box with password and passkey slots.
- **Added:** SEP-30 security scheme for account routes in the OpenAPI spec.
- **Added:** Swagger tests and improved OpenAPI documentation.
- **Added:** `AGENTS.md` with the repository conventions.
- **Fixed:** `wallet-auth` now matches the wire contract the wallet actually sends.
- **Changed:** the display name is sent to the provisioner.
- **Changed:** the console endpoints stay inside the `wallet` namespace.

#### CosmosPay-Developer-Platform (14 commits on `dev`)
- **Added:** OAuth flow for wallet sign-in.
- **Added:** SEP-10 (Stellar Web Authentication) and SEP-30 (account recovery).
- **Added:** SEP-30-compliant recovery API with better error handling.
- **Added:** paginated account listing.
- **Added:** recovery code endpoint and its schema.
- **Added:** `wallet-auth` console endpoints, which were moved under `api/wallet/`.
- **Added:** security definitions and public routes in the OpenAPI spec.
- **Added:** documentation for `AliasManager` and `AssetManager`, plus new methods documented for `Client` and `PaymentIntentManager`.
- **Added:** `AGENTS.md` with API documentation and development guidelines.
- **Changed:** clearer `wallet-auth` API descriptions about session tokens and email verification.
- **Changed:** Zod imports now use the extended version from the OpenAPI library.
- **Changed:** new unit tests for wallet authentication; the obsolete recovery and SEP-10 tests were removed.

#### CosmosJS_SDK (1 commit on `dev`)
- **Added:** `AliasManager` and `AssetManager` for aliases and the asset registry.

---

## 2. In progress — working branches and open PRs

### CosmosPay-Wallet
- **BlindPay ramps on the home screen**, using bank funding language. Branch `codex/visible-modular-ramps`, PR #78 against `main`.
- **Direct web route for Earn.** Branch `codex/web-earn-route`, PR #79 against `main`.
- **Yield protocol directory in "Earn".** Branch `codex/earn-protocol-directory`, PR #80 against `main`.
- **DeFindex vault integration**, accepting human-readable amounts. Branch `codex/defindex-wallet-integration`, PR #81 stacked on top of PR #80.

### CosmosPay-Community-Server
- **Reject expired BlindPay quotes.** Branch `codex/blindpay-quote-expiry`, PR #92.
- **Idempotent BlindPay payment execution.** Branch `codex/blindpay-execution-idempotency`, PR #93.
- **DeFindex gateway API.** Branch `codex/defindex-api`, PR #94.
- **Non-custodial Sub Rosa private RFQs.** PR #91, an external contribution.

### Dependency updates waiting for review
- **CosmosPay-Wallet:** `@stellar/stellar-sdk` 16.3.0 → 17.1.0 (#77), minor/patch group (#82), `@astrojs/react` 7.0.0 (#83).
- **CosmosPay-Community-Server:** minor/patch group with 15 updates (#95), `dotenv` 18.0.3 (#96).
- **CosmosPay-Developer-Platform:** minor/patch groups (#50, #51).
- **CosmosJS_SDK:** `@types/node` (#12).

---

## 3. Released — shipped to `main`

### Versions

| Repository | First release in period | Latest release in period | Stable releases |
|---|---|---|---|
| CosmosPay-Wallet | v1.8.0-dev.79 | v1.11.0-dev.97 | v1.8.0, v1.9.0, v1.10.0 |
| CosmosPay-Community-Server | v1.1.1 | v1.3.1 | v1.1.1, v1.2.0, v1.3.0, v1.3.1 |
| CosmosPay-Developer-Platform | v0.2.2 | v0.4.1 | v0.2.2, v0.3.0, v0.4.0, v0.4.1 |
| CosmosJS_SDK | v2.0.0 | v2.0.0 | v2.0.0 (breaking) |

The Wallet `-dev.N` builds are prereleases generated from `dev`. Stable versions are cut from `main`.

### CosmosPay-Wallet — v1.8.0, v1.9.0, v1.10.0
- **Added (v1.8.0):** social login with email verification and access codes.
- **Added (v1.8.0):** commission handling and validation for swaps (PR #73).
- **Fixed (v1.8.0):** Android setup now includes the packages needed for builds to succeed.
- **Changed (v1.9.0):** the wallet moves to the new Cosmos brand identity, and the welcome screen name is now an SVG lockup.
- **Changed (v1.10.0):** minor and patch dependency updates (PR #76).
- **Deployed:** 3 deployments of the web app to GitHub Pages.

### CosmosPay-Community-Server — v1.1.1 → v1.3.1
- **Changed (v1.1.1):** the authorization model switched to console-based verification, and the admin API credentials were removed (PR #86).
- **Added (v1.2.0):** `SignedTransactionRelay` service for relaying signed transactions.
- **Added (v1.2.0):** stronger wallet ownership verification and provisioning.
- **Added (v1.2.0):** unit tests for the BlindPay webhooks.
- **Changed (v1.2.0):** `$transaction` was replaced with `Promise.all` where appropriate.
- **Added (v1.3.0):** stored envelope handling for Stellar transactions.
- **Added (v1.3.0):** Pollar OAuth session and user registration improvements.
- **Added (v1.3.0):** end-to-end tests for the payment intent `txHash`.
- **Changed (v1.3.0):** receiver updates now require an elevated key.
- **Changed (v1.3.1):** 12 dependency updates (PR #90).

### CosmosPay-Developer-Platform — v0.2.2 → v0.4.1
- **Changed (v0.2.2):** removed the deprecated admin API secrets and updated the Payments API proxy.
- **Changed (v0.2.2):** docs search migrated from Orama to ZBSearch.
- **Changed (v0.2.2):** dependency updates (PRs #41 and #42).
- **Added (v0.3.0):** social login email verification.
- **Added (v0.3.0):** `expected_version` in receiver approval.
- **Added (v0.3.0):** `dossierVersion` and `reviewedVersion` on receivers.
- **Changed (v0.4.0):** rebrand with new tokens, typography and logo, and a new landing page built from the deck with the wallet up front.
- **Added (v0.4.1):** Cosmos Pay skill for agents (skills.stellar.org).

### CosmosJS_SDK — v2.0.0 (breaking)
- **Breaking:** follows the Payments API security contract changes.
- **Added:** `SwapManager`.
- **Added:** `dossierVersion` and `reviewedVersion` on `Receiver`, with updated approval logic.
- **Changed:** updated `PollarManager` documentation.
- **Changed:** relicensed to Apache-2.0 (PR #5).

### Cosmos-frontend (no `dev` branch, shipped directly to `main`)
- **Changed:** full rebrand, including:
  - new palette, Open Sauce One typography and SVG logo;
  - header, search, footer and mockup reskinned;
  - seven-section landing page based on the deck;
  - three rounds of review fixes;
  - section /06 featuring the wallet and the platform;
  - the agency's official character added to the repo;
  - Argentine flag for Spanish.
- **Changed:** new backend `api.cosmosapp.lat` and host `cosmosapp.lat`.
- **Fixed:** a broken chart no longer blanks the `/panel` page.
- **Deployed:** 4 production deployments.

### cosmos-backend (no `dev` branch)
- **Fixed:** uploaded image URLs are now built over HTTPS, and `multer` was bumped to 2.3.0 (PR #2).
- **Changed:** `snapshot-v1` promoted to `main` (PR #3).

### CosmosPay-Skill (new repository)
- **Added:** CosmosPay integration skill for agents (PR #1).

---

## CI health

- 187 workflow runs during the period, covering CI, releases, deployments and Dependabot.
- 26 runs failed:
  - Wallet: 10;
  - Community Server: 6;
  - Developer Platform: 9;
  - SDK: 1.
- 7 runs were cancelled.
- The README has a per-branch breakdown of these runs.
