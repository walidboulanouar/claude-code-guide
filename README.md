# Claude Code Setup Guide

**Interactive wizard for getting Claude Code fully configured — from zero to second brain.**

👉 **[Open the guide](https://walidboulanouar.github.io/claude-code-guide/)**

---

## What this is

Most people install Claude Code and stop at the terminal prompt.

This guide takes you through the full setup — step by step, based on your level. Pick where you are. Get exactly what you need. Nothing else.

Built with Claude Code. For Claude Code users.

---

## Three paths

| Level | What you get |
|---|---|
| 📦 **Not installed yet** | Install guide (Node, npm, Claude Code), Warp terminal setup, CLAUDE.md creation wizard, folder structure |
| ⚡ **Installed** | Write your CLAUDE.md from 8 questions, connect MCPs, add skills and hooks |
| 🚀 **Power user** | arscontexta second brain plugin, 50+ MCPs by category, full hooks setup, community skills list |

---

## What's inside

### CLAUDE.md
The file that makes Claude understand your business permanently — from session one.

The guide includes a prompt that interviews you like a founder advisor. Answer 8 questions. Get a complete CLAUDE.md in one session.

### MCPs (Model Context Protocol)
50+ tools organized by category:

- **Productivity** — Notion, Google Drive, Calendar, Linear
- **Communication** — Slack, Gmail, Telegram, Discord
- **CRM & Sales** — HubSpot, Salesforce, Attio, Pipedrive
- **Dev & Code** — GitHub, GitLab, Supabase, Vercel, Cloudflare
- **Data & Search** — Brave Search, Perplexity, DuckDuckGo, Exa
- **AI & Agents** — OpenAI, Anthropic, Replicate, ElevenLabs
- **Finance** — Stripe, Shopify, QuickBooks
- **Infrastructure** — AWS, Docker, Kubernetes, Terraform
- **Browser & Scraping** — Playwright, Puppeteer, Firecrawl
- **Databases** — PostgreSQL, MySQL, MongoDB, Redis
- **Social & LinkedIn** — LinkedIn (Unipile), Twitter/X, anysite

Plus: how to find any MCP in 10 seconds — just search `tool name + mcp`.

### arscontexta
A Claude Code plugin that doesn't use a template. It interviews you and derives a knowledge architecture from how your brain actually works.

Install:
```bash
/plugin marketplace add agenticnotetaking/arscontexta
/plugin install arscontexta@agenticnotetaking
/arscontexta:setup
```

Requires: `tree` + `ripgrep`

→ [github.com/agenticnotetaking/arscontexta](https://github.com/agenticnotetaking/arscontexta)

### Hooks
6 safety scripts that run automatically before/after Claude takes any action:

| Hook | Trigger | What it does |
|---|---|---|
| `bash-safety.sh` | PreToolUse · Bash | Blocks `git commit`, `force push`, `reset --hard`, `rm -rf` — forever |
| `file-protection.sh` | PreToolUse · Edit | Blocks edits to `.env` and credentials. Warns before touching CLAUDE.md. |
| `file-backup.sh` | PreToolUse · Edit | Auto-backups every file before editing. Keeps last 10 versions. |
| `search-year.sh` | PreToolUse · WebSearch | Auto-appends current year to web searches |
| `file-logger.sh` | PostToolUse · Write | Logs every file change to a daily audit log |
| `stop-notify.sh` | Stop | Sound + macOS notification when Claude finishes a task |

Full hooks bundle ships as a free GitHub drop — **day 5 of the series**.

### Skills
Community skills list: [github.com/sickn33/antigravity-awesome-skills](https://github.com/sickn33/antigravity-awesome-skills)

Walid's own skills list drops in a few days. Follow to get it.

---

## The 30-day series

This guide is day 2 of a 30-day series on building with Claude Code like a founder — not a developer.

| Day | Topic | Lead magnet |
|---|---|---|
| 1 | Why Claude Code changes how you work | — |
| 2 | This guide | Interactive wizard |
| 3 | MCPs — connect Claude to your tools | comment STACK |
| 4 | Skills — reusable agents for any task | comment SKILL |
| 5 | Hooks — the safety net + first GitHub drop | comment HOOKS |
| 6–30 | Advanced workflows, agent design, real builds | — |

One drop per day at 10am. Follow [Walid on LinkedIn](https://www.linkedin.com/in/walid-boulanouar/) to get all of it.

---

## Need help?

**Stuck somewhere?** Message me on LinkedIn — show me the error and I'll help you get unstuck.

**Want to set this up together live on your machine?** I do 1:1 paid sessions. Just ask.

**Video walkthroughs** are coming — step-by-step for each section of the series.

→ [linkedin.com/in/walid-boulanouar](https://www.linkedin.com/in/walid-boulanouar/)

---

## About

Built by [Walid Boulanouar](https://www.linkedin.com/in/walid-boulanouar/) — founder of [AY Automate](https://ayautomate.com), an AI-native engineering company that places dedicated AI engineers inside client teams.

20 active clients. 25+ reusable skills. 7 MCPs connected. 1 terminal.

This is what the setup looks like.

---

*Free. No email. No form. Built with Claude Code.*
