# Install Gulf AI Deals MCP
Server: `https://gulfaideals.com/mcp` (streamable HTTP, no auth)

- **Cursor**: [Install](cursor://anysphere.cursor-deeplink/mcp/install?name=gulf-ai-deals&config=eyJ1cmwiOiAiaHR0cHM6Ly9ndWxmYWlkZWFscy5jb20vbWNwIn0=)  — or `~/.cursor/mcp.json`: `{"mcpServers":{"gulf-ai-deals":{"url":"https://gulfaideals.com/mcp"}}}`
- **VS Code**: [Install](vscode:mcp/install?%7B%22name%22%3A%20%22gulf-ai-deals%22%2C%20%22type%22%3A%20%22http%22%2C%20%22url%22%3A%20%22https%3A//gulfaideals.com/mcp%22%7D)  — or `code --add-mcp '{"name":"gulf-ai-deals","type":"http","url":"https://gulfaideals.com/mcp"}'`
- **Windsurf** (`~/.codeium/windsurf/mcp_config.json`): `{"mcpServers":{"gulf-ai-deals":{"serverUrl":"https://gulfaideals.com/mcp"}}}`
- **Cline** (cline_mcp_settings.json): `{"mcpServers":{"gulf-ai-deals":{"type":"streamableHttp","url":"https://gulfaideals.com/mcp"}}}`
- **Claude Code**: `claude mcp add --transport http gulf-ai-deals https://gulfaideals.com/mcp`
- **Claude Desktop**: open `gulf-ai-deals.mcpb from Releases`, or Settings > Connectors > Add custom connector.
- **Gemini CLI**: `gemini mcp add --transport http gulf-ai-deals https://gulfaideals.com/mcp`
- **Codex**: `codex mcp add gulf-ai-deals --url https://gulfaideals.com/mcp`
