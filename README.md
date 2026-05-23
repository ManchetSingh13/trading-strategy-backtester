
# Trading Strategy Backtester
**R · quantmod · TTR · PerformanceAnalytics · plotly · R Markdown**

Backtests three systematic equity trading strategies on any stock 
ticker using free Yahoo Finance data. Built as part of my quantitative 
finance research alongside active options trading.

## Strategies
| Strategy | Type | Signal |
|---|---|---|
| Golden Cross | Trend following | 50-day MA crosses above 200-day MA |
| RSI Mean Reversion | Contrarian | RSI < 30 = buy, RSI > 70 = sell |
| 12-Month Momentum | Momentum | Long when 12-month return is positive |

## Key features
- Sharpe ratio, max drawdown, annualized return, win rate per strategy
- Look-ahead bias prevented — all signals lagged one trading day
- Interactive plotly charts — equity curves, drawdown, indicator plots
- Fully parameterized — change ticker and dates at the top and re-knit
- 100% free data — Yahoo Finance via quantmod, no API key needed

## Live report
[[Click here to view the interactive report]]
https://manchetsingh13.github.io/trading-strategy-backtester/backtester_final.html

## How to run locally
1. Clone this repo
2. Open `backtester_final.Rmd` in RStudio
3. Install packages (instructions inside the file)
4. Change `ticker` and dates in the params block
5. Click Knit

## Built with
R, quantmod, TTR, PerformanceAnalytics, plotly, kableExtra, DT, xts

## Author
Manchet Singh — [LinkedIn](https://linkedin.com/in/yourprofile)
University of Georgia — B.S. Data Science, Minor in Statistics
