# Awesome Agent Plugin [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome plugins, tools, markets, and MCP (Model Context Protocol) servers to empower AI Agents with hands and feet.

🌎 **English** | [简体中文](./README_zh.md)

---

🤖 **AI Agents** are powerful, but they become extraordinary when they can interact with the real world. This repository aims to collect the best plugins, tools, and servers that allow Agents to browse the web, write code, manage productivity apps, and execute tasks across frameworks.

---

## 📅 Contents
- [🏛️ Official & Framework Ecosystems](#-official--framework-ecosystems)
- [🌐 Web & Search](#-web--search)
- [💻 Developer Tools & Code Execution](#-developer-tools--code-execution)
- [📊 Databases & Storage](#-databases--storage)
- [🔧 Productivity & Collaboration](#-productivity--collaboration)
- [⚙️ Protocol & SDKs](#-protocol--sdks)
- [🤝 Contributing](#-contributing)

---

## 🏛️ Official & Framework Ecosystems
*Standard plugin marketplaces and official toolsets from major Agent frameworks.*

- [LangChain Community Tools](https://github.com/langchain-ai/langchain/tree/master/libs/community/langchain_community/tools) - The rich built-in tool ecosystem for LangChain integrations. `[LangChain]` `[Python/TS]`
- [LlamaIndex Tools (LlamaHub)](https://llamahub.ai/) - A central hub for LlamaIndex data loaders, tools, and agent datasets. `[LlamaIndex]` `[Python]`
- [MCP Servers Official Registry](https://github.com/modelcontextprotocol/servers) - Anthropic's official collection of reference Model Context Protocol servers. `[MCP]` `[Python/TS]`

## 🌐 Web & Search
*Plugins that grant agents real-time web access and advanced scraping capabilities.*

- [Tavily AI](https://tavily.com/) - A search engine specifically optimized for LLMs and RAG workflows. `[Any Framework]` `[API]`
- [Jina Reader](https://jina.ai/reader/) - A simple tool that converts any URL into clean, LLM-friendly Markdown. `[Any Framework]` `[API]`
- [Firecrawl](https://github.com/mendableai/firecrawl) - Turns entire websites into structured data or markdown with a single API call. `[Any Framework]` `[TypeScript]`
- [Brave Search MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/brave-search) - Provides secure web search capabilities to LLMs using Brave Search API. `[MCP]` `[TypeScript]`

## 💻 Developer Tools & Code Execution
*Plugins for secure code execution, Git integration, and development workflows.*

- [Agent QA](https://github.com/vostride/agent-qa) - MCP tools for authoring, running, and triaging natural-language web, Android, and iOS tests; source-available under FSL-1.1-ALv2. `[MCP]` `[TypeScript]`
- [E2B Sandbox](https://github.com/e2b-dev/E2B) - Secure, isolated cloud sandboxes for AI agents to run untrusted code. `[Any Framework]` `[Python/TS]`
- [GitHub MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/github) - Enables agents to inspect repositories, manage issues, handle PRs, and commit code. `[MCP]` `[TypeScript]`
- [GitLab Server](https://github.com/modelcontextprotocol/servers/tree/main/src/gitlab) - GitLab integration for issue tracking, repository management, and CI/CD inspection. `[MCP]` `[TypeScript]`

## 📊 Databases & Storage
*Connectors allowing agents to query, inspect, and manage data layers securely.*

- [PostgreSQL MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres) - Safe database inspecting and querying capabilities for PostgreSQL. `[MCP]` `[Python]`
- [Sqlite MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite) - Interaction layer for local SQLite databases, enabling schema inspection and SQL execution. `[MCP]` `[Python]`
- [Axiom MCP](https://github.com/axiomhq/mcp-server-axiom) - Query and analyze your log and event data directly through Axiom. `[MCP]` `[Go]`

## 🔧 Productivity & Collaboration
*Bring agents into daily enterprise workflows, messaging, and documentation systems.*

- [Google Drive & Docs MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/gdrive) - MCP Server to read and search metadata/content inside Google Drive. `[MCP]` `[TypeScript]`
- [Slack Tool Integration](https://github.com/langchain-ai/langchain/tree/master/libs/community/langchain_community/tools/slack) - Send messages, read channels, and manage Slack workspace workflows via LLM. `[LangChain]` `[Python]`
- [Notion Toolkit](https://github.com/run-llama/llama_index/tree/main/llama-index-integrations/tools/llama-index-tools-notion) - Seamless data syncing and page creation inside Notion workspaces. `[LlamaIndex]` `[Python]`

## ⚙️ Protocol & SDKs
*Core protocols and infrastructure used to build agent plugins and tools.*

- [Model Context Protocol (MCP)](https://modelcontextprotocol.io/) - An open standard protocol created by Anthropic for connecting AI models to data sources and tools.
- [MCP TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk) - The official TypeScript SDK for implementing MCP clients and servers.
- [MCP Python SDK](https://github.com/modelcontextprotocol/python-sdk) - The official Python SDK for building custom MCP integrations.

---

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place! If you have an awesome agent plugin, tool, or MCP server to share, please check out the steps below:

1. Fork the Project.
2. Create your Feature Branch (`git checkout -b feature/AmazingPlugin`).
3. Commit your Changes (`git commit -m 'Add some AmazingPlugin'`).
4. Push to the Branch (`git push origin feature/AmazingPlugin`).
5. Open a Pull Request.

Please make sure the link is valid and follow the format: `[Name](Link) - Description. [Framework] [Language]`

---

## 📄 License
Distributed under the CC0-1.0 Universal License. See `LICENSE` for more information.
