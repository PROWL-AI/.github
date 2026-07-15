# Prowl — the MCP that turns any AI agent into a research analyst

**[prowl.chat](https://prowl.chat)** · one MCP endpoint, **385 market- & competitive-intelligence tools** for your agent.

Connect any agent — Cursor, Claude, or your own stack — to `https://prowl.chat/mcp` and it instantly gains real market data: SEO & backlinks, 60+ SERP engines, ad-library intelligence, funnels, reviews, pricing, and AI/LLM mention tracking across ChatGPT / Claude / Gemini / Perplexity. Prowl plans → executes a DAG of tool calls → composes a ready-to-execute strategy report. **Decisions, not dashboards.**

Prowl replaces 10–30 hours of manual research and spreadsheet work: it discovers relevant competitors, pulls their ads, funnels, SEO signals, and customer reviews, then compares everything across the market to surface what's actually working — winning offers, messaging, creative angles, and conversion mechanics.

## Start hunting

1. Get a `prowl_…` API key at **[prowl.chat](https://prowl.chat)**.
2. Point your MCP client at `https://prowl.chat/mcp` with `Authorization: Bearer <key>`.
3. Call `prowl_list_tools` / `prowl_search_tools`, or run `prowl_analyze` for a full hunt.

**Fastest path — install the skill.** Hand your coding agent the install skill and it wires up the client config + token file itself:

```bash
claude plugin marketplace add https://github.com/PROWL-AI/prowl-skill
claude plugin install prowl@prowl
```

→ **Skill repo: [github.com/PROWL-AI/prowl-skill](https://github.com/PROWL-AI/prowl-skill)** — the installable Claude Code / Codex plugin (namespaced `/prowl:*` skill + hosted MCP config).


## What's inside

- **385 tools across 14 providers** — DataForSEO, SearchAPI (60+ engines), SerpApi, Firecrawl, Exa, Perplexity, Gemini, SpyFu, Foreplay (ad library), Apify, plus a proprietary on-page + AI-readiness auditor.
- **~15 public MCP tools** front the whole catalog — `prowl_analyze`, `prowl_call_tool`, `prowl_search_tools`, `prowl_generate_artifact`, `prowl_export_report`, and more.
- **Universal Research Engine** — a typed evidence ledger with adversarial verification and gap-fill, so reports cite hard numbers instead of guesses.
- **Playbook-shaped reports** — persona-tuned report shapes for common intelligence missions.

---

*Prowl briefs like a covert intelligence operator, not a SaaS dashboard. Stop "researching" — start hunting.* → **[Get API key](https://prowl.chat)**
