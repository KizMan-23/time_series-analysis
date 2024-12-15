Time_Series Analysis involves working with data points indexed in time order to analyze patterns, trends, and seasonal effects, and to make forecasts. 
Time series analysis is very crucial for time-dependent events such as business or wheather to understandsuch events and gain more insights using past data to better understand possible future occurances. 
Due to the important nature of time-based data, the [statsmodel.tsa](https://www.statsmodels.org/stable/tsa.html) was developed as a python package to enable working with these time-based data 
and understanding them.

[apple stock](apple_stock.ipynb) and [stock_data](stock_tsa.ipynb) are stock based time analysis. apple stock analysis stock data from AAPL stock using pandas and scikit-learn while stock_data project uses TSLA stock for  analysis using statsmodel.tsa to understand the numbers, figure out patterns, trend and use past information to make future predictions.

The use of scikit-learn on time-bases data applies classical machine learning techniques; regression and classification to model the data, analyze the patterns and predict the future.
Statsmodel.tsa developed mainly for time series data analysis adopts the model of attaining stationarity of the features across the timedelta. Stationarity means that the mean and standard deviation of the 
features will remain consistent over period of time and this can be checked using the Augmented Dickey-Fuller (ADF) test and fitting the data to ARIMA OR SARIMA(X) models.

Pandas framework offer resample() function to understand and analyze time-based data accordingly finding patterns and trends.

[Rain Test](rain_test.ipynb) is another type of time series data focusing on wheather use cases. Understanding and prediction for wheather as seen in wheather forecastings can be done using statsmodel.tsa to offer a more robuts and longer future predictions for wheather conditions.

[Sales TSA](sales_tsa.ipynb) is a typical business data that can be analyzed using the statsmodels.tsa model. Analyzing and understanding business data remains increasingly necessarily in order to find patterns,
streamline and boost operations and most importantly boost business growth.
