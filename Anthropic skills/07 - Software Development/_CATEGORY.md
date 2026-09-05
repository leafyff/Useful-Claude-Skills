# 07 - Software Development

3 skills · *Anthropic skills*

TDD, debugging, code review, planning, git, MCP servers, CI

### `claude-api`

Reference for the Claude API / Anthropic SDK — model ids, pricing, params, streaming, tool use, MCP, agents, caching, token counting, model migration. TRIGGER — read BEFORE opening the target file; don't skip because it "looks like a one-liner" — whenever: the prompt names Claude/Anthropic in any form (Claude, Anthropic, Fable, Opus, Sonnet, Haiku, `anthropic`, `@anthropic-ai`, `claude-*`, `us.anthropic.*`, `[1m]`); the user asks about an LLM (pricing/model choice/limits/caching) — never answer from memory; OR the task is LLM-shaped with provider unstated (agent/MCP/tool-definition/multi-agent/RAG/LLM-judge/computer-use; generate/summarize/extract/classify/rewrite/converse over NL; debugging refusals/cutoffs/streaming/tool-calls/tokens). SKIP only when another provider is being worked on (overrides all triggers): OpenAI/GPT/Gemini/Llama/Mistral/Cohere/Ollama named in the query; OR `grep -rE 'openai\|langchain_openai\|google.generativeai\|genai\|mistralai\|cohere\|ollama'` over the project hits (run this grep FIRST if no provider named — don't Read the file).

- **Author:** Anthropic, PBC
- **License:** Anthropic Skill License (proprietary — see LICENSE.txt in each skill)
- **Source:** [anthropics/skills](https://github.com/anthropics/skills)

### `mcp-builder`

Guide for creating high-quality MCP (Model Context Protocol) servers that enable LLMs to interact with external services through well-designed tools. Use when building MCP servers to integrate external APIs or services, whether in Python (FastMCP) or Node/TypeScript (MCP SDK).

- **Author:** Anthropic, PBC
- **License:** Anthropic Skill License (proprietary — see LICENSE.txt in each skill)
- **Source:** [anthropics/skills](https://github.com/anthropics/skills)

### `webapp-testing`

Toolkit for interacting with and testing local web applications using Playwright. Supports verifying frontend functionality, debugging UI behavior, capturing browser screenshots, and viewing browser logs.

- **Author:** Anthropic, PBC
- **License:** Anthropic Skill License (proprietary — see LICENSE.txt in each skill)
- **Source:** [anthropics/skills](https://github.com/anthropics/skills)
