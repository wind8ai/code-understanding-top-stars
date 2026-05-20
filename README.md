# codebase-analysis

**中文** | [English](./README.en.md)

> 代码库全域解析工具精选 — 架构梳理 · API 提取 · CLI 转化 · 模块拆解  
> 来源：wind8ai Stars Lists  
> 抓取：2026-05-20  

---

## Contents

01. [graphify — 45k ⭐](#1-graphify-45k-)
02. [GitNexus — 39k ⭐](#2-gitnexus-39k-)
03. [CLI-Anything — 36k ⭐](#3-cli-anything-36k-)
04. [swagger-ui — 27k ⭐](#4-swagger-ui-27k-)
05. [google/python-fire — 27k ⭐](#5-googlepython-fire-27k-)
06. [openapi-generator — 22k ⭐](#6-openapi-generator-22k-)
07. [swagger-codegen — 17k ⭐](#7-swagger-codegen-17k-)
08. [semgrep — 11k ⭐](#8-semgrep-11k-)
09. [oclif — 9.5k ⭐](#9-oclif-95k-)
10. [codeql — 8k ⭐](#10-codeql-8k-)
11. [joern — 3.2k ⭐](#11-joern-32k-)
12. [OpenDeepWiki — 3.2k ⭐](#12-opendeepwiki-32k-)
13. [smart-doc — 1.8k ⭐](#13-smart-doc-18k-)
14. [Redocly CLI — 1.5k ⭐](#14-redocly-cli-15k-)

---

## 1. graphify (45k ⭐)

**🔗** https://github.com/safishamsi/graphify  
**🍴** Fork 4.9k | **🔄** Updated May 7, 2026  
**👤** Safi (safishamsi) — 伦敦 AI 工程师，伯明翰大学数据科学硕士（Distinction），专注医疗 AI 与知识图谱

> AI 编码助手 Skill，在 AI Agent 中输入 `/graphify .` 即可将整个项目——代码、文档、PDF、图片、视频——映射为可查询的知识图谱。产出三个文件：`graph.html`（交互式节点图）、`GRAPH_REPORT.md`（关键概念与关联分析）、`graph.json`（完整图谱数据）。还可通过 `graphify export callflow-html` 生成带 Mermaid 调用流图的架构页面。支持 Claude Code、Codex、OpenCode、Cursor、Gemini CLI、GitHub Copilot CLI、Aider、OpenClaw 等 15+ 主流 Agent 工具。PyPI 包名 `graphifyy`，通过 `uv tool install graphifyy` 安装。

**匹配能力：** 📊 代码图谱 · 🏗️ 架构梳理 · 🔍 调用流分析 · 📝 自动报告

---

## 2. GitNexus (39k ⭐)

**🔗** https://github.com/abhigyanpatwari/GitNexus  
**🍴** Fork 4.5k | **🔄** Updated May 20, 2026  
**👤** Abhigyan Patwari (Akon Labs) — 代码智能引擎开发者

> 为 Agent 上下文构建"代码神经系统"。将任意代码库索引为知识图谱——覆盖每个依赖、调用链、聚簇和执行流——然后通过智能工具暴露给 AI Agent，使其不再遗漏代码。提供两种使用模式：**CLI + MCP**（`npm install -g gitnexus`，本地索引仓库，通过 MCP 服务器连接 Cursor/Claude Code/Codex/Windsurf/OpenCode 等 Agent，使用 LadybugDB 持久化存储和 Tree-sitter 原生解析）和 **Web UI**（浏览器端可视化图谱探索 + AI 对话）。Bridge 模式可将两者打通。自称"Like DeepWiki, but deeper"——DeepWiki 帮你理解代码，GitNexus 让你分析代码，因为知识图谱追踪每一层关系而非仅描述。企业版支持 PR 爆炸半径分析、自动更新代码 Wiki、多仓库统一图谱。

**匹配能力：** 🏗️ 架构梳理 · 📊 模块拆解 · 🔍 代码图谱 · 🤖 MCP/Agent 集成

---

## 3. CLI-Anything (36k ⭐)

**🔗** https://github.com/HKUDS/CLI-Anything  
**🍴** Fork 3.6k | **🔄** Updated May 2026  
**👤** HKUDS（香港大学数据科学实验室）— 学术+开源团队

> "今天的软件服务人类👨‍💻，明天的用户是 Agent🤖"——弥合 AI Agent 与世界软件的鸿沟。一行命令为任意软件生成 Agent 可用的 CLI 接口，使 Pi、OpenClaw、Cursor、Claude Code 等工具能直接操控各类应用。内置 CLI-Hub 社区注册表（`pip install cli-anything-hub`），支持浏览、安装、管理社区构建的 CLI 封装。支持预览、实时预览和轨迹循环，可让 Agent 产出实际制品：CAD 模型、3D 场景、图表、游戏画面、字幕等。已有 QGIS（GIS）、Obsidian、Safari、FreeCAD、Kdenlive、Unreal Insights 等数十个软件的 CLI 封装。

**匹配能力：** 🔌 软件→CLI 转化 · 🤖 Agent-Native · 📦 社区生态

---

## 4. swagger-ui (27k ⭐)

**🔗** https://github.com/swagger-api/swagger-ui  
**🍴** Fork 9k+ | **🔄** Updated May 2026  
**👤** SmartBear / Swagger 团队 — API 工具链行业标准制定者

> 从 Swagger/OpenAPI 规范自动生成交互式 API 文档界面。提供在线 "Try it out" 试用 API 调用、查看请求/响应模型、参数说明等功能，是 API 文档可视化的事实标准，几乎所有 RESTful 项目的标配。

**匹配能力：** 📝 API 文档可视化 · 🖥️ 交互式接口调试

---

## 5. google/python-fire (27k ⭐)

**🔗** https://github.com/google/python-fire  
**🍴** Fork 1.5k | **🔄** Updated May 2026  
**👤** Google — Python Fire 是 Google 开源的 CLI 生成库

> 从任意 Python 对象自动生成命令行接口。无需装饰器、参数定义或配置文件，直接将函数、类、模块、字典甚至对象实例转为完整可用的 CLI——包括子命令、参数推断、帮助文档。是最快的"代码→CLI"转化路径。

**匹配能力：** 🔌 代码→CLI 转化 · ⚡ 极速原型

---

## 6. openapi-generator (22k ⭐)

**🔗** https://github.com/OpenAPITools/openapi-generator  
**🍴** Fork 6.5k+ | **🔄** Updated May 2026  
**👤** OpenAPI Tools 社区 — OpenAPI 生态核心项目

> 给定 OpenAPI Spec（v2/v3），自动生成 API 客户端 SDK、服务端桩代码、文档和配置。支持 50+ 编程语言/框架，涵盖 Java/Python/TypeScript/Go/Ruby/C#/Rust 等主流语言。是 API 规范驱动开发的工业级标准工具，也是从 OpenAPI Spec 生成 CLI 客户端的首选方案。

**匹配能力：** 📝 API 文档生成 · 🔌 SDK/CLI 生成 · 📐 规范校验

---

## 7. swagger-codegen (17k ⭐)

**🔗** https://github.com/swagger-api/swagger-codegen  
**🍴** Fork 6k+ | **🔄** Updated May 2026  
**👤** SmartBear / Swagger 团队

> 模板驱动代码生成引擎，解析 OpenAPI/Swagger 定义自动生成文档、API 客户端和服务端桩代码。多语言多框架支持，是 openapi-generator 的前身项目。两者功能高度重叠，新项目推荐优先用 openapi-generator。

**匹配能力：** 📝 API 文档 · 🔌 代码生成

---

## 8. semgrep (11k ⭐)

**🔗** https://github.com/semgrep/semgrep  
**🍴** Fork 900+ | **🔄** Updated May 2026  
**👤** Semgrep Inc.（前 r2c / Return To Corp）— 代码安全分析公司

> 面向代码的语义 grep。用**看起来像源代码的模式**查找 Bug 变体——不需要 AST、正则表达式或复杂 DSL。支持 30+ 语言（Apex/Bash/C/C++/C#/Go/Java/JavaScript/Kotlin/Python/Ruby/Rust/Swift/TypeScript 等）。用 `grep "2"` 只能匹配字符串 "2"，而 Semgrep 能匹配 `x=1; y=x+1` 中语义等价的 "2"。可自定义规则批量提取代码中的 API 调用模式、路由定义、安全漏洞。开源版限单函数/文件分析，企业版支持跨文件跨函数数据流分析。

**匹配能力：** 🔍 代码模式匹配 · 📊 API 调用批量提取 · 🛡️ 安全分析

---

## 9. oclif (9.5k ⭐)

**🔗** https://github.com/oclif/oclif  
**🍴** Fork 352 | **🔄** Updated May 17, 2026  
**👤** Salesforce — Heroku CLI 背后的框架

> Node.js CLI 框架，用于生成、构建和发布命令行工具。插件化架构，支持多命令组织、自动帮助文档生成、TypeScript 原生支持、钩子系统。Heroku CLI、Salesforce CLI 等知名工具均基于 oclif 构建。适合将提取到的 API 信息封装成规范化的 CLI 工具产品。

**匹配能力：** 🔌 CLI 框架 · 📦 CLI 工具产品化

---

## 10. codeql (8k ⭐)

**🔗** https://github.com/github/codeql  
**🍴** Fork 1.5k+ | **🔄** Updated May 2026  
**👤** GitHub — 全球最大代码托管平台的官方分析引擎

> 代码查询语言与分析平台，驱动 GitHub Advanced Security 的代码扫描功能。将代码视为数据库，用类 SQL 的查询语言（QL）精准定位代码中的模式、漏洞和结构关系。包含标准库和数千个预置查询，支持 C/C++/C#/Go/Java/JavaScript/Python/Ruby/Swift。提供 VS Code 扩展、CLI 工具和 CI/CD 集成。可编写自定义查询提取 API 端点定义、路由表、调用链等结构化信息。开源用于开源项目分析，闭源项目需商业授权。

**匹配能力：** 🔍 代码结构查询 · 📊 API 端点提取 · 🏗️ 调用链分析

---

## 11. joern (3.2k ⭐)

**🔗** https://github.com/joernio/joern  
**🍴** Fork 411 | **🔄** Updated May 2026  
**👤** joern.io — 代码属性图领域开创者（源于 Saarland 大学研究）

> 开源代码分析平台，用于分析源码、字节码和二进制可执行文件。核心概念是**代码属性图（CPG）**——将 AST、控制流图、数据流图统一为跨语言的单一可查询图结构，存储在自定义图数据库中。使用 Scala DSL 查询语言挖掘代码。支持 C/C++/Java/JavaScript/Python/Kotlin/Binary。目标是为漏洞发现和静态程序分析研究提供基础工具。交互式 REPL 界面，Docker 部署支持，可作为服务器模式运行。

**匹配能力：** 📊 代码属性图 · 🔍 跨语言深度分析 · 🏗️ 调用链/数据流追踪

---

## 12. OpenDeepWiki (3.2k ⭐)

**🔗** https://github.com/AIDotNet/OpenDeepWiki  
**🍴** Fork 415 | **🔄** Updated May 2026  
**👤** AIDotNet — .NET AI 生态开源组织

> DeepWiki 开源版，基于 .NET 9 和 Semantic Kernel 开发。AI 驱动的代码知识管理平台：自动分析代码结构、理解核心概念、生成文档和知识图谱。支持 GitHub/GitLab/AtomGit/Gitee/Gitea 等多平台仓库，分钟级转化为知识库。自动生成 Mermaid 代码结构图。支持自定义 AI 模型和 API、多数据库（SQLite/PostgreSQL/MySQL/SqlServer）、多语言界面。提供对话式交互深入理解代码、MCP 协议集成（可作为 MCPServer 供其他 AI 模型调用）、SEO 友好的 Next.js 前端、数据微调平台。支持上传 ZIP/本地文件。

**匹配能力：** 🏗️ 架构文档 · 📊 模块识别 · 📝 自动文档生成 · 🤖 MCP 集成

---

## 13. smart-doc (1.8k ⭐)

**🔗** https://github.com/smart-doc-group/smart-doc  
**🍴** Fork 300+ | **🔄** Updated May 2026  
**👤** smart-doc-group — 同程开源孵化，专注 Java API 文档自动化

> Java API 文档生成工具，基于接口源码分析直接生成文档——完全零注解侵入，只需写标准 Javadoc 注释即可。基于源码的返回值结构自动推导能力强大，支持异步接口（Callable/Future/CompletableFuture）、JSR-303 参数校验规范。覆盖 Spring MVC/Spring Boot/WebFlux/Feign/JAX-RS 框架，以及 Apache Dubbo RPC、gRPC 协议。可导出 Markdown/HTML5/Word/Asciidoctor/Postman Collection/OpenAPI 3.0/JMeter 性能测试脚本等多种格式。支持加载外部源码（含 JAR 包）生成字段注释、错误码和数据字典导出、调试页面支持文件上传下载测试。

**匹配能力：** 📝 API 文档自动生成 · 🔍 源码级接口提取 · 📐 OpenAPI/Postman 输出

---

## 14. Redocly CLI (1.5k ⭐)

**🔗** https://github.com/Redocly/redocly-cli  
**🍴** Fork 217 | **🔄** Updated May 20, 2026  
**👤** Redocly — API 文档与设计平台公司

> 让 OpenAPI 开发变得简单的 CLI 工具。对任意标准进行 lint/校验，生成精美交互文档，预览 API 定义，打包多文件 OpenAPI 规范。适合在 API 提取后进行规范化校验和文档渲染。

**匹配能力：** 📐 OpenAPI 校验 · 📝 文档生成 · 🔍 规范 lint

---

## 分类索引

### 🏗️ 代码图谱 & 架构分析
- [graphify](#1-graphify-45k-) — 代码/文档 → 可查询知识图谱 + 调用流
- [GitNexus](#2-gitnexus-39k-) — CLI+MCP 代码神经系统，Agent 集成
- [joern](#11-joern-32k-) — 代码属性图（CPG）分析平台
- [codeql](#10-codeql-8k-) — 代码查询语言，GitHub 官方
- [semgrep](#8-semgrep-11k-) — 语义 grep，多语言模式匹配

### 📝 API 提取 & 文档生成
- [smart-doc](#13-smart-doc-18k-) — Java 零侵入 API 文档，源码分析
- [OpenDeepWiki](#12-opendeepwiki-32k-) — AI 驱动仓库 → Wiki + MCP
- [swagger-ui](#4-swagger-ui-27k-) — 交互式 API 文档标准
- [openapi-generator](#6-openapi-generator-22k-) — OpenAPI → SDK/CLI/文档
- [Redocly CLI](#14-redocly-cli-15k-) — OpenAPI lint + 文档渲染

### 🔌 CLI 转化 & 框架
- [CLI-Anything](#3-cli-anything-36k-) — 软件 → Agent-Native CLI
- [python-fire](#5-googlepython-fire-27k-) — Python 对象 → CLI
- [oclif](#9-oclif-95k-) — Node.js CLI 框架（Heroku/Salesforce）
- [swagger-codegen](#7-swagger-codegen-17k-) — Swagger → 代码/CLI

---

## 候选关注（Stars < 1k 但有潜力）

| 仓库 | Stars | 简介 |
|------|-------|------|
| [OpenBMB/RepoAgent](https://github.com/OpenBMB/RepoAgent) | 967 | LLM 驱动仓库文档生成 |
| [sopaco/deepwiki-rs](https://github.com/sopaco/deepwiki-rs) | 984 | Rust 实现代码文档引擎 |
| [archguard/archguard](https://github.com/archguard/archguard) | 666 | 架构治理工作台，容器/组件/代码级分析 |
| [alexknowshtml/api2cli](https://github.com/alexknowshtml/api2cli) | 436 | API → CLI 模式库（Node+Commander） |
| [TheMorpheus407/RepoLens](https://github.com/TheMorpheus407/RepoLens) | 264 | 280 个 AI Agent 多角度代码审计 |
| [tirth8205/code-review-graph](https://github.com/tirth8205/code-review-graph) | — | Claude Code 本地代码知识图谱 |
| [tangcent/apilot](https://github.com/tangcent/apilot) | 3 | 多语言 API 端点扫描 → Markdown/cURL/Postman |
| [lucianfialho/spec2cli](https://github.com/lucianfialho/spec2cli) | 16 | OpenAPI Spec → CLI，零代码生成 |

---

## 附录：数据来源 Star Lists

- [code-analysis](https://github.com/stars/wind8ai/lists/code-analysis)
- [tools](https://github.com/stars/wind8ai/lists/tools)
- [memory](https://github.com/stars/wind8ai/lists/memory)
- [CLI](https://github.com/stars/wind8ai/lists/cli)
- [Code2Schema](https://github.com/stars/wind8ai/lists/code2schema)
- [schema](https://github.com/stars/wind8ai/lists/schema)
- [API](https://github.com/stars/wind8ai/lists/api)

---

*数据截至 2026-05-20，星数取自 GitHub 页面公开信息*
