# ASOMobile plugin for Claude Code

App Store and Google Play ASO data inside Claude: keyword traffic and competition, app indexing, competitors, top charts, reviews, Apple Search Ads, organic download estimates and Keyword Monitor. The plugin connects Claude Code to the official [ASOMobile MCP server](https://api.asomobile.net/mcp-server-for-ai-agents-2515048m0) (29 tools, one per public API method) and adds six ASO skills:

- `/asomobile:aso-keyword-research` — build or expand a semantic core for an app;
- `/asomobile:aso-competitor-audit` — compare an app with its competitors and find keyword gaps;
- `/asomobile:aso-metadata-review` — audit and rewrite store metadata against target keywords;
- `/asomobile:aso-market-expansion` — choose new countries and plan a localisation;
- `/asomobile:aso-weekly-report` — weekly or monthly status report for a tracked app: ranks, charts, reviews;
- `/asomobile:asa-keyword-planning` — Apple Search Ads keyword plan from competitors' paid keywords.

## Install

```bash
claude plugin marketplace add asomobile/claude-plugins
claude plugin install asomobile@asomobile
```

Claude Code asks for your **ASOMobile API token** once. Get it in your account at [API Dashboard](https://app.asomobile.net/api-dashboard); API access is included in paid plans (see [Pricing](https://asomobile.net/en/pricing/)). The token is stored in the OS credential store and sent only to `https://mcp.asomobile.net/mcp`, which forwards it to the ASOMobile API. Every data call spends the API tokens of your plan exactly like a direct API request.

## Try it

- "Check the keyword *taxi* in the US App Store."
- "Which keywords is id284882215 indexed for in Germany? Show the top 50 by traffic."
- "Run a competitor audit for com.example.app on Google Play, US."
- "Review the metadata of id284882215 for the UK store."

## Update

```bash
claude plugin update asomobile@asomobile
```

## Support

Documentation: https://api.asomobile.net · Questions and issues: https://help.asomobile.net/en/ or the issue tracker of this repository.
