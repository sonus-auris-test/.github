## Acceptance surface

- [ ] Source repositories and third-party actions are pinned to immutable commits.
- [ ] Declared Git submodule, Zed, and native-package lanes are preserved.
- [ ] Executable product assertions run; this is not a no-op, metadata-only, skipped-success, or fixture-presence check.
- [ ] Failure, cancellation, restart, and recovery paths execute where applicable.
- [ ] Failure classification is explicit: product regression, blocked dependency, or harness regression.
- [ ] Device, emulator, desktop, provider, database, chaos, scale, and soak execution is justified and appropriately gated.
- [ ] Fixtures are synthetic; logs and artifacts contain no credentials, production audio, private messages, biometric material, or evidentiary recordings.
- [ ] Evidence records the exact upstream revision, environment, result, and retained artifacts needed to reproduce the outcome.
- [ ] Overlapping or superseded work has a semantic trace for every unique invariant, fixture, failure mode, and useful history retained or intentionally rejected.
