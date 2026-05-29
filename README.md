# Portfolio Analyzer

An interactive portfolio analytics dashboard built with vanilla HTML, CSS, and Chart.js — no frameworks, no backend, no build tools.

🔗 **Live demo:** https://harshilpatel1210.github.io/portfolio-analyzer

---

## Features

- 📈 Cumulative growth vs benchmark
- 🍩 Allocation mix donut chart
- 📊 Monthly returns (bar + benchmark line)
- 📉 Rolling drawdown curve
- 🔵 Efficient frontier — 1,000 Monte Carlo simulations
- 📐 Capital Market Line (CML) from risk-free rate
- ⭐ Max-Sharpe optimal portfolio with weight breakdown
- 📊 Risk contribution per holding
- 🟦 Pairwise correlation heatmap
- 📋 Holdings detail table
- 🧮 Full risk & return metrics (Sharpe, Sortino, VaR, CVaR, Alpha, Beta)
- 💥 10-scenario stress test (2008, COVID, rate hikes, etc.)
- 🌙 Dark / light mode toggle
- 📱 Fully responsive

---

## Model Portfolios

| Portfolio | Tickers |
|---|---|
| Magnificent 7 | AAPL, MSFT, NVDA, GOOGL, AMZN, META, TSLA |
| FAANG Heavy | META, AAPL, AMZN, NFLX, GOOGL |
| Dividend Aristocrats | JNJ, KO, PG, MMM, T, VZ, XOM |
| Berkshire / Value | AAPL, BAC, AXP, KO, CVX, OXY, KHC |
| Ray Dalio All Weather | SPY, TLT, GLD, DBC, IEF |
| 60/40 Balanced | SPY, AGG |
| Semiconductor Focus | NVDA, AMD, AVGO, QCOM, MU, TSM |
| Banking Leaders | JPM, GS, MS, BAC, C, WFC |
| ESG / Clean Energy | NEE, ENPH, BEP, SEDG, FSLR |
| Healthcare Giants | JNJ, UNH, PFE, ABBV, MDT, TMO |
| Consumer Staples | PG, KO, PEP, CL, GIS, KMB |
| Global Macro | SPY, EFA, EEM, TLT, GLD, DBC |

---

## Run Locally

```bash
git clone https://github.com/harshilpatel1210/portfolio-analyzer.git
cd portfolio-analyzer
python3 -m http.server 8080
```

Then open **http://localhost:8080** in your browser.

---

## Tech Stack

| Layer | Tech |
|---|---|
| Structure | HTML5 |
| Styling | CSS3 (custom design tokens, dark mode, responsive grid) |
| Charts | Chart.js 4.4 |
| Heatmap | Pure Canvas API |
| Math engine | Vanilla JavaScript |
| Hosting | GitHub Pages |

---

## Disclaimer

All return, volatility, and beta figures are illustrative assumptions for demonstration purposes only. Not sourced from live market data. For educational use only — not financial advice.

---

## Author

**Harshil Patel** — [github.com/harshilpatel1210](https://github.com/harshilpatel1210)
