# WhalePortfolio
Homework assignment 3
Create a box plot for each of the returns. Which box has the largest spread? Which has the smallest spread?


Calculate the standard deviation for each portfolio. Which portfolios are riskier than the S&P 500?


Calculate the annualized standard deviation (252 trading days).



Rolling Statistics


Plot the rolling standard deviation of the various portfolios along with the rolling standard deviation of the S&P 500 using a 21 day rolling window. Does the risk increase for each of the portfolios at the same time risk increases in the S&P?


Construct a correlation table for the algorithmic, whale, and S&P 500 returns. Which returns most closely mimic the S&P?


Choose one portfolio and plot a rolling beta between that portfolio's returns and S&P 500 returns. Does the portfolio seem sensitive to movements in the S&P 500?


An alternative way to calculate a rolling window is to take the exponentially weighted moving average. This is like a moving window average, but it assigns greater importance to more recent observations. Try calculating the ewm with a 21 day half-life.



Plot Sharpe Ratios
Investment managers and their institutional investors look at the return-to-risk ratio, not just the returns. (After all, if you have two portfolios that each offer a 10% return, yet one is lower risk, you would invest in the lower-risk portfolio, right?)


Using the daily returns, calculate and visualize the Sharpe ratios using a bar plot.


Determine whether the algorithmic strategies outperform both the market (S&P 500) and the whales portfolios.



Create Custom Portfolio
Harold is ecstatic that you were able to help him prove that the algorithmic trading portfolios are doing so well compared to the market and whales' portfolios. However, now you are wondering whether you can choose your own portfolio that performs just as well as the algorithmic portfolios. Investigate by doing the following:


Visit Google Sheets and use the in-built Google Finance function to choose 3-5 stocks for your own portfolio.


Download the data as CSV files and calculate the portfolio returns.


Calculate the returns for each stock.


Using those returns, calculate the weighted returns for your entire portfolio assuming an equal number of shares for each stock.


Add your portfolio returns to the DataFrame with the other portfolios and rerun the analysis. How does your portfolio fair?
