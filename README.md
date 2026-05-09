# Breakout Momentum Trading System

An algorithmic trading backtest in Python. Tests a breakout strategy with momentum confirmation on historical stock data.

---

## How It Works

- Downloads stock price data from Yahoo Finance
- Generates buy/sell signals when price breaks a 20-day high/low and RSI confirms momentum
- Simulates trades with stop losses, take profits, and position sizing
- Reports win rate, profit factor, and max drawdown

---

## Setup

```
pip install yfinance pandas numpy matplotlib curl_cffi
```

Run the notebook top to bottom. Change `TICKER`, `START_DATE`, and `END_DATE` at the top to test different stocks or time periods.

---

## Limitations

- No transaction costs or slippage modelled
- For learning purposes only — not a live trading system

---

## Resources

- [RSI (Investopedia)](https://www.investopedia.com/terms/r/rsi.asp)
- [Breakout Trading (Investopedia)](https://www.investopedia.com/terms/b/breakout.asp)
- [Momentum Trading (Investopedia)](https://www.investopedia.com/terms/m/momentum.asp)
