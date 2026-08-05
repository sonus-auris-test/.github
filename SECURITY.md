<!-- semantically reconciled from the independent and generated governance branches. -->
# Security policy

Do not commit access tokens, production credentials, raw biometric material, unencrypted private media, unredacted message content, or evidentiary recordings. Reproduce failures with synthetic fixtures and report vulnerabilities privately to the production owner.

Pull-request jobs must remain credential-free. Gated private cross-organization integration may use only an approved short-lived GitHub App installation token with least privilege. Do not add PAT fallbacks, persistent fleet tokens, or credentials written to files, artifacts, summaries, or logs.

Metadata validation, source-gate detection, and skipped emulator/provider jobs must never be represented as product or evidentiary acceptance success.
