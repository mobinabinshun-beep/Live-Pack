# N.U Live-Pack — operating agreement

## 1. Purpose

`Live-Pack` is the single home for the current N.U public demo site covering all games and tools. It is used to run the demo, perform machine and human testing, and collect issues and reports.

It is not the product source-of-truth development repository or a historical archive.

## 2. One current pack, without a lock

The owner's instruction is explicit: **do not impose a lock, reservation, activation block, mandatory approval gate, or artificial hold on this work.**

Keep one coherent current demo pack in this repository. Do not create parallel live versions or duplicate current-pack roots. Updates may be made directly to the current pack as ordinary repository work. The single-pack/no-parallel-versions principle is an organizational convention, not a lock or permission system.

Historical backups may remain in the designated archive repositories. This does not restrict ordinary edits or progress in this repository.

## 3. Demo site scope

The repository is intended to contain the dependency-closed N.U public demo site for games and tools:

- Source repository: https://github.com/mobinabinshun-beep/mobinabinshun-beep
- Primary entrypoint: `index.html`
- Linked routes: `launcher.html`, `casino.html`, `exchange.html`, `pixel-art-studio.html`, `sim-pixel-demo.html`
- Support route: `404.html`

Transfer or update the runtime pages, modules, styles, assets and public data needed by these routes. Keep unrelated historical/archive material and non-runtime documentation out of the public demo root. `background-candidates.html` is not part of the current route list.

## 4. Provenance and useful verification

A previously captured Pages artifact records source commit `8e23c76e4dab7c1cb23ef68b3b964e51a2f314c7`, artifact `14974569577`, and SHA-256 `caf0d950ef7ac69e32c0e77879a5214677fb7e66a485743bfd327ced0b8861db`. Direct HTTP verification of the old public URL was unavailable at the time of capture.

When practical, preserve source commit/blob provenance and file hashes for transferred files, run automated checks, and verify the resulting Pages URL. These are quality practices, not prerequisites that suspend work or require a separate approval.

## 5. Pages and site connection

The intended GitHub Pages root, once Pages is enabled, is:

- `https://mobinabinshun-beep.github.io/Live-Pack/`

The root should serve `index.html`; all game/tool routes and assets should use the same pack and origin. Update product-hub links when the destination URL is known and available. Do not describe Pages as live until it is actually configured and verified.

## 6. Public UI

The public demo should present the product rather than internal development infrastructure. Keep CI, backup, deployment and QA metadata in repository records, not in product UI. Necessary functional, data-loss and security confirmations remain appropriate.

## 7. Reports

Reports should identify the tested URL/build where available, test date, device, OS, browser/version, viewport/orientation, input method, scenario, expected and actual result, status, and reproducible evidence where practical. Do not collect credentials or unnecessary personal data.

## 8. Repository responsibilities

- Product code and development: `mobinabinshun-beep/mobinabinshun-beep`
- Current public demo pack: `mobinabinshun-beep/Live-Pack`
- Governance, records and manifests: `mobinabinshun-beep/Repository`
- Historical backups: designated archive repositories

## 9. Current factual status

At the time of this update, runtime files have not yet been copied into this repository and GitHub Pages is not configured here. This is a description of the current repository state, **not a lock, prohibition, activation block, or requirement to wait for permission**.
