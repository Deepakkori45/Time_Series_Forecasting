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

The ARMA (Autoregressive Moving Average)model combines two main components: the autoregressive (AR) component, which models the relationship between the current value of the time series and its past values, and the moving average (MA) component, which models the relationship between the current value and past forecast errors.
![image](https://github.com/Deepakkori45/Time_Series_Forecasting/assets/111627339/3e695877-c70c-4ddb-996e-9bbce9e42564)

 
# 6) ARIMA Model

ARIMA models are used to model time series data that exhibit non-stationarity, meaning their statistical properties like mean and variance change over time.

![image](https://github.com/Deepakkori45/Time_Series_Forecasting/assets/111627339/ccd2cbec-4c46-4ac0-ac9d-e71faabe48bd)



# 7) Seasonal ARIMA Model

SARIMA models are an extension of the ARIMA model specifically designed to handle time series data with seasonal patterns. SARIMA models include additional seasonal components alongside the non-seasonal ARIMA components. SARIMA models consist of seasonal autoregressive (SAR), seasonal integrated (SI), and seasonal moving average (SMA) components, in addition to the non-seasonal ARIMA components. SARIMA models explicitly account for seasonal patterns in the data and are particularly useful for forecasting time series with strong seasonal fluctuations.

I use the **Akaike Information Criterion (AIC)** to compare different time series models and select the one that balances goodness of fit with simplicity. A lower AIC value indicates a better fitting model while penalizing for excessive model complexity, aiding in effective model selection for time series analysis.

![image](https://github.com/Deepakkori45/Time_Series_Forecasting/assets/111627339/cefaf225-4ca4-4449-9846-4d37683fe922)


# 8) Vector Autoregression Model



# 9) Indian Stock Forecasting with LSTMs
Description: This notebook utilizes Long Short-Term Memory (LSTM) networks, a type of recurrent neural network (RNN), for forecasting Indian stock market data. LSTMs are powerful models for capturing long-term dependencies in sequential data.
File: 9) Indian_Stock_Forecasting_with_LSTMs.ipynb
