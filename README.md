# Useful Claude Skills

A curated, categorised collection of **172 Claude Skills** gathered from 12 public repositories on 2026-09-05.

## How this folder is arranged

```
Useful Claude Skills/
├── Anthropic skills/     20 official skills from anthropics/skills
├── Users' skills/        152 community skills from 11 repositories
├── _LICENSES/            full license text for every source repo
├── CREDITS.md            every author, license and a full skill index
└── README.md             this file
```

Both top folders use the **same numbered categories**, so the same kind of skill sits in the same place in either tree:

| Category | Anthropic | Users' | What lives there |
|---|---|---|---|
| **01 - Writing & Editing** | 2 | 9 | Drafting, editing, removing AI-isms, resumes, internal comms |
| **02 - Documents & Spreadsheets** | 3 | 6 | Word, Excel, PDF, Google Docs/Sheets, EPUB |
| **03 - Presentations & Slides** | 1 | 2 | PowerPoint and Google Slides |
| **04 - Design & Visual** | 6 | 1 | Brand systems, themes, canvases, front-end and generative art |
| **05 - Images, Video & Audio** | 1 | 9 | Image generation and enhancement, video prompting, TTS, GIFs |
| **06 - Music Production** | — | 53 | Songwriting, mixing, mastering, release and promo (one plugin) |
| **07 - Software Development** | 3 | 20 | TDD, debugging, code review, planning, git, MCP servers, CI |
| **08 - Databases** | — | 3 | PostgreSQL, MySQL, SQL Server query skills |
| **09 - Research & Learning** | 2 | 4 | Deep research, NotebookLM, learning workflows |
| **10 - Web Scraping & Browsing** | — | 9 | Scrapers, browser automation, transcript and article extraction |
| **11 - Productivity & Organization** | — | 11 | Kanban, Scrum, calendars, files, meetings, session logs |
| **12 - Communication & Messaging** | — | 8 | Gmail, Telegram, WhatsApp, Google Chat, app connectors |
| **13 - Marketing & Growth** | — | 5 | Ads analysis, lead research, Twitter/X optimisation, naming |
| **14 - Finance & Business** | — | 3 | Invoices, stock watching and analysis |
| **15 - Skill & Agent Building** | 2 | 6 | Creating, sharing, finding skills; personas; templates |
| **16 - AI Agent Delegation** | — | 3 | Handing work to Jules, Manus, Grok Build |

**Totals — Anthropic: 20 · Users': 152 · Grand total: 172**

## Copyright

Every skill is redistributed unmodified and keeps its original author's copyright.
Attribution lives in two places:

- **`CREDITS.md`** — the master table: every author, repository, license and skill.
- **`SOURCE.txt` inside each skill folder** — that one skill's author, license, repo URL, original path and commit.
  This travels with the skill, so attribution survives if you copy a single folder elsewhere.

Full license texts are in `_LICENSES/`. Licenses present in this collection: MIT, Apache 2.0, CC0 1.0,
and Anthropic's own skill license (proprietary — the `Anthropic skills` folder is **not** open source).

## Using a skill

Copy the skill folder (the one containing `SKILL.md`) into your skills directory — for Claude Code that is
`~/.claude/skills/`, or `.claude/skills/` inside a project. `SOURCE.txt` is inert metadata and can stay or go.

Many skills need extra setup — an API key, an MCP server, a Python package. Read the skill's own `SKILL.md` first.

## What was left out

- The **832 auto-generated `<app>-automation` stubs** in ComposioHQ's `composio-skills/` directory.
- **Five ComposioHQ copies of Anthropic skills** whose skill files are byte-identical to the originals
  (they differ only in `LICENSE.txt`). Genuine forks were kept and are labelled **(Composio fork)**.
- Repository scaffolding: `.git`, `.github`, CI configs, test suites, top-level READMEs.

See the Notes section at the bottom of `CREDITS.md` for the full reasoning.
