# Stock_close_price_forecast

How to do data visualization and time series forecast on stock price dataset?

1. Download the NVDA stock price dataset from Yahoo Finance python API on 30 days 5 minutes timeframe.

2. Plot Close price versus datetime to visualize the general trend for past 30 days.

3. With Long Short-Term Memory model, do input single feature (Close) to forecast the next 1 trading day Close price. The input length is 234 5 minutes, and output length is 78 5 minutes.

4. With Long Short-Term Memory model, do multi features (Close, High, Low, Open, Volume) to forecast the next 1 trading day Close price. The input length is 234 5 minutes, and output length is 78 5 minutes.
