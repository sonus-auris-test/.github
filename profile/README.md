# sonus-auris-test

Independent acceptance organization for **sonus-auris**.

The authenticated live inventory contains **28 test repositories** plus this governance repository: 18 generated specialized harnesses and 10 independent legacy suites.

## Generated specialized fleet

| Repository | Acceptance surface |
|---|---|
Private repository details are intentionally withheld from this public document.

Each repository’s generated plan and immutable source pins are authoritative. Metadata validation, source-gate detection, or a skipped device/provider job is not product acceptance. Gated integration must execute a real product entrypoint and fail closed when dependencies are unavailable.

## Preserved independent fleet

| Repository | Unique coverage retained pending semantic comparison |
|---|---|
Private repository details are intentionally withheld from this public document.

These repositories are not retirement candidates merely because a generated repository has a similar name. Retirement requires a semantic comparison proving that every unique invariant, fixture, failure mode, and relevant history has an explicit destination.

Pull-request checks remain deterministic and credential-free. Private cross-organization materialization requires approved short-lived GitHub App installation tokens with no PAT or persistent-token fallback. Device, provider, database, chaos, scale, and soak execution remains scheduled or manually gated.

<!-- org-project-routing:start -->
## Planning and delivery

- [GitHub Project: sonus-auris-test-project](https://github.com/orgs/sonus-auris-test/projects/1)
- [Linear planning project](https://linear.app/denman/project/githubcomsonus-auris-test-226a3ded82fb)
- [Detailed project-routing contract](../docs/PROJECTS.md)

GitHub owns code and delivery evidence; Linear owns planning and dependencies. The linked organization Project provides the cross-repository execution view.
<!-- org-project-routing:end -->


<!-- ore-org-baseline:begin -->
## Planning and governance

- Canonical Linear project: https://linear.app/denman/project/githubcomsonus-auris-test-226a3ded82fb
- Organization defaults: https://github.com/sonus-auris-test/.github
- Canonical agent policy: https://github.com/sonus-auris-test/.github/blob/main/agents.md
- Security policy: https://github.com/sonus-auris-test/.github/security/policy

Repositories in this organization use semantic conflict resolution with 3–10 relevant prior commits when useful, full cross-repository context, pull-request delivery, and a hard automated-agent denylist for destructive or history-rewriting operations.
<!-- ore-org-baseline:end -->

<!-- BEGIN MANAGED REPOSITORY RELATIONSHIPS v1 -->
## Repository relationship registry

`sonus-auris-test` declares repository roles, dependency edges, cross-organization capabilities, deployment ownership, and the git-submodule/Zed-package contract:

- [Human-readable map](architecture/REPOSITORY_RELATIONSHIPS.md)
- [Machine-readable manifest](architecture/repository-relationships.json)
- [JSON Schema](architecture/repository-relationships.schema.json)

The public registry withholds private repository names and edges.
<!-- END MANAGED REPOSITORY RELATIONSHIPS v1 -->
