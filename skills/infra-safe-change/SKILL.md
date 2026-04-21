---
description: Protect API, webhook, and external integration contracts from accidental breakage.
---

Use this skill when:
- changing API request or response shapes
- modifying webhook payloads
- renaming or removing fields
- updating auth, headers, retries, or idempotency behavior
- changing behavior relied on by external systems

Rules:
1. Assume backward compatibility is the default.
2. Identify consumers before suggesting a contract change.
3. Call out:
   - removed fields
   - renamed fields
   - changed semantics
   - changed defaults
   - changed error codes
4. Prefer additive changes over breaking changes.
5. If a breaking change is unavoidable, state the migration path clearly.
6. Explicitly consider idempotency and retry behavior for webhooks and async integrations.

Output expectations:
- Contract impact summary
- Affected consumers
- Compatibility risk
- Safer alternative if available
- Migration note if required