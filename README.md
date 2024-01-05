# Stock Portfolio Optimization

## Description

This project is a Python-based Stock Portfolio Optimization tool that aims to assist investors in maximizing returns while minimizing risk. It leverages historical stock price data from Yahoo Finance to construct a diversified portfolio. The optimization process considers factors such as expected returns, volatility, and correlations between stocks.This Python script demonstrates stock portfolio optimization using historical stock prices of Apple Inc. (AAPL), International Business Machines Corporation (IBM), and Amazon.com Inc. (AMZN). The optimization process involves calculating normalized returns, defining portfolio allocations, and analyzing portfolio performance metrics such as daily returns, cumulative return, Sharpe ratio, and more.

## Prerequisites
Make sure you have the necessary Python libraries installed:
pip install numpy pandas matplotlib seaborn statsmodels pandas_datareader yfinance

## Code Explanation

### Data Retrieval
- The script starts by importing the required libraries for data analysis and visualization.
- Historical stock prices are fetched using the Yahoo Finance API for AAPL, IBM, and AMZN from January 1, 2022, to December 31, 2022.

### Data Exploration
- The script prints the first few rows of the adjusted closing prices for each stock.

### Stock Information
- Information about AAPL, obtained from the Yahoo Finance API, is printed.

### Portfolio Allocation
- The script defines a portfolio allocation strategy (20% to AAPL, 30% to IBM, and 50% to AMZN) and calculates the normalized returns for each stock.

### Portfolio Value
- The portfolio value is calculated based on the initial investment of $500,000.

### Portfolio Statistics
- Daily returns, mean daily return, standard deviation of daily return, cumulative return, and Sharpe ratio are calculated and printed.
- The distribution of daily returns is visualized using a histogram and KDE plot.

### Portfolio Optimization
- Mean daily return, correlation between stocks, log returns, and covariance of stock returns are calculated.
- Random portfolio weights are generated, and the expected portfolio return, volatility, and Sharpe ratio are computed.
- The script then performs a simulation to find the optimal portfolio allocation with the highest Sharpe ratio.

### Results
- The optimal portfolio allocation: 0.4% to AAPL, 99.4% to IBM, and 0.2% to AMZN.
- Maximum Sharpe ratio achieved: 0.34.
- Scatter plot visualizing the efficient frontier with color-coded Sharpe ratios.

## Conclusion

The script provides insights into portfolio optimization by considering historical stock prices. It analyzes the performance of a given portfolio allocation strategy and identifies an optimal allocation for maximizing the Sharpe ratio. Users can use this as a starting point for further exploration and customization based on their investment goals and risk tolerance.

## Usage

Feel free to adapt the code for different stocks, time periods, or optimization criteria according to your preferences.





