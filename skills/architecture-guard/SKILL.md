---
description: Enforce architecture boundaries and layering rules when a task touches multiple modules, services, or cross-cutting concerns.
---

Use this skill when:
- a change touches multiple modules or packages
- a request risks bypassing boundaries
- a refactor may increase coupling
- a feature affects architecture, layering, or ownership

Your job:
1. Identify the affected layers, modules, or services first.
2. Preserve existing boundaries unless the task explicitly requires changing them.
3. Prefer the smallest safe change over broad restructuring.
4. Call out:
   - layering violations
   - unnecessary coupling
   - hidden cross-module dependencies
   - architecture drift risks
5. Recommend a safer structure if the current approach breaks boundaries.

Output expectations:
- Brief architecture assessment
- Main risk areas
- Recommended approach
- Any follow-up checks needed