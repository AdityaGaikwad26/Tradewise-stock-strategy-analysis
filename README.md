# Tradewise-stock-strategy-analysis
20/50 moving average crossover backtest on top 20 Nifty 50 stocks (Python)
# TradeWise: Stock Strategy Analysis

Backtest of a 20/50 day moving average crossover on the 20 most liquid Nifty 50 stocks, Jun 2018 to Jun 2023, starting each stock with Rs 1,00,000.

## What I did
- Cleaned 238,885 rows of Nifty 50 price data (blank rows, text dates, empty columns, index series)
- Picked the top 20 of 46 eligible stocks by average traded value
- Computed total return, annualized return, max drawdown, Sharpe ratio, win/loss ratio and trade count, with a yearly breakdown
- Answered 12 objective and 5 subjective questions with charts

## Results
- 18 of 20 stocks had a positive annualized return, but buy and hold did better on raw return in 14 of 20
- Equal-weight portfolio: 14.9% a year, max drawdown -17.4%, Sharpe 1.22 vs buy and hold 21.8%, -43.3%, 0.99
- Only 123 of 269 trades (46%) were profitable
- Best fits: Bajaj Finserv, ITC, Tata Steel, ICICI Bank

## Limitations
No brokerage, taxes or slippage; one fixed 20/50 pair; five-year window dominated by the 2020 crash and recovery. Academic analysis, not financial advice.

## Tools
Python (Pandas, NumPy, Matplotlib, Seaborn), Jupyter
