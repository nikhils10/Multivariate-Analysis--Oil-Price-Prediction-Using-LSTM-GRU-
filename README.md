# Multivariate Analysis-Oil Price Prediction Using LSTM & GRU


## Project Overview 
We carry out Analysis between variables like **West Texas intermediate(WTI),Gold Futures , US Dollar Index Futures, US 10 Year Bond Yield,Gold Futures, S&P 500,Dow Jones Utility Average**. 
Experiment out different **outliers techniques** like (1)**Zscore**,(2)**Removing Financial Crisis** Period (2007-2009 recession period) and (3)**Mahalanobis Distance** .
We then carry out comparision by observing **forecasting differences** across two models **Long Term Short Memory(LSTM) and Gated Re-current Unit(GRU)**.

## Motivation
Earlier I had worked on a time series predicion problem dealing with Apple Stock Price prediction using Seasonal-ARIMA & Prophet. 
I had an univariate series to deal with. Later when I dived into other methods for forecasting time series problems , I came across Deep Neural Network Techniques like LSTM and GRU. Also,came across using multiple explanatory variables to account for many effects to account for economic changes,etc.
Oil seemed interesting to me after I came across it in my economic course .
It was a interesting project to forecast oil price and observe relationship wrt to some economic variables like Gold Futures,Interest rates and Market Indices,etc.


## Problem Type
Time Series Forecasting Problem-Solved Using LSTM and GRU.

**Result Metrics**

Mean Squared Error(MSE),Mean Absolute Error(MAE), R2 Score.

## Actionable Insight
Understanding behaviour of Oil price and whether to invest it in or not.

## Tools & Libraries Used
- **Python 3.6**
- **Pandas**        
- **Matplotlib**        
- **Sklearn**            
- **Seaborn**
- **Statsmodels**      
- **Scipy** 
- **Keras with Tensorflow Backend**
- **Plotly** 



       

## About the Data
Individual Data series was collected from Investing.com site (https://www.investing.com/) and Yahoo Finance (https://finance.yahoo.com/). 
Time period for data ranges between 4th Jan 2000 to 10th June 2019 with Daily frequency containing 4947 records in total and 7 series in total.
The following series -(WTI ,Gold Futures , US Dollar Index Futures, US 10 Year Bond Yield,Gold Futures, S&P 500, )-Investing.com and (Dow Jones Utility Average)-Yahoo Finance.

## Initial Preprocessing 
To work on the dataset similar to the project, the following steps were carried out .

-> We collect individual time series within the same range for each feature.

-> Using VlookUp from Excel we merge the series into one dataset , we do so by the dates to align it according to the target variable WTI.

***Note***: We have put both individual time series and combined dataset in the data folder of this repo.


## Credits/Resources
-https://www.investing.com/

-https://finance.yahoo.com/

-https://towardsdatascience.com/illustrated-guide-to-lstms-and-gru-s-a-step-by-step-explanation-44e9eb85bf21

-https://machinelearningmastery.com/multivariate-time-series-forecasting-lstms-keras/

-https://machinelearningmastery.com/how-to-develop-lstm-models-for-time-series-forecasting/



