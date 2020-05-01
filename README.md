# Capital-Markets-Challenge

For the first part of the challenge I used this API url="https://www.alphavantage.co/query?function=TIME_SERIES_DAILY_ADJUSTED&symbol=AAPL&apikey="+demo. By default, outputsize=compact. Strings compact and full are accepted with the following specifications: compact returns only the latest 100 data points in the intraday time series; full returns the full-length intraday time series. The "compact" option is the one I used to reduce the data size of each API call.
I chose the the top 10 tech companies to run my APIs and from there I started my ETL until I get the final clean up tables and graphs. 

For the second part I used Yahoo Finance to extract the most relevant Indexes that track stocks: DJIA, S&P and NASDAQ. Using Pandas I did my ETLs to get the final tables and graphs for each Index. 


