# AI GitHub Trending — 2026-04-15

_Auto-updated daily at 7am ET. [Archive](./archive/)._

## Editor's Take

No prior-day archive exists for comparison, making this effectively the inaugural snapshot. Karpathy-branded prompt engineering owns the top of today's chart: andrej-karpathy-skills (#1, +9,263) treats the CLAUDE.md file as a first-class deliverable, and caveman (#4, ~2,835/day) shows that token compression itself is now a marketable skill. Memory infrastructure is the day's second-largest theme, with three independent approaches in the top 20: MemPalace (#2, MCP-native ChromaDB-backed storage), claude-mem (#3, session-capture-and-reinjection), and claude-obsidian (#16, Obsidian-wiki integration). Vercel entering the agents market with open-agents (#8, +1,020) signals that cloud platforms are productizing agent scaffolding directly. The finance-AI thread persists across virattt/ai-hedge-fund (#9, +1,007) and Vibe-Trading (#18), suggesting quantitative finance is consolidating as a durable LLM application domain alongside dev tooling.

## Top 20

### 1. [forrestchang/andrej-karpathy-skills](https://github.com/forrestchang/andrej-karpathy-skills) — ⭐ 38,493 (+9,263)
**—** · `claude-code` `skills` `prompt-engineering` `ai-agents`

A single CLAUDE.md file engineered to systematically improve Claude Code behavior, derived from Andrej Karpathy's observations on LLM coding pitfalls — covering task decomposition, verification loops, and output quality heuristics.

---

### 2. [MemPalace/mempalace](https://github.com/MemPalace/mempalace) — ⭐ 46,249 (~4,625/day est.)
**Python** · `ai` `llm` `mcp` `memory` `python`

The best-benchmarked open-source AI memory system. Provides persistent, structured memory for LLM agents via MCP integration, with ChromaDB backing.

---

### 3. [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem) — ⭐ 56,773 (+2,997)
**TypeScript** · `claude-code` `memory` `typescript` `ai`

A Claude Code plugin that automatically captures and compresses everything Claude does during coding sessions, then injects relevant context back into future sessions.

---

### 4. [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman) — ⭐ 31,177 (~2,835/day est.)
**Python** · `claude-code` `token-optimization` `llm` `prompt-engineering`

"Why use many token when few token do trick" — a Claude Code skill that cuts 65% of token usage by compressing prompts into simplified syntax without sacrificing reasoning quality.

---

### 5. [obra/superpowers](https://github.com/obra/superpowers) — ⭐ 153,345 (+1,919)
**Shell** · `agentic` `skills` `claude-code` `ai-agents`

An agentic skills framework and software development methodology providing structured, composable workflows for Claude Code, Copilot CLI, and other AI coding assistants.

---

### 6. [jamiepine/voicebox](https://github.com/jamiepine/voicebox) — ⭐ 17,816 (+1,162)
**TypeScript** · `voice-synthesis` `tts` `ai` `open-source`

The open-source voice synthesis studio — a full-featured frontend for generating, previewing, and managing AI voice output across multiple synthesis backends.

---

### 7. [Lordog/dive-into-llms](https://github.com/Lordog/dive-into-llms) — ⭐ 28,872 (+1,068)
**Jupyter Notebook** · `llm` `deep-learning` `tutorial` `python`

A hands-on programming tutorial series covering large language model fundamentals, fine-tuning, and deployment through practical notebook exercises.

---

### 8. [vercel-labs/open-agents](https://github.com/vercel-labs/open-agents) — ⭐ 2,183 (+1,020)
**TypeScript** · `agents` `cloud` `typescript` `open-source`

An open-source template from Vercel for building production-grade cloud agents — includes streaming, tool use, and deployment primitives ready for edge infrastructure.

---

### 9. [virattt/ai-hedge-fund](https://github.com/virattt/ai-hedge-fund) — ⭐ 54,632 (+1,007)
**Python** · `ai` `finance` `agents` `python` `llm`

An AI hedge fund team — multi-agent system where specialized LLM agents handle market analysis, risk management, and simulated trade execution.

---

### 10. [google/magika](https://github.com/google/magika) — ⭐ 13,350 (+833)
**Python** · `ai` `machine-learning` `file-detection` `python`

Fast and accurate AI-powered file content type detection from Google — uses a deep learning model to identify file types from content rather than extensions.

---

### 11. [JackChen-me/open-multi-agent](https://github.com/JackChen-me/open-multi-agent) — ⭐ 5,711 (~381/day est.)
**TypeScript** · `multi-agent` `llm` `typescript` `ai-agents`

TypeScript multi-agent framework — one `runTeam()` call takes a goal to a result by dynamically orchestrating specialized sub-agents with automatic task decomposition.

---

### 12. [Donchitos/Claude-Code-Game-Studios](https://github.com/Donchitos/Claude-Code-Game-Studios) — ⭐ 9,796 (+523)
**Shell** · `claude-code` `ai-agents` `skills` `game-dev`

Turn Claude Code into a full game development studio — 49 AI agents, 72 workflow skills, and a complete coordination system for shipping games with AI assistance.

---

### 13. [lsdefine/GenericAgent](https://github.com/lsdefine/GenericAgent) — ⭐ 1,524 (+413)
**Python** · `agent` `self-evolving` `python` `ai`

Self-evolving agent that grows its skill tree from a 3,300-line seed, achieving full system control with 6x lower token consumption than comparable frameworks.

---

### 14. [Arthur-Ficial/apfel](https://github.com/Arthur-Ficial/apfel) — ⭐ 4,593 (~209/day est.)
**Swift** · `llm` `macos` `on-device` `swift`

The free AI already on your Mac — native CLI and OpenAI-compatible server for running Gemma 4, Qwen3, Mistral, and DeepSeek models entirely offline on Apple Silicon.

---

### 15. [lintsinghua/claude-code-book](https://github.com/lintsinghua/claude-code-book) — ⭐ 2,721 (~181/day est.)
**—** · `agent` `claude-code` `llm` `mcp` `architecture`

A 420,000-character Chinese book dissecting the Claude Code agent harness architecture — 15 chapters covering conversation loops, tool dispatch, MCP integration, and building a custom agent runtime.

---

### 16. [AgriciDaniel/claude-obsidian](https://github.com/AgriciDaniel/claude-obsidian) — ⭐ 1,260 (~157/day est.)
**Shell** · `claude-code` `knowledge-management` `obsidian` `ai`

Claude + Obsidian knowledge companion — persistent, compounding wiki vault integration inspired by Karpathy's LLM Wiki concept, with memory and daily digest generation.

---

### 17. [VoltAgent/awesome-codex-subagents](https://github.com/VoltAgent/awesome-codex-subagents) — ⭐ 3,949 (~136/day est.)
**—** · `ai-agents` `codex` `awesome-list` `subagents`

A collection of 130+ specialized Codex subagents covering engineering, research, data analysis, and automation tasks — paste-ready configurations for common agent workflows.

---

### 18. [HKUDS/Vibe-Trading](https://github.com/HKUDS/Vibe-Trading) — ⭐ 1,887 (~135/day est.)
**Python** · `ai-agent` `trading` `mcp` `llm` `fintech`

Your personal trading agent — uses MCP and LLMs to run algorithmic strategies, backtest signals, and monitor live market positions with natural language control.

---

### 19. [HughYau/qiushi-skill](https://github.com/HughYau/qiushi-skill) — ⭐ 2,717 (~129/day est.)
**JavaScript** · `ai-agents` `skills` `methodology` `llm`

Qiushi-Skill distills the principle of seeking truth from facts into nine methodology tools for structuring AI agent reasoning, planning, and decision-making.

---

### 20. [nesquena/hermes-webui](https://github.com/nesquena/hermes-webui) — ⭐ 2,050 (~128/day est.)
**Python** · `agent` `ai-agents` `hermes-agent` `python`

Hermes WebUI — a web and mobile interface for NousResearch's Hermes Agent, providing full agent interaction without a terminal.

---

## New & Rising

Created in the last 14 days:

- [MemPalace/mempalace](https://github.com/MemPalace/mempalace) — ⭐ 46,249, born 2026-04-05
  The best-benchmarked open-source AI memory system with MCP integration and ChromaDB backing.

- [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman) — ⭐ 31,177, born 2026-04-04
  Claude Code skill that cuts 65% of token usage via prompt compression without quality loss.

- [HKUDS/Vibe-Trading](https://github.com/HKUDS/Vibe-Trading) — ⭐ 1,887, born 2026-04-01
  LLM-powered personal trading agent with MCP integration, backtesting, and natural language trade control.

- [AgriciDaniel/claude-obsidian](https://github.com/AgriciDaniel/claude-obsidian) — ⭐ 1,260, born 2026-04-07
  Claude + Obsidian knowledge companion providing persistent wiki vault integration with memory and daily digest generation.

- [Houseofmvps/codesight](https://github.com/Houseofmvps/codesight) — ⭐ 899, born 2026-04-04
  Universal AI context generator that saves thousands of tokens per conversation across Claude Code, Cursor, Copilot, and Codex.

## Methodology

Sources: github.com/trending (daily) + GitHub Search API (AI topics: ai, llm, agents, ai-agents, generative-ai, rag, machine-learning, mcp — created <30d). Ranked by today's star velocity, recency, and editorial judgment. Generated by a scheduled Claude agent at 7am ET daily.
