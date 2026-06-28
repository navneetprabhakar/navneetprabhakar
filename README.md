<div align="center">

# Navneet Prabhakar

<a href="https://readme-typing-svg.demolab.com">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=6DB33F&center=true&vCenter=true&width=760&lines=Senior+Engineering+Manager+%40+Target;AI+Agent+Architect+%E2%80%A2+MCP+%E2%80%A2+Spring+AI;Spec-driven+codegen+%E2%80%A2+multi-LLM+orchestration;Java+%E2%80%A2+enterprise+platforms+%E2%80%A2+production+AI" alt="Typing tagline" />
</a>

<p>
  <a href="https://www.linkedin.com/in/navneetprabhakar/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:navneet.prabhakar007@gmail.com"><img src="https://img.shields.io/badge/Email-Reach_out-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://komarev.com/ghpvc/?username=navneetprabhakar&label=Profile+Views&style=for-the-badge&color=6DB33F" alt="Profile Views" />
</p>

</div>

I lead engineering teams at **Target** while staying deeply hands-on — designing production-grade **AI agent systems**, **multi-LLM platforms**, and **enterprise Java**. My work lives at the intersection of cutting-edge AI and code that actually ships to production. Most of my recent energy goes into **agentic developer tooling**: turning natural language into planned, reviewed, verified software.

---

## 🧪 What I'm Building

### 🤖 Spec-driven AI codegen platform · _private_

A multi-agent system that turns natural-language change requests into **plan-gated, verified pull requests** across many repos and projects. A **Spring Boot 3 + Spring AI** engine drives a **multi-LLM router** (Anthropic · OpenAI · Gemini) with per-provider failover and cost tracking, RAG over project docs (**pgvector**), and SWE-bench-style empirical evaluation. It ships as a full product surface — a **TypeScript CLI** (installable via Homebrew), a **VS Code extension**, live **preview infrastructure** (auto-deployed through GitHub Actions), and a docs site. It grew out of my earlier **DevPilot** prototype: brainstorm → plan → implement → AI review, with plan versioning, digital sign-off, event-sourced audit trails, and OAuth2/JWT.

### 🏴‍☠️ Autonomous multi-agent dev crew · _private_

An orchestration layer on top of **Claude Code**: builder agents work in isolated domains, an **adversarial reviewer agent** approves or rejects every PR, and the whole crew is driven from Slack. Approved PRs auto-merge, rejections loop back with feedback, repeated failures escalate to me — with a morning digest. Wake up to merged PRs.

### 🧠 Local model fine-tuning · _private_

A local-first training workspace for **Gemma 4 12B** with **MLX-LM + LoRA** on Apple Silicon — reproducible gate-based experiments, holdout-loss tracking, and quantized (q4/q8) serving paths. Proof-on-laptop before any GPU/cloud spend.

### 💼 Helm — agent-first job-search PWA · [public](https://github.com/navneetprabhakar/helm)

A candidate-first job portal for **India + US** where an LLM agent is the spine, not a feature. "Today's Brief" pre-warms curated matches each morning; a hybrid keyword + LLM tool-router drives 8 tools (search, tailor resume, research company, draft counter-offer, career advice…). Weighted match scoring, **H-1B / LCA sponsorship signals**, salary intelligence with regional take-home calculators, and a reskill planner — all feature-flag-gated.

### 🎓 Education — source-aware exam-prep AI · [public](https://github.com/navneetprabhakar/education)

An AI prep platform for Indian exams: AI tutor with a **RAG** abstraction, practice/tests, mistake notebook, progress tracking, safeguarding, and parent boundaries. **Next.js + Fastify + PostgreSQL/pgvector** monorepo.

---

## 🚀 Featured Open-Source Work

### 🤖 AI Agents & MCP
- **[project-chaos](https://github.com/navneetprabhakar/project-chaos)** — Multi-LLM debate orchestrator: concurrent OpenAI / Anthropic / Gemini agents with a supervisor watching consensus in real time. Spring Boot 3.4 + Spring AI + React + STOMP/WebSocket
- **[trade-mcp-server](https://github.com/navneetprabhakar/trade-mcp-server)** — Stock-trading MCP server built on Spring AI (Groww)
- **[mcp-client](https://github.com/navneetprabhakar/mcp-client)** · **[mcp-server](https://github.com/navneetprabhakar/mcp-server)** — Reference Model Context Protocol client / server
- **[zero-trade-app](https://github.com/navneetprabhakar/zero-trade-app)** — Agentic trading on Zerodha Kite Connect: technical / news / research agents + risk manager
- **[fno-conservative-algo](https://github.com/navneetprabhakar/fno-conservative-algo)** — Conservative F&O algo trading with AI agents

### 🧠 LLM Integrations
- **[openai](https://github.com/navneetprabhakar/openai)** — OpenAI + Spring AI with RAG, pgvector, chat memory
- **[anthropic](https://github.com/navneetprabhakar/anthropic)** — Claude integration with Spring AI
- **[gemini](https://github.com/navneetprabhakar/gemini)** — Gemini API with Spring AI
- **[javagpt](https://github.com/navneetprabhakar/javagpt)** — Lightweight local GPT in Java 21 + Deep Java Library (DJL)
- **[query-builder](https://github.com/navneetprabhakar/query-builder)** — Text-to-query / text-to-SQL generator

### 💬 Bots & Messaging
- **[telegram-bot-llm](https://github.com/navneetprabhakar/telegram-bot-llm)** — Telegram bot with LLM code-gen
- **[telegram-bot](https://github.com/navneetprabhakar/telegram-bot)** — Telegram bot with LLM + MCP capabilities
- **[websocket](https://github.com/navneetprabhakar/websocket)** — Simple chat over WebSockets

### 🏗️ Enterprise Java & Fintech
- **[drools](https://github.com/navneetprabhakar/drools)** ⭐ 5 — Drools Rule Engine + Spring Boot
- **[executor](https://github.com/navneetprabhakar/executor)** ⭐ 3 — Java Executor Framework patterns
- **[credit-risk-analyser](https://github.com/navneetprabhakar/credit-risk-analyser)** — Credit risk from bank statement + bureau + GST/ITR, with Drools
- **[bank-statement-analyser](https://github.com/navneetprabhakar/bank-statement-analyser)** — Bank-statement categorisation (OCR + PDFBox + Gemini)
- **[kafka](https://github.com/navneetprabhakar/kafka)** — Kafka producer/consumer + Spring Boot
- **[elasticsearch](https://github.com/navneetprabhakar/elasticsearch)** — Elasticsearch + Spring Boot
- **[dms](https://github.com/navneetprabhakar/dms)** — Document Management System (MongoDB GridFS)
- **[jeasy](https://github.com/navneetprabhakar/jeasy)** — Jeasy Rule Engine + Spring Boot + Swagger
- **[stock-exchange-trade](https://github.com/navneetprabhakar/stock-exchange-trade)** — Groww API wrapper for stock & F&O
- **[fno-dashboard](https://github.com/navneetprabhakar/fno-dashboard)** — Investment & strategy tracking UI
- **[cowin](https://github.com/navneetprabhakar/cowin)** — CoWin Public API integration

### 🔬 Algorithms & Simulations
- **[montecarlo](https://github.com/navneetprabhakar/montecarlo)** ⭐ 1 — Monte Carlo simulations
- **[geneticAlgo](https://github.com/navneetprabhakar/geneticAlgo)** — Genetic algorithm implementation
- **[tictactoe](https://github.com/navneetprabhakar/tictactoe)** — Tic-tac-toe with minimax AI
- **[network](https://github.com/navneetprabhakar/network)** — Mail-train control system with Dijkstra scheduling (Java)

### 🎨 Developer Tooling
- **[uxdesigns](https://github.com/navneetprabhakar/uxdesigns)** — Curated `DESIGN.md` design-system files agents can read to build matching UI

---

## 🛠️ Tech Stack

![Java](https://img.shields.io/badge/Java-21-007396?logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.x-6DB33F?logo=spring&logoColor=white)
![Spring AI](https://img.shields.io/badge/Spring_AI-1.1-6DB33F?logo=spring&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-18-61DAFB?logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15+-336791?logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-336791?logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?logo=apachekafka&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic_Claude-D97757)
![Gemini](https://img.shields.io/badge/Google_Gemini-8E75B2?logo=google&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?logo=googlecloud&logoColor=white)

**Specialties:** AI agent orchestration · multi-LLM routing & failover · Model Context Protocol (MCP) · RAG + pgvector · prompt caching · LLM fine-tuning (LoRA / MLX) · rule engines (Drools, Jeasy) · distributed systems · real-time messaging (Kafka, STOMP, SSE) · observability (Micrometer, OTel, Prometheus, Grafana) · algorithms (Monte Carlo, Genetic, Minimax, Dijkstra)

---

## 🌱 Currently Exploring

- Spec-driven, plan-gated codegen workflows that keep the human in the loop
- Cost-aware LLM routing with prompt-cache hit-rate optimisation across Anthropic / OpenAI / Gemini
- Empirical, SWE-bench-style evaluation of agentic systems on real-world bug fixes
- Fine-tuning small coding models locally (Gemma + MLX + LoRA) before scaling to cloud

---

<div align="center">

### 🤝 Let's build something agentic

Spring AI · agent orchestration · MCP servers/clients · enterprise Java · rule engines · distributed systems

<a href="https://www.linkedin.com/in/navneetprabhakar/"><img src="https://img.shields.io/badge/LinkedIn-navneetprabhakar-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:navneet.prabhakar007@gmail.com"><img src="https://img.shields.io/badge/Email-navneet.prabhakar007-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>

<sub>💡 Building AI agent systems that actually ship to production.</sub>

</div>
