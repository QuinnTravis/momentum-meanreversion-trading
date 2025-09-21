# momentum-meanreversion-trading


This project implements and backtests two classic trading strategies — **momentum** and **mean reversion** — using historical S&P 500 data.

## 🚀 Project Overview
- **Momentum Strategy**: Buy when recent returns are positive, sell/hold cash when negative.  
- **Mean Reversion Strategy**: Buy when the stock is below its moving average, sell when it’s above.  

Both strategies are compared against a baseline of simply holding the S&P 500.

## 📂 Files
- `momentum_meanreversion.ipynb` — Jupyter/Colab notebook with full code.  
- `sp500.csv` — Historical price dataset (can be replaced with your own data).  

## 📊 Results
- Plots cumulative returns of strategies vs benchmark.  
- Evaluates Sharpe ratio, drawdowns, and volatility.  
- Shows parameter sensitivity (different windows for momentum and MA).  

## 🛠️ Tech Stack
- Python, Pandas, NumPy, Matplotlib  

## ✨ Next Steps
- Add transaction costs for realism  
- Try multi-asset trading (pairs)  
- Test on different time periods  

---
