# Review and promotion path for biopeia/.github

This repository publishes organization-wide community files and reusable workflows.
Changes to `main` must follow the governed pull-request path.

## Required path

1. Open or link a bounded GitHub Issue.
2. Make the change on a non-default branch.
3. Open a Pull Request using the Biopeia PR contract.
4. The `validate-pr-contract` check must pass for the exact PR head.
5. Resolve review conversations before merge.
6. Merge through the Pull Request UI/API. Do not push directly to `main`.

## GitHub enforcement target

Configure `main` with a branch protection rule or repository ruleset that:

- requires a pull request before merging;
- requires status check `validate-pr-contract`;
- requires conversation resolution;
- blocks force pushes;
- blocks branch deletion;
- does not allow routine bypass.

### Approval limitation

Do not configure a required approving-review count that the current maintainer set cannot satisfy without self-approval. GitHub does not count an author's own approval. Until a second independent reviewer with suitable repository access exists, independent human approval is a procedural requirement where the Biopeia work class/risk requires it, not a falsely claimed GitHub-enforced gate.

When an independent reviewer is available, raise the protection/ruleset to at least one required approval and, if appropriate, require Code Owner review.

## Authority

- CI validates technical/structural properties only.
- CODEOWNERS routes review but is not authority by itself.
- Scientific, FROZEN and CONSTITUTIONAL work still requires the competent authority defined by Biopeia governance.
- Administrator emergency bypass, if GitHub settings retain one, is exceptional and must be attributable in the linked Issue/PR.

## Verification

A protection change is complete only after GitHub reports `main` as protected or an active ruleset covers `main`, and a representative PR demonstrates that direct/default-branch publication cannot bypass the configured pull-request/check path.
