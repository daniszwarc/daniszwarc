# Dani Szwarc
**AI Automation Engineer · Enterprise Developer · MSc Artificial Intelligence**

---

I've spent 20+ years building enterprise software across manufacturing, community sports, and healthcare — the kind of environments where reliability isn't optional and technical debt has real consequences. Over the last few years I've shifted my focus to AI systems, not because it's trendy, but because it's where the genuinely hard and interesting problems are right now.

I build things that replace real work. That means production pipelines, not prototypes — systems where an LLM is a component in a larger architecture, not the whole story.

I'm currently finishing an MSc in Artificial Intelligence at the University of Liverpool. My capstone, WorkflowSynth, investigates whether LLMs can automatically discover and synthesize enterprise AI workflows from natural language business requirements — a problem I care about because I've lived the manual version of it.

---

## What I work on

Most of my recent work sits at the intersection of document intelligence, RAG pipelines, and agentic automation. I use LangChain and LangGraph for orchestration, pgvector and Pinecone for vector search, and the Claude and OpenAI APIs for the model layer. On the automation side, I run self-hosted n8n for workflow orchestration and integration work.

A recurring theme across all of it: AI systems that behave predictably under real operating conditions — governed content, not model guesses; RBAC and audit logging baked in from the start; failure modes that are planned for, not discovered in production.

---

## Stack

| Layer | Tools |
|---|---|
| LLM / AI | Claude API, OpenAI, LangChain, LangGraph |
| Vector / RAG | pgvector, Pinecone, semantic chunking, embedding pipelines |
| Automation | n8n (self-hosted), workflow orchestration |
| Backend | Python, FastAPI, Node.js, REST APIs |
| Frontend | Next.js, React, TypeScript |
| Data | PostgreSQL, MySQL, Snowflake (familiar) |
| DevOps | Docker, Traefik, GitHub Actions, self-managed VPS |
| Integrations | Gmail API, Drupal REST, Google Drive, SharePoint, Webhooks |

---

## Selected Projects

**[WorkflowSynth](https://github.com/daniszwarc/workflowsynth)** — MSc capstone research on automated AI workflow discovery via LLM-guided programme synthesis. LangGraph-based synthesis engine with a verify-then-repair loop and formal DSL validation. Output targets: n8n JSON and LangChain Python.

**BeyondTheProtocol** — Private clinical AI platform built for a single patient managing a complex, ongoing medical case. RAG assistant grounded in governed documents, RBAC, audit log, bilingual EN/ES support, and self-managed VPS deployment. Not open source, but the architecture problems are real: hallucination prevention, PII handling, traceability.

**[APiWiki](https://wiki.daniszwarc.cloud)** — SOX-compliant internal AI knowledge base for a Fortune 500 client. RAG-powered, on-premises LLM inference, injection-defended chat interface, RBAC, and a full audit log UI. Built to surface answers from approved content while keeping all data within the client's control boundary.

**[AlterEco Publishing Pipeline](https://github.com/daniszwarc/altereco-pipeline)** — End-to-end publishing automation for Alternativas Económicas magazine. PDF articles go in, structured Drupal content comes out. Reduced processing time from 30 minutes to 2-3 minutes per article using Claude Vision API for layout-aware extraction.

**[Soccer Verdun AI Support](https://github.com/daniszwarc/soccer-verdun-ai)** — Multi-tool AI agent for a Montreal soccer organization. Handles multilingual customer support (FR/EN) using Pinecone RAG, Gmail ingestion, and seasonal business logic. Human review stays in the loop for edge cases.

---

## Background

My enterprise years gave me something most AI engineers are still learning: what production actually means. I've debugged systems at 2am, inherited codebases with no documentation, and shipped things that had to work on the first try. That context shapes how I approach AI architecture — skeptically, with an eye on failure modes.

I'm based in Montreal. I work in English and Spanish and a bit of French.

---

*MSc Artificial Intelligence, University of Liverpool (in progress)*
