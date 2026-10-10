# Biopeia governance overview

The [Biopeia Project](https://github.com/orgs/biopeia/projects/1) coordinates work, issues define bounded deliverables, PRs record changes, and CI validates technical properties. Canonical protocols, accepted ADRs, constitutional rules and scientific evidence remain authoritative at their owners.

## Classes of work

- **ORDINARY** — engineering within approved boundaries.
- **SCIENTIFIC** — scientific mechanisms, protocols or experimental evidence.
- **FROZEN** — protected contracts and records; changes require controlled versioning.
- **CONSTITUTIONAL** — fundamental architecture or epistemic principles requiring explicit owner authorization.

Risk is evaluated separately from authority. Neither an issue nor a green CI check authorizes experiment execution, scientific claims, repository cut-over or constitutional change.

During migration, extracted repositories and open PRs are not proof of an approved transition. Retain the original canonical sources until explicit supersession.

## Public .github review path

Changes to this repository follow the enforced review/promotion path documented in [docs/review-path.md](docs/review-path.md). Direct publication to `main` is not the normal governed path.
