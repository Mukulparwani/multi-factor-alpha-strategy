# 🧠 Multi-Factor Alpha Strategy (NIFTY 50)

Created a rule-based stock ranking system using multi-factor analysis (Momentum, Volatility, Volume) on NIFTY 50 stocks. Stocks are scored monthly using normalized factor values, and top-ranked stocks are selected for portfolio simulation. Performance is benchmarked against NIFTY 50.

📊 **Strategy Return**: ~4.6%  
📈 **Benchmark Return (NIFTY 50)**: ~8.75%  
🧮 **Tools**: Python, Pandas, NumPy, yfinance, Matplotlib

## ⭐ Features
- NIFTY 50 stock list pulled using NSE API
- Factor construction (Momentum %, 1-Month Volatility, Avg Volume)
- Score-based stock ranking
- Monthly rebalancing strategy
- Backtest vs NIFTY 50 index

## 🔧 Future Work / Improvement Ideas

- 📌 **Factor Enhancement**: Include fundamental factors like ROE, ROCE, or earnings growth (using Screener.in or Tickertape APIs).
- 🧠 **Machine Learning**: Use ML models like Random Forest or XGBoost to assign dynamic weights to alpha factors.
- 💡 **Alpha Combination Optimization**: Test different weighting schemes or PCA-based factor reduction to improve scoring logic.
- 📆 **Higher Frequency Rebalancing**: Shift from monthly to bi-weekly or weekly rebalancing to capture short-term momentum.
- 🌐 **Broader Universe**: Expand beyond NIFTY 50 to mid-caps or entire NSE 500 for better alpha discovery.
- 📊 **Advanced Backtesting**: Include slippage, transaction costs, and position sizing for more realistic simulations.
