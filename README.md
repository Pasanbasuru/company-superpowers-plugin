# company-superpowers-plugin

Reusable Claude Code plugin for company-wide engineering behavior.

## Included in v0.1.0
- Skills:
  - architecture-guard
  - change-risk-evaluation
  - integration-contract-safety
  - infra-safe-change
  - state-integrity-check
- Agent:
  - security-reviewer
- Hooks:
  - SessionStart logger
  - PostToolUse logger for Write/Edit
- MCP:
  - empty scaffold in `.mcp.json`

## Local development
Run from a project directory with:

```bash
claude --plugin-dir /absolute/path/to/company-superpowers-plugin