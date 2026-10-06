# Verifier-side challenge reference

Executable reference material for the UC-4 / UC-6 verification question raised in
FG-TIDA/themes #13 and FG-TIDA/use-cases #22.

This folder points to a publicly resolvable, independently checkable artefact —
[`silent-failure-catalog`](https://github.com/zhaoxinghua09-cell/silent-failure-catalog) —
which contains the executable entries SF-005, SF-006 and SF-011 named in the #13
correspondence (dakleyer, 2026-09-29).

## Why this is executable material rather than a description

- **Runnable offline from the record alone** — each entry ships a detection
  recipe that runs with the standard library only, with no network access.
- **Integrity recorded in the repository** — a manifest records the SHA-256 of
  every file, so integrity can be checked without contacting the author.
- **Negative-control workflow** — CI records which checks were actually executed,
  which is the same "reported success while checking nothing" failure shape this
  material documents.
- **Reproducible** — clone, run the catalogue self-test, and it fails loudly if
  any gate is broken.

## Entries referenced from #13

| Entry | Link |
|---|---|
| SF-005 neutral-marker-not-counted | [failures/SF-005-neutral-marker-not-counted.md](https://github.com/zhaoxinghua09-cell/silent-failure-catalog/blob/main/failures/SF-005-neutral-marker-not-counted.md) |
| SF-006 undeclared-not-checked | [failures/SF-006-undeclared-not-checked.md](https://github.com/zhaoxinghua09-cell/silent-failure-catalog/blob/main/failures/SF-006-undeclared-not-checked.md) |
| SF-011 always-green-oracle | [failures/SF-011-always-green-oracle.md](https://github.com/zhaoxinghua09-cell/silent-failure-catalog/blob/main/failures/SF-011-always-green-oracle.md) |

See [UC4_UC6_MAPPING.md](./UC4_UC6_MAPPING.md) for the per-entry mapping to the
UC-4 / UC-6 questions.

Offered as material for discussion. Complementary to, and not a substitute for,
the negative conformance vectors raised in FG-TIDA/themes #7.
