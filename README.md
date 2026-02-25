# Justin Russas

Software engineer with 25 years building production systems — test orchestration platforms, game engines, AI content pipelines, medical device software, and developer tooling.

I build AI-augmented engineering workflows. The open source projects here are part of a local AI infrastructure I designed and run: RAG pipelines, MCP tool servers, multi-GPU inference routing, and code-aware search — all feeding into a daily development workflow where AI tooling is a force multiplier, not a novelty. I architect the systems, make the technical decisions, and use AI the way I'd use any tool in my stack.

## What I'm Building

**TikTok Live Game Platform** — Real-time interactive game on a custom C# engine with AI-driven procedural content generation (ComfyUI, MuseTalk, LLMs), TikTok Live integration, and a React + FastAPI content dashboard. Dual-GPU inference across RTX 4090 + 3090.

**RAG Developer Tools** — MCP servers that index codebases into searchable knowledge bases with hybrid semantic + keyword search. Custom language-aware chunkers for C# and Verse. Powers AI-assisted development with accurate, project-specific context.

**UEFN Dungeon Crawler** — Procedurally generated dungeon crawler in Verse with 11 game systems, Kruskal's maze generation across 3 vertical levels, and data-driven item/ability progression.

## Open Source

| Project | Description |
|---------|-------------|
| [**mcp-rag**](https://github.com/JMRussas/mcp-rag) | Config-driven RAG pipeline + MCP server. Chunks code, embeds locally via Ollama, serves hybrid search. |
| [**dungeon-gen**](https://github.com/JMRussas/dungeon-gen) | Interactive browser-based dungeon generator — Kruskal's algorithm, Union-Find, BFS room assignment. [Live demo.](https://jmrussas.github.io/dungeon-gen/) |
| [**ai-video-composite**](https://github.com/JMRussas/ai-video-composite) | Green-screen removal and compositing toolkit for AI-generated video. Three-stage cleanup pipeline (rembg + alpha cleanup + green defringing). |
| [**ollama-mcp**](https://github.com/JMRussas/ollama-mcp) | MCP server exposing local Ollama instances as tools for AI coding assistants. |

## Career Highlights

- **Dell EMC** (8 years) — Built a three-tier test orchestration platform managing 90% of automated testing for Midrange Storage. ML-optimized scheduling. Scaled VxRail engineering from 30 to 200+ people; product grew from $30M to $2B+.
- **PurpleZerker LLC** (current) — Independent engineering: Unity multiplayer at Pocket Worlds, medical device software under FDA/ISO at Full Spectrum Software, game and AI platform development.
- **Full Spectrum Software** (9 years) — Production software and technical lead across medical device products under FDA regulatory frameworks.

## Tech

`C#` `.NET` `Python` `TypeScript` `React` `FastAPI` `Unity` `UEFN/Verse` `Docker` `Ollama` `SQLite` `MCP` `RAG`
