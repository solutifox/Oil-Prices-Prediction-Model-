## Time Series For Predicting Oil Prices 

###### Oil, one of the most important commodities in the world, exhibits wide fluctuation. Its fluctuation has a big impact on many industries and economies. Instability in oil prices can cause economic instability for both oil exporting and oil consuming countries. Therefore, forecasting oil prices is important for world markets and policy makers.  The reason we are creating this model is because of how linked the health of the economy is to oil prices. Whenever there is a turmoil in oil prices, the economy is affected drastically 

###### Before applying a statistical model on the series, the series must be stationary. After examining our data, we have observed that our time series is not stationary. Also, we observed that the data was missing weekends oil prices, so we set our data frequency to business days instead of weekdays. 

###### ARIMA (Auto Regressive Integrated Moving Average) is a combination of 2 models AR (Auto Regressive) & MA (Moving Average). The ARIMA model adds differencing to an ARMA model. Differencing subtracts the current value from the previous and can be used to transform a time series into one that is stationary. 

###### Forecasting in general is tough. In practice, advanced models do well on in-sample forecasts but not so great out in the wild, as compared to more simpler models. ARIMA models occupy that middle-range area of being simple enough to not overfit while being flexible enough to capture some of the types of relationships you would see in the data. 

###### We were able to learn more about the applications of time series techniques to solve real world problems. Forecasting future events is not always a straightforward process; however, time series models can help us make assessed decisions which can help reduce risks and increase return. Constructing a reliable forecasting models are important when predicting behaviors of market movements. The next step of this project is to further evaluate the model and improve its performance. 
