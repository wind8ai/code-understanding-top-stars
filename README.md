# code-understanding-top-stars

**中文** | [English](./README.en.md)

> 代码理解工具精选 — 架构梳理 · API 提取 · CLI 转化 · 模块拆解  
> 来源：wind8ai Stars Lists  
> 抓取：2026-06-10  

---

## Contents

01. [graphify — 64.5k ⭐](#1-graphify-645k-)
02. [context7 — 57.1k ⭐](#2-context7-571k-)
03. [Understand-Anything — 56.3k ⭐](#3-understand-anything-563k-)
04. [codegraph — 46.4k ⭐](#4-codegraph-464k-)
05. [CLI-Anything — 42.6k ⭐](#5-cli-anything-426k-)
06. [GitNexus — 41.9k ⭐](#6-gitnexus-419k-)
07. [swagger-ui — 28.8k ⭐](#7-swagger-ui-288k-)
08. [python-fire — 28.2k ⭐](#8-googlepython-fire-282k-)
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
**🍴** Fork 6.6k | **🔄** Updated Jun 3, 2026  
**👤** Safi (safishamsi) — 伦敦 AI 工程师，伯明翰大学数据科学硕士（Distinction），专注医疗 AI 与知识图谱

> AI 编码助手 Skill，在 AI Agent 中输入 `/graphify .` 即可将整个项目——代码、文档、PDF、图片、视频——映射为可查询的知识图谱。产出三个文件：`graph.html`（交互式节点图）、`GRAPH_REPORT.md`（关键概念与关联分析）、`graph.json`（完整图谱数据）。还可通过 `graphify export callflow-html` 生成带 Mermaid 调用流图的架构页面。支持 Claude Code、Codex、OpenCode、Cursor、Gemini CLI、GitHub Copilot CLI、Aider、OpenClaw 等 15+ 主流 Agent 工具。PyPI 包名 `graphifyy`，通过 `uv tool install graphifyy` 安装。

**匹配能力：** 📊 代码图谱 · 🏗️ 架构梳理 · 🔍 调用流分析 · 📝 自动报告

---

## 2. context7 (57.1k ⭐)

**🔗** https://github.com/upstash/context7  
**🍴** Fork 2.7k | **🔄** Updated Jun 3, 2026  
**👤** Upstash — Serverless Data Platform 公司，提供 Redis/向量数据库/消息队列等云服务

> 为 LLM 和 AI 代码编辑器提供最新代码文档的上下文平台。解决 LLM 训练数据过时导致的代码幻觉问题——不再生成过时 API 和已弃用的用法。通过 MCP 服务器集成到 Cursor、Claude Code、Windsurf 等 AI 编辑器中，在提示词中加入 `use context7` 即可自动拉取目标库的最新文档和代码示例，注入 LLM 上下文。支持数千个开源库的实时文档索引。

**匹配能力：** 📝 实时文档上下文 · 🤖 MCP/Agent 集成 · 🔍 代码幻觉消除

---

## 3. Understand-Anything (56.3k ⭐)

**🔗** https://github.com/Lum1104/Understand-Anything  
**🍴** Fork 4.7k | **🔄** Updated Jun 4, 2026  
**👤** Lum1104 — 交互式代码知识图谱开发者，专注于让代码"可被看见而非 impress"

> Claude Code 插件，通过多 Agent 管线分析整个项目，构建包含每个文件、函数、类和依赖的知识图谱，并提供交互式可视化仪表盘来探索一切。支持 Claude Code、Codex、Cursor、Copilot、Gemini CLI 等主流平台。核心能力：结构化图谱探索（按架构层着色）、业务逻辑域视图（domains → flows → steps）、引导式导览（按依赖顺序学习代码）、语义搜索（"哪些部分处理认证？"）、Diff 影响分析（变更波及范围）、Persona 自适应 UI（根据角色调整细节密度）。还支持知识库分析（Karpathy-pattern LLM wiki）和多语言输出（中/日/韩/西/土/俄）。增量更新（只重分析变更文件），图谱为 JSON 可提交共享，大型图谱支持 git-lfs。

**匹配能力：** 📊 代码图谱 · 🏗️ 架构梳理 · 🔍 语义搜索 · 🎭 多角色 UI · 🌐 多语言

---

## 4. codegraph (46.4k ⭐)

**🔗** https://github.com/colbymchenry/codegraph  
**🍴** Fork 2.8k | **🔄** Updated Jun 4, 2026  
**👤** Colby McHenry — 15+ 年软件开发经验的独立开发者

> 预索引代码知识图谱，为 AI Agent 提供精准上下文。100% 本地运行，无需服务器、无需 API key。支持 Claude Code、Codex、Gemini CLI、Cursor、OpenCode、AntiGravity、Kiro、Hermes Agent 等主流平台。通过预建索引减少 token 消耗和工具调用次数，让 AI 更高效地理解代码库结构。

**匹配能力：** 📊 代码知识图谱 · ⚡ Token 优化 · 🤖 多 Agent 平台支持 · 🔒 本地优先

---

## 5. CLI-Anything (42.6k ⭐)

**🔗** https://github.com/HKUDS/CLI-Anything  
**🍴** Fork 4.0k | **🔄** Updated Jun 3, 2026  
**👤** HKUDS（香港大学数据科学实验室）— 学术+开源团队

> "今天的软件服务人类👨‍💻，明天的用户是 Agent🤖"——弥合 AI Agent 与世界软件的鸿沟。一行命令为任意软件生成 Agent 可用的 CLI 接口，使 Pi、OpenClaw、Cursor、Claude Code 等工具能直接操控各类应用。内置 CLI-Hub 社区注册表（`pip install cli-anything-hub`），支持浏览、安装、管理社区构建的 CLI 封装。支持预览、实时预览和轨迹循环，可让 Agent 产出实际制品：CAD 模型、3D 场景、图表、游戏画面、字幕等。已有 QGIS（GIS）、Obsidian、Safari、FreeCAD、Kdenlive、Unreal Insights 等数十个软件的 CLI 封装。

**匹配能力：** 🔌 软件→CLI 转化 · 🤖 Agent-Native · 📦 社区生态

---

## 6. GitNexus (41.9k ⭐)

**🔗** https://github.com/abhigyanpatwari/GitNexus  
**🍴** Fork 4.8k | **🔄** Updated Jun 4, 2026  
**👤** Abhigyan Patwari (Akon Labs) — 代码智能引擎开发者

> 为 Agent 上下文构建"代码神经系统"。将任意代码库索引为知识图谱——覆盖每个依赖、调用链、聚簇和执行流——然后通过智能工具暴露给 AI Agent，使其不再遗漏代码。提供两种使用模式：**CLI + MCP**（`npm install -g gitnexus`，本地索引仓库，通过 MCP 服务器连接 Cursor/Claude Code/Codex/Windsurf/OpenCode 等 Agent，使用 LadybugDB 持久化存储和 Tree-sitter 原生解析）和 **Web UI**（浏览器端可视化图谱探索 + AI 对话）。Bridge 模式可将两者打通。自称"Like DeepWiki, but deeper"——DeepWiki 帮你理解代码，GitNexus 让你分析代码，因为知识图谱追踪每一层关系而非仅描述。企业版支持 PR 爆炸半径分析、自动更新代码 Wiki、多仓库统一图谱。

**匹配能力：** 🏗️ 架构梳理 · 📊 模块拆解 · 🔍 代码图谱 · 🤖 MCP/Agent 集成

---

## 7. swagger-ui (28.8k ⭐)

**🔗** https://github.com/swagger-api/swagger-ui  
**🍴** Fork 9.3k | **🔄** Updated Jun 2, 2026  
**👤** SmartBear / Swagger 团队 — API 工具链行业标准制定者

> 从 Swagger/OpenAPI 规范自动生成交互式 API 文档界面。提供在线 "Try it out" 试用 API 调用、查看请求/响应模型、参数说明等功能，是 API 文档可视化的事实标准，几乎所有 RESTful 项目的标配。

**匹配能力：** 📝 API 文档可视化 · 🖥️ 交互式接口调试

---

## 8. google/python-fire (28.2k ⭐)

**🔗** https://github.com/google/python-fire  
**🍴** Fork 1.5k | **🔄** Updated Apr 1, 2026  
**👤** Google — Python Fire 是 Google 开源的 CLI 生成库

> 从任意 Python 对象自动生成命令行接口。无需装饰器、参数定义或配置文件，直接将函数、类、模块、字典甚至对象实例转为完整可用的 CLI——包括子命令、参数推断、帮助文档。是最快的"代码→CLI"转化路径。

**匹配能力：** 🔌 代码→CLI 转化 · ⚡ 极速原型

---

## 9. openapi-generator (26.4k ⭐)

**🔗** https://github.com/OpenAPITools/openapi-generator  
**🍴** Fork 7.6k | **🔄** Updated Jun 4, 2026  
**👤** OpenAPI Tools 社区 — OpenAPI 生态核心项目

> 给定 OpenAPI Spec（v2/v3），自动生成 API 客户端 SDK、服务端桩代码、文档和配置。支持 50+ 编程语言/框架，涵盖 Java/Python/TypeScript/Go/Ruby/C#/Rust 等主流语言。是 API 规范驱动开发的工业级标准工具，也是从 OpenAPI Spec 生成 CLI 客户端的首选方案。

**匹配能力：** 📝 API 文档生成 · 🔌 SDK/CLI 生成 · 📐 规范校验

---

## 10. tree-sitter (25.8k ⭐)

**🔗** https://github.com/tree-sitter/tree-sitter  
**🍴** Fork 2.7k | **🔄** Updated Jun 3, 2026  
**👤** Tree-sitter Community — 由 Max Brunsfeld（前 GitHub Atom 团队）创建，现为独立开源项目

> 增量解析器生成工具与解析库——几乎所有现代代码分析工具的底层基石。为源文件构建具体语法树（CST），并在源文件编辑时高效增量更新。设计目标：通用（能解析任意编程语言，200+ 语言 grammar 可用）、极快（每次击键都能解析）、鲁棒（即使存在语法错误仍能产出有用结果）、零依赖（纯 C 运行时，可嵌入任何应用）。提供 Rust/Wasm/Node/Python 等多语言绑定和 CLI 工具。GitNexus、graphify、Aider、Codebase-Memory 等上层工具均依赖 tree-sitter 做底层解析。是构建自定义代码理解管道的首选基础设施。

**匹配能力：** 🧱 底层解析基石 · 📊 AST/CST 构建 · 🔍 200+ 语言支持 · ⚡ 增量解析

---

## 11. code-review-graph (18.3k ⭐)

**🔗** https://github.com/tirth8205/code-review-graph  
**🍴** Fork 2.0k | **🔄** Updated May 25, 2026  
**👤** Tirth Patel — 代码图谱与 Token 优化领域开发者

> 停止烧 Token，开始智能审查。为 AI 编码工具构建本地代码知识图谱——用 Tree-sitter 解析仓库为 AST，存储为节点（函数/类/import）与边（调用/继承/测试覆盖）的图结构，通过 MCP 协议向 AI 助手提供精确上下文，使其只读取真正相关的代码。核心能力：**爆炸半径分析**——文件变更时追踪每个调用者、依赖方和相关测试，AI 只读这些文件而非扫描全项目。增量更新极快（2900 文件项目 <2秒），大型 Monorepo 中 27,700+ 文件被排除在审查上下文外，实际只读约 15 个文件。实测代码审查省 6.8× Token，日常编码任务省高达 49× Token。支持 Claude Code/Codex/Cursor/Gemini CLI/Kiro/GitHub Copilot 等平台，一条命令自动检测并配置所有支持的 AI 工具。

**匹配能力：** 📊 代码知识图谱 · 🔍 变更影响分析 · ⚡ Token 优化 · 🤖 MCP/多平台集成

---

## 12. swagger-codegen (17.8k ⭐)

**🔗** https://github.com/swagger-api/swagger-codegen  
**🍴** Fork 6.0k | **🔄** Updated May 19, 2026  
**👤** SmartBear / Swagger 团队

> 模板驱动代码生成引擎，解析 OpenAPI/Swagger 定义自动生成文档、API 客户端和服务端桩代码。多语言多框架支持，是 openapi-generator 的前身项目。两者功能高度重叠，新项目推荐优先用 openapi-generator。

**匹配能力：** 📝 API 文档 · 🔌 代码生成

---

## 13. semgrep (15.5k ⭐)

**🔗** https://github.com/semgrep/semgrep  
**🍴** Fork 955 | **🔄** Updated Jun 4, 2026  
**👤** Semgrep Inc.（前 r2c / Return To Corp）— 代码安全分析公司

> 面向代码的语义 grep。用**看起来像源代码的模式**查找 Bug 变体——不需要 AST、正则表达式或复杂 DSL。支持 30+ 语言（Apex/Bash/C/C++/C#/Go/Java/JavaScript/Kotlin/Python/Ruby/Rust/Swift/TypeScript 等）。用 `grep "2"` 只能匹配字符串 "2"，而 Semgrep 能匹配 `x=1; y=x+1` 中语义等价的 "2"。可自定义规则批量提取代码中的 API 调用模式、路由定义、安全漏洞。开源版限单函数/文件分析，企业版支持跨文件跨函数数据流分析。

**匹配能力：** 🔍 代码模式匹配 · 📊 API 调用批量提取 · 🛡️ 安全分析

---

## 14. codeql (9.7k ⭐)

**🔗** https://github.com/github/codeql  
**🍴** Fork 2.0k | **🔄** Updated Jun 3, 2026  
**👤** GitHub — 全球最大代码托管平台的官方分析引擎

> 代码查询语言与分析平台，驱动 GitHub Advanced Security 的代码扫描功能。将代码视为数据库，用类 SQL 的查询语言（QL）精准定位代码中的模式、漏洞和结构关系。包含标准库和数千个预置查询，支持 C/C++/C#/Go/Java/JavaScript/Python/Ruby/Swift。提供 VS Code 扩展、CLI 工具和 CI/CD 集成。可编写自定义查询提取 API 端点定义、路由表、调用链等结构化信息。开源用于开源项目分析，闭源项目需商业授权。

**匹配能力：** 🔍 代码结构查询 · 📊 API 端点提取 · 🏗️ 调用链分析

---

## 15. oclif (9.5k ⭐)

**🔗** https://github.com/oclif/oclif  
**🍴** Fork 355 | **🔄** Updated Jun 3, 2026  
**👤** Salesforce — Heroku CLI 背后的框架

> Node.js CLI 框架，用于生成、构建和发布命令行工具。插件化架构，支持多命令组织、自动帮助文档生成、TypeScript 原生支持、钩子系统。Heroku CLI、Salesforce CLI 等知名工具均基于 oclif 构建。适合将提取到的 API 信息封装成规范化的 CLI 工具产品。

**匹配能力：** 🔌 CLI 框架 · 📦 CLI 工具产品化

---

## 16. open-code-review (6.0k ⭐)

**🔗** https://github.com/alibaba/open-code-review  
**🍴** Fork 80 | **🔄** Updated Jun 4, 2026  
**👤** 阿里巴巴 — 源自阿里内部官方 AI 代码审查助手，服务数万开发者，识别百万级代码缺陷

> 开源 AI 代码审查 CLI。读取 Git diff，通过具备工具调用能力的 Agent 将变更文件发送给可配置 LLM，生成行级精度的结构化审查意见。核心设计：**确定性工程 × Agent 混合架构**——对不能出错的审查步骤用工程逻辑硬约束（精准文件选择、智能文件打包、细粒度规则匹配、外部定位与反思模块），对动态决策用 Agent（场景化提示词与工具集）。支持 workspace 模式、分支范围对比、单 commit 审查。可集成到 Claude Code（Plugin/Skill）、Codex 等编码 Agent 作为 slash command。支持 CI/CD 集成（GitHub Actions / GitLab CI），提供阿里官方规则集（NPE、线程安全、XSS、SQL 注入等）。Go 语言实现，通过 NPM 分发多平台二进制。

**匹配能力：** 🔍 AI 代码审查 · 🏗️ 确定性+Agent 混合架构 · 📐 规则匹配 · 🤖 CI/CD 集成

---

## 17. semble (5.0k ⭐)

**🔗** https://github.com/MinishLab/semble  
**🍴** Fork 200 | **🔄** Updated Jun 3, 2026  
**👤** Minish Lab — 两人开源实验室（pringled & stephantul），专注 NLP 与高效模型

> 面向 Agent 的快速精准代码搜索工具。比 grep+read 减少约 98% 的 token 消耗。为 AI 编码助手提供语义级代码搜索能力，让 Agent 能在大型代码库中精确定位相关代码片段，而不是暴力遍历文件。

**匹配能力：** 🔍 语义代码搜索 · ⚡ Token 优化 · 🤖 Agent 集成

---

## 18. OpenDeepWiki (3.3k ⭐)

**🔗** https://github.com/AIDotNet/OpenDeepWiki  
**🍴** Fork 421 | **🔄** Updated Jun 1, 2026  
**👤** AIDotNet — .NET AI 生态开源组织

> DeepWiki 开源版，基于 .NET 9 和 Semantic Kernel 开发。AI 驱动的代码知识管理平台：自动分析代码结构、理解核心概念、生成文档和知识图谱。支持 GitHub/GitLab/AtomGit/Gitee/Gitea 等多平台仓库，分钟级转化为知识库。自动生成 Mermaid 代码结构图。支持自定义 AI 模型和 API、多数据库（SQLite/PostgreSQL/MySQL/SqlServer）、多语言界面。提供对话式交互深入理解代码、MCP 协议集成（可作为 MCPServer 供其他 AI 模型调用）、SEO 友好的 Next.js 前端、数据微调平台。支持上传 ZIP/本地文件。

**匹配能力：** 🏗️ 架构文档 · 📊 模块识别 · 📝 自动文档生成 · 🤖 MCP 集成

---

## 19. joern (3.2k ⭐)

**🔗** https://github.com/joernio/joern  
**🍴** Fork 416 | **🔄** Updated Jun 3, 2026  
**👤** joern.io — 代码属性图领域开创者（源于 Saarland 大学研究）

> 开源代码分析平台，用于分析源码、字节码和二进制可执行文件。核心概念是**代码属性图（CPG）**——将 AST、控制流图、数据流图统一为跨语言的单一可查询图结构，存储在自定义图数据库中。使用 Scala DSL 查询语言挖掘代码。支持 C/C++/Java/JavaScript/Python/Kotlin/Binary。目标是为漏洞发现和静态程序分析研究提供基础工具。交互式 REPL 界面，Docker 部署支持，可作为服务器模式运行。

**匹配能力：** 📊 代码属性图 · 🔍 跨语言深度分析 · 🏗️ 调用链/数据流追踪

---

## 20. smart-doc (1.6k ⭐)

**🔗** https://github.com/TongchengOpenSource/smart-doc  
**🍴** Fork 297 | **🔄** Updated Dec 4, 2025  
**👤** 同程开源 — 专注 Java API 文档自动化

> Java API 文档生成工具，基于接口源码分析直接生成文档——完全零注解侵入，只需写标准 Javadoc 注释即可。基于源码的返回值结构自动推导能力强大，支持异步接口（Callable/Future/CompletableFuture）、JSR-303 参数校验规范。覆盖 Spring MVC/Spring Boot/WebFlux/Feign/JAX-RS 框架，以及 Apache Dubbo RPC、gRPC 协议。可导出 Markdown/HTML5/Word/Asciidoctor/Postman Collection/OpenAPI 3.0/JMeter 性能测试脚本等多种格式。支持加载外部源码（含 JAR 包）生成字段注释、错误码和数据字典导出、调试页面支持文件上传下载测试。

**匹配能力：** 📝 API 文档自动生成 · 🔍 源码级接口提取 · 📐 OpenAPI/Postman 输出

---

## 21. Redocly CLI (1.5k ⭐)

**🔗** https://github.com/Redocly/redocly-cli  
**🍴** Fork 217 | **🔄** Updated Jun 3, 2026  
**👤** Redocly — API 文档与设计平台公司

> 让 OpenAPI 开发变得简单的 CLI 工具。对任意标准进行 lint/校验，生成精美交互文档，预览 API 定义，打包多文件 OpenAPI 规范。适合在 API 提取后进行规范化校验和文档渲染。

**匹配能力：** 📐 OpenAPI 校验 · 📝 文档生成 · 🔍 规范 lint

---

## 22. CodeWiki (1.2k ⭐)

**🔗** https://github.com/FSoft-AI4Code/CodeWiki  
**🍴** Fork 183 | **🔄** Updated May 27, 2026  
**👤** FSoft AI4Code — 越南 FPT Software 旗下 AI 代码研究团队

> ACL 2026 论文开源项目——面向大规模代码库的整体结构化文档生成框架。采用动态规划启发的分层分解策略，支持任意规模代码库（实测 86K-1.4M LOC）。通过递归多 Agent 系统（cluster-analyzer → file-analyzer → doc-generator → validator）逐层分析：聚类→文件级分析→文档生成→交叉验证。支持 8 种编程语言（Python/Java/JavaScript/TypeScript/C++/C#/Go/Rust），可生成跨模块交互分析、Mermaid 架构图和可视化产物。支持多种 LLM 提供商（OpenAI/Anthropic/AWS Bedrock/Azure），也支持订阅模式（Claude Code/Codex CLI，无需 API key）。

**匹配能力：** 📝 仓库级文档生成 · 🏗️ 架构感知分析 · 🌐 8 语言支持 · 📊 跨模块交互

---

## 23. deepwiki-rs (1.0k ⭐)

**🔗** https://github.com/sopaco/deepwiki-rs  
**🍴** Fork 126 | **🔄** Updated May 16, 2026  
**👤** sopaco（姜萌）— Rust 开发者，关注去中心化与自动化

> 将代码变为清晰文档。几分钟内生成准确的技术文档和 AI 就绪的上下文——为人类团队和智能 Agent 完美结构化。Rust 实现的代码文档引擎，轻量高效。

**匹配能力：** 📝 代码文档生成 · 🏗️ 架构梳理 · ⚡ Rust 高性能

---

## 分类索引

### 🏗️ 代码图谱 & 架构分析
- [graphify](#1-graphify-590k-) — 代码/文档 → 可查询知识图谱 + 调用流
- [Understand-Anything](#3-understand-anything-514k-) — 多 Agent 管线构建交互式知识图谱 + 仪表盘
- [GitNexus](#5-gitnexus-413k-) — CLI+MCP 代码神经系统，Agent 集成
- [codegraph](#6-codegraph-399k-) — 预索引代码知识图谱，本地优先
- [tree-sitter](#10-tree-sitter-257k-) — 底层解析基石，200+ 语言 AST/CST
- [code-review-graph](#11-code-review-graph-180k-) — 本地代码图谱，爆炸半径分析
- [joern](#18-joern-32k-) — 代码属性图（CPG）分析平台
- [codeql](#14-codeql-97k-) — 代码查询语言，GitHub 官方
- [semgrep](#13-semgrep-154k-) — 语义 grep，多语言模式匹配

### 📝 API 提取 & 文档生成
- [context7](#2-context7-567k-) — LLM 实时代码文档上下文
- [smart-doc](#19-smart-doc-16k-) — Java 零侵入 API 文档，源码分析
- [OpenDeepWiki](#17-opendeepwiki-33k-) — AI 驱动仓库 → Wiki + MCP
- [deepwiki-rs](#23-deepwiki-rs-10k-) — Rust 代码文档引擎
- [CodeWiki](#22-codewiki-11k-) — ACL 2026 论文，仓库级文档生成
- [swagger-ui](#7-swagger-ui-288k-) — 交互式 API 文档标准
- [openapi-generator](#9-openapi-generator-263k-) — OpenAPI → SDK/CLI/文档
- [Redocly CLI](#20-redocly-cli-15k-) — OpenAPI lint + 文档渲染

### 🔌 CLI 转化 & 框架
- [CLI-Anything](#4-cli-anything-420k-) — 软件 → Agent-Native CLI
- [python-fire](#8-googlepython-fire-282k-) — Python 对象 → CLI
- [oclif](#15-oclif-95k-) — Node.js CLI 框架（Heroku/Salesforce）
- [swagger-codegen](#12-swagger-codegen-178k-) — Swagger → 代码/CLI

### 🔍 代码审查 & 搜索
- [open-code-review](#21-open-code-review-12k-) — 阿里开源 AI 代码审查，确定性+Agent 混合
- [semble](#16-semble-48k-) — Agent 语义代码搜索，省 98% token
- [code-review-graph](#11-code-review-graph-180k-) — 爆炸半径分析，省 6.8-49× token
- [codegraph](#6-codegraph-399k-) — 预索引图谱，减少工具调用

---

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
