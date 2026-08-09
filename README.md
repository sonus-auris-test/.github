# sonus-auris-test governance

Organization-wide community health, privacy, evidentiary integrity, and reusable workflow policy for Sonus Auris acceptance testing.

The authenticated installation contains **29 repositories total**: this governance repository plus **28 test repositories**. The test fleet consists of 18 generated specialized harnesses and 10 independent legacy suites. Both portfolios remain visible until semantic behavior and history comparisons prove that every unique invariant, fixture, failure mode, and useful historical decision has an explicit destination.

## Baseline

- Pin source repositories and third-party actions to immutable commits.
- Preserve declared Git submodule, Zed, and native-package dependency lanes.
- Run deterministic, credential-free pull-request checks.
- Execute real product assertions; metadata-only, skipped-success, and fixture-presence checks are not acceptance evidence.
- Classify failures as product regressions, blocked dependencies, or harness regressions.
- Retain exact revisions, environment details, results, and sanitized artifacts needed to reproduce evidence.
- Keep production audio, private messages, biometrics, credentials, and evidentiary recordings out of fixtures, logs, artifacts, and summaries.
- Use approved short-lived GitHub App installation tokens for gated private cross-organization materialization; do not add PAT or persistent-token fallbacks.
- Keep device, emulator, desktop, provider, database, chaos, scale, and soak checks scheduled or manually gated.

See `profile/README.md` for the exact 28-repository acceptance inventory and the preservation boundary between the generated and independent suites.


<!-- ore-org-baseline:begin -->
## Organization-wide defaults

This public repository is the canonical source for GitHub-supported community-health fallbacks, organization profile content, contribution guidance, public security/support policy, issue and pull-request templates, and agent-governance declarations for [`sonus-auris-test`](https://github.com/sonus-auris-test).

## Canonical organization links

- GitHub organization: https://github.com/sonus-auris-test
- Public organization defaults: https://github.com/sonus-auris-test/.github
- Canonical Linear project: https://linear.app/denman/project/githubcomsonus-auris-test-226a3ded82fb
- Fleet tracking issue: https://github.com/ORESoftware/k8s-cluster/issues/1222

## Safety baseline

All Git conflicts must be resolved semantically with full historical, repository-wide, organization-wide, and relevant external-organization context. Automated agents are hard-denied from destructive or history-rewriting operations, including all forms of `git stash`, `git reset`, `git clean`, `git filter-repo`, force pushing, destructive deletion, data or infrastructure teardown, credential revocation, and policy bypass.

## GitHub inheritance boundary

GitHub can use supported community-health files from a public organization `.github` repository as fallbacks and can render `profile/README.md` on the organization page. `agents.md`, `AGENTS.md`, Copilot instructions, workflows, settings, rulesets, branch protections, permissions, and secrets are not automatically inherited merely because they exist here. Each repository must carry or synchronize compatible local policy and explicitly call reusable workflows where enforcement is required.

Generated managed-policy version: `2026-08-08`.
<!-- ore-org-baseline:end -->

<!-- BEGIN MANAGED REPOSITORY RELATIONSHIPS v1 -->
## Repository relationship registry

`sonus-auris-test` declares repository roles, dependency edges, cross-organization capabilities, deployment ownership, and the git-submodule/Zed-package contract:

- [Human-readable map](architecture/REPOSITORY_RELATIONSHIPS.md)
- [Machine-readable manifest](architecture/repository-relationships.json)
- [JSON Schema](architecture/repository-relationships.schema.json)

The public registry withholds private repository names and edges.
<!-- END MANAGED REPOSITORY RELATIONSHIPS v1 -->
