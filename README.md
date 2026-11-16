# M-Money

Native Android mobile-money SMS ledger with a Supabase backend and an administration console.

## Repository status: bootstrap only

The initial repository commit is on `main`. **The full application source has not yet been imported into this branch.** The prepared source is the existing X-Integration.7 engineering candidate, not a replacement scaffold.

The source import is complete only when `app/`, `core/`, `supabase/`, `admin/` and `integration/source-lock.json` are present on `main` and the source-integrity checks pass.

## Prepared source

- Publication archive: `M-Money_GitHub_Initial_Source_2026-11-16.zip` (3,143 files).
- SHA-256: `b551a521630375278e951adbadde6d9a19df740c9a5bba41c69bcff8eab7ea3f`.
- Original X-Integration.7 archive SHA-256: `7b2cfa27d51f55e84db9cab85eee758fb88be72f6513aeb333abfdab4bdcf57a`.
- Application version: `0.2.14-mvp2`, version code `19`.

Source-hygiene and complete source-lock checks passed during preparation. Selected host regressions passed: 31 integration, 5 transport wiring, 18 host SQLite and 80 admin tests. These are not Android/device tests or full release acceptance.

## Import execution status

The two attempted GitHub-hosted runner jobs failed before executing any steps. Their cause was not established, and no successful CI run or full source upload is claimed. The temporary import workflow has been removed. A verified source archive and fast-forward import bundle are provided with the handoff; use normal Git authentication to complete the source push without rewriting `main`.

No production deployment, signed APK, physical-device acceptance, hosted-service acceptance, visual approval or release approval is implied. Do not commit credentials, signing keys, private SMS receipts or private operational evidence.
