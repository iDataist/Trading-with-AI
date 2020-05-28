# Trading-with-AI

## Trading with Momentum
I implemented a momentum trading strategy and tested if it has the potential to be profitable. I worked with historical data of a given stock universe and generated a trading signal based on a momentum indicator. I then computed the signal and produced projected returns. Lastly, I performed a statistical test to check if there is alpha in the signal. I used the end of day from Quotemedia as the dataset.

## Breakout Strategy
I implemented and evaluated a breakout signal. I run statistical tests to test for normality and to find alpha. I also found outliers and evaluated the effect that filtered outliers could have on the trading signal. I run various scenarios of the model with or without the outliers and decide if the outliers should be kept or not. I used the end of day from Quotemedia as the dataset.

## Smart Beta and Portfolio Optimization
I created two portfolios utilizing smart beta methodology and optimization. I evaluated the performance of the portfolios by calculating tracking errors. I also calculated the turnover of the portfolio and found the best timing to rebalance. I came up with the portfolio weights by analyzing fundamental data, and by quadratic programming. I used the end of day from Quotemedia as the dataset.

## Alpha Research and Factor Modeling
I researched and generated multiple alpha factors. Then I applied various techniques to evaluate the performance of the alpha factors and picked the best ones for the portfolio. I formulated an advanced portfolio optimization problem by working with constraints such as risk models, leverage, market neutrality and limits on factor exposures.

## NLP on Financial Statements
I applied Natural Language Processing on corporate filings, such as 10Q and 10K statements, from cleaning data and text processing, to feature extraction and modeling. I utilized bag-of-words and TF-IDF to generate company-specific sentiments. Based on the sentiments, I decided which company to invest in, and the optimal time to buy or sell.

## Sentiment Analysis with Neural Network
I built deep neural networks to process and interpret news data. I tested different ways of embedding words into vectors. I constructed and trained LSTM networks for sentiment classification. Lastly, I run backtests and applied the models to news data for signal generation.

## Combining Signals for Enhanced Alpha
I combined signals on a random forest for enhanced alpha. While implementing this, I also solved the problem of overlapping samples. For the dataset, I used the end of day from Quotemedia and sector data from Sharadar.

## Backtesting
I built a backtester that uses the Barra data. The backtester performed portfolio optimization that includes transaction costs. I implemented it with computational efficiency in mind, to allow for a reasonably fast backtest. I also used performance attribution to identify the major drivers of the portfolio's profit-and-loss (PnL).
