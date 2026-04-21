---
description: Protect state consistency, data correctness, and transactional integrity for backend and workflow changes.
---

Use this skill when:
- changing DB writes
- changing workflow state transitions
- changing financial/accounting logic
- changing retries, queues, or background jobs
- changing logic that can be executed more than once

Rules:
1. Check for partial update risk.
2. Check for duplicate execution risk.
3. Check for ordering dependencies.
4. Check for transactional boundaries.
5. Check for idempotency where relevant.
6. Call out any state invariants that could be violated.

Output expectations:
- Integrity risk summary
- Main failure modes
- Recommended safeguards
- Validation strategy