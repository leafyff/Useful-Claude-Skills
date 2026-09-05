# 07 - Software Development

20 skills · *Users' skills*

TDD, debugging, code review, planning, git, MCP servers, CI

### `agentbay-code-sandbox`

用于任何「运行/执行/评估代码」的请求（如 run this code、execute script、用 Python 画图、跑代码/画图/执行脚本）。通过 AgentBay SDK 创建 code_latest 沙箱，调用 run_code 执行并返回结果。支持 Python、JavaScript、R、Java。

- **Author:** AgentBay (Alibaba)
- **License:** MIT License
- **Source:** [agentbay-ai/agentbay-skills](https://github.com/agentbay-ai/agentbay-skills)

### `apple-container`

Apple's open-source `container` CLI to build, run, and manage OCI/Linux containers as lightweight per-container VMs on Apple-silicon macOS — no Docker daemon required. Use when the user mentions the `container` CLI, "apple container", running or building containers on macOS without Docker/Podman, `container run`, `container build`, `container images`, `container system start`, pushing/pulling images to a registry, or container networking on macOS. This is Apple's `container` tool specifically (repo `apple/container`), NOT Docker, Podman, containerd, nerdctl, or Kubernetes — the CLI is Docker-like but is a different tool.

- **Author:** Sanjay (GitHub: sanjay3290)
- **License:** Apache License 2.0
- **Source:** [sanjay3290/ai-skills](https://github.com/sanjay3290/ai-skills)

### `azure-devops`

Manage Azure DevOps projects, work items, repos, PRs, pipelines, wikis, test plans, security alerts, variable groups, environments/approvals, branch policies, and attachments. Use when user asks to: manage sprints, create/update work items, list repos, create PRs, run pipelines, search code, manage wiki pages, check security alerts, manage variable groups, approve deployments, or configure branch policies. Covers 13 domains with 99 tools via REST API.

- **Author:** Sanjay (GitHub: sanjay3290)
- **License:** Apache License 2.0
- **Source:** [sanjay3290/ai-skills](https://github.com/sanjay3290/ai-skills)

### `brainstorming`

You MUST use this before any creative work - creating features, building components, adding functionality, or modifying behavior. Explores user intent, requirements and design before implementation.

- **Author:** Jesse Vincent (GitHub: obra)
- **License:** MIT License
- **Source:** [obra/superpowers](https://github.com/obra/superpowers)

### `changelog-generator`

Automatically creates user-facing changelogs from git commits by analyzing commit history, categorizing changes, and transforming technical commits into clear, customer-friendly release notes. Turns hours of manual changelog writing into minutes of automated generation.

- **Author:** Composio (ComposioHQ) and contributors
- **License:** Apache License 2.0
- **Source:** [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills)

### `developer-growth-analysis`

Analyzes your recent Claude Code chat history to identify coding patterns, development gaps, and areas for improvement, curates relevant learning resources from HackerNews, and automatically sends a personalized growth report to your Slack DMs.

- **Author:** Composio (ComposioHQ) and contributors
- **License:** Apache License 2.0
- **Source:** [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills)

### `dispatching-parallel-agents`

Use when facing 2+ independent tasks that can be worked on without shared state or sequential dependencies

- **Author:** Jesse Vincent (GitHub: obra)
- **License:** MIT License
- **Source:** [obra/superpowers](https://github.com/obra/superpowers)

### `executing-plans`

Use when you have a written implementation plan to execute in a separate session with review checkpoints

- **Author:** Jesse Vincent (GitHub: obra)
- **License:** MIT License
- **Source:** [obra/superpowers](https://github.com/obra/superpowers)

### `finishing-a-development-branch`

Use when implementation is complete, all tests pass, and you need to decide how to integrate the work

- **Author:** Jesse Vincent (GitHub: obra)
- **License:** MIT License
- **Source:** [obra/superpowers](https://github.com/obra/superpowers)

### `langsmith-fetch`

Debug LangChain and LangGraph agents by fetching execution traces from LangSmith Studio. Use when debugging agent behavior, investigating errors, analyzing tool calls, checking memory operations, or examining agent performance. Automatically fetches recent traces and analyzes execution patterns. Requires langsmith-fetch CLI installed.

- **Author:** Composio (ComposioHQ) and contributors
- **License:** Apache License 2.0
- **Source:** [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills)

### `mcp-builder (Composio fork)`

Guide for creating high-quality MCP (Model Context Protocol) servers that enable LLMs to interact with external services through well-designed tools. Use when building MCP servers to integrate external APIs or services, whether in Python (FastMCP) or Node/TypeScript (MCP SDK).

- **Author:** Composio (ComposioHQ) and contributors
- **License:** Apache License 2.0
- **Source:** [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills)
- **Note:** Fork of Anthropic mcp-builder.

### `receiving-code-review`

Use when receiving code review feedback, before implementing suggestions, especially if feedback seems unclear or technically questionable - requires technical rigor and verification, not performative agreement or blind implementation

- **Author:** Jesse Vincent (GitHub: obra)
- **License:** MIT License
- **Source:** [obra/superpowers](https://github.com/obra/superpowers)

### `requesting-code-review`

Use when completing tasks, implementing major features, or before merging to verify work meets requirements

- **Author:** Jesse Vincent (GitHub: obra)
- **License:** MIT License
- **Source:** [obra/superpowers](https://github.com/obra/superpowers)

### `subagent-driven-development`

Use when executing implementation plans with independent tasks in the current session

- **Author:** Jesse Vincent (GitHub: obra)
- **License:** MIT License
- **Source:** [obra/superpowers](https://github.com/obra/superpowers)

### `systematic-debugging`

Use when encountering any bug, test failure, or unexpected behavior, before proposing fixes

- **Author:** Jesse Vincent (GitHub: obra)
- **License:** MIT License
- **Source:** [obra/superpowers](https://github.com/obra/superpowers)

### `test-driven-development`

Use when implementing any feature or bugfix, before writing implementation code

- **Author:** Jesse Vincent (GitHub: obra)
- **License:** MIT License
- **Source:** [obra/superpowers](https://github.com/obra/superpowers)

### `using-git-worktrees`

Use when starting feature work that needs isolation from current workspace or before executing implementation plans - ensures an isolated workspace exists via native tools or git worktree fallback

- **Author:** Jesse Vincent (GitHub: obra)
- **License:** MIT License
- **Source:** [obra/superpowers](https://github.com/obra/superpowers)

### `using-superpowers`

Use when starting any conversation - establishes how to find and use skills, requiring skill invocation before ANY response including clarifying questions

- **Author:** Jesse Vincent (GitHub: obra)
- **License:** MIT License
- **Source:** [obra/superpowers](https://github.com/obra/superpowers)

### `verification-before-completion`

Use when about to claim work is complete, fixed, or passing, before committing or creating PRs - requires running verification commands and confirming output before making any success claims; evidence before assertions always

- **Author:** Jesse Vincent (GitHub: obra)
- **License:** MIT License
- **Source:** [obra/superpowers](https://github.com/obra/superpowers)

### `writing-plans`

Use when you have a spec or requirements for a multi-step task, before touching code

- **Author:** Jesse Vincent (GitHub: obra)
- **License:** MIT License
- **Source:** [obra/superpowers](https://github.com/obra/superpowers)
