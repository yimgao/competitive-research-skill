# Competitive Research Assistant — Hermes Agent Skill

A Hermes Agent skill for automated competitor research, product comparison, and market analysis.

## Overview

This skill lets you research competitors, compare products, and produce structured analysis reports — all within Hermes Agent. Instead of manually visiting competitor sites and copy-pasting into a doc, just describe what you want to research and Hermes does the legwork: searches the web, browses competitor pages, extracts key features/pricing/reviews, and compiles everything into a clean Markdown report.

## Installation

```bash
# Install from the skills hub (once published)
hermes skills install competitive-research

# Or install directly from this repo
hermes skills install https://raw.githubusercontent.com/yimgao/competitive-research-skill/main/SKILL.md
```

## Usage

Load the skill:

```bash
hermes -s competitive-research
```

Then ask Hermes questions like:

- *"Research Confluence as a documentation tool"* — single competitor deep dive
- *"Compare Notion, Confluence, and Coda"* — multi-product comparison
- *"Analyze the AI coding assistant market"* — market landscape + SWOT
- *"Monitor competitor news about Windsurf"* — recurring monitoring (pair with cron)

## What It Covers

| Scenario | What Hermes does |
|----------|-----------------|
| **Single competitor deep dive** | Searches web, browses website + reviews, compiles full profile |
| **Multi-product comparison** | Researches each product, creates feature comparison table, gives recommendations |
| **Market landscape analysis** | Identifies key players, positioning, SWOT, market trends |
| **Competitor monitoring** | With cron jobs, checks for news/updates on a schedule |

## Report Structure

Each report includes:

- **Executive Summary** — key findings at a glance
- **Competitor Overview Table** — high-level comparison
- **Detailed Analysis** — per-competitor: features, pricing, strengths, weaknesses
- **Comparison Table** — feature-by-feature side-by-side
- **Recommendations** — best fit for different scenarios
- **Sources** — links to all sources used

## Requirements

- Hermes Agent (any version with `web_search` and `browser` tools enabled)
- Web toolset enabled: `hermes tools enable web`

## License

MIT
