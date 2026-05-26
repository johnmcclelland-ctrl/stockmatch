# 📊 StockMatch

**A beginner-friendly stock screener that matches stocks to your personal investing style.**

Most stock screeners throw a wall of numbers at you and assume you already know what they mean. StockMatch is different — it asks what *you* care about as an investor, scores any US stock against your personal criteria, and explains every number in plain English.

👉 **[Try it live →](https://johnmcclelland-ctrl.github.io/stockmatch/)**

![StockMatch demo](stockmatch-demo-lite.gif)

---

## ✨ Key Features

- **🎯 Personal Investor Profile** — A quick 5-question onboarding flow assesses your goals, time horizon, risk tolerance, dividend preference, and debt comfort, then auto-tunes your screening targets.
- **🎛️ Smart Criteria Calibration** — Your answers set sensible targets across 10 metrics (P/E ratio, dividend yield, debt-to-equity, net margin, ROE, and more) because a great bank looks nothing like a great tech company. Every target is adjustable.
- **📈 Best-Fit Match Scoring** — Every stock gets a 0–100% match score against your criteria, with a clear breakdown of exactly what's pulling the score up or down.
- **🧠 Plain-English Analysis** — For every stock: how it makes money, why competitors can't easily beat it, management quality, and what the long-term chart actually tells you. No jargon.
- **🌐 Real Financial Data** — Live fundamentals pulled from a real financial data provider, so the numbers you see are accurate.
- **⭐ Top Matches + Search** — See curated top matches from popular stocks instantly, and search any US ticker for live analysis.
- **💾 Saves Your Setup** — Your profile, criteria, and bookmarks persist across sessions automatically.
- **🚀 Zero Setup** — No signup, no account, no API key. Just open it and start.

---

## 🛠️ Tech Stack

- **Frontend:** Vanilla JavaScript (ES6+), HTML5, CSS3 — zero frameworks, no build step
- **Charts:** Chart.js + TradingView widgets
- **Data:** Real financial fundamentals served through a Cloudflare Worker that keeps API keys secure server-side
- **State:** Browser `localStorage` for profile, criteria, and watchlist persistence

The front-end is a single self-contained HTML file served on GitHub Pages, with a lightweight serverless proxy handling data requests securely.

---

## 🚀 Quick Start

```bash
git clone https://github.com/johnmcclelland-ctrl/stockmatch.git
cd stockmatch
open index.html
```

The live version works instantly — no setup required. Just visit the link and start matching.

---

## 💡 About This Project

StockMatch was built from scratch as a learning project — designing the investing framework, the matching logic, the full front-end, and a secure serverless data backend. The goal was to make stock research approachable for complete beginners, the way I wish it had been explained to me when I started.

---

## ⚠️ Disclaimer

StockMatch is an **educational tool, not financial advice.** The match scores and analysis are meant to help you learn how to evaluate stocks — not to tell you what to buy. Always do your own research and consider consulting a licensed financial advisor before investing.

---

## 📄 License

MIT — see [LICENSE](LICENSE) for details.
