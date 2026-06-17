# Competitive Research Report: AI Note-Taking Applications

**Date:** June 17, 2026
**Analyst:** Hermes Agent Research
**Scope:** Notion, Obsidian, Logseq, Craft

---

## Executive Summary

This report analyzes four leading AI note-taking and knowledge management applications: **Notion**, **Obsidian**, **Logseq**, and **Craft**. Each occupies a distinct position in the market—from Notion's all-in-one collaborative workspace to Logseq's open-source privacy-first approach. The key takeaway: there is no single "best" tool; the right choice depends heavily on user priorities around collaboration, privacy, cost, ecosystem, and platform preference.

| Dimension | Winner | Rationale |
|---|---|---|
| Best for Teams | **Notion** | Unmatched collaboration, databases, and AI agents |
| Best Privacy/Control | **Obsidian** | Local-first, plain-text, 100% free core |
| Best Open-Source | **Logseq** | AGPL-3.0, outliner workflow, academic focus |
| Best Design/UX | **Craft** | Apple Design Award, gorgeous native experience |
| Best Value (Free) | **Obsidian / Logseq** | Both fully functional free tiers |

---

## Comparison Table

| Feature | Notion | Obsidian | Logseq | Craft |
|---|---|---|---|---|
| **Pricing Model** | Freemium (SaaS) | Free core + paid add-ons | Free & open-source | Freemium (SaaS) |
| **Free Tier** | Unlimited pages (limited guests/upload) | Unlimited local notes | Unlimited local notes | 1,500 blocks, 1 GB storage |
| **Paid Plans Start** | $10/seat/month (Plus) | $4-5/mo (Sync), $10/mo (Publish) | N/A (free core) | $4.8/mo (Plus, yearly) |
| **Local-First** | ❌ (Cloud) | ✅ (Local markdown) | ✅ (Local markdown/org) | ❌ (Cloud) |
| **Open Source** | ❌ Proprietary | ❌ Proprietary | ✅ AGPL-3.0 | ❌ Proprietary |
| **Bidirectional Links** | ✅ | ✅ (Core feature) | ✅ (Core feature) | ⚠️ Limited |
| **Graph View** | ❌ | ✅ | ✅ | ❌ |
| **AI Features** | ✅ Agents, chat, autofill | ⚠️ Community plugins | ⚠️ Community plugins | ✅ AI assistant (Core/Fast/Max) |
| **Collaboration** | ✅ Excellent | ❌ None built-in | ⚠️ Limited | ✅ Shared Spaces |
| **Offline Mode** | ⚠️ Limited | ✅ Full offline | ✅ Full offline | ⚠️ Limited |
| **Plugin Ecosystem** | ⚠️ Limited (integrations) | ✅ 1,000+ plugins | ✅ Growing | ❌ Minimal |
| **Platforms** | Web, Win, Mac, iOS, Android | Win, Mac, Linux, iOS, Android | Win, Mac, Linux, iOS, Android, BSD | Mac, iOS, Web (limited Win/Android) |
| **E2E Encryption** | ❌ | ✅ (Sync add-on) | ⚠️ (Planned) | ❌ |

---

## Detailed Analysis

### 1. Notion

**Overview:**
Notion is a freemium, proprietary all-in-one workspace developed by Notion Labs, Inc. (founded 2013, launched 2016). It combines note-taking, wikis, databases, project management, and increasingly AI-powered automation into a single platform. Valued at over $10B, it's the most commercially successful product in this comparison.

**Key Features:**
- Block-based editor supporting text, images, databases, embeds, code, and more
- Powerful relational databases with table, board, calendar, gallery, list, and timeline views
- **Notion AI** — chat, generate, autofill, translate, meeting notes, enterprise search, research mode
- **Custom Agents** — autonomous AI agents for task routing, Q&A, reporting, and workflow automation
- Notion Calendar and Notion Mail (integrated productivity suite)
- Teamspaces (open, closed, private), permission groups, granular database permissions
- API, webhooks, and Workers (custom code extensions)
- 750+ templates, integration with 80+ apps

**Pricing:**
| Plan | Price | Key Limits |
|---|---|---|
| Free | $0 | 7-day page history, 5MB uploads, 10 guests, limited AI trial |
| Plus | $10/seat/mo | 30-day history, unlimited uploads/guests |
| Business | $20/seat/mo | 90-day history, permission groups, advanced permissions |
| Enterprise | Custom | Unlimited history, zero-retention AI, SAML SSO, advanced admin |

**Target Users:**
Startups, SMBs, enterprise teams, project managers, knowledge workers, anyone needing a collaborative digital HQ.

**Strengths (from reviews):**
- Extremely versatile — replaces multiple tools (docs, wikis, project management, spreadsheets)
- Excellent collaboration with real-time editing, comments, and granular permissions
- Powerful database features rival lightweight CRM/project management tools
- Strong AI features including autonomous agents that can automate workflows
- Large template marketplace and community
- Trusted by major companies (OpenAI, Figma, Nvidia, Toyota)

**Weaknesses (from reviews):**
- **Trustpilot score: 2.5/5** — significant billing complaints (unexpected charges, difficult cancellations, opaque pricing)
- Performance degrades with large databases (slow loading, laggy editing)
- Limited offline support (everything is cloud-dependent)
- No end-to-end encryption
- Proprietary format = vendor lock-in (hard to migrate data out)
- Can be overwhelming for simple note-taking
- File upload limit on free tier (5MB) is very restrictive

---

### 2. Obsidian

**Overview:**
Obsidian is a free, proprietary (core) note-taking application developed by Obsidian MD (Steph Ango, Erica Xu, and team). Launched in 2020, it's built around the concept of a "local-first, durable, private" knowledge base using plain Markdown files. It has become the gold standard for the Personal Knowledge Management (PKM) movement, with a 100% free core and optional paid cloud services.

**Key Features:**
- Plain-text Markdown notes stored locally on your device
- **Bidirectional linking** and backlinks (core to the knowledge graph philosophy)
- **Graph View** — interactive visualization of note connections
- **Canvas** — visual mapping and diagramming workspace
- **1,000+ community plugins** — themes, widgets, integrations, automation (Obsidian Sync, Calendar, Kanban, Dataview, Excalidraw, etc.)
- Obsidian Sync (paid): end-to-end encrypted sync across devices
- Obsidian Publish (paid): turn notes into a website
- Web Clipper, mobile apps, CLI tool
- Vim keybindings, customizable hotkeys, CSS snippets
- Core plugins: daily notes, templates, outliner, tagging, search, bookmarks

**Pricing:**
| Plan | Price | Details |
|---|---|---|
| Free (Personal) | $0 | All core features, unlimited local notes |
| Free (Commercial) | $0 | Not required to pay, but encouraged |
| Catalyst | $25 one-time | Early beta access, insider community |
| Commercial License | $50/user/year | Supporting development |
| Obsidian Sync | ~$5/mo (yearly) | E2E encrypted sync, version history |
| Obsidian Publish | ~$10/mo (yearly) | Publish notes as a website |

**Target Users:**
Power users, developers, researchers, writers, PKM enthusiasts, students, privacy-conscious individuals, people who want full control over their data.

**Strengths (from PCMag review and user sentiment):**
- **4.0/5 "Excellent" — PCMag** "Obsidian is a highly adaptable and free note-taking app for power users who don't need collaboration features"
- Completely free core with no artificial limits
- Local-first: your notes are plain text files — never locked in, never lost
- Massive plugin ecosystem enables near-infinite customization
- Graph view is unique and powerful for seeing knowledge connections
- Fast performance even with large vaults
- Privacy-first: no accounts required, no data leaves your device unless you choose sync
- Active community (Discord, Forum, Reddit)

**Weaknesses (from PCMag and user sentiment):**
- **"Difficult to get started with"** — steep learning curve for non-technical users
- **"No collaboration features"** — purely single-user; no real-time editing, comments, or sharing
- No built-in sync — requires paid Sync, third-party service, or manual effort
- Mobile experience is functional but less polished
- No native web app (desktop/mobile only)
- No AI features built-in (community plugins can add some)
- Plugin quality varies; some break on updates

---

### 3. Logseq

**Overview:**
Logseq is a free and open-source (AGPL-3.0) personal knowledge base and note-taking application created by Tienson Qin. Originally focused on the outliner workflow and inspired by Roam Research, it emphasizes local-first, privacy-first, and open-source principles. It's gained particular traction among academics, students, and the PKM community.

**Key Features:**
- **Outliner-based editor** — bullet-journal / hierarchical note-taking style
- Supports both **Markdown** and **Org-mode** syntax
- **Bidirectional linking** with backlinks, page references, and block references
- **Knowledge graph** visualization
- **PDF annotation** — highlight and take notes directly on PDFs
- **Flashcards** — built-in spaced repetition (SM-2 algorithm)
- **Whiteboards** (NEW) — visual spatial canvas
- **Task management** with TODO/DONE states and queries
- **Advanced queries** — Datomic-style Datalog queries for structured data retrieval
- Journal-based daily notes workflow
- Block-level referencing and embedding
- Plugins and themes (via community marketplace)
- Open-source: code is publicly auditable, community-contributed

**Pricing:**
| Plan | Price | Details |
|---|---|---|
| Logseq Core | $0 | AGPL-3.0 open source, all features, local storage |
| Logseq Sync | ~$5/mo | Cloud sync (GitHub Sponsors or subscription) |
| Donations | Voluntary | GitHub Sponsors, Open Collective |

Logseq was originally fully open-source. In 2024, there was community controversy when the company announced a shift toward a dual-license/cloud model, which caused some concern about the project's long-term open-source commitment.

**Target Users:**
Students, academics, researchers, writers, PKM enthusiasts, programmers, privacy advocates, anyone who prefers open-source software.

**Strengths (from community sentiment and reviews):**
- Completely free and open-source — no lock-in, no paid tiers for core features
- Outliner workflow is uniquely effective for thinking, brainstorming, and knowledge synthesis
- PDF annotation + flashcards is a powerful combination for academic study
- Bidirectional linking and block references enable true networked thought
- Privacy-first: all data stored locally by default
- Active, passionate community (2,200+ users online at time of visit)
- Cross-platform (Windows, Mac, Linux, iOS, Android, BSD)

**Weaknesses (from community sentiment):**
- Smaller plugin ecosystem than Obsidian (fewer community contributions)
- UI/UX is less polished and can feel rough around the edges
- Company transition from fully open-source caused trust concerns in the community
- Performance can be slow with very large knowledge graphs
- Mobile apps are less mature and feature-rich than desktop
- Sync solution is less battle-tested than Obsidian Sync or iCloud
- Smaller user base = fewer tutorials, resources, and third-party integrations
- Learning curve for the outliner paradigm (not intuitive for everyone)

---

### 4. Craft

**Overview:**
Craft is a freemium, proprietary document editor and note-taking app developed by Craft Docs Limited. It has won Apple Design Awards for its exceptional native macOS and iOS experience. Craft positions itself as a beautiful, Apple-first alternative to Notion and other note-taking tools, with strong AI features and cross-device sync.

**Key Features:**
- **Beautiful native design** — Apple Design Award winner, optimized for macOS/iOS
- Block-based document editor with rich formatting and media embedding
- **Cross-device sync** via Craft Cloud (real-time, reliable)
- **Shared Spaces** — collaboration for Family and Team plans
- **AI Assistant** — three models: Core (fast), Fast (efficient), Max (powerful); 50 credits/month on Plus
- Version history (7-day free, 30-day Plus)
- Link-sharing with publishable web pages
- **API & MCP access** — 100 requests/min, 20,000 blocks/min
- Templates, markdown export, smart blocks
- **Imagine with Craft** — AI-powered creative features

**Pricing:**
| Plan | Price | Key Limits |
|---|---|---|
| Free (Starter) | $0 | 1,500 blocks, 1 GB storage, 25MB uploads, 7-day history, 15 AI credits (Core/Fast only) |
| Plus | $4.8/mo (yearly) / $8/mo (monthly) | Unlimited blocks/storage/uploads, 30-day history, 50 AI credits, Max model, API |
| Family | $9/mo (yearly) | 2-6 Plus accounts + shared Space |
| Team | $50/mo | Up to 10 Plus accounts + shared Space |
| Education | Discounted | Available on request |

**Target Users:**
Apple ecosystem users (Mac, iPhone, iPad), designers, individual creators, writers, professionals who prioritize beautiful UI and native experience.

**Strengths (from user reviews and sentiment):**
- Gorgeous, native Apple design — best-in-class writing experience on Mac/iOS
- Excellent cross-device sync (reliable and fast within Apple ecosystem)
- Intuitive interface — minimal learning curve compared to Obsidian or Notion
- AI assistant is well-integrated and useful (summarization, rewriting, generation)
- Version history is robust and easy to use
- Family and Team plans offer good value for collaborative small groups
- Regularly updated with new features

**Weaknesses (from user reviews and sentiment):**
- **Limited on Windows/Android** — only a web app, not native, inferior experience
- **Expensive for what it offers** — free tier is very restrictive (1,500 blocks); Plus costs more than comparable offerings
- **No graph view, no bidirectional linking, no advanced knowledge management** — not a PKM tool
- **Small plugin/extension ecosystem** — no marketplace for community contributions
- **Vendor lock-in** — proprietary format, though markdown export is available
- AI credits feel restrictive (50/month on Plus)
- 1,500-block limit on free tier is extremely limiting for any real use

---

## Recommendations

### For Teams & Companies → **Notion**
Notion is the clear winner for collaborative environments. Its databases, AI agents, permission controls, and integration ecosystem are unmatched. Teams that need an all-in-one workspace (docs + project management + wiki) will get the most value here. The main downsides are cost at scale and cloud dependency.

### For Privacy-Conscious Power Users → **Obsidian**
If you want your data to truly be yours — forever, in plain text, with no cloud dependency — Obsidian is the best choice. The massive plugin ecosystem means it can be customized to do almost anything. Best for: developers, researchers, writers, and anyone willing to invest time in setup.

### For Academics & Open-Source Advocates → **Logseq**
Logseq's outliner workflow is uniquely suited for academic work: PDF annotations, flashcards, structured note-taking, and bidirectional linking. The open-source license (AGPL-3.0) also appeals to those who want auditability and community ownership. Best for: students, researchers, and open-source enthusiasts.

### For Apple Ecosystem Lovers → **Craft**
If you live in Apple's ecosystem and value beautiful design above all else, Craft delivers the best native experience. It's ideal for individual creators and small teams who want a simple, elegant writing tool with AI assistance. However, the restrictive free tier and Apple-only focus limit its broader appeal.

### Decision Matrix

| If you prioritize... | Choose... |
|---|---|
| Collaboration & team features | **Notion** |
| Data ownership & privacy | **Obsidian** |
| Open-source & academic workflow | **Logseq** |
| Beautiful native design | **Craft** |
| Budget (free forever) | **Obsidian** or **Logseq** |
| AI-powered automation | **Notion** (Custom Agents) |
| Simple, polished writing | **Craft** |
| Maximum customization | **Obsidian** (1,000+ plugins) |

---

## Sources

1. **Notion Official Pricing** — notion.com/pricing (accessed June 17, 2026)
2. **Obsidian Official Pricing** — obsidian.md/pricing (accessed June 17, 2026)
3. **Logseq Official Site** — logseq.com (accessed June 17, 2026)
4. **Craft Official Pricing** — craft.do/pricing (accessed June 17, 2026)
5. **Notion Wikipedia** — en.wikipedia.org/wiki/Notion_(productivity_software) (accessed June 17, 2026)
6. **Obsidian Wikipedia** — en.wikipedia.org/wiki/Obsidian_(software) (accessed June 17, 2026)
7. **Logseq Wikipedia** — en.wikipedia.org/wiki/Logseq (accessed June 17, 2026)
8. **PCMag Obsidian Review** — pcmag.com/reviews/obsidian (accessed June 17, 2026) — Rating: 4.0/5 Excellent
9. **Notion Trustpilot** — trustpilot.com/review/www.notion.so (accessed June 17, 2026) — Score: 2.5/5 (415 reviews)
10. **Obsidian About Page** — obsidian.md/about (accessed June 17, 2026)
11. **Logseq GitHub Repository** — github.com/logseq/logseq (accessed June 17, 2026) — 43.4k stars, 2.7k forks, AGPL-3.0
12. **Craft Features Page** — craft.do (accessed June 17, 2026)

---

*Report compiled by Hermes Agent on June 17, 2026. Pricing and features verified as of the date above. Always verify current pricing on official websites before making decisions.*
