# Competitive Research Assistant — Hermes Agent Skill / 竞品调研助手

**Bilingual competitor research & 小红书 (Xiaohongshu) content analysis skill for Hermes Agent.**
**Hermes Agent 的双语竞品调研 & 小红书内容分析技能。**

---

## Overview / 概述

Research competitors, analyze 小红书 trends, compare products — in Chinese or English. This skill works across both Western and Chinese social-media ecosystems.

竞品调研、小红书趋势分析、产品对比 — 支持中英文。覆盖西方市场和中文社交媒体生态。

## Features / 功能

| English | 中文 |
|---------|------|
| ✅ Single competitor deep dive | ✅ 单个竞品深度分析 |
| ✅ Multi-product comparison | ✅ 多产品对比 |
| ✅ Market landscape + SWOT | ✅ 市场格局 + SWOT |
| ✅ **小红书 content trend analysis** | ✅ **小红书内容趋势分析** |
| ✅ **小红书 competitor strategy research** | ✅ **竞品小红书策略分析** |
| ✅ Bilingual reports (EN/CN) | ✅ 双语报告（中英文） |
| ✅ Cron monitoring | ✅ 定时监控（cron） |

## Installation / 安装

```bash
# Install from GitHub directly
hermes skills install https://raw.githubusercontent.com/yimgao/competitive-research-skill/main/SKILL.md --name competitive-research

# Once published to the hub:
hermes skills install competitive-research
```

## Usage / 使用

Load the skill:

```bash
hermes -s competitive-research
```

Then ask in **English** or **中文**:

### 🇨🇳 中文示例
```
帮我分析小红书上『AI笔记工具』这个赛道的热门内容趋势
```
```
分析 Notion 和 FlowUs 在小红书上的内容策略差异
```
```
研究小红书『效率工具』话题下最新的爆款笔记模式
```

### 🌐 English examples
```
Compare Notion, Obsidian, and Craft for personal knowledge management
```
```
Research the AI coding assistant market — Copilot, Cursor, Codex
```

### 🌐 Bilingual
```
Research the note-taking app market and output the report in both English and Chinese
```

## Report Structure / 报告结构

Each report includes / 每份报告包含：

- **Executive Summary / 执行摘要**
- **Competitor/Content Overview / 竞品/内容概览**
- **Detailed Analysis / 深度分析**
- **Comparison Table / 对比表格** (if multi-product)
- **Recommendations / 建议方案**
- **Sources / 来源**

## Requirements / 要求

- Hermes Agent (web_search and browser tools enabled)
- 启用 web 工具集：`hermes tools enable web`

## License

MIT
