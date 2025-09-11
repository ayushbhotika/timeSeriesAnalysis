# stockMarketPrediction

This project performs **time series analysis and forecasting** of the weekly closing prices of the **S&P 500 Index (GSPC)** using multiple statistical and smoothing models, including Naive Forecast, SMA, WMA, SES, DES, TES (Holt-Winters), and ARIMA(1,1,1). The aim is to evaluate different forecasting approaches, compare their accuracy using error metrics (MSE, RMSE, MAPE), and identify the model with the best fit and forecasting efficiency.

## Dataset
- Weekly closing prices of the S&P 500 retrieved from [Yahoo Finance](https://finance.yahoo.com/).

## Results
- TES (Triple Exponential Smoothing) gave the best performance by effectively capturing weekly seasonality and providing the lowest forecasting errors.
- ARIMA was competitive but showed some residual challenges like non-normality and heteroskedasticity.

## Installation & Usage
git clone https://github.com/pragyyyyaa/Stock_Data_Auto_Arima_Model.git
cd Stock_Data_Auto_Arima_Model
pip install -r requirements.txt
jupyter notebook Stock_Data.ipynb


## Future Work
- Implement SARIMA for enhanced seasonality modeling.
- Experiment with GARCH/ARCH models for volatility forecasting.
- Incorporate machine learning models such as LSTM, Random Forest, and XGBoost for comparison.

---

*This project is licensed under the MIT License - see the LICENSE file for details.*


