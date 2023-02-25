# Algorithmic trading using a simple moving average strategy

We fetch US stock intraday data using Alpha Vantage API and store the data in a pandas dataframe.

Define an indicator using Simple moving Average of stock price 'close' column over a specified time period. 

Generate 'signal' for BUY or SELL a stock based on a defined strategy : 

- BUY (when indicator cuts close upwards)
- SELL (when indicator cuts close downwards)
- NO_SIGNAL (when indicator and close do not cut each other)
