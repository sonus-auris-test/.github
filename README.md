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
