# 📊 BTC ETF Cost Basis Tracker (Lite)

A lightweight, open-source web tool that calculates and visualizes the real-time **aggregate cost basis** of Bitcoin held by U.S. spot Bitcoin ETFs — compared directly to the current BTC market price.

Built for transparency, education, and community use. No backend required — runs entirely in your browser.

🔗 **Live Demo**: [https://btcbasistracker.github.io/BTCBasisTracker/](https://btcbasistracker.github.io/BTCBasisTracker/)  
🐦 **Follow for advanced insights**: [@btcbasistracker on X](https://x.com/btcbasistracker)

---

## ✨ Features

- **Real-time cost basis calculation** from user-provided ETF flow & BTC price data  
- Interactive chart comparing **BTC price vs. ETF cost basis**  
- Key metrics: distance from basis (%), total BTC held, total USD invested  
- Responsive timeframes (1W, 1M, 3M, 6M, 1Y, All)  
- Copy-paste friendly data input (supports multiple date formats)  
- Works offline — 100% client-side JavaScript  

> 💡 This is the **public lite version** of a more advanced institutional dashboard. For flow efficiency, reversion timing, confluence alerts, and backtested strategies, follow [@btcbasistracker](https://x.com/btcbasistracker).

---

## 🚀 How to Use

1. Go to the **[Live Demo](https://btcbasistracker.github.io/BTCBasisTracker/)**
2. **Paste your data**:
   - **ETF Flow Data**: Daily net flows into Bitcoin ETFs (in millions USD)
   - **BTC Price Data**: Daily closing prices (USD)
3. Click **"🧮 CALCULATE COST BASIS"** — results appear instantly!

> ✅ **Tip**: Paste raw data from any source. The tool **automatically matches dates that appear in both datasets** — no manual alignment needed!

---

## 📥 Data Sources (Recommended)

- **ETF Flows**: [etf.com](https://www.etf.com/), [Farside Investors](https://farside.co.uk/), or official issuer filings  
- **BTC Price**: [CoinGecko](https://www.coingecko.com/), [Kaiko](https://www.kaiko.com/), or [TradingView](https://www.tradingview.com/)

---

## 🛠️ Tech Stack

- **HTML5 + CSS3** – Clean, responsive layout  
- **JavaScript (ES6)** – Core logic & parsing  
- **Chart.js** – Interactive, animated charts  
- **Zero dependencies** beyond Chart.js (loaded via CDN)

---

## 📜 License

This project is licensed under the **MIT License** — free to use, modify, and share.  
*Not financial advice. For informational purposes only.*

> ℹ️ **To add a LICENSE file**:  
> On GitHub, go to your repo → **Add file → Create new file** → name it `LICENSE` → choose **MIT License** from the template dropdown → commit.

---

## 🙌 Acknowledgements

Inspired by on-chain and ETF analytics communities.  
Special thanks to developers of [Chart.js](https://www.chartjs.org/) and open data providers.

---

## 🔗 Connect

- Follow **[@btcbasistracker](https://x.com/btcbasistracker)** on X for daily updates, institutional-grade signals, and strategy insights.
- Questions? Open an [Issue](https://github.com/btcbasistracker/BTCBasisTracker/issues)!
