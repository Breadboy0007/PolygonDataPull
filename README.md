# PolygonDataPull
Data pull from polygon.io

Must have API key from Polygon.io.  They offer an awesome free version, but it's limited to 2 years of historical data and 5 requests per minute.  Upgrading to the next tier seems highly worth it.

Given a time period and a stock ticker, this script returns a dataframe with 13 30-min bars for each full trading day (6.5 hrs) within the specified time period. 

To use, insert API key for 'API key', insert starting epoch in ms and as a string for after, ending epoch in ms and as a string for last, and stock ticker as a string for ticker.
