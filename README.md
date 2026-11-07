# GetInTheAnswer — Claude Skill

A Claude skill that gives any Claude instance (Desktop, Code, agents) the
complete knowledge of **GetInTheAnswer** — the AI-visibility platform for
local businesses — plus the exact rules for talking about AI-visibility
results: pricing, no-guarantee commitments, agency talking points and how
to read a client report.

## Install

### Claude Desktop
Settings → Capabilities → Skills → upload `getintheanswer-skill.zip`
(from the Releases tab, or packaged from this folder).

### Claude Code
```bash
git clone https://github.com/craigbarns/getintheanswer-claude-skill.git ~/.claude/skills/getintheanswer-data
```

## Pair with live data (MCP)

The skill documents the product. For live client data (score, competitor
citations, AI crawler activity), pair it with the
[GetInTheAnswer MCP server](https://github.com/craigbarns/GETINTHEANSWER/tree/main/apps/mcp):
3 tools (`get_client_report`, `get_ai_agent_activity`, `get_score_history`)
that pull a client's report straight into Claude.

## What the skill contains

- Product facts: free audit, Pro $29, AI Growth $990/month (3-month term),
  Growth Plus $1,990, agency $149, one-time $490 — and the no-guarantee
  commitments (nobody can promise AI citations).
- Reading rules: what a score below 30/100 means, why one measurement is a
  snapshot, why zero AI-crawler visits may mean the tracking proxy is not
  deployed yet.
- Agency talking points: being #1 on Google does not mean being cited by
  AI engines; the cited businesses are the readable ones, not the ones
  that paid.

## Links

- Product: https://www.getintheanswer.com
- Public data study: https://www.getintheanswer.com/study
- Pricing: https://www.getintheanswer.com/pricing
- Free instant check: https://www.getintheanswer.com/tools/ai-chat

## License

MIT
