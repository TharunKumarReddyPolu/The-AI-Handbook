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
| **[Glama MCP Directory](https://glama.ai/mcp/servers)** | Searchable directory to discover, inspect, and compare thousands of MCP servers |
| **[GitHub MCP Server](https://github.com/github/github-mcp-server)** | Official GitHub MCP server for inspecting repos, managing issues/PRs, and automating Actions |
| **[Firecrawl MCP](https://github.com/firecrawl/firecrawl-mcp-server)** | Official Firecrawl MCP server for web scraping, crawling, and search |
| **[Supabase MCP](https://github.com/supabase/mcp)** | Official Supabase MCP server for querying databases, managing schemas, and inspecting projects |
| **[Cloudflare MCP](https://github.com/cloudflare/mcp)** | Official Cloudflare MCP server for managing Workers, D1, R2, and edge infrastructure |
| **[Figma MCP Server](https://developers.figma.com/docs/figma-mcp-server/)** | Official Figma MCP server giving coding agents direct design context from Figma frames |
| **[Sentry MCP](https://mcp.sentry.dev/)** | Official Sentry MCP server for querying production errors, traces, and issue context |
| **[Hugging Face MCP Server](https://github.com/huggingface/hf-mcp-server)** | Official Hugging Face MCP server connecting agents to Hub models, datasets, Spaces, and papers |
| **[AWS Labs MCP Servers](https://awslabs.github.io/mcp/)** | Official suite of AWS MCP servers for architecture, documentation, CDK/Terraform, and cloud operations ([GitHub](https://github.com/awslabs/mcp)) |
| **[Microsoft MCP Catalog](https://github.com/microsoft/mcp)** | Official Microsoft & Azure MCP server collection for cloud, DevOps, and enterprise data |
| **[Google MCP Directory](https://github.com/google/mcp)** | Official Google Cloud and Workspace MCP servers for BigQuery, Maps, and developer workflows |
| **[GitLab MCP Server](https://docs.gitlab.com/user/model_context_protocol/mcp_server/)** | Official GitLab MCP server for issues, merge requests, pipelines, and repository context |
| **[Atlassian Rovo MCP](https://www.atlassian.com/platform/rovo-mcp)** | Official Atlassian MCP server connecting AI agents to Jira issues and Confluence pages |
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

## 🎯 When to Use What

| Need | Best MCP Server / Registry |
|---|---|
| Discover & browse community MCP servers | MCP.so, Smithery, Glama MCP Directory, MCP Market |
| Up-to-date library & framework docs | Context7 |
| Git, PRs, CI/CD & issue tracking | GitHub MCP Server, GitLab MCP Server, Atlassian Rovo MCP |
| Databases, backends & cloud infra | Supabase MCP, Cloudflare MCP, AWS Labs MCP, Microsoft MCP |
| Browser automation & web scraping | Playwright MCP, Firecrawl MCP, Tavily MCP |
| Design-to-code & production debugging | Figma MCP Server, Sentry MCP |

---

[← Back to Handbook](../README.md)
