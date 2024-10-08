# Stock-Portfolio-Tracker_Code-Alpha
This is a simple Stock Portfolio Manager written in Python that allows users to track and manage their stock investments. It utilizes the yfinance library to fetch real-time stock data, including current prices, and calculates the performance of each stock in the user's portfolio based on the number of shares and purchase prices.

*Features*
1. Add Stocks: Add a stock to the portfolio by specifying the stock ticker, the number of shares, and the purchase price.
2. Remove Stocks: Remove a stock from the portfolio by specifying the stock ticker.
3. View Portfolio: Display all the stocks in the portfolio, including the current market price and the performance (gain or loss) for each stock based on the difference between the current price and purchase price.
4.  Track Performance: The total performance of the portfolio is displayed, helping users keep track of their overall investment gains or losses.

*How it Works*
1. The program fetches real-time stock data from Yahoo Finance using the yfinance library.
2. Users can add stocks by entering the stock ticker, the number of shares, and the purchase price.
3. The portfolio stores the stocks with the associated details, and users can view the portfolio to see the performance of their investments.
4. Users can remove stocks from the portfolio as needed.
   
*Technologies Used*
Python 3.x

yfinance: A Python library for fetching real-time stock market data from Yahoo Finance.

*Requirements*

Python 3.x

yfinance (You can install it via pip install yfinance)
