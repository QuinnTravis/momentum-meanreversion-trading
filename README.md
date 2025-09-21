# momentum-meanreversion-trading


This project implements and backtests two classic trading strategies — **momentum** and **mean reversion** — using historical S&P 500 data.

## 🚀 Project Overview
- **Momentum Strategy**: Buy when recent returns are positive, sell/hold cash when negative.  
- **Mean Reversion Strategy**: Buy when the stock is below its moving average, sell when it’s above.  

Both strategies are compared against a baseline of simply holding the S&P 500.

## 📂 Files
- `Momentum_Mean_Reversion.ipynb` — Jupyter/Colab notebook with full code.  
- `all_stocks_5yr.csv` — Stock data of S&P500 from 2013-2018

  
## 📊 Results
- Plots cumulative returns of strategies vs benchmark.  
- Evaluates Sharpe ratio, drawdowns, and volatility.  
- Shows parameter sensitivity (different windows for momentum and MA).  

## 🛠️ Tech Stack
- Python, Pandas, NumPy, Matplotlib  


