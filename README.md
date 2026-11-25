# N.U Live-Pack

**Purpose:** the single canonical home of the one dependency-closed public demo site for all N.U games and tools, as clarified by the owner scope addendum.

This repository is not a product-release channel and not a historical archive. Its one live slot is reserved for the current demo used for execution, machine testing, human testing, issue/report collection and explicit owner acceptance.

## Current state

- Live slot: **EMPTY — migration blocked pending final runtime-baseline verification**
- Active pack count: **0** (target invariant: exactly 1 when activated; never 2)
- Human QA: not handed off from this repository
- Owner acceptance: not claimed
- GitHub Pages / live URL: not yet configured or verified here

## Canonical controls

- [Single Live-Pack contract](./LIVE-PACK-CONTRACT.md)
- [The one and only Live-Pack lock](./LIVE-PACK-LOCK.md)
- [Owner scope addendum — whole N.U games and tools demo site](./OWNER-SCOPE-ADDENDUM.md)

## Source and intended entry point

- Previous source repository: https://github.com/mobinabinshun-beep/mobinabinshun-beep
- Previous Studio entry point: `pixel-art-studio.html`
- Previous public demo URL: https://mobinabinshun-beep.github.io/mobinabinshun-beep/pixel-art-studio.html
- Captured Pages artifact/source identity: commit `8e23c76e4dab7c1cb23ef68b3b964e51a2f314c7`, artifact `14974569577`, SHA-256 `caf0d950ef7ac69e32c0e77879a5214677fb7e66a485743bfd327ced0b8861db`.
- Runtime snapshot record: https://github.com/mobinabinshun-beep/Repository/blob/main/Operations/2026-11-25/NU-PUBLIC-DEMO-RUNTIME-BASELINE-SNAPSHOT-2026-11-25-fa.md

The captured Pages artifact is useful recovery evidence, but direct public-URL HTTP verification was PARTIAL in the capture record. No source/runtime files are copied or redirected until the required live-baseline gate is closed.

## One-slot invariant

Only one active live pack may exist in this repository. Updates replace the contents of that same slot after the prescribed baseline, machine-test and backup gates. Candidate builds, old versions, snapshots and backups belong in their designated source/backup/archive locations, never as parallel live packs here.

The lock file is the sole authority for the slot's state. Do not create numbered live packs, parallel current folders, or a second active lock.


## Studio repository network

- [N.U Game Studio repository network map](https://github.com/mobinabinshun-beep/Documentation/blob/docs/network-integration-2026-11-25/00-START-HERE/REPOSITORY-NETWORK-INDEX-fa.md)
- [Central historical archive and repository register](https://github.com/mobinabinshun-beep/N.U-Game-Studio-Archive)
- [Live-Pack onboarding record](https://github.com/mobinabinshun-beep/N.U-Game-Studio-Archive/blob/main/02-REGISTERS/SOURCE-REPOSITORY-REGISTER-fa.md)

This repository remains the sole one-slot live QA demo location. The network links do not change the EMPTY / ACTIVATION-BLOCKED state or authorize runtime migration, deployment, or product release.
