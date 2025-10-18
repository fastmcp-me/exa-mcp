[![Add to Cursor](https://fastmcp.me/badges/cursor_dark.svg)](https://fastmcp.me/MCP/Details/541/exa-search)
[![Add to VS Code](https://fastmcp.me/badges/vscode_dark.svg)](https://fastmcp.me/MCP/Details/541/exa-search)
[![Add to Claude](https://fastmcp.me/badges/claude_dark.svg)](https://fastmcp.me/MCP/Details/541/exa-search)
[![Add to ChatGPT](https://fastmcp.me/badges/chatgpt_dark.svg)](https://fastmcp.me/MCP/Details/541/exa-search)
[![Add to Codex](https://fastmcp.me/badges/codex_dark.svg)](https://fastmcp.me/MCP/Details/541/exa-search)
[![Add to Gemini](https://fastmcp.me/badges/gemini_dark.svg)](https://fastmcp.me/MCP/Details/541/exa-search)

# exa-mcp

MCP server for [Exa](https://exa.ai/) Search API.

This project is sponsored by [ChatWise](https://chatwise.app), an all-in-one LLM chatbot with first-class MCP support.

## Usage

Get your API Key [here](https://dashboard.exa.ai/api-keys).

### Configure manually

```bash
# stdio server
npx -y exa-mcp

# sse server
npx -y exa-mcp --sse
```

Environment variables:

```
EXA_API_KEY=<your-api-key>
```

### JSON config

```json
{
  "mcpServers": {
    "exa": {
      "command": "npx",
      "args": ["-y", "exa-mcp"],
      "env": {
        "EXA_API_KEY": "<your-api-key>"
      }
    }
  }
}
```

## License

MIT.
