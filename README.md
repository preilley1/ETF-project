# ETF-Capstone
Data Science Immersive, General Assembly, October 2018.

## Predicting the price of an ETF using the prices of other correlated and uncorrelated pricing.

This repository is for experimenting in future price prediction.
This would really work with any type of time series data but this focuses on ETF prices.  Specifically an ETF tracking the S&P 500 index.

I ran through many interations in different notebooks and used different techniques, some of which I added to the final notebook where it was applicable.  Most of the notebooks were created with different ways to train and test the data.  As I researched the project, I found many different techniques to do handle this.  The final product is a combinatino of training and testing.  I held the last 10% of the data to the side and trained and tested on the first 90% to make sure the model was working.  From there I tested the model on the remaining 10%. 

It was a challenging project for me as, full disclosure, my coding expertise before the course started was nill so the coding was really the challenging part for me.


These are a couple of good articles on walk forward validation for time series data which I was not able to implament in time but something I will be taking a look at moving forward.

https://ntguardian.wordpress.com/2017/06/19/walk-forward-analysis-demonstration-backtrader/

https://machinelearningmastery.com/backtest-machine-learning-models-time-series-forecasting/
