# Backtesting
Simple Backtester w/ Yahoo Finance-

I struggled for a long time to find a good simple backtester. I was using one that was highly regarded, but it was nearly impossible to simply test all your portfolio. Rather it would only enable one ticker at a time. So here's my take on a simple backtesting script.

Getting to Run:
Make sure to edit save file location for Yahoo CSV's. I.e. both locations below:

def SaveData(df, filename):
        df.to_csv("C:/Users/james/Desktop//Backtester/Stocks" + filename + '.csv')

getData(yfinance_ticker,time)
df = pd.read_csv("C:/Users/james/Desktop//Backtester/Stocks" + yfinance_ticker + '.csv')

Tweaking Strategy:
To edit strategy, simply add/edit to the indicators section. Also add/edit to the run strategy section. That strategy in there is one that I found to be pretty good on another backtester. I actually had that strategy trading live in a robin-stocks bot for a while.

I'm not a financial advisor, nor is this financial advice. This is simply a tool and I am a novice programmer who enjoys automating trades. Did I mention I'm a self-taught novice. 

Cheers!
