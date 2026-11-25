# N.U Live-Pack — operating contract

## 1. Single purpose

`Live-Pack` is the sole repository for the one currently active N.U public demo pack. It is the live laboratory for:
- running the current demo;
- machine smoke/regression checks;
- human testing by the owner and invited testers;
- issue, defect and test-report intake;
- recording exact-build human results and owner acceptance.

It is not the source-of-truth development repository, product-release repository, backup archive, or a place for multiple parallel live candidates.

## 2. One active pack only

The governing owner-ratified rule is [REL-SINGLEPACK-001 — Single Live-Pack / No Parallel Versions](https://github.com/mobinabinshun-beep/Repository-of-protocols-principles-norms-manifestos-and-rules-for-the-Game-N.U-Studio-project./blob/main/01-PROTOCOL-REGISTRY/REL-SINGLEPACK-001-fa.md).

The repository has one live slot and one lock record: [LIVE-PACK-LOCK.md](./LIVE-PACK-LOCK.md). When active, the slot contains one complete, deployable pack. Do not add `live-v2`, `candidate-2`, parallel deployment roots, or additional active locks. Replace the one slot through a verified update process. Keep historical builds in the designated backup/archive repositories.

## 3. Migration target

**Binding scope override:** the [OWNER-SCOPE-ADDENDUM.md](./OWNER-SCOPE-ADDENDUM.md) supersedes the Studio-only wording below. The single live slot is the whole dependency-closed games-and-tools demo site; see the addendum and the Repository no-parallel-versions protocol.

The binding owner scope is the dependency-closed N.U public demo site for games and tools:
- source repository: https://github.com/mobinabinshun-beep/mobinabinshun-beep
- primary entrypoint: `index.html`
- linked routes: `launcher.html`, `casino.html`, `exchange.html`, `pixel-art-studio.html`, `sim-pixel-demo.html`
- support route: `404.html`
- prior Pages origin: https://mobinabinshun-beep.github.io/mobinabinshun-beep/

Transfer only the runtime pages, modules, styles, assets and public data required by those routes, determined by a path-level dependency manifest. Exclude historical/archive HTML, non-runtime documentation and unrelated files. `background-candidates.html` remains excluded pending classification. Internal navigation and report links must resolve within the new canonical origin; intentional external publication links remain external.

## 4. Migration gate and provenance

A prior Pages snapshot records deployed source commit `8e23c76e4dab7c1cb23ef68b3b964e51a2f314c7`, Pages artifact `14974569577`, and artifact SHA-256 `caf0d950ef7ac69e32c0e77879a5214677fb7e66a485743bfd327ced0b8861db`. The artifact and decomposed source baskets were captured; direct HTTP verification of the public URL was marked PARTIAL / NOT ACCESSIBLE in the snapshot record.

Before any runtime migration write:
- finish/refresh the live runtime snapshot under sections 18–19 of the canonical N.U unified protocol;
- verify that the captured artifact remains downloadable and its digest matches;
- verify the actual served HTML/build identity or explicitly document the remaining unverified basket and keep activation blocked;
- record a PRE-CHANGE recovery ref and a transfer manifest with source path, source commit/blob, destination path, byte size and SHA-256 for every transferred file.

No claim of complete migration or backup is valid without fetch-back and hash verification.

## 5. Pages and page connection

GitHub Pages for this repository must serve the one whole-site demo pack from this repository's default branch. The root URL serves `index.html`; all game/tool routes and assets share this pack and origin. Product-hub links change only after the new Pages URL and build identity are independently verified.

Expected URLs after Pages configuration is verified:
- Root/library: `https://mobinabinshun-beep.github.io/Live-Pack/`
- Studio: `https://mobinabinshun-beep.github.io/Live-Pack/pixel-art-studio.html`

This is an intended URL, not a claim that Pages is configured or live today.

## 6. QA lifecycle and public UI

Required sequence: runtime baseline → scoped transfer/update → automated checks → verified pre-deploy backup → Pages deployment → live URL/build verification → post-deploy smoke → human QA handoff → explicit owner decision.

The exact candidate commit/build identity, test status, known limitations and QA handoff evidence belong in repository records and reports, not in the public product UI. The public demo must match the downloadable/local product experience wherever the environment supports the same behavior. The only permitted public-demo introductory text is:

`Welcome to N.U — Public Test Demo`

Necessary functional, data-loss and security confirmations remain allowed. Infrastructure, development, CI, backup, deployment and QA labels/metadata must not be displayed as product UI. This section follows the owner-mandated Demo/Product Parity and Clean UI Principle (2026-11-24), which supersedes older instructions requiring visible candidate/build labels inside the page.

Human QA and owner acceptance are separate evidence states. Deploying a demo candidate is QA handoff, not product release or production promotion.

## 7. Reports and acceptance

Each report identifies the exact URL/build SHA, test date, device, OS, browser/version, viewport/orientation, input method, scenario, expected and actual result, PASS/FAIL/BLOCKED, and reproducible evidence where possible. Do not collect credentials or unnecessary personal data.

Only the owner can record acceptance for the exact build and scope. Acceptance does not authorize production promotion; that requires a separate direct owner instruction.

## 8. Cross-repository ownership

- Product code and development remain in `mobinabinshun-beep/mobinabinshun-beep`.
- The single live QA pack and its Pages deployment belong in `mobinabinshun-beep/Live-Pack`.
- Governance, canonical records, manifests and historical backups remain in `mobinabinshun-beep/Repository`.
- The archive repository must index this repository as a first-class N.U repository.
- Activation work is tracked in [Live-Pack issue #1](https://github.com/mobinabinshun-beep/Live-Pack/issues/1).

## 9. Current state

As of 2026-11-25: contract and slot reservation are documentation-only. No runtime files have been migrated, no page has been redirected, Pages has not been verified for this repository, and the live slot remains EMPTY / ACTIVATION-BLOCKED.


<!-- owner single-live-pack scope update pending canonical protocol sync -->
