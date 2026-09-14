<!--
  Anshul Jain — GitHub profile README (corrected 14 Sept 2026)
  Paste this into: github.com/anshul-jain-devx108/anshul-jain-devx108 → README.md

  WHAT CHANGED AND WHY: see ../17-github-readme-changelog.md
  ONE RULE: this file and your resume must never contradict each other.
-->

<h1 align="center">Anshul Jain</h1>
<h3 align="center">Applied AI Engineer — I take ambiguous business problems and ship agentic systems that survive production.</h3>

<p align="center">
  <a href="https://github.com/agno-agi/agno/pulls?q=author%3Aanshul-jain-devx108"><img src="https://img.shields.io/badge/Agno-contributor-2E86DE" alt="Agno contributor" /></a>
  <a href="https://linkedin.com/in/anshul-jain-2b1b0b250/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:anshul.jain.devx@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

### About

- 🏢 **Junior Software Engineer — AI / Backend @ [Celebal Technologies](https://celebaltech.com)** · Feb 2026 – Present
- 🌟 **Contributor to [Agno](https://github.com/agno-agi/agno)** — `GoogleSlidesTools` (19 tools, [#6830](https://github.com/agno-agi/agno/pull/6830)) and `YouTools` fixes ([#8906](https://github.com/agno-agi/agno/pull/8906)) merged into the core codebase
- 🧠 I build **production agentic systems**: multi-agent orchestration, RAG, document intelligence, on-prem LLM deployment
- 🏗️ End-to-end ownership — problem discovery → architecture (HLD/LLD) → LLM integration → cloud deployment → handover
- ☁️ **AWS Bedrock** · **Azure OpenAI / AI Foundry** · **GCP Vertex AI** · Python · FastAPI · Agno
- 📫 **anshul.jain.devx@gmail.com** — open to Applied AI / Forward Deployed Engineer roles, remote or relocation

---
i
pur
### Featured work

**📧 Email Intelligence System** — *Agno AgentOS · GPT-OSS (on-prem) · OCR · WhatsApp Business API · Outlook & Gmail API*
Production email intelligence for a logistics operation running **1,000+ vehicles** under government tenders — classifies, routes and drafts replies to unstructured government audit notices scattered across state-wise inboxes. Fully **on-premise and data-sovereign**: GPT-OSS deployed on client infrastructure with a human-in-the-loop approval gate. Owned end-to-end from discovery to rollout → **30% less manual effort, $24K+ realized savings, $120K+ projected annual savings, zero data egress.**

**🌍 [Global Trade Sentinel](https://github.com/anshul-jain-devx108/global-trade-sentinel)** — *Agno AgentOS · You.com Research API · Microsoft Foundry · Supabase · Slack · Teams*
Autonomous trade-compliance monitoring across **40+ sources and jurisdictions** — a router agent plus **6 specialist agents** surface only the regulations that touch a company's HS codes, suppliers and target markets. Parallel specialist execution, scheduled sweeps, persistent sessions and memory, and a human-in-the-loop gate on expensive deep-research calls. Every finding carries primary-source citations.

**🤖 Enterprise Multi-Agent AI Chatbot** — *AWS Bedrock · Agno · FastAPI · Milvus*
One natural-language interface over heterogeneous enterprise data. A leader agent decomposes and routes queries to specialists for **NL2SQL** over SQL/Parquet, S3 document retrieval and semantic **RAG**, with vector-based schema discovery narrowing tables before query generation. Custom **tool-output compression** cut token cost and latency **30%**.

---

### Open Source — [Agno](https://github.com/agno-agi/agno)

| PR | What |
|---|---|
| ✅ [**#6830**](https://github.com/agno-agi/agno/pull/6830) | **`GoogleSlidesTools`** — 19 production-grade tools wrapping the Google Slides API (presentation lifecycle, slide manipulation, content generation, batch ops), with dual **OAuth 2.0 / service-account** auth. Completes Agno's Google Workspace coverage alongside Sheets, Docs, Drive, Calendar and Gmail. |
| ✅ [**#8906**](https://github.com/agno-agi/agno/pull/8906) | **`YouTools` fixes** — exposed missing search parameters, corrected `LiveCrawl` enum handling and array serialization, added configurable crawl timeouts to eliminate gateway timeouts. With tests. |
| 🔄 [**#8930**](https://github.com/agno-agi/agno/issues/8930) | **`YouTools` expansion** to You.com's Research, Contents and Finance APIs — proposed and built. Refactored a flat module into a package with shared auth and backwards-compatible re-exports; submitted as three separately reviewable PRs: [#8958](https://github.com/agno-agi/agno/pull/8958), [#9020](https://github.com/agno-agi/agno/pull/9020), [#9031](https://github.com/agno-agi/agno/pull/9031). |

---

### Core Skills

**Languages & Backend** — Python, SQL, FastAPI, async/asyncio, Pydantic, REST API design, pytest
**AI & Agentic** — Agno, agentic workflows, multi-agent orchestration, RAG, prompt & context engineering, structured outputs, LLM evals & guardrails, knowledge graphs, Hugging Face
**AI Protocols** — MCP (Model Context Protocol), A2A (Agent-to-Agent)
**Observability & Evals** — Langfuse (tracing, evaluations), AWS Bedrock Guardrails, structured logging
**Cloud** — AWS (Bedrock, Lambda, S3, Textract, API Gateway) · Azure (OpenAI, AI Foundry, Document Intelligence, Functions, Blob, SQL) · GCP (Vertex AI, Cloud Run)
**Data & Vector Stores** — PostgreSQL, Milvus, MongoDB, Supabase, Azure SQL, ChromaDB
**Tools & DevOps** — Git, Docker, Linux, Azure DevOps, CI/CD, Postman

*Also worked with:* C/C++, JavaScript, Node.js, Express.js, React

---

### Work Experience

**🏢 Celebal Technologies — Junior Software Engineer, AI / Backend** · *Feb 2026 – Present · India*

- Architected and shipped an internal **AI Control Plane** on **Azure** — a multi-agent system with specialized agents for document processing, outbound communication and email monitoring, built on **Azure OpenAI**, **Azure Document Intelligence** and **Agno** stateful workflows to classify, extract and route work automatically. **40% less manual review effort.**
- Built **AI-powered procurement automation** — purchase-order processing, goods-receipt automation, PO validation and supplier correspondence, using agentic workflows to extract, validate, reconcile and route procurement data across business processes.
- Built a **resume shortlisting engine** on **Microsoft Foundry** embedding models, scoring candidates against JD requirements end-to-end from upload to scored report.
- Architected the platform's **cloud-native backend** on **Azure AI Foundry**, **Blob Storage** and **Azure SQL** for high-volume document processing and parallel agent execution; serverless execution via **Azure Functions**, secured with **OAuth 2.0 / Microsoft Identity Platform** and SSO, shipped through **Azure DevOps** CI/CD.

**🧠 Innoflexion — AI Engineer (Contract)** · *Jun 2025 – Dec 2025 · Remote*

- Architected an **enterprise multi-agent AI chatbot** on **AWS Bedrock** (Claude) using agentic **RAG**, MCP-style tool calling and context engineering across structured (Parquet, SQL), semi-structured (S3) and unstructured (PDF) sources — **cutting token cost and query latency 30% each.**
- Deployed an **enterprise deep-research and insight synthesis system** on **GCP Vertex AI + Cloud Run** — **Agno** multi-agent orchestration with **knowledge-graph**-backed retrieval, a coordinator agent decomposing objectives and retrieval sub-agents gathering context in parallel. **65% less manual research effort, 45% lower insight latency.**
- Built an **agentic document analysis and OCR pipeline** on **AWS Textract** + **Lambda**, with prompt normalisation and temperature calibration for reliable extraction from no-fixed-format documents.
- Integrated an **AI Gateway** for rate limiting, model routing and fallback; wired **LLM observability** through **Langfuse** (**40% faster debugging**) and enforced **AWS Bedrock Guardrails** against prompt injection and out-of-scope queries.
- Shipped every service as a **Dockerized FastAPI** microservice behind **AWS API Gateway** and **GCP Cloud Run** with auto-scaling.
- Owned **client-facing delivery** across **3 time zones** — requirements → shipped production systems, technical discussions, product demos, and GTM support for AI offerings.

---

### Achievements

- 🥇 **Smart India Hackathon 2024** — National Finalist
- 🥈 **Rajasthan Police Hackathon** — Finalist
- 🚀 **Informatica AI/GenAI Hackathon 2025** — advanced to Prototype Development phase

---

### Education

**Poornima University, Jaipur** · *2022 – 2026*
B.Tech, Computer Science and Engineering

---

<p align="center">
  <a href="https://linkedin.com/in/anshul-jain-2b1b0b250/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:anshul.jain.devx@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white" alt="Email" /></a>
</p>
