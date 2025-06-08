# Quant Momentum Strategies

This project implements and backtests a simple momentum-based trading strategy using moving average crossovers. It is designed to demonstrate core quantitative finance skills: signal generation, backtesting, and performance evaluation.

## 📈 Strategy Overview

- **Instrument**: SPY (S&P 500 ETF)
- **Logic**: Buy when 50-day MA > 200-day MA, sell when 50-day MA < 200-day MA
- **Data Source**: [Yahoo Finance](https://finance.yahoo.com/) via `yfinance`

## 📊 Metrics Reported

- Cumulative Return
- Sharpe Ratio
- Maximum Drawdown
- Trade Count
- Win Rate

## 🔧 How to Run

1. Install dependencies:

```bash
pip install -r requirements.txt
