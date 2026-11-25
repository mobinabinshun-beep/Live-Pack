# N.U Live-Pack — runtime-only operating contract

## 1. Purpose and sole slot
`mobinabinshun-beep/Live-Pack` is the only repository/root for the one current, dependency-closed N.U games-and-tools public demo and QA runtime. Product development remains in the product source repository. Historical versions and evidence belong in the Archive; governance, manifests, operation records and QA reports belong in Repository.

## 2. Runtime-only repository content
When active, the Live-Pack runtime root must contain only files required to execute the single current site: entrypoints, transitive modules, styles, assets, public data and strictly required runtime health/service-worker resources. No backup, old version, alternate candidate root, archive, report, manifest, historical HTML, unrelated document or second deployment may be added. No parallel live-v2/candidate root is allowed.

The existing three governance documents are bootstrap records retained while the repository is empty; they are not runtime content. Once a verified runtime pack replaces this bootstrap state, repository governance remains canonical in Repository and historical snapshots in Archive.

## 3. Mandatory pre-write rule
No state-changing action may occur until the owner request and conversation context, purpose, authority, rationale, exact scope, exclusions, dependencies, risks, acceptance criteria and recovery method are recorded. The exact pre-change state must be captured and archived separately with provenance, per-file/config manifest, byte sizes and hashes, then fetched back and verified. The resulting operation record and after-state evidence must also be archived.

The canonical rule is [NU-MANDATORY-OPERATION-DOCUMENTATION-AND-ARCHIVE-GATE](https://github.com/mobinabinshun-beep/Repository/blob/main/Governance/NU-MANDATORY-OPERATION-DOCUMENTATION-AND-ARCHIVE-GATE-fa.md). This is a machine responsibility and a necessary prerequisite for MACHINE-PASS/MACHINE-APPROVED. If any required record, archive, recovery point or evidence is unavailable, status is BLOCKED and no write/deploy is allowed.

## 4. One-pack lifecycle
1. Read applicable governance, source history, issues/PRs, previous reports, current runtime and artifacts.
2. Capture the actually served baseline; distinguish it from current source HEAD and old artifacts.
3. Decompose each prior version into independent baskets (routes, modules, styles, assets, data, service worker, health/report resources) and archive each basket with provenance and manifest. Do not merge different revisions into one ambiguous backup.
4. Complete a dependency-closed manifest for the entire site and resolve every missing/uncertain dependency.
5. Populate only the single canonical Live-Pack root with the selected pack; fetch back and verify every file.
6. Run focused, integration, browser, cross-route and service-worker tests against one exact commit.
7. Archive and verify the exact candidate before deployment.
8. Deploy only that candidate to the single Pages slot; independently verify HTTP served identity, routes and assets.
9. Record exact-build human QA handoff and keep human acceptance distinct from machine results.

## 5. Current verified status (2026-11-25)
- No runtime pack is currently present in this repository.
- The current source audit reports a missing `assets/nu-celestial-city.png` path required by `nu-background-engine.js`; do not substitute another image without explicit owner decision.
- Root README is a runtime health dependency; Exchange service-worker precache and scope need complete validation.
- Full dynamic dependency/report-intake manifest and independent browser/network tests remain open.
- Previous Pages artifact SHA-256 integrity was verified, but public HTTP served identity was not.
- Therefore active pack count is 0; no transfer, Pages activation, deployment, redirect or owner acceptance is claimed.

## 6. Public UI and data
The public UI must present the product, not internal infrastructure. Keep build, backup, CI and QA records outside the runtime UI. Do not copy personal localStorage, saves, private projects, credentials, tokens or tester personal data into GitHub.

## 7. Status vocabulary
Use separate states for IMPLEMENTED, ARCHIVE-READBACK-VERIFIED, SHA256-VERIFIED, RESTORE-TESTED, MACHINE-QA-PASSED/FAILED, DEPLOYMENT-VERIFIED/UNVERIFIED, HUMAN-QA-PENDING/PASSED/FAILED and OWNER-APPROVED/REJECTED. No state implies another.
