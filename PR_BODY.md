## Summary

This contribution adds a verifier-side challenge reference set for the UC-4 / UC-6 verification question discussed in #13 and #22.

It points to a **publicly resolvable, independently checkable evidence artefact** — the `silent-failure-catalog` — which already contains **executable entries SF-005, SF-006 and SF-011** named in the #13 correspondence (dakleyer, 2026-09-29).

## What makes this a reference implementation (not a description)

- **Executable offline from the record alone**: each entry ships a detection recipe runnable with stdlib only, no network.
- **Pinned manifest**: `manifest.sha256` records every file's SHA-256; integrity is verifiable without contacting the author.
- **Publicly resolvable artefact**: the catalog ships `manifest.sha256` (every file SHA-256) and a `gates.yml` CI workflow; GitHub release v0.1.0 is the pinned, citable snapshot. (Zenodo archival is configured via `.zenodo.json` and will resolve on first tagged release; no DOI is asserted here until it resolves.)
- **Negative-control workflow**: the `gates.yml` CI proves which checks are *actually executed* — the same "reported success while checking nothing" failure shape this catalog documents.
- **Reproducible**: clone → run `tools/check-catalog.py --selftest` → red if any gate fails.

## Mapping to UC-4 / UC-6 (from #13)

| Our entry | UC-4/UC-6 question it answers |
|---|---|
| SF-005 neutral-marker-not-counted | Does missing required approval evidence affect the admission decision, or merely appear as a note beside an overall pass? |
| SF-006 undeclared-not-checked | Can participation/provenance checks expose a material contribution omitted from the declared record? |
| SF-011 always-green-oracle | Does the verifier still reject the deliberately invalid case after changes to rule/implementation/test? |

Full per-entry mapping: `contributions/verifier-side-challenge-reference/UC4_UC6_MAPPING.md`

## Licensing / rights

Offered under the project's layered notice: **code MIT, content All Rights Reserved** (upstream LICENSE / LICENSE-CONTENT). Attribution: "Zhao Xinghua / Steven Zhao·China". Not a substitute for the negative conformance vectors in #7; complementary to them.

## Next step

We can table the exact UC-4 selection (SF-011 as expected-rejection, SF-005 as legitimate-pass) after today's call, alongside the challenge round agreed in #13.
