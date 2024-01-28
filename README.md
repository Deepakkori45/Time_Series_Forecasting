# Project Repository Overview
# 1) ACF and PACF Understanding

**Autocorrelation Function (ACF):** The ACF is primarily used to identify the order of the moving average (MA) component in models like the ARIMA (Autoregressive Integrated Moving Average) model.
By analyzing the ACF plot, analysts can identify the number of significant lags at which autocorrelation is present, which helps determine the order of the MA component.

**Partial Autocorrelation Function (PACF):** the PACF is primarily used to identify the order of the autoregressive (AR) component in models like the ARIMA model.
By analyzing the PACF plot, analysts can identify the number of significant lags at which autocorrelation is present, which helps determine the order of the AR component.

# 2) Augmented Dickey-Fuller Test(ADF)

The Augmented Dickey-Fuller (ADF) test is utilized in time series analysis to determine whether a given time series dataset is **stationary or non-stationary.** 
If the calculated test statistic is less than the critical value, the null hypothesis of a unit root is rejected, and the time series is considered stationary else rejected.


# 3) AR Model

An Autoregressive (AR) model is a type of time series model used to forecast future values based on past observations. In an AR model, the value of the time series at any given point is modeled as a linear combination of its past values, also known as lagged values, along with an error term. 
![image](https://github.com/Deepakkori45/Time_Series_Forecasting/assets/111627339/0e72fc2b-b316-4061-bf0e-ee3a1e8e952e)

# 4) MA Model

A Moving Average (MA) model is a type of time series model used for forecasting future values based on past observations. Unlike the Autoregressive (AR) model which regresses the current value of the time series on its own past values, the MA model regresses the current value on past **forecast errors**, also known as the residual errors.
![image](https://github.com/Deepakkori45/Time_Series_Forecasting/assets/111627339/8eb58af6-3619-4c70-b9cc-f20e7145cefc)




# 5) ARMA Model

Description: This notebook implements an Autoregressive Moving Average (ARMA) model, which combines both the AR and MA models into a single framework. It's useful for capturing both short-term trends and long-term dependencies in the data.
![image](https://github.com/Deepakkori45/Time_Series_Forecasting/assets/111627339/3e695877-c70c-4ddb-996e-9bbce9e42564)

 
# 6) ARIMA Model

Description: This notebook implements an Autoregressive Integrated Moving Average (ARIMA) model, which extends the ARMA model by including differencing to make the time series stationary. It's useful for non-stationary data.
![image](https://github.com/Deepakkori45/Time_Series_Forecasting/assets/111627339/ccd2cbec-4c46-4ac0-ac9d-e71faabe48bd)



# 7) Seasonal ARIMA Model

Description: This notebook implements a Seasonal ARIMA (SARIMA) model, which extends the ARIMA model to handle seasonality in the data. It's useful for time series data with periodic patterns.
![image](https://github.com/Deepakkori45/Time_Series_Forecasting/assets/111627339/cefaf225-4ca4-4449-9846-4d37683fe922)



# 8) Vector Autoregression Model

Description: This notebook implements a Vector Autoregression (VAR) model, a multivariate time series model where each variable is modeled as a linear combination of its lagged values and the lagged values of other variables. It's useful for analyzing and forecasting multiple time series simultaneously.
File: 8) VAR_Model.ipynb

# 9) Indian Stock Forecasting with LSTMs
Description: This notebook utilizes Long Short-Term Memory (LSTM) networks, a type of recurrent neural network (RNN), for forecasting Indian stock market data. LSTMs are powerful models for capturing long-term dependencies in sequential data.
File: 9) Indian_Stock_Forecasting_with_LSTMs.ipynb
