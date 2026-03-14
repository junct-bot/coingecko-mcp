# Coingecko MCP Server

MCP server for Coingecko. Agent-ready API for Coingecko.

Hosted at [coingecko.mcp.junct.dev/mcp](https://coingecko.mcp.junct.dev/mcp). Free to use. No auth. No API key required.

Part of [Junct](https://junct.dev) — the agent-readiness layer for the crypto stack.

## Quick Start

Add to your MCP client config (Claude Desktop, Cursor, Windsurf):

```json
{
  "mcpServers": {
    "coingecko": {
      "url": "https://coingecko.mcp.junct.dev/mcp",
      "transport": "streamable-http"
    }
  }
}
```

## About

This MCP server is **deterministically generated** from the Coingecko API specification. Every tool maps 1:1 to a real API endpoint — no hallucinated endpoints, no phantom tools.

- **Protocol:** Coingecko
- **Endpoint:** `https://coingecko.mcp.junct.dev/mcp`
- **Transport:** Streamable HTTP
- **Auth:** None required
- **Documentation:** [coingecko.mcp.junct.dev/llms.txt](https://coingecko.mcp.junct.dev/llms.txt)
- **Server card:** [coingecko.mcp.junct.dev/.well-known/mcp/server.json](https://coingecko.mcp.junct.dev/.well-known/mcp/server.json)

## Links

- [Junct Dashboard](https://junct.dev/servers/coingecko)
- [llms.txt](https://coingecko.mcp.junct.dev/llms.txt)
- [agents.md](https://coingecko.mcp.junct.dev/agents.md)
- [OpenAPI spec](https://coingecko.mcp.junct.dev/openapi.json)

## Keywords

Coingecko, MCP server, DeFi, AI agent, agent-ready API, crypto tools, Model Context Protocol, hosted MCP
