# Skills

Portable [Agent Skills](https://agentskills.io) for Claude Code, Cursor, Codex, Copilot, Gemini CLI, and anything else that reads `SKILL.md`.

## Install

Copy a skill folder into one of:

```text
.agents/skills/
.claude/skills/
.cursor/skills/
.codex/skills/
~/.claude/skills/
~/.codex/skills/
```

Or clone this repo and point the agent at it. `AGENTS.md` at the repo root is enough for Codex / Cursor / Copilot / Gemini to see the catalog.

## Skills

| Folder | Use when |
| --- | --- |
| `indie-solo-router` | User does not know which founder or channel to follow |
| `indie-launch-x` | Launch and grow on X |
| `indie-launch-seo` | Search / exact-match domains / AEO |
| `indie-launch-shortform` | TikTok, UGC, slideshows |
| `indie-validate-offer` | Idea is not validated yet |
| `indie-ship-portfolio` | Many small products, ship-or-die tempo |

Each skill tells the agent which `playbooks/*.md` file to read. Do not duplicate those files here.
