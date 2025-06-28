# BullBear-Engine
# Market-Neutral Momentum Alpha Engine 🚀

## Overview
This project implements a **market-neutral momentum trading strategy** designed during the InterIIT TechMeet Bootcamp 2024–25. The core objective was to **exploit relative price movements in NIFTY 50 stocks** by combining long and short positions, while neutralizing exposure to overall market direction (beta ≈ 0).

Our approach involves composite momentum scoring, dynamic entry-exit conditions, and strict risk management, all validated through backtesting.

---

## 📈 Key Features
- 📊 **Composite Momentum Scoring**: Uses RSI, MACD, ROC, ADX, and ATR to rank stocks.
- 🧠 **Three Hypothesis Strategies**:
  - Momentum + Volume-Based Strategy
  - Support/Resistance Breakout Confirmation
  - Simple ROC Momentum Filter
- ⚖️ **Market-Neutral Execution**: Simultaneous long/short allocation across ranked equities.
- 💡 **Dynamic Risk Management**: Stop-loss based on ATR, ADX, and volume dynamics.
- 📉 **Backtested Metrics**:
  - Cumulative Returns
  - Annualized Sharpe Ratio
  - Max Drawdown
  - Frequency of Trades

---

## 📊 Technical Indicators Used
- RSI (Relative Strength Index)
- MACD (Moving Average Convergence Divergence)
- ROC (Rate of Change)
- ADX (Average Directional Index)
- ATR (Average True Range)

Each indicator is weighted and contributes to a **composite momentum score**, which is used to rank and select top/bottom performing stocks.

---

## 🧪 Backtesting & Evaluation
Performance is evaluated using:
- Equity curve analysis
- Sharpe Ratio computation
- Drawdown statistics
- Trade logs

Backtests confirm robustness of hypotheses and validate entry-exit logic.

---

## 🛠️ Tools & Stack
- Python (Pandas, NumPy, TA-Lib)
- Backtrader / custom backtesting engine
- Matplotlib & Seaborn (for visualizations)
- Yahoo Finance API / CSV datasets

---

## 📁 Folder Structure
