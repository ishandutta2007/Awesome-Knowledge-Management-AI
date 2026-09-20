# Awesome-Knowledge-Management-AI

Top Knowledge Management AI Tools Ecosystem

Curated List of SaaS Products & Open-Source GitHub Projects
Focused on AI-Powered Search, Enterprise RAG, Knowledge Graph & Intelligent Documentation
Last updated: September 2026

This repository tracks notable SaaS platforms and open-source projects for Knowledge Management AI. These tools help organizations capture, organize, and retrieve institutional knowledge using AI-powered search, retrieval-augmented generation (RAG), knowledge graphs, and intelligent assistants.

Examples include Guru, Slab, Confluence, Notion, Document360, Bloomfire, Helpjuice, Tettra, Nuclino, Stack Overflow for Teams, Glean, Notion AI, Confluence AI, and Document360 AI (the category leaders).

Open-source emphasis: This section is heavily expanded with every major active project for self-hosting, custom RAG pipelines, and transparent AI-powered knowledge retrieval — ideal for teams that want full control over sensitive internal documentation and AI workflows without per-seat SaaS fees.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

Table of Contents

SaaS/Hosted Platforms

Open-Source GitHub Projects

How to Contribute

Disclaimer

SaaS/Hosted Platforms

Glean
AI-powered enterprise search and work assistant. Indexes 100+ applications with permission-aware retrieval, builds an Enterprise Knowledge Graph connecting people, content, and activity, and provides AI agents for cross-application workflows. Requires a ~100-seat minimum with quote-based pricing -
1
-
2
-
10
.

Notion AI
AI assistant integrated into the Notion workspace. Now bundled into the Business plan, providing writing assistance, Q&A across workspace content, enterprise search, AI meeting notes, and AI agents that handle multi-step tasks -
1
-
3
-
18
.

Confluence + Rovo
Atlassian's AI engine bundled into paid Confluence Cloud plans. Provides AI search across the org's knowledge graph, chat, agents, and "Remix" capabilities that transform content into charts, infographics, and presentations. Partner agents connect to Lovable, Replit, and Gamma via MCP -
1
-
4
-
12
.

Document360 AI (Eddy AI)
Knowledge base platform with AI-assisted article generation, SEO metadata, intelligent search, and AI chatbot. The Knowledge Pulse module uses Eddy AI for duplicate content detection and conversion of repeated content into reusable snippets -
5
-
13
.

Guru
AI-powered knowledge management that surfaces verified answers directly in Slack, browser, and other tools. Verification workflows ensure accuracy, with AI search across cards and collections.

Slab
Modern knowledge base with AI-powered unified search across connected tools. Focuses on streamlined internal documentation with verification workflows.

Bloomfire
Knowledge engagement platform with AI-powered search, community Q&A, and content verification. Focused on enterprise knowledge sharing and employee onboarding.

Helpjuice
Knowledge base software with AI-powered search, rich text editor, version control, and multi-language support. Known for ease of use and responsive support.

Tettra
Lightweight internal knowledge base with AI capabilities. Integrates with Slack and Teams to capture tribal knowledge and turn conversations into documentation.

Nuclino
Collaborative wiki with AI features. Combines docs, real-time editing, and a visual graph view for connected knowledge.

Stack Overflow for Teams
Private Q&A platform evolving into Stack Internal with AI-powered knowledge ingestion from tools like Teams and Confluence, MCP server for AI integration, and human-verified content workflows.

Open-Source GitHub Projects

PipesHub
Fully extensible AI context layer that unifies business data for explainable enterprise search and agentic workflow automation. Features 87+ connectors (Slack, GitHub, Notion, Salesforce, Jira, IoT platforms), hybrid semantic + keyword search, RAG pipeline with citations, MCP server, and permission-aware indexing. Tech stack: Neo4j/ArangoDB, Qdrant/OpenSearch, MongoDB, FastAPI, LangChain. Self-hostable via Docker Compose. License: Open source -
6
.

OpenBeam
Open-source Glean alternative positioning itself as the only platform bridging SaaS tools and physical operations data (IoT sensors, industrial protocols, camera feeds) in one searchable layer. 87 connectors including digital (Slack, GitHub, Notion, Linear, Salesforce, Jira, Gmail), IoT (Samsara, Verkada, AWS IoT), and industrial protocols (MQTT, OPC-UA, BACnet). Features hybrid search (sub-200ms p99), AI agents with 100+ composable tools, six autonomous agents on Temporal cron schedules, MCP server, and permission-aware indexing. Self-hostable via Docker Compose. License: AGPL -
14
.

Xyne
AI-first search and answer engine for work. Open-source alternative to Glean, Gemini, and MS Copilot. Connects to Google Workspace, Atlassian suite, Slack, GitHub, and more. Securely indexes data, maps a graph of relationships, and provides Google + ChatGPT-like experience for finding anything across applications. Docker image available. License: Open source -
7
.

Kherad
Self-hosted, git-backed knowledge base with a Notion-like block editor. Every save is a real git commit with merge-request review workflow. Features RAG chat over docs with cited sources, AI specialist agents that draft wiki pages, document/voice ingest (PDF, Office, OCR, speech-to-text), link graph, and permission-aware full-text search. Built with TypeScript (Fastify, Next.js), PostgreSQL, Drizzle ORM. Docker Compose deployment. License: Open source -
8
.

Petrichor
Self-hosted knowledge platform for humans and AI agents. Turns Markdown into wikis, evidence, and agent-ready knowledge. Features Agentic RAG with BM25/Vector/Wiki fusion, semantic Wiki extraction with entity and concept mapping, multi-article aggregation with source citations, Agent Runtime with ReAct tool loops and sub-agents, MCP support, and export to OKF/Obsidian/Agent Skill packages. Tech stack: Go + Gin, PostgreSQL, Redis, S3, Caddy. Docker Compose deployment. License: Open source -
15
.

Additional Strong Open-Source Options

RAG Frameworks: LangChain (multi-provider LLM orchestration), LlamaIndex (data framework for LLM applications), Haystack (NLP framework for semantic search and QA).

Vector Databases: Qdrant, Weaviate, Milvus, pgvector (PostgreSQL extension for vector similarity search).

Knowledge Graphs: Neo4j (graph database for relationship mapping), ArangoDB (multi-model database), Apache AGE (graph extension for PostgreSQL).

Wiki & Documentation: Outline (collaborative knowledge base with AI search), Docmost (Confluence/Notion alternative with real-time collaboration), BookStack (structured documentation platform), AppFlowy (open-source Notion alternative with AI integration).

Enterprise Search: Typesense (fast typo-tolerant search), Meilisearch (lightning-fast search engine), OpenSearch (distributed search and analytics).

Frameworks for building custom systems: Combine PipesHub or OpenBeam for the AI context layer, Neo4j for knowledge graph, Qdrant for vector search, LangChain for RAG orchestration, and Ollama for self-hosted LLM inference. Add Kherad or Outline for the wiki frontend.

How to Contribute

Fork the repo.

Add/edit entries in README.md (follow existing format).

Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

Submit PR with a short explanation.

Star the repo if you find it useful!

Disclaimer

This is a community-curated list — not exhaustive and not an endorsement.

Knowledge management AI tools handle sensitive internal documentation; ensure proper access controls, permission-aware indexing, and AI governance policies.

Self-hosted open-source solutions require proper security hardening, model management, and regular audits.

Made for knowledge managers, platform engineers, AI practitioners, and enterprise architects.
Let's make knowledge management AI more open, transparent, and context-aware.
