📊 BTC ETF Cost Basis Tracker (Lite)
A lightweight, open-source web tool that calculates and visualizes the real-time aggregate cost basis of Bitcoin held by U.S. spot Bitcoin ETFs — compared directly to the current BTC market price.

Built for transparency, education, and community use. No backend required — runs entirely in your browser.

🔗 Live Demo: https://btcbasistracker.github.io/BTCBasisTracker/
🔗 How to use: Download index.html and open it in any modern browser.
🐦 Follow for advanced insights: @btcbasistracker on X

✨ Features
Real-time cost basis calculation from user-provided ETF flow & BTC price data
Interactive chart comparing BTC price vs. ETF cost basis
Key metrics: distance from basis (%), total BTC held, total USD invested
Responsive timeframes (1W, 1M, 3M, 6M, 1Y, All)
Copy-paste friendly data input (supports multiple date formats)
Works offline — 100% client-side JavaScript
💡 This is the public lite version of a more advanced institutional dashboard. For flow efficiency, reversion timing, confluence alerts, and backtested strategies, follow @btcbasistracker.

🚀 How to Use
Download or clone this repo:
git clone https://github.com/btcbasistracker/BTCBasisTracker.git
Open index.html in any modern browser (Chrome, Firefox, Safari, Edge).
Paste your data:
ETF Flow Data: Daily net flows into Bitcoin ETFs (in millions USD)
BTC Price Data: Daily closing prices (USD)
Example format:
2026-01-10, 125.3
2026-01-09, -42.1
Click "🧮 CALCULATE COST BASIS" — results appear instantly!
✅ Tip: Paste raw data from any source. The tool automatically matches dates that appear in both datasets — no manual alignment needed!

📥 Data Sources (Recommended)
ETF Flows: etf.com, Farside Investors, or official issuer filings
BTC Price: CoinGecko, Kaiko, or TradingView

🛠️ Tech Stack
HTML5 + CSS3 – Clean, responsive layout
JavaScript (ES6) – Core logic & parsing
Chart.js – Interactive, animated charts
Zero dependencies beyond Chart.js (loaded via CDN)

📜 License
MIT License — free to use, modify, and share.
Not financial advice. For informational purposes only.

🙌 Acknowledgements
Inspired by on-chain and ETF analytics communities.
Special thanks to developers of Chart.js and open data providers.

🔗 Connect
Follow @btcbasistracker on X for daily updates, institutional-grade signals, and strategy insights.
Questions? Open an Issue!
