# Loxo Plugin for Claude Code and Cowork

Search candidates, review pipelines, prep outreach, and log activities in [Loxo ATS](https://loxo.co) — powered by the Loxo MCP Server.

## Skills

| Skill | What it does |
|---|---|
| `candidate-sourcing` | Search Loxo for candidates by title, specialty, or keyword |
| `pipeline-review` | See all candidates in a job's pipeline by stage, flag stalled records |
| `candidate-brief` | One-page brief on any candidate before a call or submission |
| `outreach-prep` | Draft a tailored outreach message and log it on approval |
| `log-activity` | Record calls, emails, notes, and LinkedIn touches against a candidate |

## Installation

### Prerequisites
- Loxo API key and agency slug (from your Loxo account settings)

### Claude Code

```bash
# Add this plugin
claude plugin marketplace add nickm248/loxo-mcp-server

# Install the plugin
claude plugin install loxo@loxo-mcp-server
```

Or install the MCP server directly via Smithery:

```bash
npx -y @smithery/cli install loxo-mcp-server --client claude
```

### Environment Variables

```
LOXO_API_KEY=your_api_key
LOXO_AGENCY_SLUG=your_agency_slug
LOXO_DOMAIN=app.loxo.co
```

## License

MIT
