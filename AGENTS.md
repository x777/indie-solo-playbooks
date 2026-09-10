# AGENTS.md

This repository is a living archive of public solo-founder launch systems (updated 10 Sep 2026).

Read this file for project context. Load a skill from `skills/` when the user wants to apply a system, not when they only want to edit markdown.

## Layout

- `playbooks/01`–`14` — one founder per file. Source of truth. Do not invent quotes.
- `skills/*/SKILL.md` — portable Agent Skills (agentskills.io). Copy a folder into `.agents/skills`, `.claude/skills`, `.cursor/skills`, or `.codex/skills`.
- `README.md` — human catalog.
- `assets/cover.svg` — landing banner.

## Rules

1. Treat playbook numbers and revenue as the founder's public claims, not audited facts.
2. Never flatten every founder into one method. Pick one system and stay inside it for the 30-day plan.
3. If the user names a founder, open that playbook first.
4. If the user names a channel, use the router skill, then one channel skill.
5. Reply in the user's language.

## Router

| Need | Skill | Playbooks |
| --- | --- | --- |
| Not sure which founder | `skills/indie-solo-router` | catalog |
| X / audience-first launch | `skills/indie-launch-x` | 01, 02, 04, 06 |
| SEO / exact-match / AEO | `skills/indie-launch-seo` | 13, 14 |
| TikTok / UGC / short video | `skills/indie-launch-shortform` | 09, 11 |
| Validate before building | `skills/indie-validate-offer` | 08, 12 |
| Ship many small products | `skills/indie-ship-portfolio` | 02, 03, 07 |
| Paid + product loop | read `playbooks/05-danny-postma.md` | 05 |
| Content + PLG SaaS | read `playbooks/10-yasser-elsaid.md` | 10 |

Full list: `README.md`.
