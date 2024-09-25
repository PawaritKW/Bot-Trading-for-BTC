# Introduction

Algorithmic trading involves using automated systems to execute trades based on predefined strategies, offering speed and efficiency in the dynamic cryptocurrency market. This report focuses on developing, backtesting, and evaluating algorithmic trading strategies for the BTC/USDT pair across various time intervals: 1 minute, 1 hour, 4 hours, and 1 day.

# Data Collection
 
- Live Data:
 - We used the Binance API to fetch the current price of BTC/USDT. This live data fetch is done using a function that sends a request to the Binance API and retrieves the latest price.
- Historical Data:
     - Historical price data was collected for the BTC/USDT trading pair using the Binance API.
     - Data was fetched for various intervals: 1 minute, 1 hour, 4 hours, and 1 day, with up to 1000 data points per request.
     - The data includes timestamps, open, high, low, close prices, and volume.

# Implement Trading Strategies 

SMA50: 
- The 50-day SMA is an intermediate-term moving average that offers a broader perspective on price trends

SMA200: 
- The 200-day SMA is a long-term moving average that provides a measure of the overall trend and acts as a significant support or resistance level.

Moving average convergence/divergence (MACD):
- MACD is a technical indicator to help investors identify price trends, measure trend momentum, and identify market entry points for buying or selling.

Fibonacci retracement:
- Fibonacci retracement levels stemming from the Fibonacci sequence are horizontal lines that indicate where support and resistance are likely to occur. Each level is associated with a percentage.
