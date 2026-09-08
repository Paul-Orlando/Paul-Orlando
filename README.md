# Paul Orlando
**Creative Technologist & AI Agent Developer**

I design and build production-grade AI agent systems — from single-agent RAG pipelines to multi-agent orchestration frameworks. My work spans agentic workflow design, retrieval-augmented generation, prompt engineering, full-stack AI applications, enterprise AI architecture, and serverless deployment patterns. I also apply generative AI tools and prompt engineering techniques to produce commercial brand imagery for major retail clients.

Based in US & EU/Ireland.

🌐 [paulforlando.com](https://paulforlando.com)  |  💼 [LinkedIn](https://linkedin.com/in/paul-orlando)  |  📧 Available for freelance & consulting

---

## What I Build

Single Agents → Multi-Agent Systems → Enterprise Orchestration Pipelines → Full-Stack AI Applications → Serverless Production Systems

I focus on agents that are production-ready — properly configured, defensively prompted, and designed to fail gracefully. Not just demos.

---

## AWS & Enterprise Work

### Serverless Agentic AI Travel Agent
**Production-ready enterprise agentic AI on AWS**

A fully functional travel booking agent demonstrating serverless multi-tool agent orchestration:

- **Agent Framework:** Strands SDK + Bedrock Nova Lite
- **Memory:** S3 SessionManager for persistent conversation history
- **RAG:** Bedrock Knowledge Bases for private data access
- **Extensibility:** Model Context Protocol (MCP) dynamic tool loading
- **API:** Secure HTTP via API Gateway + Cognito OAuth2
- **Scale:** Handles 1000+ concurrent requests, ~$0.02/request

**Pattern:** Multi-tool orchestration → Persistent memory → RAG integration → Secure API exposure

**GitHub:** [serverless-agentic-ai-travel-agent](https://github.com/Paul-Orlando/serverless-agentic-ai-travel-agent)

**Stack:** Strands SDK · Bedrock · Lambda · API Gateway · Cognito · S3 · Knowledge Bases

---

## Agent Portfolio

| Agent | Pattern | Stack | Demo |
|---|---|---|---|
| [Prelegal](https://github.com/Paul-Orlando/prelegal_document_app) | AI Interview + Document Assembly | Node.js · Express · SQLite · OpenRouter · Common Paper Templates | [🔗 Live](https://prelegaldocumentapp-production.up.railway.app/) |
| [Serverless Agentic AI Travel Agent](https://github.com/Paul-Orlando/serverless-agentic-ai-travel-agent) | Multi-Tool Orchestration + Memory + RAG | Strands SDK · Bedrock · Lambda · API Gateway · Cognito · S3 | [🔗 Repo](https://github.com/Paul-Orlando/serverless-agentic-ai-travel-agent) |
| [Food Chatbot App](https://github.com/Paul-Orlando/food-chatbot-app) | Agentic RAG + Cart | Next.js · FastAPI · ChromaDB · OpenAI | [🔗 Live](https://food-chatbot-app.vercel.app) |
| [AI Agent Team Supervisor App](https://github.com/Paul-Orlando/ai-agent-team-supervisor-app) | Supervisor Pattern | OpenAI Agents SDK · Next.js · FastAPI · ChromaDB | [🔗 Live](https://ai-agent-team-supervisor-app.vercel.app) |
| [Data Analysis Agent App](https://github.com/Paul-Orlando/data-analysis-agent-app) | Interactive Data Agent | Claude Code · Next.js · FastAPI · OpenAI · Recharts | [🔗 Live](https://data-analysis-agent-app.vercel.app) |
| [Deep Research Agent App](https://github.com/Paul-Orlando/deep-research-agent-app) | Full-Stack Research App | Claude Code · Next.js · OpenRouter · Exa AI · TypeScript | [🔗 Live](https://deep-research-agent-app.vercel.app) |
| [Web Research Hub](https://github.com/Paul-Orlando/web-research-hub) | Hierarchical 3-Agent Pipeline + MCP | Next.js · FastAPI · OpenRouter · Gemini 2.5 Flash · Exa AI · MCP | [🔗 Live](https://web-research-hub.vercel.app) |
| [Web Research Hub MCP Server](https://github.com/Paul-Orlando/web-research-hub-mcp-server) | Custom MCP Server · Research Tools | FastAPI · FastMCP · Streamable HTTP · Exa AI · Python | [🔗 Live](https://web-research-hub-mcp.onrender.com) |
| [GenAI Concepts Chat](https://github.com/Paul-Orlando/genai-concepts-chat) | Agentic RAG + Custom MCP Server | Node.js · Express · TypeScript · Pinecone · OpenRouter · Gemini Flash 2.5 | [🔗 Live](https://genai-concepts-chat.railway.app) |
| [Pinecone Agentic Search MCP Server](https://github.com/Paul-Orlando/pinecone-mcp-server) | Custom MCP Server · Agentic RAG | Node.js · TypeScript · Pinecone · OpenRouter · MCP Protocol · Railway | [🔗 Live](https://pinecone-mcp-server.railway.app) |
| AI Document Generator | LLM Chain + Quality Gate | n8n · OpenRouter · GPT-4.1 · LangChain | — |
| AI Agent Team — Supervisor Pattern | Supervisor Orchestration | Flowise AgentFlows V2/V3 · GPT-4o · LangChain | — |
| AI Food Chatbot Agent | Agentic RAG + Tool Routing | Flowise · GPT-4o · Postgres · OpenAI Moderation | — |
| AI Multi-Agent Content Pipeline | Sequential Multi-Agent | Flowise · GPT-4o · FAISS · RAG | — |
| AI Web Research Agent | RAG + Web Scraping | Flowise · GPT-4o-mini · FAISS · Cheerio | — |
| AI Research Assistant RAG | Lightweight RAG | Python · OpenAI · NumPy · Scikit-learn | — |
| Data Analysis Agent | Custom GPT | GPT-4 · Python · Pandas · Scikit-learn | — |

---

## 🎨 Creative Work — AI Product Visualization

I use generative AI tools with prompt engineering techniques to produce brand imagery for major retail clients across the following disciplines:

- Generative AI Image Creation
- AI Art Direction
- Commercial Product Visualization
- Lifestyle Imagery

🔗 [View Portfolio on ArtStation](https://www.artstation.com/paul-orlando)  |  [Repository](https://github.com/Paul-Orlando/ai-product-visualization)

---

## Core Skills

**Agent Design** — tool routing, prompt engineering, multi-agent orchestration, supervisor patterns, retrieval-augmented generation, hallucination detection, moderation, memory, full-stack AI applications, MCP server development, serverless agent deployment

**Cloud & Infrastructure** — AWS Lambda, API Gateway, Bedrock, Cognito, S3, Knowledge Bases, CloudWatch, serverless architecture patterns

**Stack** — Flowise · LangChain · OpenAI API · Python · FastAPI · Next.js · n8n · TypeScript · OpenRouter · Exa · Postgres · FAISS · Neon · Supabase · Claude Code · Pinecone · FastMCP · MCP Protocol · Railway · Vercel · Strands SDK

**Disciplines** — 3D Visualization · Generative AI · Data Analytics · AI Product Visualization · Serverless Architecture

---

## Approach

Every agent in this portfolio is built with the same standard:

- Explicit, rule-based system prompts — no vague instructions
- Tool descriptions written as policies, not labels
- Temperature tuned to the use case — not left at default
- Failure modes addressed — iteration caps, moderation, fallbacks
- Production considerations documented — memory, security, deployment

---

## 🔒 Production Standards

Every live application in this portfolio is built with production-grade security and cost controls — not just functional demos.

**MCP Server Security**
Both custom MCP servers implement API key authentication (`X-API-Key` header, 401 on invalid key) and sliding-window rate limiting (5–10 requests/IP/hour, 429 on exceed) with self-host instructions embedded in every error response. Rate limiting is implemented as pure middleware without third-party auth frameworks — correct IP detection behind Railway's proxy via `X-Forwarded-For` header parsing.

**AWS Lambda Security & Scalability**
The serverless agentic AI system implements Cognito OAuth2 authentication, per-user session isolation, S3-backed state management, and automatic horizontal scaling. Infrastructure costs are controlled through serverless pay-per-use pricing (~$0.02/request), with no idle server overhead.

**Cost Protection**
All LLM API keys (OpenAI, OpenRouter) are capped at hard monthly spend limits. Exa AI auto-recharge is capped per calendar month. Rate limiting at the infrastructure layer provides the first line of defense; spend caps at the provider level provide a hard ceiling if rate limiting is ever bypassed.

Production AI systems require controls at every layer — request-level rate limiting, infrastructure-level authentication, provider-level spend caps, and cloud-native security. Each application in this portfolio is built with these standards, reflecting practices applied in enterprise deployments where cost, security, and reliability are non-negotiable.

---

*Open to collaboration on agent design, AI workflow architecture, serverless AI systems, and creative technology projects.*
