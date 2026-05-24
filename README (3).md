# 📊 StockMatch

**A beginner-friendly stock screener that matches stocks to your personal investing style.**

Most stock screeners throw a wall of numbers at you and assume you already know what they mean. StockMatch is different — it asks what *you* care about as an investor, scores any US stock against your personal criteria, and explains every number in plain English.

👉 **[Try it live →](https://johnmcclelland-ctrl.github.io/stockmatch/)**

![StockMatch demo](stockmatch-demo-lite.gif)

---

## ✨ Key Features

- **🎯 Personal Investor Profile** — A quick onboarding flow assesses your goals, time horizon, and risk tolerance, then auto-tunes your screening targets (Growth, Income, Safety, or Balanced).
- **🎛️ Smart Criteria Calibration** — Industry-aware presets automatically adjust your targets across 10 metrics (P/E ratio, dividend yield, debt-to-equity, net margin, ROE, and more) because a great bank looks nothing like a great tech company.
- **📈 Best-Fit Match Scoring** — Every stock gets a 0–100% match score against your criteria, with a clear breakdown of exactly what's pulling the score up or down.
- **🧠 Plain-English Analysis** — For every stock: how it makes money, why competitors can't easily beat it, management quality, and what the long-term chart actually tells you. No jargon.
- **🌐 Explore by Industry** — Browse top stocks across technology, finance, healthcare, consumer, energy, and more.
- **⭐ Save Your Favorites** — Bookmark stocks to a watchlist and revisit them anytime.
- **💾 Saves Your Setup** — Your profile, criteria, and bookmarks persist across sessions automatically.
- **🚀 Instant Demo Mode** — Try it immediately with 13 major stocks. No signup, no key, no setup required.

---

## 🛠️ Tech Stack

- **Frontend:** Vanilla JavaScript (ES6+), HTML5, CSS3 — zero frameworks, no build step
- **Charts:** Chart.js + TradingView widgets
- **Live Data:** Real financial data pulled through an AI data service
- **State:** Browser `localStorage` for profile, criteria, and watchlist persistence

Because it's a single self-contained HTML file, it runs anywhere — just open it in a browser or drop it on any static host.

---

## 🚀 Quick Start

```bash
git clone https://github.com/johnmcclelland-ctrl/stockmatch.git
cd stockmatch
open index.html
```

Demo mode works instantly and offline. To search **any** US stock with live data, connect a free data key — the app walks you through getting one in about two minutes (no credit card required).

---

## 💡 About This Project

StockMatch was built from scratch as a learning project — designing both the investing framework and the full implementation. The goal was to make stock research approachable for complete beginners, the way I wish it had been explained to me when I started.

---

## ⚠️ Disclaimer

StockMatch is an **educational tool, not financial advice.** The match scores and analysis are meant to help you learn how to evaluate stocks — not to tell you what to buy. Always do your own research and consider consulting a licensed financial advisor before investing.

---

## 📄 License

MIT — see [LICENSE](LICENSE) for details.
