# Users' skills

152 skills.

Skills from 11 community repositories. Each keeps its original author's copyright —
see `SOURCE.txt` in each skill folder, or the master table in `CREDITS.md`.

| Author | Repository | License | Skills |
|---|---|---|---|
| Composio (ComposioHQ) and contributors | [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) | Apache License 2.0 | 28 |
| Jesse Vincent (GitHub: obra) | [obra/superpowers](https://github.com/obra/superpowers) | MIT License | 14 |
| Bitwize Music Studio | [bitwize-music-studio/claude-ai-music-skills](https://github.com/bitwize-music-studio/claude-ai-music-skills) | CC0 1.0 Universal (Public Domain Dedication) | 53 |
| Sanjay (GitHub: sanjay3290) | [sanjay3290/ai-skills](https://github.com/sanjay3290/ai-skills) | Apache License 2.0 | 24 |
| AgentBay (Alibaba) | [agentbay-ai/agentbay-skills](https://github.com/agentbay-ai/agentbay-skills) | MIT License | 15 |
| Conor Bronsdon | [conorbronsdon/avoid-ai-writing](https://github.com/conorbronsdon/avoid-ai-writing) | MIT License | 7 |
| Michal Parkola and the Tapestry Skills Contributors | [michalparkola/tapestry-skills](https://github.com/michalparkola/tapestry-skills) | MIT License | 7 |
| takechanman1228 | [takechanman1228/claude-persona](https://github.com/takechanman1228/claude-persona) | MIT License | 1 |
| Square Zero Labs | [Square-Zero-Labs/video-prompting-skill](https://github.com/Square-Zero-Labs/video-prompting-skill) | Apache License 2.0 | 1 |
| Scott Smerchek (GitHub: smerchek) | [smerchek/claude-epub-skill](https://github.com/smerchek/claude-epub-skill) | MIT License | 1 |
| Matt Joyce (GitHub: mattjoyce) | [mattjoyce/kanban-skill](https://github.com/mattjoyce/kanban-skill) | Apache License 2.0 | 1 |

## 01 - Writing & Editing

| Skill | What it does | Author |
|---|---|---|
| `ai-writing-detector` | Use when the user asks to detect, scan, audit, score, or flag AI-writing patterns without rewriting the text, including requests for a deterministic local detector result… | Conor Bronsdon |
| `avoid-ai-writing` | Audit and rewrite content to remove AI writing patterns ("AI-isms"). Use this skill when asked to "remove AI-isms," "clean up AI writing," "edit writing for AI patterns,"… | Conor Bronsdon |
| `avoid-ai-writing-router` | Use when a request combines AI-writing audit, rewrite, file editing, voice preservation, false-positive interpretation, verification, or when the user invokes Avoid AI Wr… | Conor Bronsdon |
| `content-research-writer` | Assists in writing high-quality content by conducting research, adding citations, improving hooks, iterating on outlines, and providing real-time feedback on each section… | Composio (ComposioHQ) and contributors |
| `false-positive-reviewer` | Use when a user asks what AI-writing flags mean, whether detector output proves AI authorship, or wants a careful interpretation of possible false positives, especially f… | Conor Bronsdon |
| `file-edit-in-place` | Use when the user names a local file and explicitly asks to clean, rewrite, humanize, or remove AI-writing patterns in that file itself, with minimal targeted edits and p… | Conor Bronsdon |
| `preservation-verifier` | Use when the user provides an original and rewritten version, asks whether a rewrite preserved protected content, or wants a deterministic check for code, frontmatter, qu… | Conor Bronsdon |
| `tailored-resume-generator` | Analyzes job descriptions and generates tailored resumes that highlight relevant experience, skills, and achievements to maximize interview chances | Composio (ComposioHQ) and contributors |
| `voice-preserving-rewriter` | Use when the user asks to rewrite, humanize, clean up, or remove AI-isms from text while preserving the writer's voice, facts, intent, structure, register, and protected… | Conor Bronsdon |

## 02 - Documents & Spreadsheets

| Skill | What it does | Author |
|---|---|---|
| `docx (Composio fork)` | Comprehensive document creation, editing, and analysis with support for tracked changes, comments, formatting preservation, and text extraction. When Claude needs to work… | Composio (ComposioHQ) and contributors |
| `google-docs` | Interact with Google Docs - create documents, search by title, read content, and edit text. Use when user asks to: create a Google Doc, find a document, read doc content,… | Sanjay (GitHub: sanjay3290) |
| `google-sheets` | Read and write Google Sheets spreadsheets - get content, update cells, append rows, fetch specific ranges, search for spreadsheets, and view metadata. Use when user asks… | Sanjay (GitHub: sanjay3290) |
| `markdown-to-epub` | Convert markdown documents and chat summaries into formatted EPUB ebook files that can be read on any device or uploaded to Kindle. | Scott Smerchek (GitHub: smerchek) |
| `pdf (Composio fork)` | Comprehensive PDF manipulation toolkit for extracting text and tables, creating new PDFs, merging/splitting documents, and handling forms. When Claude needs to fill in a… | Composio (ComposioHQ) and contributors |
| `xlsx (Composio fork)` | Comprehensive spreadsheet creation, editing, and analysis with support for formulas, formatting, data analysis, and visualization. When Claude needs to work with spreadsh… | Composio (ComposioHQ) and contributors |

## 03 - Presentations & Slides

| Skill | What it does | Author |
|---|---|---|
| `google-slides` | Read and write Google Slides presentations - get text, find presentations, create presentations, add slides, replace text, and manage slide content. Use when user asks to… | Sanjay (GitHub: sanjay3290) |
| `pptx (Composio fork)` | Presentation creation, editing, and analysis. When Claude needs to work with presentations (.pptx files) for: (1) Creating new presentations, (2) Modifying or editing con… | Composio (ComposioHQ) and contributors |

## 04 - Design & Visual

| Skill | What it does | Author |
|---|---|---|
| `artifacts-builder (Composio fork)` | Suite of tools for creating elaborate, multi-component claude.ai HTML artifacts using modern frontend web technologies (React, Tailwind CSS, shadcn/ui). Use for complex a… | Composio (ComposioHQ) and contributors |

## 05 - Images, Video & Audio

| Skill | What it does | Author |
|---|---|---|
| `elevenlabs` | Convert documents and text to audio using ElevenLabs text-to-speech. Use this skill when the user wants to create a podcast, narrate a document, read aloud text, generate… | Sanjay (GitHub: sanjay3290) |
| `google-tts` | Convert documents and text to audio using Google Cloud Text-to-Speech. Use this skill when the user wants to: narrate a document, read aloud text, generate audio from a f… | Sanjay (GitHub: sanjay3290) |
| `image-enhancer` | Improves the quality of images, especially screenshots, by enhancing resolution, sharpness, and clarity. Perfect for preparing images for presentations, documentation, or… | Composio (ComposioHQ) and contributors |
| `imagen` | Generate images using Google Gemini's image generation capabilities. Use this skill when the user needs to create, generate, or produce images for any purpose including U… | Sanjay (GitHub: sanjay3290) |
| `qwen-image` | Generate images using Qwen Image API (Alibaba Cloud DashScope). Use when users request image generation with Chinese prompts or need high-quality AI-generated images from… | AgentBay (Alibaba) |
| `qwen-wanx-comic-gen` | 使用通义千问·万相(wan2.6-t2i)生成漫画或动漫风格的图片。当用户说"生成漫画""用万相画漫画""生成漫画风格图片""用千问画一张二次元角色"等与漫画风格图像生成相关的请求时,执行本技能。 | AgentBay (Alibaba) |
| `slack-gif-creator (Composio fork)` | Toolkit for creating animated GIFs optimized for Slack, with validators for size constraints and composable animation primitives. This skill applies when users request an… | Composio (ComposioHQ) and contributors |
| `video-prompting` | Draft and refine prompts for video generation models (including text-to-video, image/keyframe-to-video, and reference-driven generation), and create character-sheet promp… | Square Zero Labs |
| `youtube-downloader` | Download YouTube videos with customizable quality and format options. Use this skill when the user asks to download, save, or grab YouTube videos. Supports various qualit… | Composio (ComposioHQ) and contributors |

## 06 - Music Production

| Skill | What it does | Author |
|---|---|---|
| `about` | Provides information about the bitwize-music plugin, its version, and its creator. Use when the user asks about the plugin, its purpose, version, or capabilities. | Bitwize Music Studio |
| `album-art-director` | Creates visual concepts for album artwork and generates AI art prompts. Use during planning for concept discussion, or after all tracks are Final for actual artwork gener… | Bitwize Music Studio |
| `album-conceptualizer` | Designs album concepts, tracklist architecture, and thematic planning through 7 structured phases. Use when planning a new album or reworking an existing album concept. | Bitwize Music Studio |
| `album-dashboard` | Shows a structured progress dashboard for an album with percentage complete per phase, blocking items, and status breakdown. Use for a quick visual overview of album prog… | Bitwize Music Studio |
| `album-ideas` | Tracks and manages album ideas including brainstorming, planning, and status updates. Use when the user wants to add, review, or organize their album idea backlog. | Bitwize Music Studio |
| `clipboard` | Copies track content (lyrics, style prompts, streaming lyrics) to the system clipboard. Use when the user needs to paste lyrics or style prompts into Suno or other extern… | Bitwize Music Studio |
| `cloud-uploader` | Uploads promo videos and content to Cloudflare R2 or AWS S3. Use when the user wants to host promo content for social media or distribution. | Bitwize Music Studio |
| `configure` | Sets up or edits the plugin configuration file interactively. Use on first-time setup, when config is missing, or when the user wants to change settings. | Bitwize Music Studio |
| `document-hunter` | Searches and retrieves documents from free public sources using automated browser navigation. Use when research needs primary source documents like court filings, governm… | Bitwize Music Studio |
| `explicit-checker` | Scans lyrics for explicit content and verifies that explicit flags match actual content. Use before Suno generation or release to ensure accurate content ratings. | Bitwize Music Studio |
| `genre-creator` | Create new genre documentation files for the bitwize-music genre library. Use when the user wants to add a genre, says "/genre-creator", "neues Genre erstellen", "Genre h… | Bitwize Music Studio |
| `health-check` | Runs plugin health checks (venv packages, skill registration, and album slug collisions). Use when the user asks to check plugin health, verify setup, or troubleshoot mis… | Bitwize Music Studio |
| `help` | Shows available skills, common workflows, and quick reference for the plugin. Use when the user asks for help, what skills are available, or how to do something. | Bitwize Music Studio |
| `import-art` | Places album art files in the correct audio and content directory locations. Use when the user has generated or downloaded album artwork that needs to be saved. | Bitwize Music Studio |
| `import-audio` | Moves audio files to the correct album location with proper path structure. Use when the user has downloaded WAV files from Suno or other sources that need to be organize… | Bitwize Music Studio |
| `import-track` | Moves track markdown files to the correct album location. Use when the user has track files in Downloads or other locations that need to be placed in an album. | Bitwize Music Studio |
| `lyric-refiner` | Autonomous multi-pass lyric refinement for tightening, cohesion, and album unity. Use after lyrics are written to polish a track or entire album through iterative passes. | Bitwize Music Studio |
| `lyric-reviewer` | Reviews lyrics against a quality checklist before Suno generation. Use before generating tracks to catch rhyme, prosody, pronunciation, and structural issues. | Bitwize Music Studio |
| `lyric-writer` | Writes or reviews lyrics with professional prosody, rhyme craft, and quality checks. Use when writing new lyrics, revising existing lyrics, or when the user says 'let's w… | Bitwize Music Studio |
| `mastering-engineer` | Guides audio mastering for streaming platforms including loudness optimization and tonal balance. Use when the user has approved tracks and wants to master audio files. | Bitwize Music Studio |
| `mix-engineer` | Polishes raw Suno audio by processing per-stem WAVs (vocals, backing_vocals, drums, bass, guitar, keyboard, strings, brass, woodwinds, percussion, synth, other) with targ… | Bitwize Music Studio |
| `new-album` | Creates a new album with the correct directory structure and templates. Use IMMEDIATELY when the user says 'make a new album' or similar, before any discussion. | Bitwize Music Studio |
| `next-step` | Analyzes album state and recommends the optimal next action. Use when the user asks "what should I do next?" or "what's left to do? | Bitwize Music Studio |
| `plagiarism-checker` | Scans lyrics for phrases that may match existing songs using web search and LLM knowledge. Use before release to check for unintentional borrowing. | Bitwize Music Studio |
| `pre-generation-check` | Validates all pre-generation gates before sending tracks to Suno. Checks sources verified, lyrics reviewed, pronunciation resolved, explicit flag set, style prompt comple… | Bitwize Music Studio |
| `promo-director` | Generates 15-second vertical promo videos for social media from mastered audio. Use after mastering is complete and before release, when the user wants social media conte… | Bitwize Music Studio |
| `promo-reviewer` | Reviews and iterates on social media copy in album promo/ files. Use after populating promo templates and before release to polish platform-specific posts. | Bitwize Music Studio |
| `promo-writer` | Generates platform-specific social media copy from album themes, track concepts, and lyrics. Use when promo/ templates need to be populated before release. | Bitwize Music Studio |
| `promote-idea` | Converts an album idea from IDEAS.md into an actual album project in one step. Use when the user says "promote [idea title]", "turn idea into album", or "start working on… | Bitwize Music Studio |
| `pronunciation-specialist` | Scans lyrics for pronunciation risks and prevents Suno mispronunciations. Use when writing lyrics with proper nouns, technical terms, homographs, or non-English words. | Bitwize Music Studio |
| `release-director` | Coordinates album release including QA, distribution prep, and platform uploads. Use when mastering and album art are complete and the user is ready to release. | Bitwize Music Studio |
| `rename` | Renames an album or track, updating slugs, titles, and all mirrored paths. Use when the user wants to rename an album or track. | Bitwize Music Studio |
| `researcher` | Conducts investigative-grade research with primary source analysis, cross-verification, and trial-level depth. Use when an album needs factual research, source material,… | Bitwize Music Studio |
| `researchers-biographical` | Researches personal backgrounds, interviews, motivations, and humanizing details. Use when research needs biographical context about people involved in the album's subjec… | Bitwize Music Studio |
| `researchers-financial` | Researches SEC filings, earnings calls, analyst reports, and market data. Use when the album subject involves financial crimes, corporate stories, or market events. | Bitwize Music Studio |
| `researchers-gov` | Researches DOJ/FBI/SEC press releases, agency statements, and government sources. Use when research needs official government records or agency documentation. | Bitwize Music Studio |
| `researchers-historical` | Researches archives, contemporary accounts, and timeline reconstruction. Use when the album subject involves historical events that need primary source verification. | Bitwize Music Studio |
| `researchers-journalism` | Researches investigative articles, interviews, and news coverage. Use when research needs journalistic sources for cross-referencing or additional context. | Bitwize Music Studio |
| `researchers-legal` | Researches court documents, indictments, plea agreements, and sentencing records. Use when the album subject involves legal proceedings or criminal cases. | Bitwize Music Studio |
| `researchers-primary-source` | Researches the subject's own words from tweets, blogs, forums, and chat logs. Use when research needs direct quotes or first-person accounts. | Bitwize Music Studio |
| `researchers-security` | Researches malware analysis, CVEs, attribution reports, and hacker community sources. Use when the album subject involves cybersecurity incidents or threat actors. | Bitwize Music Studio |
| `researchers-tech` | Researches project histories, changelogs, developer interviews, and open source documentation. Use when the album subject involves technology projects or developer storie… | Bitwize Music Studio |
| `researchers-verifier` | Performs quality control, citation validation, and fact-checking before human review. Use after research is complete to verify all sources and claims before production. | Bitwize Music Studio |
| `resume` | Finds an album by name and shows detailed status with next steps. Use when the user mentions an album name or wants to continue previous work. | Bitwize Music Studio |
| `session-start` | Runs the session startup procedure - verifies setup, loads config and state, checks skill models, and reports project status. Use at the beginning of a fresh session. | Bitwize Music Studio |
| `setup` | Detects your Python environment and guides you through installing plugin dependencies. Use on first-time setup or when MCP server fails to start. | Bitwize Music Studio |
| `sheet-music-publisher` | Converts mastered audio to sheet music and creates printable songbooks. Use after mastering when the user wants sheet music or a songbook for their album. | Bitwize Music Studio |
| `suno-engineer` | Constructs technical Suno V5/V5.5 style prompts, selects genres, and optimizes generation settings. Use when creating or refining Suno prompts for track generation. | Bitwize Music Studio |
| `test` | Runs automated tests to validate plugin integrity across 14 categories. Use before creating PRs, after making changes to skills or templates, or to verify plugin health. | Bitwize Music Studio |
| `tutorial` | Provides interactive guided album creation for new users. Use when the user is new to the plugin or asks for a walkthrough of the album creation process. | Bitwize Music Studio |
| `validate-album` | Validates album directory structure, file locations, and content integrity. Use before release or whenever the user wants to check an album's structural health. | Bitwize Music Studio |
| `verify-sources` | Captures human source verification for tracks, timestamps it, and updates track files. Use when sources need human review before generation. | Bitwize Music Studio |
| `voice-checker` | Reviews lyrics and prose for AI-written patterns (abstract noun stacking, over-explained metaphors, cliche escalation, missing idiosyncrasy, prose AI tells). Advisory War… | Bitwize Music Studio |

## 07 - Software Development

| Skill | What it does | Author |
|---|---|---|
| `agentbay-code-sandbox` | 用于任何「运行/执行/评估代码」的请求（如 run this code、execute script、用 Python 画图、跑代码/画图/执行脚本）。通过 AgentBay SDK 创建 code_latest 沙箱，调用 run_code 执行并返回结果。支持 Python、JavaScript、R、Java。 | AgentBay (Alibaba) |
| `apple-container` | Apple's open-source `container` CLI to build, run, and manage OCI/Linux containers as lightweight per-container VMs on Apple-silicon macOS — no Docker daemon required. Us… | Sanjay (GitHub: sanjay3290) |
| `azure-devops` | Manage Azure DevOps projects, work items, repos, PRs, pipelines, wikis, test plans, security alerts, variable groups, environments/approvals, branch policies, and attachm… | Sanjay (GitHub: sanjay3290) |
| `brainstorming` | You MUST use this before any creative work - creating features, building components, adding functionality, or modifying behavior. Explores user intent, requirements and d… | Jesse Vincent (GitHub: obra) |
| `changelog-generator` | Automatically creates user-facing changelogs from git commits by analyzing commit history, categorizing changes, and transforming technical commits into clear, customer-f… | Composio (ComposioHQ) and contributors |
| `developer-growth-analysis` | Analyzes your recent Claude Code chat history to identify coding patterns, development gaps, and areas for improvement, curates relevant learning resources from HackerNew… | Composio (ComposioHQ) and contributors |
| `dispatching-parallel-agents` | Use when facing 2+ independent tasks that can be worked on without shared state or sequential dependencies | Jesse Vincent (GitHub: obra) |
| `executing-plans` | Use when you have a written implementation plan to execute in a separate session with review checkpoints | Jesse Vincent (GitHub: obra) |
| `finishing-a-development-branch` | Use when implementation is complete, all tests pass, and you need to decide how to integrate the work | Jesse Vincent (GitHub: obra) |
| `langsmith-fetch` | Debug LangChain and LangGraph agents by fetching execution traces from LangSmith Studio. Use when debugging agent behavior, investigating errors, analyzing tool calls, ch… | Composio (ComposioHQ) and contributors |
| `mcp-builder (Composio fork)` | Guide for creating high-quality MCP (Model Context Protocol) servers that enable LLMs to interact with external services through well-designed tools. Use when building MC… | Composio (ComposioHQ) and contributors |
| `receiving-code-review` | Use when receiving code review feedback, before implementing suggestions, especially if feedback seems unclear or technically questionable - requires technical rigor and… | Jesse Vincent (GitHub: obra) |
| `requesting-code-review` | Use when completing tasks, implementing major features, or before merging to verify work meets requirements | Jesse Vincent (GitHub: obra) |
| `subagent-driven-development` | Use when executing implementation plans with independent tasks in the current session | Jesse Vincent (GitHub: obra) |
| `systematic-debugging` | Use when encountering any bug, test failure, or unexpected behavior, before proposing fixes | Jesse Vincent (GitHub: obra) |
| `test-driven-development` | Use when implementing any feature or bugfix, before writing implementation code | Jesse Vincent (GitHub: obra) |
| `using-git-worktrees` | Use when starting feature work that needs isolation from current workspace or before executing implementation plans - ensures an isolated workspace exists via native tool… | Jesse Vincent (GitHub: obra) |
| `using-superpowers` | Use when starting any conversation - establishes how to find and use skills, requiring skill invocation before ANY response including clarifying questions | Jesse Vincent (GitHub: obra) |
| `verification-before-completion` | Use when about to claim work is complete, fixed, or passing, before committing or creating PRs - requires running verification commands and confirming output before makin… | Jesse Vincent (GitHub: obra) |
| `writing-plans` | Use when you have a spec or requirements for a multi-step task, before touching code | Jesse Vincent (GitHub: obra) |

## 08 - Databases

| Skill | What it does | Author |
|---|---|---|
| `mssql` | Execute read-only SQL queries against multiple Microsoft SQL Server databases. Use when: (1) querying MSSQL/SQL Server databases, (2) exploring database schemas/tables, (… | Sanjay (GitHub: sanjay3290) |
| `mysql` | Execute read-only SQL queries against multiple MySQL databases. Use when: (1) querying MySQL databases, (2) exploring database schemas/tables, (3) running SELECT queries… | Sanjay (GitHub: sanjay3290) |
| `postgres` | Execute read-only SQL queries against multiple PostgreSQL databases. Use when: (1) querying PostgreSQL databases, (2) exploring database schemas/tables, (3) running SELEC… | Sanjay (GitHub: sanjay3290) |

## 09 - Research & Learning

| Skill | What it does | Author |
|---|---|---|
| `deep-research` | Execute autonomous multi-step research using Google Gemini Deep Research Agent. Use for: market analysis, competitive landscaping, literature reviews, technical research,… | Sanjay (GitHub: sanjay3290) |
| `learn-this` | Unified content extraction and action planning. Use when user says "learn-this <URL>", "learn this <URL>", "weave <URL>", "help me plan <URL>", "extract and plan <URL>",… | Michal Parkola and the Tapestry Skills Contributors |
| `notebooklm` | Query and manage Google NotebookLM notebooks with persistent profile auth, source sync, batch/multi queries, and structured exports. Use when user asks to query NotebookL… | Sanjay (GitHub: sanjay3290) |
| `ship-learn-next` | Transform learning content (like YouTube transcripts, articles, tutorials) into actionable implementation plans using the Ship-Learn-Next framework. Use when user wants t… | Michal Parkola and the Tapestry Skills Contributors |

## 10 - Web Scraping & Browsing

| Skill | What it does | Author |
|---|---|---|
| `amap-traffic` | 高德地图实时路况查询与最优自驾路线规划技能。基于高德交通态势API和路径规划API，提供实时拥堵信息和最快路线建议。 | AgentBay (Alibaba) |
| `article-extractor` | Extract clean article content from URLs (blog posts, articles, tutorials) and save as readable text. Use when user wants to download, extract, or save an article/blog pos… | Michal Parkola and the Tapestry Skills Contributors |
| `boss-job-search` | 查询Boss直聘职位信息。当用户想要搜索Boss直聘上的职位、筛选特定公司规模的岗位时使用此skill。 | AgentBay (Alibaba) |
| `douban-movie-review` | 查询豆瓣电影热门影评信息。当用户想要查询某部电影的豆瓣影评、用户评价、热门短评时使用此skill。 | AgentBay (Alibaba) |
| `moltbook-hot-posts` | 查询Moltbook（Agent社区）热门帖子信息。当用户想要查询Agent社区热帖、最新讨论、热门话题时使用此skill。 | AgentBay (Alibaba) |
| `web-scraper` | Scrape web pages and save as HTML or Markdown (with text and images). Minimal dependencies - only requests and beautifulsoup4. Use when the user provides a URL and wants… | AgentBay (Alibaba) |
| `weibo-hot-search` | 查询微博热搜信息。当用户想要查询微博热搜榜、文娱热搜、热度排行时使用此skill。 | AgentBay (Alibaba) |
| `wuying-browser-use` | 自动化浏览器交互，用于网页测试、表单填写、截图和数据提取。当用户需要浏览网站、与网页交互或提取信息时使用。 | AgentBay (Alibaba) |
| `youtube-transcript` | Download YouTube video transcripts when user provides a YouTube URL or asks to download/get/fetch a transcript from YouTube. Also use when user wants to transcribe or get… | Michal Parkola and the Tapestry Skills Contributors |

## 11 - Productivity & Organization

| Skill | What it does | Author |
|---|---|---|
| `atlassian` | Manage Jira issues and Confluence wiki pages in Atlassian Cloud. Use when: (1) searching/creating/updating Jira issues with JQL, (2) searching/reading/creating Confluence… | Sanjay (GitHub: sanjay3290) |
| `file-organizer` | Intelligently organizes your files and folders across your computer by understanding context, finding duplicates, suggesting better structures, and automating cleanup tas… | Composio (ComposioHQ) and contributors |
| `google-calendar` | Interact with Google Calendar - list calendars, view events, create/update/delete events, and find free time. Use when user asks to: check calendar, schedule a meeting, c… | Sanjay (GitHub: sanjay3290) |
| `google-drive` | Interact with Google Drive - search files, find folders, list contents, download files, upload files, create folders, move, copy, rename, and trash files. Use when user a… | Sanjay (GitHub: sanjay3290) |
| `kanban-ai` | Manage a Markdown-based Kanban board using card files in a kanban/ directory (including kanban/archived/ for completed cards). Use when the user asks to create, move, vie… | Matt Joyce (GitHub: mattjoyce) |
| `meeting-insights-analyzer` | Analyzes meeting transcripts and recordings to uncover behavioral patterns, communication insights, and actionable feedback. Identifies when you avoid conflict, use fille… | Composio (ComposioHQ) and contributors |
| `outline-wiki` | Search, read, and manage Outline wiki documents. Use when: (1) searching wiki for documentation, (2) reading wiki pages or articles, (3) listing wiki collections or docum… | Sanjay (GitHub: sanjay3290) |
| `raffle-winner-picker` | Picks random winners from lists, spreadsheets, or Google Sheets for giveaways, raffles, and contests. Ensures fair, unbiased selection with transparency. | Composio (ComposioHQ) and contributors |
| `scrum-sage` | AI-powered Scrum Master and Enterprise Agility Coach based on Jeff Sutherland, Taiichi Ohno, and First Principles thinking. Use when user needs help with Scrum, sprint an… | Michal Parkola and the Tapestry Skills Contributors |
| `session-log` | Summarize the current conversation session and append results to the weekly agent-log. Use when user says "log this", "session log", "summarize this session", or asks to… | Michal Parkola and the Tapestry Skills Contributors |
| `unblock-action` | Help the user unblock a vague or stuck action item by clarifying the intended output, scoping it to today, and identifying the concrete next action. Use when user says "u… | Michal Parkola and the Tapestry Skills Contributors |

## 12 - Communication & Messaging

| Skill | What it does | Author |
|---|---|---|
| `connect` | Connect Claude to any app. Send emails, create issues, post messages, update databases - take real actions across Gmail, Slack, GitHub, Notion, and 1000+ services. | Composio (ComposioHQ) and contributors |
| `connect-apps` | Connect Claude to external apps like Gmail, Slack, GitHub. Use this skill when the user wants to send emails, create issues, post messages, or take actions in external se… | Composio (ComposioHQ) and contributors |
| `connect-apps-plugin` | — | Composio (ComposioHQ) and contributors |
| `gmail` | Interact with Gmail - search emails, read messages, send emails, create drafts, and manage labels. Use when user asks to: search email, read email, send email, create ema… | Sanjay (GitHub: sanjay3290) |
| `google-chat` | Interact with Google Chat - list spaces, send messages, read conversations, and manage DMs. Use when user asks to: send a message on Google Chat, read chat messages, list… | Sanjay (GitHub: sanjay3290) |
| `im-reminder` | IM 定时提醒技能，支持一次性和周期性定时任务。通过 cron job 在指定时间唤醒 Agent，自动检测当前 IM 频道，保证消息准确送达。 | AgentBay (Alibaba) |
| `telegram` | Send Telegram messages, files, and alerts via bot API; read replies; ask questions with inline buttons and wait for the answer (approve-from-phone). Supports multiple bot… | Sanjay (GitHub: sanjay3290) |
| `whatsapp` | Send and receive WhatsApp messages via the unofficial linked-device client pywhats (pip install pywhats) — pair with QR, send text/images, group chat, read receipts, pres… | Sanjay (GitHub: sanjay3290) |

## 13 - Marketing & Growth

| Skill | What it does | Author |
|---|---|---|
| `agentbay-opinion-monitor` | 舆情监控技能，最终产出舆情报告。当用户问「某事件/话题舆情如何」「舆论怎么样」「做舆情分析」「运行舆情分析」或按关键词/平台爬取并生成舆情报告时，使用本技能。约定：凡舆情相关意图即执行全流程（爬取→情感分析→生成报告）。爬取由本技能完成；情感分析由主 Agent 按提示词自主判断；报告由 generate_report 生成。 | AgentBay (Alibaba) |
| `competitive-ads-extractor` | Extracts and analyzes competitors' ads from ad libraries (Facebook, LinkedIn, etc.) to understand what messaging, problems, and creative approaches are working. Helps ins… | Composio (ComposioHQ) and contributors |
| `domain-name-brainstormer` | Generates creative domain name ideas for your project and checks availability across multiple TLDs (.com, .io, .dev, .ai, etc.). Saves hours of brainstorming and manual c… | Composio (ComposioHQ) and contributors |
| `lead-research-assistant` | Identifies high-quality leads for your product or service by analyzing your business, searching for target companies, and providing actionable contact strategies. Perfect… | Composio (ComposioHQ) and contributors |
| `twitter-algorithm-optimizer` | Analyze and optimize tweets for maximum reach using Twitter's open-source algorithm insights. Rewrite and edit user tweets to improve engagement and visibility based on h… | Composio (ComposioHQ) and contributors |

## 14 - Finance & Business

| Skill | What it does | Author |
|---|---|---|
| `china-stock-analysis` | A股价值投资分析工具，提供股票筛选、个股深度分析、行业对比和估值计算功能。基于价值投资理论，使用akshare获取公开财务数据，适合低频交易的普通投资者。 | AgentBay (Alibaba) |
| `invoice-organizer` | Automatically organizes invoices and receipts for tax preparation by reading messy files, extracting key information, renaming them consistently, and sorting them into lo… | Composio (ComposioHQ) and contributors |
| `stock-watcher` | Manage and monitor a personal stock watchlist with support for adding, removing, listing stocks, and summarizing their recent performance using data from 10jqka.com.cn. U… | AgentBay (Alibaba) |

## 15 - Skill & Agent Building

| Skill | What it does | Author |
|---|---|---|
| `find-skills` | Helps users discover, search and install agent skills from the marketplace. Use when the user wants to find a skill, discover new capabilities, find specific tools (espec… | AgentBay (Alibaba) |
| `persona` | Build a persona panel, explore customer motivations through open-ended questions, and pressure-test product concepts before spending on fieldwork. Generates diverse AI pe… | takechanman1228 |
| `skill-creator (Composio fork)` | Guide for creating effective skills. This skill should be used when users want to create a new skill (or update an existing skill) that extends Claude's capabilities with… | Composio (ComposioHQ) and contributors |
| `skill-share` | A skill that creates new Claude skills and automatically shares them on Slack using Rube for seamless team collaboration and skill discovery. | Composio (ComposioHQ) and contributors |
| `template-skill` | Replace with description of the skill and when Claude should use it. | Composio (ComposioHQ) and contributors |
| `writing-skills` | Use when creating new skills, editing existing skills, or verifying skills work before deployment | Jesse Vincent (GitHub: obra) |

## 16 - AI Agent Delegation

| Skill | What it does | Author |
|---|---|---|
| `grok-build` | Orchestrate coding work by delegating well-specified implementation tasks to xAI's Grok Build CLI (grok) running headlessly, while the coding assistant plans, writes the… | Sanjay (GitHub: sanjay3290) |
| `jules` | Delegate coding tasks to Google Jules AI agent for asynchronous execution. Use when user says: 'have Jules fix', 'delegate to Jules', 'send to Jules', 'ask Jules to', 'ch… | Sanjay (GitHub: sanjay3290) |
| `manus` | Delegate complex, long-running tasks to Manus AI agent for autonomous execution. Use when user says 'use manus', 'delegate to manus', 'send to manus', 'have manus do', 'a… | Sanjay (GitHub: sanjay3290) |
