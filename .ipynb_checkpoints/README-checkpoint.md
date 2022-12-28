# SP500 Stock Market Prediction using Machine Learning

The stock market has a wealth of data, statistics, and analytics that can be applied to it, making it a great machine learning tool for beginners. The purpose of this project is to explore financial data and try applying rudimental machine learning models to it (not necessarily to achieve "good" results).

In this project, we extract data, examine existing features and create new ones. We then determine if we want to buy or sell stocks in the market using rudimental machine learning models. The project is separated into two parts:

**1. Regression for Trading**  
1. Extract open, close and volume data for SP500 stocks.
2. Create indicators: 
    * EMA: https://www.investopedia.com/terms/e/ema.asp  
    * MACD: https://www.investopedia.com/terms/m/macd.asp  
    * RSI: https://www.investopedia.com/terms/r/rsi.asp  
    * Bollinger Bands: https://www.investopedia.com/terms/b/bollingerbands.asp
    * % Change of each indicator
3. Apply a regression model (from sklearn) and evaluate it by comparing model trading decisions to equally investing in all stocks.

**2. Classification for Investing**
1. Extract yearly financial information SP500 stocks.
2. Create financial ratio indicators. (Extracting all the data takes a while, so I have attached a copy: **`combined.csv`**.) Some of the ratios are on the following cheat sheet: https://cheatography.com/reccur/cheat-sheets/financial-ratios/
3. Apply a classification model (from sklearn) and evaluate it by comparing model trading decisions to equally investing in all stocks.