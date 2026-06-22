# Hi, I'm Aiex 👋

I build developer tools and APIs that turn complex problems into simple interfaces.

---

## 🌸 Papalily — My Project

**[papalily.com](https://www.papalily.com)** · AI-powered web scraping API

Turn any website into structured JSON with a plain-English prompt. No CSS selectors. No DOM queries. No HTML parsing. Works on React, Vue, Next.js — any JavaScript-rendered site.

```bash
curl -X POST https://api.papalily.com/scrape \
  -H "x-api-key: YOUR_KEY" \
  -H "Content-Type: application/json" \
  -d '{"url":"https://stripe.com/pricing","prompt":"get all pricing plans with features and prices"}'
```

**What it does:**
- 🌐 Launches a real Chromium browser — executes all JavaScript
- 🤖 AI reads the rendered page and extracts exactly what you asked for
- 📦 Returns clean, structured JSON — ready to use

**Use cases:**
- Competitor price monitoring
- Job listing aggregation
- Product data extraction
- Lead enrichment
- E-commerce scraping

| | |
|---|---|
| 🌐 Website | [papalily.com](https://www.papalily.com) |
| 📦 API | [RapidAPI — Free tier available](https://rapidapi.com/andognet/api/papalily) |
| 📖 Docs | [papalily.com/docs.html](https://www.papalily.com/docs.html) |
| 📝 Blog | [papalily.com/blog](https://www.papalily.com/blog/) |
| 💬 Examples | [github.com/aiex/papalily-examples](https://github.com/aiex/papalily-examples) |

> **Free tier** — 50 requests/month, no credit card required.
> **v1.1.1** — Now live on RapidAPI.

---

## 🧭 Lodestone — Control Plane for Telegram Agent Fleets

**[github.com/aiex/lodestone](https://github.com/aiex/lodestone)** · A single-channel control plane for a fleet of Telegram agents

You run several agents (bots) that each own different projects on different servers. As the fleet grows you lose the overview — *which agent owns what, and what is it allowed to touch?* Lodestone gives you **one hub group** to see the whole fleet and dispatch work to any agent.

**How it works:**
- Runs as a **Telegram userbot** (MTProto/Telethon) — can message your agent bots and read their replies
- **Registry** (SQLite) syncs from `config.yaml` — agents, projects, permissions, logs
- **AI brain** — natural language routing to the right agent via OpenAI-compatible LLM
- **Agent Loop** — supervised autonomous runs with token budget + dev/live PR approval gate
- **Web dashboard** — read-only fleet view with usage/cost charts
- **Unified memory** — optional TencentDB-Agent-Memory Gateway for cross-agent context

```bash
git clone https://github.com/aiex/lodestone.git && cd lodestone
python3 -m venv .venv && source .venv/bin/activate
pip install -e .
# configure config/config.yaml, then:
lodestone init && lodestone login && lodestone run
```

| | |
|---|---|
| 🐙 Source | [github.com/aiex/lodestone](https://github.com/aiex/lodestone) |
| 📦 Package | `lodestone-hub` |
| 🧠 AI | OpenAI / Kimi / GLM / Meridian proxy compatible |
| 💾 Memory | TencentDB-Agent-Memory Gateway (optional) |
| 🌐 Dashboard | Localhost + token auth, reads SQLite registry |

---

## 🛠 Repos

| Project | Description |
|---|---|
| [papalily-site](https://github.com/aiex/papalily-site) | Papalily marketing site & blog |
| [papalily-examples](https://github.com/aiex/papalily-examples) | Code examples — Node.js, Python, PHP, cURL |
| [lodestone](https://github.com/aiex/lodestone) | Control plane for Telegram agent fleets |

---

## 📊 Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=aiex&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=c9b1ff&icon_color=c9b1ff&text_color=a0aec0)

---

## 📫 Contact

- 📧 [aiex@outlook.com](mailto:aiex@outlook.com)
- 🌐 [papalily.com](https://www.papalily.com)
