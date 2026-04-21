---
description: Evaluate infrastructure and deployment changes safely before applying them.
---

Use this skill when:
- changing deployment config
- modifying Docker, CI/CD, Terraform, cloud resources, or environment variables
- adjusting service scaling, secrets usage, or network/security settings

Rules:
1. Prefer minimal infra changes.
2. Call out environment-specific assumptions.
3. Highlight:
   - secrets exposure risks
   - permission scope changes
   - rollback difficulty
   - downtime risk
   - missing observability
4. Never assume deploy safety without verification.
5. Prefer changes that are easy to roll back.

Output expectations:
- Infra change summary
- Risk areas
- Rollback notes
- Verification checklist