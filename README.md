# ASOMobile plugins for Claude Code

Official plugin marketplace of [ASOMobile](https://asomobile.net): App Store and Google Play ASO data for AI agents.

| Plugin | What it does |
|---|---|
| [`asomobile`](plugins/asomobile/) | Connects Claude Code to the ASOMobile MCP server (keyword metrics, app indexing, competitors, top charts, reviews, Apple Search Ads, Keyword Monitor) and adds six ASO skills: keyword research, competitor audit, metadata review, market expansion, weekly report, Apple Search Ads planning. |

## Install

```bash
claude plugin marketplace add asomobile/claude-plugins
claude plugin install asomobile@asomobile
```

You will be asked for your ASOMobile API token ([API Dashboard](https://app.asomobile.net/api-dashboard)). Other MCP clients (Cursor, VS Code, Codex, Claude API) can use the same server directly: see [MCP server for AI agents](https://api.asomobile.net/mcp-server-for-ai-agents-2515048m0).

## License

MIT. Store listings, reviews and other data returned by the tools belong to their respective owners and are subject to the [ASOMobile Terms of Use](https://app.asomobile.net/assets/terms/Terms%20of%20Use%20-%20ASOMobile.pdf).
