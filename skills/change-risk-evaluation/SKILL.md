---
description: Evaluate implementation risk before or during a change, especially for API, schema, infra, deploy, auth, or cross-service work.
---

Use this skill when:
- a change may be breaking
- a change affects external systems
- a change affects production behavior
- a change touches data, auth, or deployment

Classify the change as:
- Low risk
- Medium risk
- High risk

Always assess:
1. User impact
2. Backward compatibility
3. Deployment/rollback complexity
4. Test surface
5. Operational risk
6. Data integrity risk
7. Security risk

Output expectations:
- Risk level
- Why it has that risk level
- Preconditions before merge or deploy
- Rollback considerations
- Validation steps