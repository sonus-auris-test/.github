# sonus-auris-test

Independent acceptance organization for **sonus-auris**.

The authenticated live inventory contains **28 test repositories** plus this governance repository: 18 generated specialized harnesses and 10 independent legacy suites.

## Generated specialized fleet

| Repository | Acceptance surface |
|---|---|
| `android-recorder-emulator-e2e` | Android recording, lifecycle, permissions, restart, and emulator behavior |
| `ios-recorder-simulator-e2e` | iOS recording, lifecycle, permissions, restart, and simulator behavior |
| `scheduled-capture-e2e` | Always-on and scheduled capture windows, transitions, and recovery |
| `permission-lifecycle-e2e` | Permission grant, denial, revocation, relaunch, and recovery |
| `audio-codec-container-e2e` | Audio codecs, containers, duration, metadata, and corruption handling |
| `encryption-key-rotation-e2e` | On-device encryption, key rotation, overlap, rollback, and loss handling |
| `retention-pruning-e2e` | Retention limits, plaintext-to-encrypted transitions, pruning, and restart durability |
| `evidence-integrity-e2e` | Hashes, manifests, ordering, tamper detection, and evidentiary export integrity |
| `offline-sync-e2e` | Offline recording metadata, conflict handling, retries, and convergence |
| `clients-rust-consumer` | Rust SDK consumption and compatibility |
| `clients-typescript-consumer` | TypeScript SDK consumption and compatibility |
| `clients-dart-consumer` | Dart/Flutter SDK consumption and compatibility |
| `api-contract-e2e` | Recorder, session, upload, retention, export, and authentication API contracts |
| `web-console-e2e` | Browser console workflows, accessibility, privacy, and error states |
| `desktop-shutdown-e2e` | Desktop quit, flush, permission, tray, and shutdown lifecycle |
| `waveform-golden-e2e` | Deterministic waveform rendering and audio-derived golden fixtures |
| `long-run-soak-e2e` | Long-duration capture, resource bounds, rollover, and recovery |
| `mcp-contract-e2e` | MCP schemas, authorization, redaction, and administrative boundaries |

Each repository’s generated plan and immutable source pins are authoritative. Metadata validation, source-gate detection, or a skipped device/provider job is not product acceptance. Gated integration must execute a real product entrypoint and fail closed when dependencies are unavailable.

## Preserved independent fleet

| Repository | Unique coverage retained pending semantic comparison |
|---|---|
| `android-ios-recorder-emulators` | Combined mobile emulator matrix and cross-platform recording scenarios |
| `desktop-recorder-e2e` | Independent desktop recorder lifecycle and evidence fixtures |
| `clients-api-contract` | Cross-client and API consumer matrix |
| `audio-retention-encryption` | Combined retention, plaintext window, encryption, and recovery invariants |
| `scheduled-always-on` | Always-on scheduling and failover scenarios |
| `voxletra-transcription` | Voxletra transcription interoperability and privacy boundaries |
| `multi-device-sync` | Multi-device synchronization and conflict scenarios |
| `permission-lifecycle` | Independent mobile/desktop permission lifecycle coverage |
| `long-duration-soak` | Independent long-duration and resource-bound soak evidence |
| `recovery-export-evidence` | Recovery, export, chain-of-custody, and legal-evidence scenarios |

These repositories are not retirement candidates merely because a generated repository has a similar name. Retirement requires a semantic comparison proving that every unique invariant, fixture, failure mode, and relevant history has an explicit destination.

Pull-request checks remain deterministic and credential-free. Private cross-organization materialization requires approved short-lived GitHub App installation tokens with no PAT or persistent-token fallback. Device, provider, database, chaos, scale, and soak execution remains scheduled or manually gated.
