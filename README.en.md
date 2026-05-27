# codebase-analysis

[中文](./README.md) | **English**

> Curated Tools for Full Codebase Analysis — Architecture · API Extraction · CLI Conversion · Module Decomposition  
> Source: wind8ai Stars Lists  
> Updated: 2026-05-27  

---

## Contents

01. [context7 — 56.2k ⭐](#1-context7-562k-)
02. [graphify — 54.7k ⭐](#2-graphify-547k-)
03. [CLI-Anything — 40.8k ⭐](#3-cli-anything-408k-)
04. [GitNexus — 40.5k ⭐](#4-gitnexus-405k-)
05. [codegraph — 29.3k ⭐](#5-codegraph-293k-)
06. [swagger-ui — 28.8k ⭐](#6-swagger-ui-288k-)
07. [google/python-fire — 28.2k ⭐](#7-googlepython-fire-282k-)
08. [openapi-generator — 26.3k ⭐](#8-openapi-generator-263k-)
09. [tree-sitter — 25.6k ⭐](#9-tree-sitter-256k-)
10. [swagger-codegen — 17.7k ⭐](#10-swagger-codegen-177k-)
11. [code-review-graph — 17.5k ⭐](#11-code-review-graph-175k-)
12. [semgrep — 15.3k ⭐](#12-semgrep-153k-)
13. [codeql — 9.6k ⭐](#13-codeql-96k-)
14. [oclif — 9.5k ⭐](#14-oclif-95k-)
15. [semble — 4.4k ⭐](#15-semble-44k-)
16. [OpenDeepWiki — 3.3k ⭐](#16-opendeepwiki-33k-)
17. [joern — 3.2k ⭐](#17-joern-32k-)
18. [smart-doc — 1.6k ⭐](#18-smart-doc-16k-)
19. [Redocly CLI — 1.5k ⭐](#19-redocly-cli-15k-)
20. [deepwiki-rs — 1k ⭐](#20-deepwiki-rs-1k-)

---

## 1. context7 (56.2k ⭐)

**🔗** https://github.com/upstash/context7  
**🍴** Fork 2.7k | **🔄** Updated May 25, 2026  
**👤** Upstash — Serverless Data Platform, offering Redis, Vector DB, QStash and more

> Up-to-date code documentation context platform for LLMs and AI code editors. Solves the hallucination problem caused by outdated LLM training data — no more deprecated APIs and obsolete patterns. Integrates via MCP server into Cursor, Claude Code, Windsurf, and other AI editors. Add `use context7` to your prompt and it automatically pulls the latest docs and code examples for any library, injecting them into LLM context. Indexes real-time documentation for thousands of open-source libraries.

**Capabilities:** 📝 Real-time Doc Context · 🤖 MCP/Agent Integration · 🔍 Hallucination Prevention

---

## 2. graphify (54.7k ⭐)

**🔗** https://github.com/safishamsi/graphify  
**🍴** Fork 5.8k | **🔄** Updated May 27, 2026  
**👤** Safi (safishamsi) — London AI Engineer, Birmingham MSc Data Science (Distinction)

> AI coding assistant skill. Type `/graphify .` in your AI agent and it maps your entire project — code, docs, PDFs, images, videos — into a queryable knowledge graph. Outputs three files: `graph.html` (interactive node visualization), `GRAPH_REPORT.md` (key concepts & surprising connections), and `graph.json` (full graph data for re-querying without re-reading files). Also supports `graphify export callflow-html` for readable architecture pages with Mermaid call-flow diagrams. Works in Claude Code, Codex, OpenCode, Cursor, Gemini CLI, GitHub Copilot CLI, Aider, OpenClaw, and 15+ agents. PyPI package: `graphifyy`, install via `uv tool install graphifyy`.

**Capabilities:** 📊 Code Graph · 🏗️ Architecture · 🔍 Call-flow Analysis · 📝 Auto Reports

---

## 3. CLI-Anything (40.8k ⭐)

**🔗** https://github.com/HKUDS/CLI-Anything  
**🍴** Fork 3.9k | **🔄** Updated May 23, 2026  
**👤** HKUDS (HKU Data Science Lab) — Academic + Open-source Team

> "Today's Software Serves Humans👨‍💻. Tomorrow's Users will be Agents🤖." Bridges the gap between AI agents and the world's software. One command line generates agent-ready CLI interfaces for any software, enabling Pi, OpenClaw, Cursor, Claude Code, and more to directly control applications. Built-in CLI-Hub community registry (`pip install cli-anything-hub`) for browsing, installing, and managing community-built CLI wrappers. Supports preview, live preview, and trajectory loops for agents to produce real artifacts: CAD builds, 3D scenes, diagrams, gameplay, subtitles, and more.

**Capabilities:** 🔌 Software→CLI Conversion · 🤖 Agent-Native · 📦 Community Ecosystem

---

## 4. GitNexus (40.5k ⭐)

**🔗** https://github.com/abhigyanpatwari/GitNexus  
**🍴** Fork 4.6k | **🔄** Updated May 27, 2026  
**👤** Abhigyan Patwari (Akon Labs)

> Building nervous system for agent context. Indexes any codebase into a knowledge graph — every dependency, call chain, cluster, and execution flow — then exposes it through smart tools so AI agents never miss code. Two modes: **CLI + MCP** (`npm install -g gitnexus`, indexes repos locally, connects AI agents via MCP server, uses LadybugDB for persistent storage and native Tree-sitter parsing) and **Web UI** (visual graph explorer + AI chat in browser). Bridge mode connects both. Self-described as "Like DeepWiki, but deeper" — DeepWiki helps you understand code, GitNexus lets you analyze it. Enterprise edition supports PR blast radius analysis, auto-updating Code Wiki, and multi-repo unified graphs.

**Capabilities:** 🏗️ Architecture · 📊 Module Decomposition · 🔍 Code Graph · 🤖 MCP/Agent Integration

---

## 5. codegraph (29.3k ⭐)

**🔗** https://github.com/colbymchenry/codegraph  
**🍴** Fork 1.7k | **🔄** Updated May 27, 2026  
**👤** Colby McHenry — Independent developer with 15+ years of software experience

> Pre-indexed code knowledge graph for AI agents — fewer tokens, fewer tool calls, 100% local. No server, no API key required. Supports Claude Code, Codex, Gemini CLI, Cursor, OpenCode, AntiGravity, Kiro, Hermes Agent, and more. Builds a persistent index of your codebase to provide precise context, reducing token consumption and enabling AI to understand code structure more efficiently.

**Capabilities:** 📊 Code Knowledge Graph · ⚡ Token Optimization · 🤖 Multi-Agent Support · 🔒 Local-first

---

## 6. swagger-ui (28.8k ⭐)

**🔗** https://github.com/swagger-api/swagger-ui  
**🍴** Fork 9.3k | **🔄** Updated May 2026  
**👤** SmartBear / Swagger Team — API Toolchain Industry Standard

> Dynamically generates beautiful interactive API documentation from Swagger/OpenAPI specs. Provides "Try it out" live API testing, request/response model viewing, and parameter documentation. The de facto standard for API documentation visualization, used across virtually all RESTful projects.

**Capabilities:** 📝 API Documentation · 🖥️ Interactive API Debugging

---

## 7. google/python-fire (28.2k ⭐)

**🔗** https://github.com/google/python-fire  
**🍴** Fork 1.5k | **🔄** Updated Apr 2026  
**👤** Google

> Automatically generates CLI interfaces from absolutely any Python object. No decorators, argument definitions, or config files needed — directly converts functions, classes, modules, dicts, even object instances into fully usable CLIs with subcommands, argument inference, and help docs. The fastest path from code to CLI.

**Capabilities:** 🔌 Code→CLI Conversion · ⚡ Rapid Prototyping

---

## 8. openapi-generator (26.3k ⭐)

**🔗** https://github.com/OpenAPITools/openapi-generator  
**🍴** Fork 7.5k | **🔄** Updated May 2026  
**👤** OpenAPI Tools Community

> Given an OpenAPI Spec (v2/v3), automatically generates API client SDKs, server stubs, documentation, and configuration. Supports 50+ languages/frameworks including Java/Python/TypeScript/Go/Ruby/C#/Rust. The industrial-grade standard for spec-driven development and the go-to solution for generating CLI clients from OpenAPI specs.

**Capabilities:** 📝 API Docs · 🔌 SDK/CLI Generation · 📐 Spec Validation

---

## 9. tree-sitter (25.6k ⭐)

**🔗** https://github.com/tree-sitter/tree-sitter  
**🍴** Fork 2.7k | **🔄** Updated May 2026  
**👤** Tree-sitter Community — Created by Max Brunsfeld (former GitHub Atom team)

> Incremental parser generator and parsing library — the foundational infrastructure beneath almost all modern code analysis tools. Builds concrete syntax trees (CST) and efficiently updates them incrementally. Design goals: general (200+ language grammars), fast (parse on every keystroke), robust (useful results with syntax errors), dependency-free (pure C runtime). Provides Rust/Wasm/Node/Python bindings. GitNexus, graphify, Aider, and other tools depend on tree-sitter for parsing. The go-to foundation for building custom code analysis pipelines.

**Capabilities:** 🧱 Foundational Parser · 📊 AST/CST Construction · 🔍 200+ Languages · ⚡ Incremental Parsing

---

## 10. swagger-codegen (17.7k ⭐)

**🔗** https://github.com/swagger-api/swagger-codegen  
**🍴** Fork 6k | **🔄** Updated May 2026  
**👤** SmartBear / Swagger Team

> Template-driven code generation engine that parses OpenAPI/Swagger definitions to generate documentation, API clients, and server stubs. The predecessor to openapi-generator; new projects should prefer openapi-generator.

**Capabilities:** 📝 API Docs · 🔌 Code Generation

---

## 11. code-review-graph (17.5k ⭐)

**🔗** https://github.com/tirth8205/code-review-graph  
**🍴** Fork 1.9k | **🔄** Updated May 25, 2026  
**👤** Tirth Patel — Code graph & token optimization developer

> Stop burning tokens. Start reviewing smarter. Builds a local code knowledge graph — parses repos into ASTs with Tree-sitter, stores as nodes and edges, serves precise context via MCP. Core capability: **blast radius analysis** — traces every caller, dependent, and test affected by file changes. In large monorepos, 27,700+ files excluded from review context, only ~15 files actually read. 6.8× fewer tokens on reviews, up to 49× fewer on daily tasks. One command auto-configures all supported AI platforms.

**Capabilities:** 📊 Code Knowledge Graph · 🔍 Blast Radius Analysis · ⚡ Token Optimization · 🤖 MCP/Multi-platform

---

## 12. semgrep (15.3k ⭐)

**🔗** https://github.com/semgrep/semgrep  
**🍴** Fork 949 | **🔄** Updated May 2026  
**👤** Semgrep Inc. (formerly r2c / Return To Corp)

> Semantic grep for code. Finds bug variants using **patterns that look like source code** — no ASTs, regex, or DSLs needed. 30+ languages supported. Custom rules can batch-extract API call patterns, route definitions, and security vulnerabilities. Open-source for single function/file; enterprise supports cross-file dataflow analysis.

**Capabilities:** 🔍 Code Pattern Matching · 📊 API Call Batch Extraction · 🛡️ Security Analysis

---

## 13. codeql (9.6k ⭐)

**🔗** https://github.com/github/codeql  
**🍴** Fork 2k | **🔄** Updated May 2026  
**👤** GitHub — Powers GitHub Advanced Security

> Code query language and analysis platform. Treats code as a database, using SQL-like QL to locate patterns, vulnerabilities, and structural relationships. Thousands of pre-built queries, supports C/C++/C#/Go/Java/JavaScript/Python/Ruby/Swift. Custom queries can extract API endpoints, routing tables, and call chains.

**Capabilities:** 🔍 Code Structure Queries · 📊 API Endpoint Extraction · 🏗️ Call Chain Analysis

---

## 14. oclif (9.5k ⭐)

**🔗** https://github.com/oclif/oclif  
**🍴** Fork 354 | **🔄** Updated May 24, 2026  
**👤** Salesforce — The Framework Behind Heroku CLI

> Node.js CLI framework for generating, building, and releasing command-line tools. Plugin architecture, multi-command support, auto help generation, native TypeScript, hook system. Powers Heroku CLI and Salesforce CLI.

**Capabilities:** 🔌 CLI Framework · 📦 CLI Tool Productization

---

## 15. semble (4.4k ⭐)

**🔗** https://github.com/MinishLab/semble  
**🍴** Fork 178 | **🔄** Updated May 21, 2026  
**👤** Minish Lab — Two-person open-source lab (pringled & stephantul), focused on NLP and efficient models

> Fast and accurate code search for agents. Uses ~98% fewer tokens than grep+read. Provides semantic-level code search for AI coding assistants, enabling precise code fragment location in large codebases without brute-force file traversal.

**Capabilities:** 🔍 Semantic Code Search · ⚡ Token Optimization · 🤖 Agent Integration

---

## 16. OpenDeepWiki (3.3k ⭐)

**🔗** https://github.com/AIDotNet/OpenDeepWiki  
**🍴** Fork 416 | **🔄** Updated May 12, 2026  
**👤** AIDotNet — .NET AI Ecosystem

> Open-source DeepWiki, built on .NET 9 and Semantic Kernel. AI-powered code knowledge management: analyzes code structure, generates documentation and knowledge graphs. Supports GitHub/GitLab/Gitee/Gitea repositories. Features MCP protocol integration, conversational interaction, Mermaid diagrams, and multi-database support.

**Capabilities:** 🏗️ Architecture Docs · 📊 Module Identification · 📝 Auto Documentation · 🤖 MCP Integration

---

## 17. joern (3.2k ⭐)

**🔗** https://github.com/joernio/joern  
**🍴** Fork 414 | **🔄** Updated May 2026  
**👤** joern.io — Pioneers of Code Property Graphs (Saarland University)

> Open-source platform for analyzing source code, bytecode, and binaries. Core concept: **Code Property Graphs (CPG)** — unifying AST, control flow, and data flow into a single queryable cross-language graph. Supports C/C++/Java/JavaScript/Python/Kotlin/Binary. Scala DSL queries, interactive REPL, Docker deployment.

**Capabilities:** 📊 Code Property Graphs · 🔍 Cross-language Analysis · 🏗️ Call Chain/Dataflow Tracing

---

## 18. smart-doc (1.6k ⭐)

**🔗** https://github.com/TongchengOpenSource/smart-doc  
**🍴** Fork 297 | **🔄** Updated Dec 2025  
**👤** Tongcheng Open Source — Java API Documentation

> Java API documentation generator based on source code analysis — completely zero-injection, just standard Javadoc comments. Covers Spring MVC/Boot/WebFlux/Feign/JAX-RS/Dubbo/gRPC. Exports to Markdown/HTML5/Word/Postman/OpenAPI 3.0/JMeter.

**Capabilities:** 📝 Auto API Docs · 🔍 Source-level Extraction · 📐 OpenAPI/Postman Output

---

## 19. Redocly CLI (1.5k ⭐)

**🔗** https://github.com/Redocly/redocly-cli  
**🍴** Fork 217 | **🔄** Updated May 27, 2026  
**👤** Redocly — API Documentation Platform

> Makes OpenAPI easy. Lint/validate to any standard, generate beautiful interactive docs, preview API definitions, and bundle multi-file OpenAPI specs.

**Capabilities:** 📐 OpenAPI Validation · 📝 Doc Generation · 🔍 Spec Linting

---

## 20. deepwiki-rs (1k ⭐)

**🔗** https://github.com/sopaco/deepwiki-rs  
**🍴** Fork 125 | **🔄** Updated Apr 2026  
**👤** sopaco (Jiang Meng) — Rust developer focused on decentralization and automation

> Turn code into clarity. Generates accurate technical documentation and AI-ready context in minutes — perfectly structured for human teams and intelligent agents. A lightweight, high-performance Rust code documentation engine.

**Capabilities:** 📝 Code Documentation · 🏗️ Architecture · ⚡ Rust Performance

---

## Category Index

### 🏗️ Code Graph & Architecture Analysis
- [graphify](#2-graphify-547k-) — Code/docs → queryable knowledge graph + call-flow
- [GitNexus](#4-gitnexus-405k-) — CLI+MCP code nervous system, agent integration
- [codegraph](#5-codegraph-293k-) — Pre-indexed code knowledge graph, local-first
- [tree-sitter](#9-tree-sitter-256k-) — Foundational parser, 200+ language AST/CST
- [code-review-graph](#11-code-review-graph-175k-) — Local code graph, blast radius analysis
- [joern](#17-joern-32k-) — Code Property Graph (CPG) platform
- [codeql](#13-codeql-96k-) — Code query language, by GitHub
- [semgrep](#12-semgrep-153k-) — Semantic grep, multi-language pattern matching

### 📝 API Extraction & Documentation
- [context7](#1-context7-562k-) — Real-time code doc context for LLMs
- [smart-doc](#18-smart-doc-16k-) — Java zero-injection API docs, source analysis
- [OpenDeepWiki](#16-opendeepwiki-33k-) — AI-driven repo → Wiki + MCP
- [deepwiki-rs](#20-deepwiki-rs-1k-) — Rust code documentation engine
- [swagger-ui](#6-swagger-ui-288k-) — Interactive API docs standard
- [openapi-generator](#8-openapi-generator-263k-) — OpenAPI → SDK/CLI/docs
- [Redocly CLI](#19-redocly-cli-15k-) — OpenAPI lint + doc rendering

### 🔌 CLI Conversion & Frameworks
- [CLI-Anything](#3-cli-anything-408k-) — Software → Agent-Native CLI
- [python-fire](#7-googlepython-fire-282k-) — Python objects → CLI
- [oclif](#14-oclif-95k-) — Node.js CLI framework (Heroku/Salesforce)
- [swagger-codegen](#10-swagger-codegen-177k-) — Swagger → code/CLI

### 🔍 Code Search & Token Optimization
- [semble](#15-semble-44k-) — Agent semantic code search, ~98% fewer tokens
- [code-review-graph](#11-code-review-graph-175k-) — Blast radius analysis, 6.8-49× fewer tokens
- [codegraph](#5-codegraph-293k-) — Pre-indexed graph, fewer tool calls

---

## Watchlist (Stars < 1k, High Potential)

| Repository | Stars | Description |
|------------|-------|-------------|
| [OpenBMB/RepoAgent](https://github.com/OpenBMB/RepoAgent) | 969 | LLM-powered repository documentation |
| [archguard/archguard](https://github.com/archguard/archguard) | 668 | Architecture governance workbench |
| [alexknowshtml/api2cli](https://github.com/alexknowshtml/api2cli) | 437 | API → CLI patterns (Node+Commander) |
| [TheMorpheus407/RepoLens](https://github.com/TheMorpheus407/RepoLens) | 268 | 280 AI agents for multi-lens code audit |
| [lucianfialho/spec2cli](https://github.com/lucianfialho/spec2cli) | 16 | OpenAPI Spec → CLI, zero code generation |
| [tangcent/apilot](https://github.com/tangcent/apilot) | 3 | Multi-language API endpoint scanner |

---

*Data as of 2026-05-27, star counts from GitHub public pages*
