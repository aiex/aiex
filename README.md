# Hi, I'm Aiex 👋

I build developer tools and APIs that make complex problems simple.

## 🚀 Current Project

### [Papalily](https://www.papalily.com) — AI Web Scraping API

Turn any website into structured JSON with a plain-English prompt. No CSS selectors. No DOM queries. Works on React, Vue, and Next.js sites.

- 🌐 **Website:** [papalily.com](https://www.papalily.com)
- 📦 **API:** [rapidapi.com/andognet/api/papalily](https://rapidapi.com/andognet/api/papalily)
- 📖 **Examples & Docs:** [github.com/aiex/papalily-examples](https://github.com/aiex/papalily-examples)

**How it works:**
1. POST a URL + plain-English prompt
2. Real Chromium browser renders the page
3. AI extracts exactly what you asked for — clean JSON

```bash
curl -X POST https://api.papalily.com/scrape \
  -H "x-api-key: YOUR_KEY" \
  -H "Content-Type: application/json" \
  -d '{"url":"https://example.com","prompt":"get all product prices"}'
```

**Free tier available** — 50 requests/month, no credit card.

## 🛠 Repos

| Project | Description |
|---------|-------------|
| [papalily-examples](https://github.com/aiex/papalily-examples) | Code examples for the Papalily API (Node.js, Python, PHP, cURL) |

## 📊 Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=aiex&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=c9b1ff&icon_color=c9b1ff&text_color=a0aec0)

## 📫 Get in Touch

Try Papalily free: [rapidapi.com/andognet/api/papalily](https://rapidapi.com/andognet/api/papalily)
