# code-understanding-top-stars

[中文](./README.md) | **English**

> Curated Code Understanding Tools — Architecture Mapping · API Extraction · CLI Conversion · Module Decomposition  
> Source: wind8ai Stars Lists  
> Fetched: 2026-06-04  

---

## Contents

01. [graphify — 64.5k ⭐](#1-graphify-645k-)
02. [context7 — 57.1k ⭐](#2-context7-571k-)
03. [Understand-Anything — 56.3k ⭐](#3-understand-anything-563k-)
04. [codegraph — 46.4k ⭐](#4-codegraph-464k-)
05. [CLI-Anything — 42.6k ⭐](#5-cli-anything-426k-)
06. [GitNexus — 41.9k ⭐](#6-gitnexus-419k-)
07. [swagger-ui — 28.8k ⭐](#7-swagger-ui-288k-)
08. [python-fire — 28.2k ⭐](#8-python-fire-282k-)
09. [openapi-generator — 26.4k ⭐](#9-openapi-generator-264k-)
10. [tree-sitter — 25.8k ⭐](#10-tree-sitter-258k-)
11. [code-review-graph — 18.3k ⭐](#11-code-review-graph-183k-)
12. [swagger-codegen — 17.8k ⭐](#12-swagger-codegen-178k-)
13. [semgrep — 15.5k ⭐](#13-semgrep-155k-)
14. [codeql — 9.7k ⭐](#14-codeql-97k-)
15. [oclif — 9.5k ⭐](#15-oclif-95k-)
16. [open-code-review — 6.0k ⭐](#16-open-code-review-60k-)
17. [semble — 5.0k ⭐](#17-semble-50k-)
18. [OpenDeepWiki — 3.3k ⭐](#18-opendeepwiki-33k-)
19. [joern — 3.2k ⭐](#19-joern-32k-)
20. [smart-doc — 1.6k ⭐](#20-smart-doc-16k-)
21. [redocly-cli — 1.5k ⭐](#21-redocly-cli-15k-)
22. [CodeWiki — 1.2k ⭐](#22-codewiki-12k-)
23. [deepwiki-rs — 1.0k ⭐](#23-deepwiki-rs-10k-)

---

## 1. graphify (64.5k ⭐)

**🔗** https://github.com/safishamsi/graphify  
**🍴** Forks 6.2k | **🔄** Updated Jun 3, 2026  
**👤** Safi (safishamsi) — London-based AI engineer, MSc Data Science (Distinction) from University of Birmingham, focused on healthcare AI and knowledge graphs

> AI coding assistant skill that maps an entire project — code, docs, PDFs, images, videos — into a queryable knowledge graph by running `/graphify .` in your AI agent. Produces three outputs: `graph.html` (interactive node diagram), `GRAPH_REPORT.md` (key concepts & relationship analysis), and `graph.json` (full graph data). Can also generate architecture pages with Mermaid call flow diagrams via `graphify export callflow-html`. Supports 15+ mainstream agent tools including Claude Code, Codex, OpenCode, Cursor, Gemini CLI, GitHub Copilot CLI, Aider, and OpenClaw. PyPI package `graphifyy`, install via `uv tool install graphifyy`.

**Matched Capabilities:** 📊 Code Graph · 🏗️ Architecture Mapping · 🔍 Call Flow Analysis · 📝 Auto Report

---

## 2. context7 (57.1k ⭐)

**🔗** https://github.com/upstash/context7  
**🍴** Forks 2.7k | **🔄** Updated Jun 3, 2026  
**👤** Upstash — Serverless Data Platform company providing Redis/vector database/message queue cloud services

> Provides up-to-date code documentation context for LLMs and AI code editors. Solves the code hallucination problem caused by outdated LLM training data — no more generating obsolete APIs and deprecated usage patterns. Integrates via MCP server into AI editors like Cursor, Claude Code, and Windsurf. Adding `use context7` to prompts automatically pulls the latest documentation and code examples for target libraries, injecting them into LLM context. Supports real-time documentation indexing for thousands of open-source libraries.

**Matched Capabilities:** 📝 Real-time Documentation Context · 🤖 MCP/Agent Integration · 🔍 Code Hallucination Elimination

---

## 3. Understand-Anything (56.3k ⭐)

**🔗** https://github.com/Lum1104/Understand-Anything  
**🍴** Forks 4.2k | **🔄** Updated Jun 4, 2026  
**👤** Lum1104 — interactive code knowledge graph developer, focused on making code "seen, not impressed"

> Claude Code plugin that analyzes entire projects through a multi-agent pipeline, building a knowledge graph of every file, function, class, and dependency, then provides an interactive visual dashboard to explore it all. Supports Claude Code, Codex, Cursor, Copilot, Gemini CLI, and other mainstream platforms. Core capabilities: structural graph exploration (color-coded by architecture layer), business logic domain view (domains → flows → steps), guided tours (learn codebase in dependency order), semantic search ("which parts handle auth?"), diff impact analysis (change ripple effects), persona-adaptive UI (adjusts detail density by role). Also supports knowledge base analysis (Karpathy-pattern LLM wiki) and multi-language output (Chinese/Japanese/Korean/Spanish/Turkish/Russian). Incremental updates (only re-analyzes changed files), graph is JSON and can be committed/shared, large graphs support git-lfs.

**Matched Capabilities:** 📊 Code Graph · 🏗️ Architecture Mapping · 🔍 Semantic Search · 🎭 Multi-Role UI · 🌐 Multi-Language

---

## 4. codegraph (46.4k ⭐)

**🔗** https://github.com/colbymchenry/codegraph  
**🍴** Forks 2.5k | **🔄** Updated Jun 4, 2026  
**👤** Colby McHenry — independent developer with 15+ years of software development experience

> Pre-indexed code knowledge graph providing precise context for AI agents. Runs 100% locally — no servers, no API keys. Supports Claude Code, Codex, Gemini CLI, Cursor, OpenCode, AntiGravity, Kiro, Hermes Agent, and other mainstream platforms. Reduces token consumption and tool calls through pre-built indexing, enabling AI to understand codebase structure more efficiently.

**Matched Capabilities:** 📊 Code Knowledge Graph · ⚡ Token Optimization · 🤖 Multi-Agent Platform Support · 🔒 Local-First

---

## 5. CLI-Anything (42.6k ⭐)

**🔗** https://github.com/HKUDS/CLI-Anything  
**🍴** Forks 4.0k | **🔄** Updated Jun 3, 2026  
**👤** HKUDS (Hong Kong University Data Science Lab) — academic + open-source team

> "Today's software serves humans 👨‍💻, tomorrow's users will be agents 🤖" — bridging the gap between AI agents and the world's software. Generates agent-ready CLI interfaces for any software with a single command, enabling tools like Pi, OpenClaw, Cursor, and Claude Code to directly control various applications. Built-in CLI-Hub community registry (`pip install cli-anything-hub`) for browsing, installing, and managing community-built CLI wrappers. Supports preview, live preview, and trajectory loops, allowing agents to produce real artifacts: CAD models, 3D scenes, diagrams, game footage, subtitles, and more. Dozens of software CLI wrappers already available including QGIS (GIS), Obsidian, Safari, FreeCAD, Kdenlive, and Unreal Insights.

**Matched Capabilities:** 🔌 Software→CLI Conversion · 🤖 Agent-Native · 📦 Community Ecosystem

---

## 6. GitNexus (41.9k ⭐)

**🔗** https://github.com/abhigyanpatwari/GitNexus  
**🍴** Forks 4.7k | **🔄** Updated Jun 4, 2026  
**👤** Abhigyan Patwari (Akon Labs) — code intelligence engine developer

> Builds a "code nervous system" for agent context. Indexes any codebase into a knowledge graph — covering every dependency, call chain, cluster, and execution flow — then exposes it through smart tools so AI agents never miss code. Two modes: **CLI + MCP** (`npm install -g gitnexus`, local repo indexing, connects to Cursor/Claude Code/Codex/Windsurf/OpenCode via MCP server, using LadybugDB persistent storage and native Tree-sitter parsing) and **Web UI** (browser-based visual graph explorer + AI chat). Bridge mode connects both. Claims "Like DeepWiki, but deeper" — DeepWiki helps you understand code, GitNexus lets you analyze it, because the knowledge graph tracks every relationship, not just descriptions. Enterprise edition offers PR blast radius analysis, automatic code wiki updates, and multi-repo unified graphs.

**Matched Capabilities:** 🏗️ Architecture Mapping · 📊 Module Decomposition · 🔍 Code Graph · 🤖 MCP/Agent Integration

---

## 7. swagger-ui (28.8k ⭐)

**🔗** https://github.com/swagger-api/swagger-ui  
**🍴** Forks 9.3k | **🔄** Updated Jun 2, 2026  
**👤** SmartBear / Swagger team — API toolchain industry standard setter

> Automatically generates interactive API documentation interfaces from Swagger/OpenAPI specifications. Provides online "Try it out" API trial calls, request/response model viewing, parameter descriptions, and more. The de facto standard for API documentation visualization, essential for almost every RESTful project.

**Matched Capabilities:** 📝 API Documentation Visualization · 🖥️ Interactive API Debugging

---

## 8. google/python-fire (28.2k ⭐)

**🔗** https://github.com/google/python-fire  
**🍴** Forks 1.5k | **🔄** Updated Apr 1, 2026  
**👤** Google — Python Fire is Google's open-source CLI generation library

> Automatically generates command-line interfaces from any Python object. No decorators, parameter definitions, or configuration files needed — directly converts functions, classes, modules, dictionaries, and even object instances into fully functional CLIs, including subcommands, parameter inference, and help documentation. The fastest path from code to CLI.

**Matched Capabilities:** 🔌 Code→CLI Conversion · ⚡ Rapid Prototyping

---

## 9. openapi-generator (26.4k ⭐)

**🔗** https://github.com/OpenAPITools/openapi-generator  
**🍴** Forks 7.5k | **🔄** Updated Jun 4, 2026  
**👤** OpenAPI Tools Community — OpenAPI ecosystem core project

> Given an OpenAPI Spec (v2/v3), automatically generates API client SDKs, server stubs, documentation, and configurations. Supports 50+ programming languages/frameworks, covering Java/Python/TypeScript/Go/Ruby/C#/Rust and other mainstream languages. The industrial-grade standard tool for API spec-driven development and the top choice for generating CLI clients from OpenAPI specs.

**Matched Capabilities:** 📝 API Doc Generation · 🔌 SDK/CLI Generation · 📐 Spec Validation

---

## 10. tree-sitter (25.8k ⭐)

**🔗** https://github.com/tree-sitter/tree-sitter  
**🍴** Forks 2.7k | **🔄** Updated Jun 3, 2026  
**👤** Tree-sitter Community — created by Max Brunsfeld (former GitHub Atom team), now an independent open-source project

> Incremental parser generator and parsing library — the foundational cornerstone for nearly all modern code analysis tools. Builds concrete syntax trees (CST) for source files and efficiently incrementally updates them as files are edited. Design goals: universal (can parse any programming language, 200+ language grammars available), extremely fast (parses on every keystroke), robust (still produces useful results even with syntax errors), zero-dependency (pure C runtime, embeddable in any application). Provides Rust/Wasm/Node/Python and other language bindings plus CLI tools. Higher-level tools like GitNexus, graphify, Aider, and Codebase-Memory all rely on tree-sitter for underlying parsing. The preferred infrastructure for building custom code understanding pipelines.

**Matched Capabilities:** 🧱 Foundational Parsing · 📊 AST/CST Construction · 🔍 200+ Language Support · ⚡ Incremental Parsing

---

## 11. code-review-graph (18.3k ⭐)

**🔗** https://github.com/tirth8205/code-review-graph  
**🍴** Forks 1.9k | **🔄** Updated May 25, 2026  
**👤** Tirth Patel — developer in code graph and token optimization

> Stop burning tokens, start reviewing smartly. Builds a local code knowledge graph for AI coding tools — parses repos into ASTs using Tree-sitter, stores as nodes (functions/classes/imports) and edges (calls/inheritance/test coverage), provides precise context to AI assistants via MCP protocol so they only read truly relevant code. Core capability: **blast radius analysis** — when files change, traces every caller, dependent, and related test so the AI reads only those files instead of scanning the entire project. Incremental updates are extremely fast (<2 seconds for a 2900-file project); in large monorepos, 27,700+ files are excluded from review context, reading only ~15 files. Saves 6.8× tokens in code review and up to 49× in daily coding tasks. Supports Claude Code/Codex/Cursor/Gemini CLI/Kiro/GitHub Copilot platforms, auto-detecting and configuring all supported AI tools with one command.

**Matched Capabilities:** 📊 Code Knowledge Graph · 🔍 Change Impact Analysis · ⚡ Token Optimization · 🤖 MCP/Multi-Platform Integration

---

## 12. swagger-codegen (17.8k ⭐)

**🔗** https://github.com/swagger-api/swagger-codegen  
**🍴** Forks 6.0k | **🔄** Updated May 19, 2026  
**👤** SmartBear / Swagger team

> Template-driven code generation engine that parses OpenAPI/Swagger definitions to automatically generate documentation, API clients, and server stubs. Multi-language and multi-framework support. The predecessor to openapi-generator. The two have highly overlapping functionality; new projects are recommended to prioritize openapi-generator.

**Matched Capabilities:** 📝 API Documentation · 🔌 Code Generation

---

## 13. semgrep (15.5k ⭐)

**🔗** https://github.com/semgrep/semgrep  
**🍴** Forks 955 | **🔄** Updated Jun 4, 2026  
**👤** Semgrep Inc. (formerly r2c / Return To Corp) — code security analysis company

> Semantic grep for code. Finds bug variants using **patterns that look like source code** — no ASTs, regular expressions, or complex DSLs needed. Supports 30+ languages (Apex/Bash/C/C++/C#/Go/Java/JavaScript/Kotlin/Python/Ruby/Rust/Swift/TypeScript, etc.). While `grep "2"` only matches the string "2", Semgrep can match semantically equivalent "2" in `x=1; y=x+1`. Custom rules can batch-extract API call patterns, route definitions, and security vulnerabilities from code. The open-source version is limited to single-function/file analysis; the enterprise edition supports cross-file and cross-function data flow analysis.

**Matched Capabilities:** 🔍 Code Pattern Matching · 📊 Batch API Call Extraction · 🛡️ Security Analysis

---

## 14. codeql (9.7k ⭐)

**🔗** https://github.com/github/codeql  
**🍴** Forks 2.0k | **🔄** Updated Jun 3, 2026  
**👤** GitHub — the official analysis engine from the world's largest code hosting platform

> Code query language and analysis platform powering GitHub Advanced Security's code scanning feature. Treats code as a database, using a SQL-like query language (QL) to precisely locate patterns, vulnerabilities, and structural relationships in code. Includes standard libraries and thousands of pre-built queries, supporting C/C++/C#/Go/Java/JavaScript/Python/Ruby/Swift. Provides VS Code extension, CLI tools, and CI/CD integration. Custom queries can extract API endpoint definitions, route tables, call chains, and other structured information. Open-source for open-source project analysis; commercial license required for private repositories.

**Matched Capabilities:** 🔍 Code Structure Query · 📊 API Endpoint Extraction · 🏗️ Call Chain Analysis

---

## 15. oclif (9.5k ⭐)

**🔗** https://github.com/oclif/oclif  
**🍴** Forks 355 | **🔄** Updated Jun 3, 2026  
**👤** Salesforce — the framework behind Heroku CLI

> Node.js CLI framework for creating, building, and publishing command-line tools. Plugin architecture supporting multi-command organization, automatic help documentation generation, native TypeScript support, and hook system. Well-known tools including Heroku CLI and Salesforce CLI are all built on oclif. Suitable for encapsulating extracted API information into standardized CLI tool products.

**Matched Capabilities:** 🔌 CLI Framework · 📦 CLI Tool Productization

---

## 16. open-code-review (6.0k ⭐)

**🔗** https://github.com/alibaba/open-code-review  
**🍴** Forks 80 | **🔄** Updated Jun 4, 2026  
**👤** Alibaba — originated from Alibaba's internal official AI code review assistant, serving tens of thousands of developers and identifying millions of code defects

> Open-source AI-powered code review CLI. Reads Git diffs, sends changed files to a configurable LLM via an agent with tool-use capabilities, and generates structured review comments with line-level precision. Core design: **deterministic engineering × agent hybrid architecture** — uses hard engineering constraints for review steps that must not go wrong (precise file selection, smart file bundling, fine-grained rule matching, external positioning and reflection modules), while the agent handles dynamic decisions (scenario-tuned prompts and toolsets). Supports workspace mode, branch comparison, and single-commit review. Integrates into Claude Code (Plugin/Skill), Codex, and other coding agents as a slash command. Supports CI/CD integration (GitHub Actions / GitLab CI), with built-in Alibaba official ruleset (NPE, thread-safety, XSS, SQL injection, etc.). Go implementation, multi-platform binaries distributed via NPM.

**Matched Capabilities:** 🔍 AI Code Review · 🏗️ Deterministic + Agent Hybrid · 📐 Rule Matching · 🤖 CI/CD Integration

---

## 17. semble (5.0k ⭐)

**🔗** https://github.com/MinishLab/semble  
**🍴** Forks 200 | **🔄** Updated Jun 3, 2026  
**👤** Minish Lab — two-person open-source lab (pringled & stephantul), focused on NLP and efficient models

> Fast and precise code search tool for agents. Reduces token consumption by approximately 98% compared to grep+read. Provides semantic code search capabilities for AI coding assistants, enabling agents to precisely locate relevant code snippets in large codebases instead of brute-force file traversal.

**Matched Capabilities:** 🔍 Semantic Code Search · ⚡ Token Optimization · 🤖 Agent Integration

---

## 18. OpenDeepWiki (3.3k ⭐)

**🔗** https://github.com/AIDotNet/OpenDeepWiki  
**🍴** Forks 421 | **🔄** Updated Jun 1, 2026  
**👤** AIDotNet — .NET AI ecosystem open-source organization

> Open-source DeepWiki version built on .NET 9 and Semantic Kernel. AI-driven code knowledge management platform: automatically analyzes code structure, understands core concepts, and generates documentation and knowledge graphs. Supports repositories from GitHub/GitLab/AtomGit/Gitee/Gitea and other platforms, converting them into knowledge bases in minutes. Automatically generates Mermaid code structure diagrams. Supports custom AI models and APIs, multiple databases (SQLite/PostgreSQL/MySQL/SqlServer), and multi-language interfaces. Provides conversational interaction for deep code understanding, MCP protocol integration (can serve as MCPServer for other AI models), SEO-friendly Next.js frontend, and data fine-tuning platform. Supports ZIP/local file uploads.

**Matched Capabilities:** 🏗️ Architecture Documentation · 📊 Module Recognition · 📝 Auto Documentation · 🤖 MCP Integration

---

## 19. joern (3.2k ⭐)

**🔗** https://github.com/joernio/joern  
**🍴** Forks 416 | **🔄** Updated Jun 3, 2026  
**👤** joern.io — pioneer in code property graphs (originated from Saarland University research)

> Open-source code analysis platform for analyzing source code, bytecode, and binary executables. Core concept is the **Code Property Graph (CPG)** — unifying ASTs, control flow graphs, and data flow graphs into a single cross-language queryable graph structure, stored in a custom graph database. Uses a Scala DSL query language to mine code. Supports C/C++/Java/JavaScript/Python/Kotlin/Binary. Aims to provide foundational tooling for vulnerability discovery and static program analysis research. Interactive REPL interface, Docker deployment support, can run in server mode.

**Matched Capabilities:** 📊 Code Property Graph · 🔍 Cross-Language Deep Analysis · 🏗️ Call Chain/Data Flow Tracking

---

## 20. smart-doc (1.6k ⭐)

**🔗** https://github.com/TongchengOpenSource/smart-doc  
**🍴** Forks 297 | **🔄** Updated Dec 4, 2025  
**👤** Tongcheng Open Source — focused on Java API documentation automation

> Java API documentation generation tool that directly generates documentation from interface source code analysis — zero annotation intrusion, just write standard Javadoc comments. Powerful return value structure auto-derivation based on source code, supporting async interfaces (Callable/Future/CompletableFuture) and JSR-303 parameter validation specs. Covers Spring MVC/Spring Boot/WebFlux/Feign/JAX-RS frameworks, plus Apache Dubbo RPC and gRPC protocols. Can export to Markdown/HTML5/Word/Asciidoctor/Postman Collection/OpenAPI 3.0/JMeter performance test scripts and other formats. Supports loading external source code (including JARs) for field comment generation, error code and data dictionary export, and debug pages with file upload/download testing.

**Matched Capabilities:** 📝 Auto API Documentation · 🔍 Source-Level Interface Extraction · 📐 OpenAPI/Postman Output

---

## 21. Redocly CLI (1.5k ⭐)

**🔗** https://github.com/Redocly/redocly-cli  
**🍴** Forks 217 | **🔄** Updated Jun 3, 2026  
**👤** Redocly — API documentation and design platform company

> CLI tool that makes OpenAPI development simple. Lint/validate against any standard, generate beautiful interactive documentation, preview API definitions, and bundle multi-file OpenAPI specs. Suitable for standardized validation and documentation rendering after API extraction.

**Matched Capabilities:** 📐 OpenAPI Validation · 📝 Documentation Generation · 🔍 Spec Linting

---

## 22. CodeWiki (1.2k ⭐)

**🔗** https://github.com/FSoft-AI4Code/CodeWiki  
**🍴** Forks 183 | **🔄** Updated May 27, 2026  
**👤** FSoft AI4Code — AI code research team under Vietnam's FPT Software

> ACL 2026 paper open-source project — holistic structured documentation generation framework for large-scale codebases. Uses dynamic programming-inspired hierarchical decomposition strategy, supporting codebases of any size (tested 86K-1.4M LOC). Recursive multi-agent system (cluster-analyzer → file-analyzer → doc-generator → validator) analyzes layer by layer: clustering → file-level analysis → documentation generation → cross-validation. Supports 8 programming languages (Python/Java/JavaScript/TypeScript/C++/C#/Go/Rust), generates cross-module interaction analysis, Mermaid architecture diagrams, and visual artifacts. Supports multiple LLM providers (OpenAI/Anthropic/AWS Bedrock/Azure), and subscription mode via Claude Code/Codex CLI (no API key required).

**Matched Capabilities:** 📝 Repository-Level Documentation · 🏗️ Architecture-Aware Analysis · 🌐 8-Language Support · 📊 Cross-Module Interaction

---

## 23. deepwiki-rs (1.0k ⭐)

**🔗** https://github.com/sopaco/deepwiki-rs  
**🍴** Forks 126 | **🔄** Updated May 16, 2026  
**👤** sopaco (姜萌) — Rust developer, focused on decentralization and automation

> Turns code into clear documentation. Generates accurate technical documentation and AI-ready context in minutes — perfectly structured for both human teams and intelligent agents. A Rust-implemented code documentation engine, lightweight and efficient.

**Matched Capabilities:** 📝 Code Documentation Generation · 🏗️ Architecture Mapping · ⚡ Rust High Performance

---

## Category Index

### 🏗️ Code Graph & Architecture Analysis
- [graphify](#1-graphify-590k-) — code/docs → queryable knowledge graph + call flow
- [Understand-Anything](#3-understand-anything-514k-) — multi-agent pipeline builds interactive knowledge graph + dashboard
- [GitNexus](#5-gitnexus-413k-) — CLI+MCP code nervous system, agent integration
- [codegraph](#6-codegraph-399k-) — pre-indexed code knowledge graph, local-first
- [tree-sitter](#10-tree-sitter-257k-) — foundational parsing, 200+ language AST/CST
- [code-review-graph](#11-code-review-graph-180k-) — local code graph, blast radius analysis
- [joern](#18-joern-32k-) — code property graph (CPG) analysis platform
- [codeql](#14-codeql-97k-) — code query language, GitHub official
- [semgrep](#13-semgrep-154k-) — semantic grep, multi-language pattern matching

### 📝 API Extraction & Documentation
- [context7](#2-context7-567k-) — real-time code documentation context for LLMs
- [smart-doc](#19-smart-doc-16k-) — Java zero-intrusion API docs, source analysis
- [OpenDeepWiki](#17-opendeepwiki-33k-) — AI-driven repo → Wiki + MCP
- [deepwiki-rs](#23-deepwiki-rs-10k-) — Rust code documentation engine
- [CodeWiki](#22-codewiki-11k-) — ACL 2026 paper, repository-level documentation
- [swagger-ui](#7-swagger-ui-288k-) — interactive API documentation standard
- [openapi-generator](#9-openapi-generator-263k-) — OpenAPI → SDK/CLI/docs
- [Redocly CLI](#20-redocly-cli-15k-) — OpenAPI lint + documentation rendering

### 🔌 CLI Conversion & Frameworks
- [CLI-Anything](#4-cli-anything-420k-) — software → agent-native CLI
- [python-fire](#8-googlepython-fire-282k-) — Python object → CLI
- [oclif](#15-oclif-95k-) — Node.js CLI framework (Heroku/Salesforce)
- [swagger-codegen](#12-swagger-codegen-178k-) — Swagger → code/CLI

### 🔍 Code Review & Search
- [open-code-review](#21-open-code-review-12k-) — Alibaba open-source AI code review, deterministic + agent hybrid
- [semble](#16-semble-48k-) — agent semantic code search, saves 98% tokens
- [code-review-graph](#11-code-review-graph-180k-) — blast radius analysis, saves 6.8-49× tokens
- [codegraph](#6-codegraph-399k-) — pre-indexed graph, reduces tool calls

---

## Candidates to Watch (Stars < 1k but Promising)

| Repository | Stars | Description |
|------------|-------|-------------|
| [OpenBMB/RepoAgent](https://github.com/OpenBMB/RepoAgent) | 980 | LLM-driven repository documentation generation |
| [archguard/archguard](https://github.com/archguard/archguard) | 668 | Architecture governance workbench, container/component/code-level analysis |
| [alexknowshtml/api2cli](https://github.com/alexknowshtml/api2cli) | 437 | API → CLI pattern library (Node+Commander) |
| [TheMorpheus407/RepoLens](https://github.com/TheMorpheus407/RepoLens) | 268 | 280 AI agents for multi-angle code auditing |
| [lucianfialho/spec2cli](https://github.com/lucianfialho/spec2cli) | 18 | OpenAPI Spec → CLI, zero code generation |
| [tangcent/apilot](https://github.com/tangcent/apilot) | 4 | Multi-language API endpoint scanning → Markdown/cURL/Postman |

---

*Data as of 2026-06-04, star counts from GitHub public pages*
---

## 候选池（Star < 1k）

| # | 项目 | 链接 | 星数 | 说明 |
|---|------|------|------|------|
| 1 | OpenBMB/RepoAgent | https://github.com/OpenBMB/RepoAgent | 983 ⭐ | 代码仓库 Agent，自动分析与代码交互 |
| 2 | archguard/archguard | https://github.com/archguard/archguard | 669 ⭐ | 架构治理平台，代码架构分析与可视化 |
| 3 | alexknowshtml/api2cli | https://github.com/alexknowshtml/api2cli | 442 ⭐ | API 转 CLI 工具 |
| 4 | TheMorpheus407/RepoLens | https://github.com/TheMorpheus407/RepoLens | 270 ⭐ | 代码仓库分析透镜 |
| 5 | lucianfialho/spec2cli | https://github.com/lucianfialho/spec2cli | 18 ⭐ | Spec 转 CLI 工具 |
| 6 | tangcent/apilot | https://github.com/tangcent/apilot | 4 ⭐ | API 导航工具 |
