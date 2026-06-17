---
name: competitive-research
description: "Use when researching competitors, comparing products, or producing structured market analysis reports via web search and browsing."
version: 1.0.0
author: yimgao
license: MIT
metadata:
  hermes:
    tags: [research, competitive-analysis, market-intelligence, comparison, web-research]
    related_skills: [writing-plans, spike]
---

# Competitive Research Assistant

> **Automate competitor research, feature comparison, and market analysis using web search and browser tools.**

## Overview

This skill helps you research competitors, compare products, and produce structured analysis reports — all within Hermes Agent. Instead of manually visiting competitor sites and copy-pasting into a doc, you describe what you want to research and Hermes does the legwork: searches the web, browses competitor pages, extracts key features/pricing/reviews, and compiles everything into a clean Markdown report.

**What it can do for you:**
- Research a single competitor in depth (features, pricing, target audience, funding)
- Compare 2-5 competitors side-by-side
- Analyze market positioning and write SWOT analysis
- Monitor competitor news and updates (via cron jobs)
- Track pricing changes over time

## When to Use

- **Before making a tech stack decision** — compare tools/frameworks/SaaS products
- **When entering a new market** — understand the competitive landscape
- **Before building a new feature** — see what competitors already offer
- **For weekly/monthly competitive monitoring** — pair with cron jobs for recurring reports
- **For pitch decks / investor materials** — get structured competitor landscape

## Core Workflow

### 1️⃣ Single Competitor Deep Dive

```
User: Research Confluence as a documentation tool
Hermes should:
  1. Web search: "Confluence documentation features pricing 2026"
  2. Web search: "Confluence reviews pros cons"
  3. Browse the Confluence pricing page
  4. Browse 1-2 review sites (G2, Capterra)
  5. Compile report covering: Features, Pricing, Target Users, Pros/Cons, Alternatives
```

### 2️⃣ Competitive Comparison

```
User: Compare Notion, Confluence, and Coda for team documentation
Hermes should:
  1. Research each product individually (features, pricing, reviews)
  2. Create a comparison table with columns: Feature | Notion | Confluence | Coda
  3. Add pros/cons for each
  4. Summarize which is best for: small teams, enterprise, developers, non-technical users
  5. Save report to ~/research/ or Documents/
```

### 3️⃣ Market Landscape + SWOT

```
User: Analyze the AI coding assistant market — GitHub Copilot, Cursor, Codex, Claude Code
Hermes should:
  1. Research each competitor
  2. Market positioning analysis (price segment, target audience)
  3. SWOT for each competitor
  4. Overall market trends summary
  5. Save as a structured report
```

## Research Methodology

### Step 1: Define Scope

Before searching, clarify:
- **What exactly** are you researching? (product, company, category)
- **Dimensions** to cover? (features, pricing, reviews, market share, funding)
- **Number of competitors?** (1 deep dive, 3-5 comparison, or broad landscape)
- **Output format?** (brief summary, detailed report, comparison table)

### Step 2: Multi-Source Strategy

Always gather data from **at least 3 sources** per competitor:

| Source Type | Examples | What to extract |
|-------------|----------|-----------------|
| Official website | product.site, docs.product.site | Features claimed, pricing, use cases |
| Review platforms | G2, Capterra, ProductHunt | User ratings, pros/cons, reviews |
| Tech media | TechCrunch, The Verge, blogs | News, funding, market position |
| Community | Reddit, Hacker News, Discord | Real user sentiment, complaints |
| Comparison articles | "X vs Y vs Z" blog posts | Side-by-side feature lists |

### Step 3: Data Extraction

For each source, extract these facts:
- **Features:** What does it do? What's unique?
- **Pricing:** Free tier? Tiered? Enterprise? Per-seat?
- **Target audience:** Individual? Team? Enterprise? Developer?
- **Integrations:** What does it integrate with?
- **Strengths:** What users praise most
- **Weaknesses:** Common complaints
- **Market position:** Leader? Challenger? Niche?

### Step 4: Report Compilation

Structure the output as a clean Markdown report:

```markdown
# Competitive Research Report: [Category]

**Date:** YYYY-MM-DD
**Scope:** [Brief description of what was analyzed]

---

## Executive Summary
[2-3 paragraph overview of findings]

## Competitor Overview

| Competitor | Key Differentiator | Price Range | Target User |
|------------|--------------------|-------------|-------------|
| Product A | ... | $X-$Y/mo | ... |
| Product B | ... | $X-$Y/mo | ... |

## Detailed Analysis

### Product A
**Features:**
- Feature 1
- Feature 2
- ...

**Pricing:** $X/mo for Y users
**Strengths:** ...
**Weaknesses:** ...

### Product B
...

## Comparison Table

| Feature | Product A | Product B | Product C |
|---------|-----------|-----------|-----------|
| Feature 1 | ✅ | ✅ | ❌ |
| Feature 2 | ✅ | ❌ | ✅ |
| Feature 3 | ❌ | ✅ | ✅ |

## Recommendations
- **Best for small teams:** ...
- **Best for enterprise:** ...
- **Best for developers:** ...
- **Best value:** ...

## Sources
- [Official Site A](url)
- [Review on G2](url)
- [Comparison article](url)
```

### Step 5: Save & Share

Save the report to a standard location:

```
~/research/competitive/<category>/YYYY-MM-DD-<topic>.md
```

## Example Prompts

### Quick comparison
```
Compare Linear and Jira for project management. I want a features table, pricing comparison, and which is better for a 10-person startup.
```

### Deep dive
```
I need a deep dive on Mintlify as a documentation platform. Cover: features, pricing tiers, reviews from G2, what users complain about, main alternatives.
```

### Market landscape
```
Research the MCP (Model Context Protocol) server ecosystem. What MCP servers exist? Compare 5 popular ones: features, setup complexity, use cases.
```

### Cron monitoring (recurring)
```
Set up a weekly cron job to monitor new competitor news about Windsurf and Cursor IDE.
```

## Common Pitfalls

1. **Relying on one source.** Different sources tell different stories. Always cross-reference: official site claims vs user reviews vs analyst takes.

2. **Outdated pricing info.** SaaS pricing changes frequently. Check dates on review pages. When in doubt, visit the official pricing page.

3. **Confusing feature claims with actual capabilities.** A competitor might claim "AI-powered" but implement it minimally. Look for screenshots, demos, and user testimonials.

4. **Ignoring context.** A comparison table without context (team size, use case, budget) is misleading. Always note who the product is designed for.

5. **Only looking at features.** Pricing, support quality, onboarding experience, ecosystem/integrations are equally important.

6. **Forgetting to save the report.** After gathering all data, actually write the report to a file — don't just display it in the chat.

## Verification Checklist

- [ ] Gathered data from 3+ sources per competitor
- [ ] Official features confirmed against actual product screenshots/demos
- [ ] Pricing verified on official pricing pages (not third-party estimates)
- [ ] At least one user review source consulted (G2, Reddit, ProductHunt)
- [ ] Report is comprehensive: features, pricing, pros/cons, recommendations
- [ ] Sources are listed at the bottom of the report
- [ ] Report saved to file (not just displayed)
- [ ] Markdown formatting is clean and readable
