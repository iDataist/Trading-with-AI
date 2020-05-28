# Trading-with-AI

## Trading with Momentum
I implemented the momentum trading strategy, and tested if it has the potential to be profitable. For the dataset, I used the end of day from Quotemedia. I computed the signal and applied it to the dataset to produce projected returns. Finally, I performed a statistical test on the mean of the returns to check if there is alpha in the signal.

## Breakout Strategy
I implemented the breakout strategy. For the dataset, I used the end of day from Quotemedia. I found and removed any outliers. I also tested to see if it has the potential to be profitable using a Histogram and P-Value.

## Smart Beta and Portfolio Optimization
I built a smart beta portfolio and compared it to a benchmark index. To find out how well the smart beta portfolio did, I calculated the tracking error against the index. I then optimized the weights by using quadratic programming. I rebalanced the portfolio with the optimized weights and calculated turn over to evaluate the performance. I used the turn over metric to find the optimal rebalancing Frequency. For the dataset, I used the end of day from Quotemedia.

## Alpha Research and Factor Modeling
I built a statistical risk model using PCA. I used this model to build a portfolio along with 5 alpha factors. I created these factors, then evaluated them using factor-weighted returns, quantile analysis, sharpe ratio, and turnover analysis. I optimized the portfolio using the risk model and factors using multiple optimization formulations. For the dataset, I used the end of day from Quotemedia and sector data from Sharadar.

## NLP on Financial Statements
I performed a NLP Analysis on 10-k financial statements to generate an alpha factor. For the dataset, I used the end of day from Quotemedia and Loughran-McDonald sentiment word lists.

## Sentiment Analysis with Neural Network
I built a deep learning model to classify the sentiment of messages from StockTwits, a social network for investors and traders. I used the model to predict if any particular message is positive or negative. I then generated a signal of the public sentiment for various ticker symbols.

## Combining Signals for Enhanced Alpha
I combined signals on a random forest for enhanced alpha. While implementing this, I also solved the problem of overlapping samples. For the dataset, I used the end of day from Quotemedia and sector data from Sharadar.

## Backtesting
I built a backtester that uses the Barra data. The backtester performed portfolio optimization that includes transaction costs. I implemented it with computational efficiency in mind, to allow for a reasonably fast backtest. I also used performance attribution to identify the major drivers of the portfolio's profit-and-loss (PnL).
