# codebase-analysis

**English** | [中文](./README.md)

> Curated Tools for Full Codebase Analysis — Architecture · API Extraction · CLI Conversion · Module Decomposition  
> Source: wind8ai Stars Lists  
> Updated: 2026-05-20  

---

## Contents

01. [graphify — 45k ⭐](#1-graphify-45k-)
02. [GitNexus — 39k ⭐](#2-gitnexus-39k-)
03. [CLI-Anything — 36k ⭐](#3-cli-anything-36k-)
04. [swagger-ui — 27k ⭐](#4-swagger-ui-27k-)
05. [google/python-fire — 27k ⭐](#5-googlepython-fire-27k-)
06. [openapi-generator — 22k ⭐](#6-openapi-generator-22k-)
07. [tree-sitter — 19k ⭐](#7-tree-sitter-19k-)
08. [swagger-codegen — 17k ⭐](#8-swagger-codegen-17k-)
09. [code-review-graph — 16.9k ⭐](#9-code-review-graph-169k-)
10. [semgrep — 11k ⭐](#10-semgrep-11k-)
11. [oclif — 9.5k ⭐](#11-oclif-95k-)
12. [codeql — 8k ⭐](#12-codeql-8k-)
13. [joern — 3.2k ⭐](#13-joern-32k-)
14. [OpenDeepWiki — 3.2k ⭐](#14-opendeepwiki-32k-)
15. [smart-doc — 1.8k ⭐](#15-smart-doc-18k-)
16. [Redocly CLI — 1.5k ⭐](#16-redocly-cli-15k-)

---

## 1. graphify (45k ⭐)

**🔗** https://github.com/safishamsi/graphify  
**🍴** Fork 4.9k | **🔄** Updated May 7, 2026  
**👤** Safi (safishamsi) — London AI Engineer, Birmingham MSc Data Science (Distinction)

> AI coding assistant skill. Type `/graphify .` in your AI agent and it maps your entire project — code, docs, PDFs, images, videos — into a queryable knowledge graph. Outputs three files: `graph.html` (interactive node visualization), `GRAPH_REPORT.md` (key concepts & surprising connections), and `graph.json` (full graph data for re-querying without re-reading files). Also supports `graphify export callflow-html` for readable architecture pages with Mermaid call-flow diagrams. Works in Claude Code, Codex, OpenCode, Cursor, Gemini CLI, GitHub Copilot CLI, Aider, OpenClaw, Factory Droid, Trae, Hermes, Kimi Code, Kiro, Pi, and Google Antigravity (15+ agents). PyPI package: `graphifyy`, install via `uv tool install graphifyy`.

**Capabilities:** 📊 Code Graph · 🏗️ Architecture · 🔍 Call-flow Analysis · 📝 Auto Reports

---

## 2. GitNexus (39k ⭐)

**🔗** https://github.com/abhigyanpatwari/GitNexus  
**🍴** Fork 4.5k | **🔄** Updated May 20, 2026  
**👤** Abhigyan Patwari (Akon Labs)

> Building nervous system for agent context. Indexes any codebase into a knowledge graph — every dependency, call chain, cluster, and execution flow — then exposes it through smart tools so AI agents never miss code. Two modes: **CLI + MCP** (`npm install -g gitnexus`, indexes repos locally, connects AI agents via MCP server to Cursor/Claude Code/Codex/Windsurf/OpenCode, uses LadybugDB for persistent storage and native Tree-sitter parsing) and **Web UI** (visual graph explorer + AI chat in browser). Bridge mode connects both — the web UI auto-detects the local server and browses all CLI-indexed repos without re-uploading. Self-described as "Like DeepWiki, but deeper" — DeepWiki helps you understand code, GitNexus lets you analyze it, because a knowledge graph tracks every relationship, not just descriptions. Enterprise edition supports PR blast radius analysis, auto-updating Code Wiki, and multi-repo unified graphs.

**Capabilities:** 🏗️ Architecture · 📊 Module Decomposition · 🔍 Code Graph · 🤖 MCP/Agent Integration

---

## 3. CLI-Anything (36k ⭐)

**🔗** https://github.com/HKUDS/CLI-Anything  
**🍴** Fork 3.6k | **🔄** Updated May 2026  
**👤** HKUDS (HKU Data Science Lab) — Academic + Open-source Team

> "Today's Software Serves Humans👨‍💻. Tomorrow's Users will be Agents🤖." Bridges the gap between AI agents and the world's software. One command line generates agent-ready CLI interfaces for any software, enabling Pi, OpenClaw, Cursor, Claude Code, and more to directly control applications. Built-in CLI-Hub community registry (`pip install cli-anything-hub`) for browsing, installing, and managing community-built CLI wrappers. Supports preview, live preview, and trajectory loops for agents to produce real artifacts: CAD builds, 3D scenes, diagrams, gameplay, subtitles, and more. Dozens of software wrappers already available: QGIS (GIS), Obsidian, Safari, FreeCAD, Kdenlive, Unreal Insights, etc.

**Capabilities:** 🔌 Software→CLI Conversion · 🤖 Agent-Native · 📦 Community Ecosystem

---

## 4. swagger-ui (27k ⭐)

**🔗** https://github.com/swagger-api/swagger-ui  
**🍴** Fork 9k+ | **🔄** Updated May 2026  
**👤** SmartBear / Swagger Team — API Toolchain Industry Standard

> Dynamically generates beautiful interactive API documentation from Swagger/OpenAPI specs. Provides "Try it out" live API testing, request/response model viewing, and parameter documentation. The de facto standard for API documentation visualization, used as a baseline across virtually all RESTful projects.

**Capabilities:** 📝 API Documentation · 🖥️ Interactive API Debugging

---

## 5. google/python-fire (27k ⭐)

**🔗** https://github.com/google/python-fire  
**🍴** Fork 1.5k | **🔄** Updated May 2026  
**👤** Google

> Automatically generates CLI interfaces from absolutely any Python object. No decorators, argument definitions, or config files needed — directly converts functions, classes, modules, dicts, even object instances into fully usable CLIs with subcommands, argument inference, and help docs. The fastest path from code to CLI.

**Capabilities:** 🔌 Code→CLI Conversion · ⚡ Rapid Prototyping

---

## 6. openapi-generator (22k ⭐)

**🔗** https://github.com/OpenAPITools/openapi-generator  
**🍴** Fork 6.5k+ | **🔄** Updated May 2026  
**👤** OpenAPI Tools Community

> Given an OpenAPI Spec (v2/v3), automatically generates API client SDKs, server stubs, documentation, and configuration. Supports 50+ languages/frameworks including Java/Python/TypeScript/Go/Ruby/C#/Rust and more. The industrial-grade standard for spec-driven development and the go-to solution for generating CLI clients from OpenAPI specs.

**Capabilities:** 📝 API Docs · 🔌 SDK/CLI Generation · 📐 Spec Validation

---

## 7. tree-sitter (19k ⭐)

**🔗** https://github.com/tree-sitter/tree-sitter  
**🍴** Fork 1.5k+ | **🔄** Updated May 2026  
**👤** Tree-sitter Community — Created by Max Brunsfeld (former GitHub Atom team), now an independent open-source project

> Incremental parser generator tool and parsing library — the foundational infrastructure beneath almost all modern code analysis tools. Builds concrete syntax trees (CST) for source files and efficiently updates them incrementally as files are edited. Design goals: general (parse any programming language, 200+ language grammars available), fast (parse on every keystroke in a text editor), robust (useful results even with syntax errors), dependency-free (pure C runtime, embeddable in any application). Provides Rust/Wasm/Node/Python bindings and CLI tool. GitNexus, graphify, Aider, Codebase-Memory, and other higher-level tools all depend on tree-sitter for underlying parsing. The go-to foundation for building custom code analysis pipelines.

**Capabilities:** 🧱 Foundational Parser · 📊 AST/CST Construction · 🔍 200+ Languages · ⚡ Incremental Parsing

---

## 8. swagger-codegen (17k ⭐)

**🔗** https://github.com/swagger-api/swagger-codegen  
**🍴** Fork 6k+ | **🔄** Updated May 2026  
**👤** SmartBear / Swagger Team

> Template-driven code generation engine that parses OpenAPI/Swagger definitions to generate documentation, API clients, and server stubs across multiple languages and frameworks. The predecessor to openapi-generator; both have significant feature overlap. New projects should prefer openapi-generator.

**Capabilities:** 📝 API Docs · 🔌 Code Generation

---

## 9. code-review-graph (16.9k ⭐)

**🔗** https://github.com/tirth8205/code-review-graph  
**🍴** Fork 1.8k | **🔄** Updated May 2026  
**👤** Tirth Patel — Code graph & token optimization developer

> Stop burning tokens. Start reviewing smarter. Builds a local code knowledge graph for AI coding tools — parses your repo into an AST with Tree-sitter, stores it as a graph of nodes (functions, classes, imports) and edges (calls, inheritance, test coverage), then serves precise context to AI assistants via MCP so they read only what matters. Core capability: **blast radius analysis** — when a file changes, traces every caller, dependent, and test that could be affected. AI reads only these files instead of scanning the whole project. Incremental updates are extremely fast (2,900-file project re-indexes in <2 seconds). In large monorepos, 27,700+ files are excluded from review context, with only ~15 files actually read. Measured results: 6.8× fewer tokens on code reviews, up to 49× fewer on daily coding tasks. Supports Claude Code/Codex/Cursor/Gemini CLI/Kiro/GitHub Copilot and more — one command auto-detects and configures all supported platforms.

**Capabilities:** 📊 Code Knowledge Graph · 🔍 Blast Radius Analysis · ⚡ Token Optimization · 🤖 MCP/Multi-platform

---

## 10. semgrep (11k ⭐)

**🔗** https://github.com/semgrep/semgrep  
**🍴** Fork 900+ | **🔄** Updated May 2026  
**👤** Semgrep Inc. (formerly r2c / Return To Corp)

> Semantic grep for code. Finds bug variants using **patterns that look like source code** — no ASTs, regex wrestling, or painful DSLs needed. Supports 30+ languages (Apex/Bash/C/C++/C#/Go/Java/JavaScript/Kotlin/Python/Ruby/Rust/Swift/TypeScript and more). While `grep "2"` only matches the string "2", Semgrep matches `x=1; y=x+1` as semantically equivalent. Custom rules can batch-extract API call patterns, route definitions, and security vulnerabilities from codebases. Open-source edition analyzes within single functions/files; enterprise edition supports cross-file/cross-function dataflow analysis with 20,000+ proprietary rules.

**Capabilities:** 🔍 Code Pattern Matching · 📊 API Call Batch Extraction · 🛡️ Security Analysis

---

## 11. oclif (9.5k ⭐)

**🔗** https://github.com/oclif/oclif  
**🍴** Fork 352 | **🔄** Updated May 17, 2026  
**👤** Salesforce — The Framework Behind Heroku CLI

> Node.js CLI framework for generating, building, and releasing command-line tools. Plugin architecture, multi-command support, auto help generation, native TypeScript, hook system. Powers Heroku CLI, Salesforce CLI, and other well-known tools. Ideal for packaging extracted API information into standardized, production-grade CLI tools.

**Capabilities:** 🔌 CLI Framework · 📦 CLI Tool Productization

---

## 12. codeql (8k ⭐)

**🔗** https://github.com/github/codeql  
**🍴** Fork 1.5k+ | **🔄** Updated May 2026  
**👤** GitHub — Powers GitHub Advanced Security

> Code query language and analysis platform powering code scanning in GitHub Advanced Security. Treats code as a database, using a SQL-like query language (QL) to precisely locate patterns, vulnerabilities, and structural relationships. Ships with standard libraries and thousands of pre-built queries. Supports C/C++/C#/Go/Java/JavaScript/Python/Ruby/Swift. Provides VS Code extension, CLI tool, and CI/CD integration. Custom queries can extract API endpoint definitions, routing tables, call chains, and other structural information. Open-source for analyzing open-source projects; commercial license required for closed-source.

**Capabilities:** 🔍 Code Structure Queries · 📊 API Endpoint Extraction · 🏗️ Call Chain Analysis

---

## 13. joern (3.2k ⭐)

**🔗** https://github.com/joernio/joern  
**🍴** Fork 411 | **🔄** Updated May 2026  
**👤** joern.io — Pioneers of Code Property Graphs (Saarland University)

> Open-source platform for analyzing source code, bytecode, and binary executables. Core concept: **Code Property Graphs (CPG)** — unifying AST, control flow, and data flow graphs into a single queryable cross-language graph structure stored in a custom graph database. Uses a Scala-based DSL query language for code mining. Supports C/C++/Java/JavaScript/Python/Kotlin/Binary. Designed for vulnerability discovery and static program analysis research. Features interactive REPL, Docker deployment, and server mode.

**Capabilities:** 📊 Code Property Graphs · 🔍 Cross-language Deep Analysis · 🏗️ Call Chain/Dataflow Tracing

---

## 14. OpenDeepWiki (3.2k ⭐)

**🔗** https://github.com/AIDotNet/OpenDeepWiki  
**🍴** Fork 415 | **🔄** Updated May 2026  
**👤** AIDotNet — .NET AI Ecosystem

> Open-source DeepWiki, built on .NET 9 and Semantic Kernel. AI-powered code knowledge management platform: automatically analyzes code structure, understands core concepts, generates documentation and knowledge graphs. Supports GitHub/GitLab/AtomGit/Gitee/Gitea repositories — converts to knowledge bases in minutes. Auto-generates Mermaid code structure diagrams. Supports custom AI models and APIs, multiple databases (SQLite/PostgreSQL/MySQL/SqlServer), multi-language UI. Features conversational interaction for deep code understanding, MCP protocol integration (can serve as MCPServer for other AI models), SEO-friendly Next.js frontend, and data fine-tuning platform. Supports ZIP/local file upload.

**Capabilities:** 🏗️ Architecture Docs · 📊 Module Identification · 📝 Auto Documentation · 🤖 MCP Integration

---

## 15. smart-doc (1.8k ⭐)

**🔗** https://github.com/smart-doc-group/smart-doc  
**🍴** Fork 300+ | **🔄** Updated May 2026  
**👤** smart-doc-group — Incubated by Tongcheng Open Source

> Java API documentation generator based on interface source code analysis — completely zero-injection with no annotations needed, just standard Javadoc comments. Powerful automatic return value structure derivation, supports async interfaces (Callable/Future/CompletableFuture) and JSR-303 parameter validation. Covers Spring MVC/Spring Boot/WebFlux/Feign/JAX-RS frameworks plus Apache Dubbo RPC and gRPC protocols. Exports to Markdown/HTML5/Word/Asciidoctor/Postman Collection/OpenAPI 3.0/JMeter performance test scripts. Supports loading external source code (including JAR packages) for field comments, error code and data dictionary export, and debug pages with file upload/download testing.

**Capabilities:** 📝 Auto API Docs · 🔍 Source-level Extraction · 📐 OpenAPI/Postman Output

---

## 16. Redocly CLI (1.5k ⭐)

**🔗** https://github.com/Redocly/redocly-cli  
**🍴** Fork 217 | **🔄** Updated May 20, 2026  
**👤** Redocly — API Documentation Platform

> Makes OpenAPI easy. Lint/validate to any standard, generate beautiful interactive docs, preview API definitions, and bundle multi-file OpenAPI specs. Ideal for post-extraction spec validation and documentation rendering.

**Capabilities:** 📐 OpenAPI Validation · 📝 Doc Generation · 🔍 Spec Linting

---

## Category Index

### 🏗️ Code Graph & Architecture Analysis
- [graphify](#1-graphify-45k-) — Code/docs → queryable knowledge graph + call-flow
- [GitNexus](#2-gitnexus-39k-) — CLI+MCP code nervous system, agent integration
- [tree-sitter](#7-tree-sitter-19k-) — Foundational parser, 200+ language AST/CST
- [code-review-graph](#9-code-review-graph-169k-) — Local code graph, blast radius analysis
- [joern](#13-joern-32k-) — Code Property Graph (CPG) platform
- [codeql](#12-codeql-8k-) — Code query language, by GitHub
- [semgrep](#10-semgrep-11k-) — Semantic grep, multi-language pattern matching

### 📝 API Extraction & Documentation
- [smart-doc](#13-smart-doc-18k-) — Java zero-injection API docs, source analysis
- [OpenDeepWiki](#12-opendeepwiki-32k-) — AI-driven repo → Wiki + MCP
- [swagger-ui](#4-swagger-ui-27k-) — Interactive API docs standard
- [openapi-generator](#6-openapi-generator-22k-) — OpenAPI → SDK/CLI/docs
- [Redocly CLI](#14-redocly-cli-15k-) — OpenAPI lint + doc rendering

### 🔌 CLI Conversion & Frameworks
- [CLI-Anything](#3-cli-anything-36k-) — Software → Agent-Native CLI
- [python-fire](#5-googlepython-fire-27k-) — Python objects → CLI
- [oclif](#9-oclif-95k-) — Node.js CLI framework (Heroku/Salesforce)
- [swagger-codegen](#7-swagger-codegen-17k-) — Swagger → code/CLI

---

## Watchlist (Stars < 1k, High Potential)

| Repository | Stars | Description |
|------------|-------|-------------|
| [OpenBMB/RepoAgent](https://github.com/OpenBMB/RepoAgent) | 967 | LLM-powered repository documentation |
| [sopaco/deepwiki-rs](https://github.com/sopaco/deepwiki-rs) | 984 | Rust code documentation engine |
| [archguard/archguard](https://github.com/archguard/archguard) | 666 | Architecture governance workbench |
| [alexknowshtml/api2cli](https://github.com/alexknowshtml/api2cli) | 436 | API → CLI patterns (Node+Commander) |
| [TheMorpheus407/RepoLens](https://github.com/TheMorpheus407/RepoLens) | 264 | 280 AI agents for multi-lens code audit |
| [tirth8205/code-review-graph](https://github.com/tirth8205/code-review-graph) | — | Local code knowledge graph for Claude Code |
| [tangcent/apilot](https://github.com/tangcent/apilot) | 3 | Multi-language API endpoint scanner |
| [lucianfialho/spec2cli](https://github.com/lucianfialho/spec2cli) | 16 | OpenAPI Spec → CLI, zero code generation |

---

## Appendix: Source Star Lists

- [code-analysis](https://github.com/stars/wind8ai/lists/code-analysis)
- [tools](https://github.com/stars/wind8ai/lists/tools)
- [memory](https://github.com/stars/wind8ai/lists/memory)
- [CLI](https://github.com/stars/wind8ai/lists/cli)
- [Code2Schema](https://github.com/stars/wind8ai/lists/code2schema)
- [schema](https://github.com/stars/wind8ai/lists/schema)
- [API](https://github.com/stars/wind8ai/lists/api)

---

*Data as of 2026-05-20, star counts from GitHub public pages*
