This project is about grouping companies listed on the Nepal Stock Exchange (NEPSE) based on their stock market behaviour. I used K-Means clustering to find companies with similar stock performance and understand their risk and liquidity patterns. The main goal is to see how different companies behave in the stock market.

Methodology

For this project, I used NEPSE stock prices, market indices, company information and dividend data. I selected 240 companies with at least 500 trading days and calculated features such as returns, volatility, maximum drawdown, turnover and beta. Then, I used StandardScaler, PCA and K-Means clustering to divide the companies into four groups. I also compared the results with sectors, market capitalisation and dividends.

Results and Conclusion

The model created four different groups of companies based on their stock behaviour. The results are shown using charts and tables in the Jupyter Notebook. The model has some limitations, such as low silhouette score and possible survivorship bias, so the results may change depending on the selected time period. This project is only for learning and analysis purposes and should not be considered investment advice.

