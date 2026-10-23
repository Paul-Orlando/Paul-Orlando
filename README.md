# Paul Orlando
**Creative Technologist & AI Agent Developer**

I design and build AI agent systems to production standards — from single-agent RAG pipelines to multi-agent orchestration frameworks. My work spans agentic workflow design, retrieval-augmented generation, prompt engineering, full-stack AI applications, AI system architecture, real-time streaming systems, and serverless deployment patterns. I also apply generative AI tools and prompt engineering techniques to produce commercial brand imagery for major retail clients.

Based in US & EU/Ireland.

🌐 [paulforlando.com](https://www.paulforlando.com)  |  💼 [LinkedIn](https://www.linkedin.com/in/paul-orlando-7841b5154/)  |  📧 Available for freelance & consulting

---

## What I Build

Single Agents → Multi-Agent Systems → Orchestration Pipelines → Real-Time Full-Stack AI Applications → Serverless Production Systems

I build every agent as if it were going to production — properly configured, defensively prompted, designed to fail gracefully, protected with cost controls and rate limiting, and measured where it matters.

---

## Featured AI Systems

### Gatewell Parts Desk — AI Operations Assistant for Auto Parts Distribution
**Role-aware AI assistant with server-side guardrails, measured by a 50-question evaluation**

An employee-facing operations app for a fictional U.S. auto parts distributor (11 warehouses, domestic and international orders). Customer service, warehouse staff and managers check stock, quote shipping and currency, work support cases and read analytics — with an AI assistant that answers only from company data:

- **Role-Based Tool Access:** 4 roles (warehouse, customer service, CS supervisor, manager) with server-side redaction of costs, money and customer fields, plus warehouse/region/company data scope
- **Grounding Check:** Server-side guard blocks any stock figure, date or price not backed by a tool call; rejected drafts are discarded and retried, never shown to the user
- **Tool-Supplied Totals:** The model never does its own arithmetic — every total comes from the tools, after an evaluation caught summing errors
- **Decision Support:** Read-only suggested actions — warehouse transfers, reorder quantities and in-stock substitutes — labeled as suggestions, never executed
- **Domain Logic:** Multi-carrier shipping quotes, CAD/MXN/GBP pricing with import tax, stock-aware delivery dates, time-zone-labeled ETAs, live-person handoff routing with team hours
- **Evaluation:** 50 questions × 3 runs scored on facts, tool choice, handoffs and refusals — pass rate raised from **80% to 99%**, refusal accuracy **97%**, about **$0.003 per question** (~$2 for the whole evaluation)
- **Testing:** 200+ automated tests, including permission tests and a check that re-verifies every evaluation answer against the database
- **Cost Protection:** Dual-layer limits (5 questions per visitor, 25 per network address, support-case caps at code level + $5 monthly provider cap)
- **Deployment:** Railway with a persistent volume, health checks and security headers; all company, vehicle, brand and carrier names are fictional

**Pattern:** Role-scoped tools → Server-side redaction → LLM tool loop with round and size caps → Grounding check → Audit log → Measured by evaluation

**GitHub:** [gatewell-parts-desk](https://github.com/Paul-Orlando/gatewell-parts-desk)  
**Live:** [web-production-25c5.up.railway.app](https://web-production-25c5.up.railway.app)

**Stack:** FastAPI · Python · SQLite · JavaScript · Chart.js · OpenRouter · Gemini 3.1 Flash-Lite · Railway

---

### FinAlly — AI Trading Workstation
**Multi-agent trading system with real-time streaming and production safety controls**

An AI-powered trading platform demonstrating multi-agent orchestration, real-time data streaming, domain-specific logic, and layered cost protection:

- **5-Agent Orchestration:** Portfolio (execution), Risk (validation), Analyzer (insights), Watchlist (management), Chat Orchestrator (LLM routing)
- **Real-Time Streaming:** Server-sent events (SSE) for live price updates with flash animations
- **Domain Logic:** Portfolio mathematics, P&L tracking, position constraints, audit logging
- **Testing:** Playwright E2E suite (10 tests, 4 consecutive fresh runs, all passing)
- **Cost Protection:** Dual-layer rate limiting (15 chat/hr, 20 trades/hr code-level + $5 monthly provider cap)
- **Deployment:** Docker multi-stage build with a locked dependency set, Railway, automatic health checks

**Pattern:** Deterministic agents (Risk, Portfolio, Analyzer) + LLM orchestrator → Real-time state management → Atomic transactions → E2E tested

**GitHub:** [multi_agent_trading_app](https://github.com/Paul-Orlando/multi_agent_trading_app)  
**Live:** [multiagenttradingapp-production.up.railway.app](https://multiagenttradingapp-production.up.railway.app)

**Stack:** FastAPI · Next.js · SQLite · Playwright · OpenRouter (Cerebras) · LiteLLM · SSE · Docker · Railway

---

### Serverless Agentic AI Travel Agent
**Serverless agentic AI on AWS, built to production standards**

A fully functional travel booking agent demonstrating serverless multi-tool agent orchestration:

- **Agent Framework:** Strands SDK + Bedrock Nova Lite
- **Memory:** S3 SessionManager for persistent conversation history
- **RAG:** Bedrock Knowledge Bases for private data access
- **Extensibility:** Model Context Protocol (MCP) dynamic tool loading
- **API:** Secure HTTP via API Gateway + Cognito OAuth2
- **Scale:** Serverless auto-scaling (Lambda + API Gateway), estimated ~$0.02/request

**Pattern:** Multi-tool orchestration → Persistent memory → RAG integration → Secure API exposure

**GitHub:** [serverless-agentic-ai-travel-agent](https://github.com/Paul-Orlando/serverless-agentic-ai-travel-agent)

**Stack:** Strands SDK · Bedrock · Lambda · API Gateway · Cognito · S3 · Knowledge Bases

---

## Agent Portfolio

| Agent | Pattern | Stack | Demo |
|---|---|---|---|
| [Gatewell Parts Desk](https://github.com/Paul-Orlando/gatewell-parts-desk) | Role-Aware Tool Agent + Grounding Check + Evaluated | FastAPI · Python · SQLite · OpenRouter · Gemini 3.1 Flash-Lite · Railway | [🔗 Live](https://web-production-25c5.up.railway.app) |
| [FinAlly Trading App](https://github.com/Paul-Orlando/multi_agent_trading_app) | Multi-Agent + Real-Time Streaming + E2E Tested | FastAPI · Next.js · SQLite · Playwright · OpenRouter (Cerebras) · Railway | [🔗 Live](https://multiagenttradingapp-production.up.railway.app) |
| [Prelegal](https://github.com/Paul-Orlando/prelegal_document_app) | AI Interview + Document Assembly | Node.js · Express · SQLite · OpenRouter · Common Paper Templates | [🔗 Live](https://prelegaldocumentapp-production.up.railway.app/) |
| [Serverless Agentic AI Travel Agent](https://github.com/Paul-Orlando/serverless-agentic-ai-travel-agent) | Multi-Tool Orchestration + Memory + RAG | Strands SDK · Bedrock · Lambda · API Gateway · Cognito · S3 | [🔗 Repo](https://github.com/Paul-Orlando/serverless-agentic-ai-travel-agent) |
| [Food Chatbot App](https://github.com/Paul-Orlando/food-chatbot-app) | Agentic RAG + Cart | Next.js · FastAPI · ChromaDB · OpenAI | [🔗 Live](https://food-chatbot-app.vercel.app) |
| [AI Agent Team Supervisor App](https://github.com/Paul-Orlando/ai-agent-team-supervisor-app) | Supervisor Pattern | OpenAI Agents SDK · Next.js · FastAPI · ChromaDB | [🔗 Live](https://ai-agent-team-supervisor-app.vercel.app) |
| [Data Analysis Agent App](https://github.com/Paul-Orlando/data-analysis-agent-app) | Interactive Data Agent | Claude Code · Next.js · FastAPI · OpenRouter · Gemini 2.5 Flash · Recharts | [🔗 Live](https://data-analysis-agent-app.vercel.app) |
| [Web Research Hub](https://github.com/Paul-Orlando/web-research-hub) | Hierarchical 3-Agent Pipeline + MCP | Next.js · FastAPI · OpenRouter · Gemini 2.5 Flash · Exa AI · MCP | [🔗 Live](https://web-research-hub.vercel.app) |
| [Web Research Hub MCP Server](https://github.com/Paul-Orlando/web-research-hub-mcp-server) | Custom MCP Server · Research Tools | FastAPI · FastMCP · Streamable HTTP · Exa AI · Python | — |
| [Pinecone Agentic Search MCP Server](https://github.com/Paul-Orlando/pinecone-mcp-server) | Custom MCP Server · Agentic RAG | Node.js · TypeScript · Pinecone · OpenRouter · MCP Protocol · Railway | — |

### Earlier Builds — Low-Code & Prototypes

| Agent | Pattern | Stack |
|---|---|---|
| [AI Document Generator](https://github.com/Paul-Orlando/ai-n8n-document-generator) | LLM Chain + Quality Gate | n8n · OpenRouter · GPT-4.1 · LangChain |
| [AI Agent Team — Supervisor Pattern](https://github.com/Paul-Orlando/ai-agent-team-supervisor-pattern) | Supervisor Orchestration | Flowise AgentFlows V2/V3 · GPT-4o · LangChain |
| [AI Food Chatbot Agent](https://github.com/Paul-Orlando/ai-food-chatbot-agent) | Agentic RAG + Tool Routing | Flowise · GPT-4o · Postgres · OpenAI Moderation |
| [AI Multi-Agent Content Pipeline](https://github.com/Paul-Orlando/ai-multi-agent-content-pipeline) | Sequential Multi-Agent | Flowise · GPT-4o · FAISS · RAG |
| [AI Web Research Agent](https://github.com/Paul-Orlando/ai-web-research-agent) | RAG + Web Scraping | Flowise · GPT-4o-mini · FAISS · Cheerio |
| [AI Research Assistant RAG](https://github.com/Paul-Orlando/ai-research-assistant-rag) | Lightweight RAG | Python · OpenAI · NumPy · Scikit-learn |
| [Data Analysis Agent (Custom GPT)](https://github.com/Paul-Orlando/data-analysis-agent) | Custom GPT | GPT-4 · Python · Pandas · Scikit-learn |

---

## 🎨 Creative Work — AI Product Visualization

I use generative AI tools with prompt engineering techniques to produce brand imagery for major retail clients across the following disciplines:

- Generative AI Image Creation
- AI Art Direction
- Commercial Product Visualization
- Lifestyle Imagery

🔗 [View Portfolio on ArtStation](https://paulorlando.artstation.com/albums/15070123)  |  [Repository](https://github.com/Paul-Orlando/ai-product-visualization)

---

## Core Skills

**Agent Design** — tool routing, prompt engineering, multi-agent orchestration, supervisor patterns, retrieval-augmented generation, hallucination detection, moderation, memory, full-stack AI applications, MCP server development, serverless agent deployment, real-time streaming systems, role-based tool access, grounding checks, LLM evaluation sets

**Cloud & Infrastructure** — AWS Lambda, API Gateway, Bedrock, Cognito, S3, Knowledge Bases, CloudWatch, serverless architecture patterns, Railway, Docker multi-stage builds

**Stack** — Flowise · LangChain · OpenAI API · Python · FastAPI · Next.js · n8n · TypeScript · OpenRouter · Exa · Postgres · FAISS · Neon · Supabase · Claude Code · Pinecone · FastMCP · MCP Protocol · Railway · Vercel · Strands SDK · Cerebras · Gemini · Chart.js

**Disciplines** — 3D Visualization · Generative AI · Data Analytics · AI Product Visualization · Serverless Architecture · Real-Time Systems

---

## Approach

Every agent in this portfolio is built with the same standard:

- Explicit, rule-based system prompts — no vague instructions
- Tool descriptions written as policies, not labels
- Temperature tuned to the use case — not left at default
- Failure modes addressed — iteration caps, moderation, fallbacks
- Production considerations documented — memory, security, deployment, cost controls
- Measured, not assumed — evaluation sets with expected answers drawn from real data, rerun after every fix

---

## 🔒 Production Standards

Every live application in this portfolio is built with production-style security and cost controls, even as a demo.

**Real-Time System Resilience**
FinAlly demonstrates real-time state management with SSE streaming, connection status indicators, automatic reconnection, and atomic database transactions. The system handles concurrent requests with in-memory rate limiting and maintains audit logs for compliance.

**Data Access & Answer Grounding**
Gatewell Parts Desk enforces role permissions on the server, not in the prompt: every tool result passes through redaction and data-scope filters before the model sees it, so a warehouse role cannot receive costs even if asked directly. A server-side grounding check withholds any figure the model states without a tool lookup, and every question and tool call is written to an audit log.

**MCP Server Security**
Custom MCP servers implement API key authentication (`X-API-Key` header, 401 on invalid key) and sliding-window rate limiting (5–10 requests/IP/hour, 429 on exceed) with self-host instructions embedded in every error response. Rate limiting is implemented as pure middleware without third-party auth frameworks — correct IP detection behind Railway's proxy via `X-Forwarded-For` header parsing.

**AWS Lambda Security & Scalability**
The serverless agentic AI system implements Cognito OAuth2 authentication, per-user session isolation, S3-backed state management, and automatic horizontal scaling. Infrastructure costs are controlled through serverless pay-per-use pricing (~$0.02/request), with no idle server overhead.

**Cost Protection**
All LLM API keys (OpenAI, OpenRouter) are capped at hard monthly spend limits. Exa AI auto-recharge is capped per calendar month. Rate limiting at the infrastructure layer provides the first line of defense; spend caps at the provider level provide a hard ceiling if rate limiting is ever bypassed.

Production AI systems require controls at every layer — request-level rate limiting, infrastructure-level authentication, provider-level spend caps, and cloud-native security. Each application in this portfolio is built with these standards, following the practices real deployments need, where cost, security, reliability, and real-time performance are non-negotiable.

---

*Open to collaboration on agent design, AI workflow architecture, serverless AI systems, real-time applications, and creative technology projects.*
