# venture-suite

![npm](https://img.shields.io/npm/v/@veyralabs/venture-suite) ![license](https://img.shields.io/badge/license-MIT-green)

Venture Intelligence pack for Claude Code. Validate startup and SaaS ideas before building - using real evidence from HN, Reddit, GitHub, and web search. No API keys required.

Part of [VeyraSkills](https://github.com/veyralabsgroup/veyraskills) by [VeyraLabs](https://github.com/veyralabsgroup).

## Install

```bash
npx @veyralabs/skills install venture-suite
```

## Skills included

| Skill | What it does |
|-------|-------------|
| [venture-analyst](./venture-analyst/SKILL.md) | Four-phase idea validation: problem discovery, competitor intelligence, validation experiments, Bull/Bear/Judge verdict |

## Usage

```
/venture-analyst A SaaS tool for X targeting Y customers
```

## Zero friction design

No API keys. No paid accounts. No setup beyond `npm install`.

The skill collects evidence from public sources (HN Algolia, Reddit, GitHub, DuckDuckGo, Google Trends) and auto-detects available enhancements silently - if you have Docker installed, it can launch SearXNG automatically for better search coverage.

## License

MIT. Built by [VeyraLabs](https://veyralabs.com).
