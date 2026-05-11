# Hey there, I'm Navneet Prabhakar 👋

### Senior Engineering Manager @ Target · AI Agent Architect · Java Enterprise Engineer

I lead engineering teams at Target while staying deeply hands-on — building production-grade AI agent systems, MCP integrations, and enterprise Java platforms. My work sits at the intersection of cutting-edge AI and shipping code that runs in production.

<p>
  <a href="https://github.com/navneetprabhakar?tab=followers">
    <img src="https://img.shields.io/github/followers/navneetprabhakar?label=Followers&style=for-the-badge&color=4078c0&logo=github&logoColor=white&v=2" alt="GitHub Followers" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=navneetprabhakar&label=Profile+Views&style=for-the-badge&color=blueviolet" alt="Profile Views" />
  <img src="https://img.shields.io/badge/Open_to-Collaboration-2ea44f?style=for-the-badge" alt="Open to Collaboration" />
</p>

---

## 🛠️ Currently Building

### ExecuteSpec — Agentic codegen platform *(private, in stealth)*

A multi-agent AI coding system: submit a spec, get production code with PRs opened against your repos. **Spring Boot 3.3 + Spring AI 1.1 + React + PostgreSQL + Redis**, deployed on GCP.

**Pipeline:** Smart Classifier → Outline/Skeleton Planner → parallel Task Expansion → Sequential Worker with native tool-calling → Reviewer (general + wiring passes) → auto-preview + GitHub PR.

**What makes it interesting:**
- **Tri-provider native tool calling** through one `LlmRouter` — Anthropic (Claude Sonnet/Haiku 4.x), OpenAI (GPT-5.4), Google Gemini (3 Pro/Flash). Per-provider circuit breakers, prompt-cache-aware cost tracking, BYOK + managed-key modes.
- **Empirically validated** — resolves SWE-bench Lite instances (medium 67%, hard 60% across 3 providers) and scores 98/100 on ProgramBench cmatrix.
- **Multi-repo project workspaces** with versioned architecture docs, RAG over project docs (pgvector), cross-repo contract registries, and a `.executespec/` folder pattern that lives in customer git.
- **Customer-facing surfaces** — PR Review agent, Code Review scanner (semgrep + LLM triage), automated CI-failure patch mode, project chat with apply-suggestion, multi-tenant orgs + Stripe/Razorpay billing.
- **Engineering discipline** — ~180 Flyway migrations, 1,000+ test suite, ArchUnit guards, native tool-calling end-to-end (no XML parsing hacks), cleanroom Docker containers for safe code execution.

📬 **Want a demo, architecture deep-dive, or to compare notes on agentic codegen systems?** [Email me](mailto:navneet.prabhakar007@gmail.com) or [reach out on LinkedIn](https://www.linkedin.com/in/navneetprabhakar/) — happy to walk through the design.

### [project-chaos](https://github.com/navneetprabhakar/project-chaos) — Multi-LLM debate orchestrator

Concurrent debates between OpenAI, Anthropic, and Gemini agents with a supervisor agent monitoring consensus in real-time. Spring Boot 3.4 + Spring AI + React + STOMP/WebSocket. Open source, runnable locally.

---

## 🚀 Featured Projects

### AI Agents & MCP
- **[project-chaos](https://github.com/navneetprabhakar/project-chaos)** — Multi-agent debate system with OpenAI/Anthropic/Gemini and an automated supervisor for consensus detection
- **[trade-mcp-server](https://github.com/navneetprabhakar/trade-mcp-server)** — Stock trading MCP server with Spring AI
- **[mcp-client](https://github.com/navneetprabhakar/mcp-client)** / **[mcp-server](https://github.com/navneetprabhakar/mcp-server)** — Reference MCP client/server implementations
- **[zero-trade-app](https://github.com/navneetprabhakar/zero-trade-app)** — Agentic AI trading on Zerodha Kite Connect with technical/news/research agents + risk manager
- **[fno-conservative-algo](https://github.com/navneetprabhakar/fno-conservative-algo)** — Conservative F&O algorithmic trading with AI agents

### LLM Integrations
- **[openai](https://github.com/navneetprabhakar/openai)** — OpenAI + Spring AI with RAG, pgvector, chat memory
- **[anthropic](https://github.com/navneetprabhakar/anthropic)** — Claude integration with Spring AI
- **[gemini](https://github.com/navneetprabhakar/gemini)** — Gemini API with Spring AI
- **[javagpt](https://github.com/navneetprabhakar/javagpt)** — Lightweight local GPT in Java 21 + Deep Java Library (DJL)
- **[query-builder](https://github.com/navneetprabhakar/query-builder)** — Text-to-query generator

### Bots & Messaging
- **[telegram-bot-llm](https://github.com/navneetprabhakar/telegram-bot-llm)** — Telegram bot with LLM code-gen
- **[telegram-bot](https://github.com/navneetprabhakar/telegram-bot)** — Telegram bot with LLM + MCP capabilities
- **[websocket](https://github.com/navneetprabhakar/websocket)** — Simple chat over WebSockets

### Enterprise Java
- **[drools](https://github.com/navneetprabhakar/drools)** ⭐ 5 — Drools Rule Engine + Spring Boot
- **[executor](https://github.com/navneetprabhakar/executor)** ⭐ 3 — Java Executor Framework patterns
- **[kafka](https://github.com/navneetprabhakar/kafka)** — Kafka producer/consumer + Spring Boot
- **[elasticsearch](https://github.com/navneetprabhakar/elasticsearch)** — Elasticsearch + Spring Boot
- **[dms](https://github.com/navneetprabhakar/dms)** — Document Management System (MongoDB GridFS)
- **[bank-statement-analyser](https://github.com/navneetprabhakar/bank-statement-analyser)** — Bank statement categorisation
- **[credit-risk-analyser](https://github.com/navneetprabhakar/credit-risk-analyser)** — Credit risk from bank statement + bureau + GST/ITR
- **[jeasy](https://github.com/navneetprabhakar/jeasy)** — Jeasy Rule Engine + Spring Boot + Swagger
- **[stock-exchange-trade](https://github.com/navneetprabhakar/stock-exchange-trade)** — Groww API wrapper for stock & F&O
- **[fno-dashboard](https://github.com/navneetprabhakar/fno-dashboard)** — Investment & strategy tracking UI
- **[cowin](https://github.com/navneetprabhakar/cowin)** — CoWin Public API integration

### Algorithms & Simulations
- **[montecarlo](https://github.com/navneetprabhakar/montecarlo)** ⭐ 1 — Monte Carlo simulations
- **[geneticAlgo](https://github.com/navneetprabhakar/geneticAlgo)** — Genetic algorithm implementation
- **[tictactoe](https://github.com/navneetprabhakar/tictactoe)** — Tic-tac-toe with minimax AI player
- **[network](https://github.com/navneetprabhakar/network)** — Mail-train control system (Java)

---

## 💻 Tech Stack

![Java](https://img.shields.io/badge/Java-21-007396?logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.x-6DB33F?logo=spring&logoColor=white)
![Spring AI](https://img.shields.io/badge/Spring_AI-1.1-6DB33F?logo=spring&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15+-336791?logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?logo=apachekafka&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?logo=elasticsearch&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)
![React](https://img.shields.io/badge/React-18-61DAFB?logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic_Claude-D97757)
![Gemini](https://img.shields.io/badge/Google_Gemini-8E75B2?logo=google&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?logo=googlecloud&logoColor=white)

**Specialties:** AI agent orchestration · multi-LLM routing & failover · Model Context Protocol (MCP) · RAG + pgvector · prompt caching · rule engines (Drools, Jeasy) · distributed systems · real-time messaging (Kafka, STOMP, SSE) · observability (Micrometer, OTel, Prometheus, Tempo, Grafana) · algorithms (Monte Carlo, Genetic, Minimax, Dijkstra)

---

## 🌱 Currently Exploring

- Production patterns for multi-agent codegen pipelines (planner → worker → reviewer with native tool calling)
- Cost-aware LLM routing with prompt-cache hit-rate optimisation across Anthropic / OpenAI / Gemini
- SWE-bench-style empirical evaluation of agentic systems on real-world bug-fix benchmarks
- High-performance LLM inference with Java + DJL

---

## 🤝 Let's Collaborate

Open to chats on AI/LLM in enterprise Java, Spring AI + agent orchestration, MCP servers/clients, rule engines, distributed systems, and algorithmic problem-solving. If you're building something agentic and want to compare notes — or want to learn more about ExecuteSpec — drop me a line.

## 📫 Get In Touch

- 💼 [LinkedIn](https://www.linkedin.com/in/navneetprabhakar/)
- 📧 navneet.prabhakar007@gmail.com
- 🐙 You're already here — explore the repos above

---

💡 *Building AI agent systems that actually ship to production.*
