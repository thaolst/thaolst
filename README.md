<p align="center">
  <img src="https://img.shields.io/badge/Growth%20Marketing-×%20AI-FF3366?style=flat-square" />
  <img src="https://img.shields.io/badge/Status-Building%20in%20Public-4ade80?style=flat-square" />
  <img src="https://img.shields.io/badge/Fintech-SEA-00D4B4?style=flat-square" />
  <img src="https://img.shields.io/pypi/v/growth-mcp?style=flat-square&color=60a5fa&label=PyPI" />
  <img src="https://img.shields.io/github/stars/thaolst?style=flat-square&color=facc15&logo=github" alt="total stars" />
</p>

<h1 align="center">Building an AI Assistant for Growth Marketers 🚀</h1>

<p align="center">
  <em>Everything here is a building block — open-source, production-tested, built in public.</em>
</p>

---

## The Vision

Most marketing AI tools are either **too generic** (ChatGPT wrappers) or **too technical** (need a data scientist to operate).

I'm building something different: **an AI assistant that understands growth marketing** — campaign mechanics, retention economics, voucher design, segment analysis. The kind of stuff that takes a senior PM 3 hours and should take 3 minutes.

**This GitHub is the open-source foundation.** Every repo is a module. Follow the journey.

---

## The Building Blocks

| Module | Repo | What it does | Status |
|--------|------|-------------|--------|
| 🧠 **Data & Analysis** | [growth-mcp](https://github.com/thaolst/growth-mcp) | MCP server — cohort analysis, churn prediction, A/B testing, campaign math | `v1.0` · PyPI · ★10 · 🍴2 |
| 📝 **Prompt Engine** | [ai-growth-prompts](https://github.com/thaolst/ai-growth-prompts) | 40+ prompts for campaign brief, voucher design, segmentation, game mechanics | ★11 · 🍴3 |
| 🤖 **Agent Skills** | [ai-growth-agents-for-marketers](https://github.com/thaolst/ai-growth-agents-for-marketers) | Installable agent skills — `npx skills add thaolst/ai-growth-agents-for-marketers` | ★5 · 🍴4 |
| 🔄 **Social Auto-Pilot** | [tara-agent](https://github.com/thaolst/tara-agent) | Telegram agent for LinkedIn, Facebook, Threads automation | ★5 · 🍴7 |
| 🌱 **Side projects** | [tara-bot](https://github.com/thaolst/tara-bot) · [travel-growth-playbook](https://github.com/thaolst/travel-growth-playbook) · [coffee-globe](https://github.com/thaolst/coffee-globe) | Experiments beyond the growth stack — flight search, travel frameworks, and a world-coffee atlas | ★59 · ★3 · 🆕 |

**Coming next:** Web UI for growth-mcp → marketers use it without CLI. Campaign Brief Generator. Retention Analyzer.

---

## What these tools actually save

| Workflow | Before | After | Module |
|----------|--------|-------|--------|
| Campaign brief | 3 hours | 20 min | prompts |
| A/B test analysis | 3 hours | 15 min | mcp |
| MEU planning | 2-3 days | 30 min | prompts |
| Campaign history query | 30 min | 30 sec | mcp + agents |
| Voucher design | 2 hours | 15 min | prompts |

---

## 🗺️ Roadmap

```
Q3 2026
├── 🎯 growth-mcp Web UI (Streamlit) — MVP
├── 📦 Campaign Brief Generator — first end-to-end tool
├── 📈 Retention Cohort Analyzer — upload CSV → insights
└── 📝 Daily skill drops — new growth marketing skill every 1-2 days

Q4 2026
├── 🧩 Unified AI Assistant — combine MCP + prompts + agents
├── 🌐 Public beta — invite-only
└── 📊 Community features — share campaigns, templates

2027
├── 🚀 Full launch
└── 🔌 Plugin ecosystem — 3rd party tools
```

---

## 📝 Latest Builds

<!-- DAILY-LOG:START -->
**Sep 2026**
- ☕ **Coffee Globe** launched — bilingual VI/EN atlas of world coffee (globe, species, brewing, Vietnamese coffee culture), live on GitHub Pages
- 🧠 **growth-mcp** — new **Campaign Memory**: search past campaigns and save learnings
- 🤖 **ai-growth-agents-for-marketers** — live demo site published
- ✈️ **tara-bot** — now ★59; natural-language flight search with affiliate links
<!-- DAILY-LOG:END -->

---

## Projects in detail

### [growth-mcp](https://github.com/thaolst/growth-mcp) · ★10
![pypi](https://img.shields.io/pypi/v/growth-mcp?style=flat-square&color=60a5fa)

MCP server for growth marketing and loyalty program economics. 25 tools, 3 prompts, 2 resources, 130 tests.  
New: **Campaign Memory** — search past campaigns and save learnings.  
`pip install growth-mcp` — works with Claude, Cursor, any MCP client.

> *Data & analysis backbone of the AI assistant.*

### [ai-growth-prompts](https://github.com/thaolst/ai-growth-prompts) · ★11
![stars](https://img.shields.io/github/stars/thaolst/ai-growth-prompts?style=social)

Prompt library from live fintech campaigns. Voucher design, user segmentation, game mechanics, retention loops. 8 categories, tested in production.

> *The prompt engine — what the assistant says and how it thinks.*

### [ai-growth-agents-for-marketers](https://github.com/thaolst/ai-growth-agents-for-marketers) · ★5
![stars](https://img.shields.io/github/stars/thaolst/ai-growth-agents-for-marketers?style=social)

Prompts and Python agents for growth marketing work. Installable as Agent Skills.  
`npx skills add thaolst/ai-growth-agents-for-marketers`

> *The agent layer — multi-step workflows and automations.*

### [tara-bot](https://github.com/thaolst/tara-bot) · ★59
Personal AI agent on Telegram. Flight search in natural language. Side project.

---

### [coffee-globe](https://github.com/thaolst/coffee-globe) · 🆕 _side project_
Bilingual (VI/EN) atlas of world coffee — interactive globe, species and varieties, brewing methods, health and economy, plus a deep section on Vietnamese coffee culture. Plain HTML/JS, live on GitHub Pages.

> *A side project — coffee, storytelling and craft.*

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=thaolst&theme=github_dark" width="100%" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=thaolst&show_icons=true&theme=github_dark&hide=contribs&count_private=true" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=thaolst&layout=compact&theme=github_dark&hide=html" height="150" />
</p>

---

## Let's connect

[LinkedIn](https://www.linkedin.com/in/thaolst/) · [Substack](https://thaolst.substack.com/) · [PyPI](https://pypi.org/user/thaolst/)

*Growth marketer. Building AI tools for marketers in public. Fork, star, follow — this is just the beginning.*
