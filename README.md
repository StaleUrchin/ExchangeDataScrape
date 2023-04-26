ExchangeDataScrape pulls exchanges and level 1 financial data in a two step process.

The first step requires StockSymbol API which can be found here: 

https://stock-symbol.herokuapp.com/

StockSymbol was created by Yongthong Tan and is licensed by MIT and is accessible on Python3.7 and higher 

As of version0.0.5, all listings were last updated on 2022-01-10

Package information can be found here: 

https://pypi.org/project/stocksymbol/

The second step is to pull all listed symbols within the desired market/index and scrape financials via yfinance.
