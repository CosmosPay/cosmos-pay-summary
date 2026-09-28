# Changelog — Cosmos Pay

## Useful links

| Resource | What is there |
|---|---|
| 🔎 [**Customer discovery**](https://drive.google.com/drive/folders/12ptY7S2VAlkPxbdrgF29zUTOs41A1qvn?usp=sharing) | Customer interviews (Cosmos Pay \| Customer Interview) |
| 📁 [**All work so far**](https://drive.google.com/drive/folders/1o4MkIxEV5sDReQ04XtSG74anE6rMP1AV?hl=es-419) | Shared Cosmos folder with all the work done to date |
| 🎨 [**Brandbook**](https://drive.google.com/drive/folders/1-9_LJAWzupN-8JNaEsJ-7cs6PHytv4Sg?hl=es-419) | Cosmos brand identity and brand assets |
| ⛓️ [**Live on-chain activity**](README.md#live-on-chain-activity--cosmos-wallet-users) | Mainnet transactions of Cosmos Wallet users |

Overall changelog for the `CosmosPay` organization, from **Saturday 12/09/2026 at 15:00 (Argentina time, UTC-3)** to **27/09/2026 21:31 (ART)**. Dates use the DD/MM format.

The changelog is ordered by work priority:

1. **Unreleased: on `dev`.** Work integrated into `dev` that has not reached `main` yet.
2. **In progress: working branches and open PRs.** Work that is not merged anywhere yet.
3. **Released: shipped to `main`.** Versions published during the period.

Commit-level detail is in the [README](README.md).

> **Update 27/09 evening:** `dev` was promoted to `main` in the Wallet, the Community Server and the Developer Platform. All the sign-in, recovery and passkey work that was waiting on `dev` now ships as **Wallet v1.11.0 / v1.11.1**, **Community Server v1.4.0** and **Developer Platform v0.5.0**. The open feature PRs (BlindPay, Earn and DeFindex) and almost all Dependabot PRs were merged too.

---

## 1. Unreleased — on `dev`

Only `CosmosJS_SDK` still has work waiting on `dev`.

#### CosmosJS_SDK (1 commit on `dev`)
- **Added:** `AliasManager` and `AssetManager` for aliases and the asset registry.

---

## 2. In progress — working branches and open PRs

- **CosmosJS_SDK:** Dependabot update for `@types/node` (#12), still open.
- **CosmosPay-Community-Server:** PR #91 (non-custodial Sub Rosa private RFQs, an external contribution) was **closed without merging**.

Nothing else is open. Every other feature and dependency PR from the period has been merged.

---

## 3. Released — shipped to `main`

### Versions

| Repository | First release in period | Latest release in period | Stable releases |
|---|---|---|---|
| CosmosPay-Wallet | v1.8.0-dev.79 | **v1.11.1** | v1.8.0, v1.9.0, v1.10.0, **v1.11.0**, **v1.11.1** |
| CosmosPay-Community-Server | v1.1.1 | **v1.4.0** | v1.1.1, v1.2.0, v1.3.0, v1.3.1, **v1.4.0** |
| CosmosPay-Developer-Platform | v0.2.2 | **v0.5.0** | v0.2.2, v0.3.0, v0.4.0, v0.4.1, **v0.5.0** |
| CosmosJS_SDK | v2.0.0 | v2.0.0 | v2.0.0 (breaking) |

The Wallet `-dev.N` builds are prereleases generated from `dev`. Stable versions are cut from `main`.

### CosmosPay-Wallet — v1.11.0, v1.11.1 (27/09)

**Sign-in, account recovery and passkeys**
- **Added:** new sign-in methods UI, which replaces the old social login component.
- **Added:** styles for account recovery and onboarding.
- **Added:** SEP-10 authentication and account recovery improvements.
- **Added:** the sign-in backend can be switched with a flag instead of a rewrite.
- **Added:** account recovery with identity tokens and email codes.
- **Added:** session token handling during sign-in and recovery.
- **Added:** passkey unlock, plus commands to create and retrieve passkeys and check their status.
- **Added:** MFA setup during sign-in.
- **Added:** OpenAPI sync script and gateway contract tests.
- **Removed:** legacy Pollar tests, replaced with tests for purging legacy wallets.

**Earn, ramps and DeFindex**
- **Added:** BlindPay on/off-ramp actions on the home screen, using bank funding language (PR #78).
- **Added:** yield protocol directory in "Earn" (PR #80).
- **Added:** DeFindex vault integration, accepting human-readable amounts (PR #81).
- **Fixed:** direct web route for Earn (PR #79).

**Platform and dependencies**
- **Added:** dev icons for local builds on every platform.
- **Changed:** `@stellar/stellar-sdk` 16.3.0 → 17.1.0 (PR #77), with the code and the DeFindex contract calls adapted to the new XDR shape.
- **Changed:** npm and Rust dependencies updated to latest, including `@astrojs/react` 7.0.0 (PRs #82, #83 and #84).
- **Changed:** better error handling in the development proxy, with trimmed dependencies.
- **Fixed:** the Android `cosmos` plugin compiles against API 36 for Tauri 2.12 (PR #85).
- **Changed (v1.11.1):** OpenAPI contract synced with the community server (PR #87).
- *Shipped through PR #86 (v1.11.0) and PR #88 (v1.11.1).*

### CosmosPay-Wallet — v1.8.0, v1.9.0, v1.10.0
- **Added (v1.8.0):** social login with email verification and access codes.
- **Added (v1.8.0):** commission handling and validation for swaps (PR #73).
- **Fixed (v1.8.0):** Android setup now includes the packages needed for builds to succeed.
- **Changed (v1.9.0):** the wallet moves to the new Cosmos brand identity, and the welcome screen name is now an SVG lockup.
- **Changed (v1.10.0):** minor and patch dependency updates (PR #76).
- **Deployed:** 3 deployments of the web app to GitHub Pages.

### CosmosPay-Community-Server — v1.4.0 (27/09)

**Wallet sign-in and recovery**
- **Added:** the community server serves the wallet's own sign-in (`wallet-auth`).
- **Added:** Authentik support as an OIDC provider.
- **Added:** handling of unverified emails in the Authentik sign-in flow.
- **Added:** `max_age` enforcement in the Authentik sign-in flow.
- **Added:** return URL handling for wallet authentication.
- **Added:** v3 backup box with password and passkey slots.
- **Added:** SEP-30 security scheme for account routes in the OpenAPI spec.
- **Added:** Swagger tests and improved OpenAPI documentation.
- **Added:** `AGENTS.md` with the repository conventions.
- **Fixed:** `wallet-auth` now matches the wire contract the wallet actually sends.
- **Changed:** the display name is sent to the provisioner.
- **Changed:** the console endpoints stay inside the `wallet` namespace.
- **Removed:** Pollar integration (`PollarWalletsService`, its references and its e2e tests).

**BlindPay and DeFindex**
- **Fixed:** expired BlindPay quotes are rejected (PR #92).
- **Fixed:** BlindPay payment execution is idempotent; the quote check returns the execution key (PR #93).
- **Added:** DeFindex gateway API, served at `/v1/defindex` (PR #94).

**Platform and dependencies**
- **Fixed:** `dev` CI is green again (lint and `wallet-auth` e2e) (PR #97).
- **Changed:** dependencies and GitHub Actions updated to latest, including `dotenv` 18.0.3 and 15 minor/patch updates (PRs #95, #96 and #98).
- *Shipped through PR #99.*

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

### CosmosPay-Developer-Platform — v0.5.0 (27/09)
- **Added:** OAuth flow for wallet sign-in.
- **Added:** SEP-10 (Stellar Web Authentication) and SEP-30 (account recovery).
- **Added:** SEP-30-compliant recovery API with better error handling.
- **Added:** paginated account listing.
- **Added:** recovery code endpoint and its schema.
- **Added:** `wallet-auth` console endpoints, which were moved under `api/wallet/`.
- **Added:** security definitions and public routes in the OpenAPI spec.
- **Added:** documentation for `AliasManager` and `AssetManager`, plus new methods documented for `Client` and `PaymentIntentManager`.
- **Added:** `AGENTS.md` with API documentation and development guidelines.
- **Changed:** clearer `wallet-auth` API descriptions: session tokens, email verification, return URLs, new error responses, and the sealed box with password and passkey.
- **Changed:** Zod imports now use the extended version from the OpenAPI library.
- **Changed:** new unit tests for wallet authentication; the obsolete recovery and SEP-10 tests were removed.
- **Removed:** Pollar social login (PR #52).
- **Fixed:** the docs `llms.txt` index is awaited (fumadocs-core 16.15.13).
- **Changed:** dependencies updated to latest (PRs #50, #51 and #53).
- *Shipped through PR #54.*

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

### .github (organization profile)
- **Added:** organization profile README.

---

## CI health

- 263 workflow runs during the period, covering CI, releases, deployments and Dependabot.
- 36 runs failed:
  - Wallet: 16;
  - Community Server: 8;
  - Developer Platform: 11;
  - SDK: 1.
- 12 runs were cancelled.
- The README has a per-branch breakdown of these runs.
