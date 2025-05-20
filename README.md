
# Quant Portfolio Optimization – VN30 Strategy

This project implements a rule-based quantitative trading strategy on VN30 stocks, evaluates backtested returns versus VNINDEX, and constructs an efficient frontier using top-performing stocks from the best sector (by Top25 ratio).

## Features

- Technical indicators: SMA, Volume MA, ATR, RSI, MACD, Bollinger Bands, Stochastic
- Strategy logic: all indicators must confirm Buy, any confirms Sell
- Backtest: Compares each stock’s performance vs VNINDEX
- Sector classification using `vnstock.screener`
- Selects top sector based on performance ratio
- Builds portfolio of 10 top stocks in that sector
- Efficient Frontier visualization with optimal portfolio

## Tools

- Python 3.x
- Libraries: vnstock, pandas, numpy, matplotlib

## Author

Hoàng Công Đăng Khoa  
MSc Financial Engineering (WQU), CFA Level 2 Candidate
