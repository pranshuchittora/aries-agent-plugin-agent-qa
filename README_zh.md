# Awesome Agent Plugin [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> 🤖 智能体插件与 MCP 服务精选优质列表 —— 赋予 AI 智能体连接现实世界的“手和脚”。

[English](./README.md) | 简体中文

---

## 📅 目录
- [🏛️ 官方与框架生态](#官方与框架生态)
- [🌐 网页与搜索](#网页与搜索)
- [💻 开发者工具与代码执行](#开发者工具与代码执行)
- [📊 数据库与存储](#数据库与存储)
- [🔧 办公与协同](#办公与协同)
- [⚙️ 协议与 SDK](#协议与-sdk)
- [🤝 贡献指南](#贡献指南)

---

## 🏛️ 官方与框架生态
*各大智能体框架的官方工具集与标准市场。*

- [LangChain Community Tools](https://github.com/langchain-ai/langchain/tree/master/libs/community/langchain_community/tools) - LangChain 丰富的内置社区工具生态。 `[LangChain]` `[Python/TS]`
- [LlamaIndex Tools (LlamaHub)](https://llamahub.ai/) - LlamaIndex 数据加载器与工具的官方中心。 `[LlamaIndex]` `[Python]`
- [MCP Servers Official Registry](https://github.com/modelcontextprotocol/servers) - Anthropic 官方维护的 MCP 参考服务端示例。 `[MCP]` `[Python/TS]`

## 🌐 网页与搜索
*为智能体提供实时联网访问与高级网页爬取解析能力。*

- [Tavily AI](https://tavily.com/) - 专为大语言模型和 RAG 工作流优化的联网搜索引擎。 `[Any Framework]` `[API]`
- [Jina Reader](https://jina.ai/reader/) - 将任意网页 URL 转换为干净、适合 LLM 阅读的 Markdown。 `[Any Framework]` `[API]`
- [Firecrawl](https://github.com/mendableai/firecrawl) - 仅需一次 API 调用即可将整个网站转为结构化数据或 Markdown。 `[Any Framework]` `[TypeScript]`
- [Brave Search MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/brave-search) - 使用 Brave Search API 为模型提供安全的联网搜索。 `[MCP]` `[TypeScript]`

## 💻 开发者工具与代码执行
*用于安全执行代码、集成 Git 仓库以及辅助日常开发流的插件。*

- [Agent QA](https://github.com/vostride/agent-qa) - 通过 MCP 工具以自然语言编写、运行 Web、Android 与 iOS 测试并分析失败原因；源码可见，采用 FSL-1.1-ALv2 许可。 `[MCP]` `[TypeScript]`
- [E2B Sandbox](https://github.com/e2b-dev/E2B) - 供 AI 智能体安全运行未信任代码的云端隔离沙箱环境。 `[Any Framework]` `[Python/TS]`
- [GitHub MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/github) - 允许智能体审查代码、管理 Issue/PR 以及提交 Commit。 `[MCP]` `[TypeScript]`
- [GitLab Server](https://github.com/modelcontextprotocol/servers/tree/main/src/gitlab) - 集成 GitLab 覆盖代码库管理、Issue 追踪与 CI/CD 审查。 `[MCP]` `[TypeScript]`

## 📊 数据库与存储
*允许智能体安全地查询、审查和管理持久化数据层的连接器。*

- [PostgreSQL MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres) - 针对 PostgreSQL 的安全数据库架构审查与 SQL 查询。 `[MCP]` `[Python]`
- [Sqlite MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite) - 本地 SQLite 数据库交互层，支持架构分析与 SQL 执行。 `[MCP]` `[Python]`
- [Axiom MCP](https://github.com/axiomhq/mcp-server-axiom) - 通过 Axiom 直接查询和分析日志与事件数据。 `[MCP]` `[Go]`

## 🔧 办公与协同
*将智能体带入日常企业工作流、即时通讯以及文档管理系统。*

- [Google Drive & Docs MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/gdrive) - 读取和检索 Google 云端硬盘内的文档与元数据。 `[MCP]` `[TypeScript]`
- [Slack Tool Integration](https://github.com/langchain-ai/langchain/tree/master/libs/community/langchain_community/tools/slack) - 允许 LLM 发送消息、读取频道并管理 Slack 工作流。 `[LangChain]` `[Python]`
- [Notion Toolkit](https://github.com/run-llama/llama_index/tree/main/llama-index-integrations/tools/llama-index-tools-notion) - 无缝同步和操作 Notion 工作区内的数据与页面。 `[LlamaIndex]` `[Python]`

## ⚙️ 协议与 SDK
*用于构建智能体插件和工具的核心协议与基础设施。*

- [Model Context Protocol (MCP)](https://modelcontextprotocol.io/) - Anthropic 推出的用于连接 AI 模型与数据源、工具的开放标准协议。
- [MCP TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk) - 用于实现 MCP 客户端和官方 TypeScript SDK。
- [MCP Python SDK](https://github.com/modelcontextprotocol/python-sdk) - 用于构建自定义 MCP 集成的官方 Python SDK。

---

## 🤝 贡献指南
欢迎提交贡献！如果你有优质的智能体插件或 MCP 服务想分享，请遵循以下步骤：
1. Fork 本项目。
2. 创建你的特性分支 (`git checkout -b feature/AmazingPlugin`)。
3. 提交你的修改 (`git commit -m 'Add some AmazingPlugin'`)。
4. 推送到分支 (`git push origin feature/AmazingPlugin`)。
5. 发起 Pull Request。

请确保链接有效，并遵循格式：`[名称](链接) - 简介。 [框架] [语言]`

---

## 📄 开源协议
本项目基于 CC0-1.0 Universal 许可协议开源。详情请参阅 `LICENSE` 文件。
