# Stock_Market_Prediction
Stock Market Prediction using Linear Regression, SARIMA and LSTM models. </br><hr>
Predicting stock prices has been a popular topic in both financial and academic fields, and an increasing number of people are trying to ascertain this problem. There are different ways of moving toward this problem. In the past, fundamental analysis, technical analysis, and quantitative analysis have been conducted, but building predictive models using ML knowledge has become more famous. In this project, I have tried different models, such as linear regression, LSTM, and ARIMA in this project.
## About the dataset
Dataset contains historical daily prices for all tickers currently trading on NASDAQ. It contains prices for up to April 1st 2020. Our dataset for this project is from a Kaggle whose size is of about 2.7GB. <br/>
The dataset consists of 8050 files and 56.4k columns.All that ticker data is then stored in either ETFs or stocks folder, depending on a type. Moreover, each filename is the corresponding ticker symbol. At last, symbols_valid_meta.csv contains some additional metadata for each ticker such as full name.The various features of the dataset are as follows:
Column Names | Column Description
------------- | -------------
Date  | Specifies trading date
Open  | Opening price of the stock
High  | Maximum price during the day
Low  | Minimum price during the day
Close  | Close price adjusted for splits
Adj Close  | Adjusted close price adjusted for both dividends and splits.
Volume  | The number of shares that changed hands during a given day

Data Source: [https://www.kaggle.com/datasets/jacksoncrow/stock-market-dataset] <br/>

## Methodologies/Algorithms Used
1. Linear Regression
2. Seasonal Auto Regressive Integrated Moving Average (SARIMA)
3. LSTM 

## Conclusion
* To conclude, for the company Apple the model Automated Regressive Integrated Moving Average (ARIMA) was the best fit. On the other hand, linear regression and LSTM performed equally and these are the conclusions according to the root mean square error.
* For different data the best fit model can vary. As we forecast further out into the future, it is natural for us to become less confident in our values. This is reflected by the confidence intervals generated by our model, which grow larger as we move further out into the future.

