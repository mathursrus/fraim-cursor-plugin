# FRAIM Cursor Marketplace Package

This package contains the Cursor plugin submission bundle for FRAIM.

## Contents

| Path | Purpose |
|---|---|
| `.cursor-plugin/marketplace.json` | Target-local marketplace manifest for package validation. |
| `plugins/fraim/.cursor-plugin/plugin.json` | Cursor plugin manifest. |
| `plugins/fraim/mcp.json` | Remote FRAIM MCP server config. |
| `plugins/fraim/rules/fraim.mdc` | Always-on FRAIM discovery rule. |
| `plugins/fraim/skills/fraim/SKILL.md` | FRAIM workflow skill. |
| `plugins/fraim/commands/fraim.md` | Command entry point. |

The repository root also has `.cursor-plugin/marketplace.json` so the public GitHub repository can be submitted directly to Cursor's marketplace publish flow.

## Submission

Submit the public repository URL through `https://cursor.com/marketplace/publish` after the package lands on the branch used for review. Record the submission state, listing URL, reviewer feedback, and install/use smoke evidence in `docs/evidence/674-marketplace-acceptance.md`.

