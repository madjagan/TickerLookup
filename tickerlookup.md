# Ticker Lookup.

There are many websites where free historical trading data can be got. Some of the prominent ones are:
- finance.yahoo.com
- investing.com

Some good APIs have been helped in accessing from this sites programmatically as well.
- yfinance
- investpy.
However, each of these sites follow their own convention to reference this symbol.

For example:
Company: 3 M India.
NSESymbol: 3MINDIA.
Symbol_yfinance:3MINDIA.NS
Symbol_investpy:TMIN

[/Users/Madhavan.J/OpenProjects/QuantTrader/PyNotebooks/HubProjects/TickerLookup/investingdotcom.png]
[./HubProjects/TickerLookup/yahoofinance.png]

We are primarily interested in fetching the historical data from these websites. There are several well published APIs to fetch the data.
However, each of these APIs require symbol which is specific to that website.

## The Goal
- To maintain a look up table of tickers which can be used for querying various APIs.
- 






