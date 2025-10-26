# 📈 Quantitative Trading Strategies — Momentum & Mean Reversion

### 🧠 Overview
This project implements and compares two classical **quantitative trading strategies** using historical S&P 500 stock data:

1. **Momentum Strategy** → trend-following: buy when prices rise, sell when they fall.  
2. **Mean Reversion Strategy** → contrarian: buy when prices drop below average, sell when above.

Each model is tested, optimized, and evaluated using:
- **Sharpe Ratio** – risk-adjusted performance  
- **Maximum Drawdown** – downside risk  
- **Cumulative Returns** – long-term portfolio growth  

The notebook includes parameter optimization (grid search), modular functions, and clear step-by-step documentation to simulate a real quant research workflow.

---

### ⚙️ Tech Stack
| Category | Tools |
|-----------|-------|
| **Languages** | Python 3 |
| **Libraries** | Pandas · NumPy · Matplotlib |
| **Environment** | Google Colab / Jupyter Notebook |
| **Data Source** | `all_stocks_5yr.csv` (public Kaggle dataset) |

---

### 🧩 Features
- Modular backtesting framework for both strategies  
- Sharpe ratio & drawdown utility functions  
- Parameter grid search for the best lookback window  
- Benchmark comparison vs. S&P 500  
- Publication-quality visualization with annotated metrics  
- Fully commented step-by-step notebook (great for learning or interviews)

---

### 🪄 Example Output
Example performance for **AAPL (2013 – 2018)**:

![Strategy Performance](results/strategy_performance.png)


