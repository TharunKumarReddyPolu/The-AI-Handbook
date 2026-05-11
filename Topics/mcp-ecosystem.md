# 🔌 MCP Ecosystem

> The **Model Context Protocol (MCP)** is an open standard for connecting AI models to external tools and data sources. Think of it as **USB-C for AI** — one protocol to connect everything.

---

## 🔑 Key Concepts

- **MCP Server** — A service that exposes tools, resources, or data to AI models via the MCP standard
- **MCP Client/Host** — The AI application (e.g., Claude, Cursor, VS Code) that connects to MCP servers
- **Tools** — Functions that an AI can invoke through MCP (e.g., search the web, query a database)
- **Resources** — Data sources an AI can read via MCP (e.g., files, documentation, database schemas)

---

## 🛠️ Registries & Servers

| Resource | Description |
|---|---|
| **[MCP.so](https://mcp.so/)** | MCP server and client registry |
| **[MCP Market](https://mcpmarket.com/)** | Marketplace for MCP servers |
| **[Context7 (Upstash)](https://github.com/upstash/context7#installation)** | Updated docs and context for LLMs via MCP |
| **[Anthropic MCP Spec](https://modelcontextprotocol.io/)** | Official MCP specification and documentation |
| **[MCP Servers (GitHub)](https://github.com/modelcontextprotocol/servers)** | Official repository of reference MCP server implementations |
| **[Smithery](https://smithery.ai/)** | MCP server registry and discovery platform |
| **[Tavily MCP](https://github.com/tavily-ai/tavily-mcp)** | Real-time web search MCP server for grounding AI |
| **[Playwright MCP](https://github.com/microsoft/playwright-mcp)** | Browser automation MCP server by Microsoft |

---

> 💡 **Why MCP matters**: Instead of building custom integrations for every tool, MCP lets AI models talk to databases, APIs, and file systems through a standard protocol. It's becoming the backbone of the AI agent ecosystem.

---

## 💡 Pro Tips

- **Context7** is essential for keeping your AI's code documentation up to date
- **Smithery** and **MCP.so** are the best places to discover community-built MCP servers
- **Playwright MCP** gives your AI the ability to browse and interact with web pages autonomously
- The protocol now supports **Streamable HTTP** for remote servers and **OAuth 2.1** for enterprise auth

---

[← Back to Handbook](../README.md)
