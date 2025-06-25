# Arbitrage2: Cross-Exchange Crypto Arbitrage Bot

## 📈 Overview

**Arbitrage2** is a Python-based notebook project for detecting and executing cross-exchange arbitrage opportunities in the cryptocurrency market.  
Built with [ccxt](https://github.com/ccxt/ccxt) for multi-exchange integration, it scans price discrepancies between exchanges (like Binance, Kraken, Coinbase, etc.), computes potential profit after fees, and demonstrates backtesting or live trade logic.

This notebook serves as both a research tool and a development base for real-time arbitrage trading.

---

## 🚀 Features

- **Multi-Exchange Integration:** Easily connect to dozens of exchanges with [ccxt].
- **Live Price Monitoring:** Continuously fetches and compares asset prices across exchanges.
- **Arbitrage Detection:** Identifies opportunities based on user-defined thresholds, accounting for trading fees.
- **Backtesting & Visualization:** Simulate trades and visualize results using `matplotlib`.
- **Modular Code:** Easily extend for more assets, exchanges, or trading logic.

---

## 🛠️ Installation

Clone this repo (or download the notebook), then install requirements:

```bash
pip install ccxt pandas matplotlib
```

You’ll also need a valid Python 3 environment (recommended: 3.8+).

---

## ⚡ Usage

1. **Open** `arbitrage2.ipynb` in [Jupyter Notebook](https://jupyter.org/) or [Google Colab].
2. **Edit** the configuration section to set your target exchanges, trading pairs, and API keys (if needed).
3. **Run** the cells in order. The notebook will:
   - Load required libraries
   - Connect to exchanges via CCXT
   - Fetch live prices or historical data
   - Scan for arbitrage opportunities
   - (Optionally) Simulate or execute trades

**Note:**  
If you want to place real trades, you must add your API credentials in the config section and unlock trading permissions at your own risk.

---

## 📊 Customization

- **Add More Exchanges:** Just add their CCXT names to the exchanges list.
- **Change Assets:** Set your target symbol/pair (e.g., BTC/USDT).
- **Adjust Arbitrage Logic:** Edit profit threshold, fee structure, or signal logic as needed.

---

## 🤝 Contribution

Feel free to fork, modify, and submit pull requests!  
If you find bugs or want new features, open an [issue](https://github.com/niwek1/arbitrage2/issues).

---

## 👤 Author & Contact

Project by **niwek1**  
For questions, collaboration, or consulting, [connect on LinkedIn](https://www.linkedin.com/in/niwek1) or open a GitHub issue.

---

## ⚠️ Disclaimer

> This notebook is for educational and research purposes only. Crypto trading carries risk. Use real-money trading at your own discretion.
