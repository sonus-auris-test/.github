# sonus-auris-test

Independent acceptance organization for **sonus-auris**.

Always-on audio mobile/desktop, SDK/API, encryption/retention, scheduling, Voxletra, sync, permissions, soak, and evidence export.

## Portfolio

| Repository | Class | Readiness | Primary dependency path |
|---|---|---|---|
| `android-ios-recorder-emulators` | mobile/emulator | `ready` | `matrix` |
| `desktop-recorder-e2e` | desktop E2E | `ready` | `matrix` |
| `clients-api-contract` | SDK consumer | `ready` | `matrix` |
| `audio-retention-encryption` | security | `ready` | `matrix` |
| `scheduled-always-on` | scheduler/failover | `ready` | `matrix` |
| `voxletra-transcription` | interoperability | `mixed` | `matrix` |
| `multi-device-sync` | synchronization | `ready` | `matrix` |
| `permission-lifecycle` | security | `ready` | `matrix` |
| `long-duration-soak` | performance/scale | `ready` | `matrix` |
| `recovery-export-evidence` | interoperability | `ready` | `matrix` |

Pull requests run deterministic harness checks. Emulators, desktop matrices, live APIs/providers, databases, chaos, scale, and soaks are scheduled/manual. Missing upstreams or credentials are blocked readiness—not false passes or product regressions.
