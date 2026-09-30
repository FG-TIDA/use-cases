# Verifier-side challenge reference (silent-failure-catalog)

> Executable reference implementation for the UC-4 / UC-6 verification question discussed in FG-TIDA/themes #13 and FG-TIDA/use-cases #22.

This folder points to a **publicly resolvable, independently checkable evidence artefact** — [`silent-failure-catalog`](https://github.com/zhaoxinghua09-cell/silent-failure-catalog) (GitHub release v0.1.0, pinned `manifest.sha256` + `gates.yml` CI) — which already contains **executable entries SF-005, SF-006 and SF-011** named in the #13 correspondence (dakleyer, 2026-09-29).

## Why this is a reference implementation (not a description)

- **Executable offline from the record alone**: each entry ships a detection recipe runnable with stdlib only, no network.
- **Pinned manifest**: `manifest.sha256` records every file's SHA-256; integrity is verifiable without contacting the author.
- **Pinned, citable snapshot**: GitHub release `v0.1.0` is the pinned, citable snapshot; integrity is fixed by `manifest.sha256` set digest `7449337e5f315e1f71d64a65d03a8673d85ced1cb17ba70af2f2da8a57132060` at pin `82018d3c`. (Zenodo archival is configured via `.zenodo.json` and will resolve on first tagged release; **no DOI is asserted here until it resolves**.)
- **Negative-control workflow**: the `gates.yml` CI proves which checks are *actually executed* — the same "reported success while checking nothing" failure shape this catalog documents.
- **Reproducible**: clone → run `tools/check-catalog.py --selftest` → red if any gate fails.

## Entries referenced from #13

| Entry | Link |
|---|---|
| SF-005 neutral-marker-not-counted | [failures/SF-005-neutral-marker-not-counted.md](https://github.com/zhaoxinghua09-cell/silent-failure-catalog/blob/main/failures/SF-005-neutral-marker-not-counted.md) |
| SF-006 undeclared-not-checked | [failures/SF-006-undeclared-not-checked.md](https://github.com/zhaoxinghua09-cell/silent-failure-catalog/blob/main/failures/SF-006-undeclared-not-checked.md) |
| SF-011 always-green-oracle | [failures/SF-011-always-green-oracle.md](https://github.com/zhaoxinghua09-cell/silent-failure-catalog/blob/main/failures/SF-011-always-green-oracle.md) |

See [UC4_UC6_MAPPING.md](./UC4_UC6_MAPPING.md) for the per-entry mapping to the UC-4 / UC-6 questions.

## Licensing / rights

- **Code**: MIT. **Content / methodology text**: All Rights Reserved (not covered by MIT; no free redistribution).
- **Attribution**: "Zhao Xinghua / Steven Zhao·China".
- **Brand note**: "SynomosAI" and "MedXpert" are brand names only — no legal entity registered, no trademark registered.
- This is **complementary to** the negative conformance vectors in FG-TIDA/themes #7; not a substitute.
