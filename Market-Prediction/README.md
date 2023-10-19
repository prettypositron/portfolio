# Market-Prediction
Market Prediction using NLP Sentiment Analysis and DL Models
# Crypto Forecasting

**Hierarchical Time-Series (HTS)** means that time-series models will be merged into ensembles.

**Models**
1.1 For extrapolation of time-series data I will use an ensemble of neural nets likely fully-connected (FC), Tabnet, and AutoEncoders
1.2 Simple models will be LGB, XGB, Catboost, HistGBM
1.3 Will use ARIMA, SARIMAX for their unique features when ensembling
1.4 Ensemble and stack
1.5 I initally wished to create a pure LSTM, but I have been having issues with these

**Advanced Features**
2.1 Fancy Loss Function : this is going to be a bitch. 
2.2 Sample weights that catalyze the NN to work better
2.3 Incorporation of prior knowledge from the dataset into the network architecture

**Implementations**

| CV (Cross-Validation) + Model | Hyperparameter Optimization | Time-Series Models | Feature Engineering |
|---|---|---|---|
| NN | MLP + AE | LSTM | Technical Analysis |
| 

# Applying Legacy Asset Class Correlations to Cryptocurrencies

Stocks and T-Bonds have a negative correlation coefficient. When consumers are spending and the economy is expanding, you will see a rise in the prices of stocks. During times of economic contraction, you will instead see a rise in the yields of T-Bonds. Investors can also exploit the absence of correlation like gold which has a low to almost-no correlation with equity markets to weather the storm of economic turmoil.

As cryptocurrency undergoes a shift from retail investors to institutional investors, it has been difficult to predict a pattern in cryptocurrency prices which can swing with investor whims. The best we can do is investigate correlations. 

One example is the correlation between the price of BTC with the rate of inflation, which makes sense in theory but a country like Venezuela presents an example contrary to this assertion. 

>Among cryptocurrency assets with substantial valuations, correlation is an on-and-off affair. Bitcoin prices have set investor and price momentum in crypto markets for most of the last decade. Lately, however, as other cryptocurrencies have garnered popularity with developers and investors, that correlation has proven difficult to maintain. For example, bitcoin prices fell even as prices for Ethereum’s ether (ETH) rose to new heights in early 2018. - [Correlations Within The Context of Cryptocurrencies](https://www.gemini.com/cryptopedia/asset-correlation-between-cryptocurrencies#section-establishing-correlations-between-cryptocurrencies)
