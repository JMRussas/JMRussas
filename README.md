# Justin Russas

Software engineer with 25 years building production systems — test orchestration platforms, game engines, AI content pipelines, medical device software, and developer tooling.

I build AI-augmented engineering workflows. The open source projects here are part of a local AI infrastructure I designed and run: task orchestration with multi-model routing, RAG pipelines, MCP tool servers, multi-GPU inference, and code-aware search — all feeding into a daily development workflow where AI tooling is a force multiplier, not a novelty. I architect the systems, make the technical decisions, and use AI the way I'd use any tool in my stack.

## What I'm Building

**Orchestration Engine** — AI-powered task orchestration platform. Decomposes requirements into a dependency-aware DAG, routes each task to the cheapest capable model (local Ollama → Haiku → Sonnet), and executes in parallel with TOCTOU-safe budget reservation, tool use, and real-time SSE progress streaming. FastAPI + React, 390+ tests at 85% coverage. This is the system that ties everything below together.

**TraceabilityMedCode** (private — commercial product in development) — Code-native traceability framework for IEC 62304 / ISO 13485 / FDA 21 CFR 820 compliance. Embeds structured annotations directly in source code comments, then validates the full chain from requirements → code → tests → reviews. Risk-class-aware validation (A/B/C), SHA-256 tamper detection, CI pipeline gating, and a VS Code extension with real-time diagnostics. Designed from patterns I've seen repeatedly across 11 years of regulated medical device development. TypeScript monorepo, 218 tests.

**TikTok Live Game Platform** — Real-time interactive game on a custom C# engine with AI-driven procedural content generation (ComfyUI, MuseTalk, LLMs), TikTok Live integration, and a React + FastAPI content dashboard. Dual-GPU inference across RTX 4090 + 3090.

**Cozy Creatures** — Multiplayer social hangout where players are cute low-poly creature avatars in themed 3D rooms. React Three Fiber, Socket.io real-time sync, LiveKit spatial voice chat, 30-skin collectible cosmetics system with HSL shaders and GPU particles. 10k+ lines of TypeScript across client, server, and shared packages. 382 tests.

**UEFN Dungeon Crawler** — Procedurally generated dungeon crawler in Verse with 11 game systems, Kruskal's maze generation across 3 vertical levels, and data-driven item/ability progression.

## Open Source

| Project | Description |
|---------|-------------|
| [**orchestration-engine**](https://github.com/JMRussas/orchestration-engine) | Multi-model task orchestration: dependency DAG, budget-aware model routing, parallel execution, real-time SSE. 390+ tests. |
| [**ai-engineering-conventions**](https://github.com/JMRussas/ai-engineering-conventions) | 14 process conventions for AI-augmented development — planning rigor, guardrail hooks, checkpoint commits, context budgeting, and more. Extracted from daily practice. |
| [**mcp-rag**](https://github.com/JMRussas/mcp-rag) | Config-driven RAG pipeline + MCP server. Chunks code with language-aware parsers, embeds locally via Ollama, serves hybrid semantic/keyword search. |
| [**cozy-creatures**](https://github.com/JMRussas/cozy-creatures) | Multiplayer 3D social hangout: React Three Fiber, Socket.io, LiveKit voice, collectible skin system. 382 tests. |
| [**dungeon-gen**](https://github.com/JMRussas/dungeon-gen) | Interactive browser-based dungeon generator — Kruskal's algorithm, Union-Find, BFS room assignment. [Live demo.](https://jmrussas.github.io/dungeon-gen/) |
| [**ollama-mcp**](https://github.com/JMRussas/ollama-mcp) | MCP server exposing local Ollama instances as tools for AI coding assistants. Multi-host routing, generate/chat/embed/list endpoints. |
| [**ai-video-composite**](https://github.com/JMRussas/ai-video-composite) | Green-screen removal and compositing toolkit for AI-generated video. Three-stage cleanup pipeline (rembg + alpha cleanup + green defringing). |

## Career Highlights

- **Dell EMC** (8 years) — Built a three-tier test orchestration platform managing 90% of automated testing for Midrange Storage. ML-optimized scheduling. Scaled VxRail engineering from 30 to 200+ people; product grew from $30M to $2B+.
- **Full Spectrum Software** (9 years) — Production software and technical lead across regulated medical device products: infusion pumps, ultrasound imaging, EEG monitoring, and radiation dosimetry systems. IEC 62304, ISO 13485.
- **Full Spectrum Software** (2 years, return engagement) — Technical project management with hands-on development. Regulated IoT on Linux, intelligent catheter systems. FDA regulatory frameworks, IEC 62304.
- **Haemonetics** (current) — R&D Program Manager across multiple medical device software products: TEG, NexLynk, and BloodTrack.

## Tech

`C#` `.NET` `Python` `TypeScript` `React` `React Three Fiber` `FastAPI` `Unity` `UEFN/Verse` `Docker` `Ollama` `SQLite` `Socket.io` `LiveKit` `MCP` `RAG`
