![st moving avg](https://github.com/user-attachments/assets/0e6db7b3-7874-406d-bd19-ab76ec5e1b3f)Time_Series Analysis involves working with data points indexed in time order to analyze patterns, trends, and seasonal effects, and to make forecasts. 
Time series analysis is very crucial for time-dependent events such as business or wheather to understand such events and gain more insights using past data to better understand possible future occurances. 
Due to the important nature of time-based data, the [statsmodel.tsa](https://www.statsmodels.org/stable/tsa.html) was developed as a python package to enable working with these time-based data 
and understanding them.

[apple stock](apple_stock.ipynb) and [stock_data](stock_tsa.ipynb) are time based stocks analysis. Apple stock analysis stock data from AAPL stock using pandas and scikit-learn while stock_data project uses TSLA stock for  analysis using statsmodel.tsa to understand the numbers, figure out patterns, trend and use past information to make future predictions.

![apple close](https://github.com/user-attachments/assets/88873ff7-f25e-4b6c-aaa2-34736b5d4170)

The use of scikit-learn on time-bases data applies classical machine learning techniques; regression and classification to model the data, analyze the patterns and predict the future.

![st moving avg](https://github.com/user-attachments/assets/ce699b9d-4a68-4946-bbb3-17294936e54d)

Statsmodel.tsa developed mainly for time series data analysis adopts the model of attaining stationarity of the features across the timedelta. Stationarity means that the mean and standard deviation of the 
features will remain consistent over period of time and this can be checked using the Augmented Dickey-Fuller (ADF) test and fitting the data to ARIMA OR SARIMA(X) models.

![st stationarity](https://github.com/user-attachments/assets/5fdba1e0-faa0-46c5-ab46-f0d9ae37335c)

![st moving avg](https://github.com/user-attachments/assets/ce4f5b54-d3a2-4273-ae1c-68403b327b65)

Pandas framework offer resample() function to understand and analyze time-based data accordingly finding patterns and trends.

![st resampling](https://github.com/user-attachments/assets/5a858953-d0cd-4f8e-ac57-472efad9e652)

[Rain Test](rain_test.ipynb) is another type of time series data focusing on wheather use cases. Understanding and prediction for wheather as seen in wheather forecastings can be done using statsmodel.tsa to offer a more robuts and longer future predictions for wheather conditions.

![wheather 1](https://github.com/user-attachments/assets/f44481dc-247b-4efc-96ef-254560eac5c1)

![wheatjer 2](https://github.com/user-attachments/assets/f37c1f9f-aeb9-4ec9-bff9-304972782a77)

[Sales TSA](sales_tsa.ipynb) is a typical business data that can be analyzed using the statsmodels.tsa model. Analyzing and understanding business data remains increasingly necessarily in order to find patterns,
streamline and boost operations and most importantly boost business growth.

![sales pacf   acf](https://github.com/user-attachments/assets/4e43cfbc-78d5-44e6-b69c-a569b40bec8f)
