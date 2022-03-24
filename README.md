# NETFLIX-Stock_Correlation

# Stock Correlation 

In this Notebook, lI analyze the following five semiconductor stocks: `HD`, `INTC`, `AMD`, `MU`, `NVDA`, and `TSM`. Then, Ichoose the stock with the least correlation to `JNJ` in order to diversify a portfolio. The data was generated using the [GOOGLEFINANCE](https://support.google.com/docs/answer/3093281?hl=en) historical market data script.

To learn more about diversification and how correlation in a portfolio helps to minimize risk, review this [article on diversification](https://www.investopedia.com/terms/d/diversification.asp).

## Steps

1. I Imported the Pandas and Plotly Express libraries.

2. Read the CSV file into a DataFrame and set the date column as the index.

3. Used the `pct_change` function to calculate the daily returns.

4. Dropped any rows with missing data.

5. Created a correlation matrix. 

6. Created a heatmap using the correlation matrix. 

7. Useed the `unstack` function to find the best stock pair for diversification.

8. Last, I explain which semiconductor stock would be the best candidate to add to the existing portfolio and why.
