# Justin Russas

**Principal Engineer / Engineering Manager · AI systems, developer infrastructure, and regulated software**

I bring 25+ years of software engineering and technical leadership, and I am looking for senior individual contributor or engineering management roles. My background spans medical device software, test orchestration at Dell EMC, and current projects in AI evaluation, task execution, and C# graphics.

I focus on systems whose behavior can be inspected: explicit execution plans, meaningful failure states, and verification that tests the claims we make about the software.

## Start here

| Project | Engineering question | Evidence |
|---|---|---|
| **[Tiered moderation agent](https://github.com/JMRussas/tiered-moderation-agent)** · Python | How should an AI system behave when it cannot classify an input reliably? | [Case study](https://github.com/JMRussas/tiered-moderation-agent/blob/main/docs/case-study.md): uncertainty-preserving fallbacks, regression tests, recorded evaluations, and dataset limits. |
| **[Orchestration Engine](https://github.com/JMRussas/orchestration-engine)** · Python / React | How do you coordinate dependent AI tasks while making plans, cost, and recovery visible? | [Case study](https://github.com/JMRussas/orchestration-engine/blob/main/docs/case-study.md): dependency graphs, budget reservations, stale-work recovery, and process-local guarantees. |
| **[Hekate](https://github.com/JMRussas/Hekate)** · Python / C# / React | How do you keep multi-agent software work reviewable when the models doing it can be wrong? | [README](https://github.com/JMRussas/Hekate#readme): multi-pass plan review, test-first development, cross-model code review, and a dated inventory of what the legacy engine does not guarantee. |
| **[ChatAgent](https://github.com/JMRussas/ChatAgent)** · TypeScript / Python | How does a chat assistant stay responsive while background agents do bounded, checkpointed work? | [Case study](https://github.com/JMRussas/ChatAgent/blob/main/docs/portfolio-case-study.md) and [results](https://github.com/JMRussas/ChatAgent/blob/main/docs/results.md): lifecycle fault injection and local-model contention measurements. |

For **AI and platform roles**, start with moderation and orchestration, then Hekate and ChatAgent, then [mcp-rag](https://github.com/JMRussas/mcp-rag), a local code-search pipeline with optional hybrid retrieval and source freshness checks.

For **real-time and full-stack roles**, start with [Cozy Creatures](https://github.com/JMRussas/cozy-creatures), a multiplayer browser application with Socket.io and spatial voice. For a quick interactive example, try the [dungeon generator](https://jmrussas.github.io/dungeon-gen/).

## Professional foundation

- **Dell EMC — eight years:** built a three-tier orchestration platform managing 90% of automated testing for Midrange Storage, including ML-optimized scheduling. Engineering leadership during VxRail's growth from 30 to 200+ engineers and $30M to $2B+ in product revenue.
- **Full Spectrum Software — eleven years across two engagements:** production development, technical leadership, and hands-on project management across infusion pumps, ultrasound, EEG, radiation dosimetry, and regulated IoT.
- **Haemonetics — most recent role, ended June 2026:** R&D Program Manager across TEG, NexLynk, and BloodTrack medical device software products.

The public projects demonstrate current implementation work. My professional experience provides the context for larger-scale delivery and leadership; these prototypes do not claim equivalent deployment scale.

Most of my code is not public. Twenty-five years of it is employer-owned, and my larger independent projects are private, including a TikTok LIVE game platform built on a C# engine with eight pluggable game modules and TraceabilityMedCode, a code-native IEC 62304 / ISO 13485 traceability tool for medical device software. I can walk through private work in interviews.

## How I work

I use AI coding tools and document that assistance in commit history. My responsibility is system design, technical decisions, review, and verification. The case studies above show concrete failures and tradeoffs.

[AI Engineering Conventions](https://github.com/JMRussas/ai-engineering-conventions) collects the practical process. [AI Engineering Research](https://github.com/JMRussas/ai-engineering-research) contains the companion practitioner writing, including *Faster Isn't Better*.

Additional tools: [agent-bridge-mcp](https://github.com/JMRussas/agent-bridge-mcp), a durable mailbox and cross-machine source access for coding agents · [Ollama MCP](https://github.com/JMRussas/ollama-mcp) · [AI video compositing](https://github.com/JMRussas/ai-video-composite).

**Core stack:** C# / .NET · Python · TypeScript / React · SQLite · Docker · local inference · WebGPU.

[LinkedIn](https://www.linkedin.com/in/justin-russas-7102a9/)
