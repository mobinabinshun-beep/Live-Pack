# N.U Live-Pack — single-slot lock

- Lock ID: `NU-LIVE-PACK-SINGLE-SLOT`
- Repository: https://github.com/mobinabinshun-beep/Live-Pack
- State: **RESERVED / EMPTY / ACTIVATION-BLOCKED**
- Active pack: **NONE**
- Active pack count: **0**
- Allowed maximum: **1**
- Lock scope: the one canonical public demo pack and its active Pages deployment only.

## Meaning

This is the one and only live-slot lock record. It reserves the repository for exactly one active demo pack once migration is safe. It does not claim that a pack is currently deployed, running, machine-approved, human-tested or owner-accepted.

## Activation gate

Do not populate or deploy the live slot until all are evidenced:

1. Exact currently served demo identity is verified against the Pages deployment and HTTP response; all runtime snapshot baskets are captured or explicitly dispositioned under the canonical sections 18–19 protocol.
2. The exact deployed pack and all required assets/dependencies are recoverable and hash-verified.
3. The source-to-Live-Pack transfer is complete with explicit provenance and no unrelated product changes.
4. All whole-demo entrypoints (index/library, Launcher, Casino, Exchange, Pixel Art Studio, SIM PIXEL and support routes), relative assets, navigation, state flows and report links resolve within the same deployment SHA and origin.
5. Required automated checks pass on one exact commit.
6. An exact pre-deploy backup is verified.
7. The new Pages deployment is live and its served build identity is independently verified.

## State transitions

`RESERVED / EMPTY` → `ACTIVE / HUMAN-QA-PENDING` only after the activation gate.

`ACTIVE / HUMAN-QA-PENDING` → `ACTIVE / HUMAN-QA-PASSED` only after recorded human reports and explicit owner acceptance for that exact build and scope.

A new candidate replaces the same live slot; it does not create another live pack. Preserve prior builds through the existing backup/archive system. A human rejection returns the slot to a correction cycle; it does not erase evidence.

## Non-negotiable boundaries

- Live means demo/test environment, never production promotion.
- Machine PASS is not human PASS.
- Human PASS is not a separate release authorization.
- No production release, promotion or launch is authorized by this lock.
- No credentials, secrets, private tester data or unnecessary personal data may be stored here.
- Do not weaken repository security or branch protections to implement this lock.
