# Gulf AI Hub — MCP server & AI plugins

Read-only, no-auth MCP server for **GCC AI deals, AI agent use cases and Arabic-capable AI tools** from [gulfaideals.com](https://gulfaideals.com).

**Endpoint:** `https://gulfaideals.com/mcp` (streamable HTTP)
**Tools:** `search_deals`, `search_use_cases`, `search_tools`, `get_item`

## Install
- **Claude Code:** `/plugin marketplace add gulfaideals/gulf-ai-hub-mcp` then `/plugin install gulf-ai-deals@gulf-ai-deals`
- **Gemini CLI:** `gemini extensions install https://github.com/gulfaideals/gulf-ai-hub-mcp`
- **Claude Desktop:** download `gulf-ai-deals.mcpb` from [Releases](https://github.com/gulfaideals/gulf-ai-hub-mcp/releases) and open it, or add a custom connector with the URL above.
- **Cursor / VS Code / Windsurf / Cline / Codex:** see [INSTALL.md](INSTALL.md).
- **ChatGPT:** Developer mode → add app with the URL above (no auth); Custom GPT config in [chatgpt/](chatgpt/).

Example prompts: "Latest Saudi AI data-center deals in 2026", "AI agent use cases in UAE banking", "Best Arabic speech-to-text tools".

Privacy: [privacy.md](privacy.md). Code MIT; data CC BY 4.0. Site source: [gulfaideals/gulf-ai-hub](https://github.com/gulfaideals/gulf-ai-hub).
