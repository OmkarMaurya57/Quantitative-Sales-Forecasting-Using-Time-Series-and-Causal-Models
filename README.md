# Quantitative Sales Forecasting Using Time Series and Causal Models

##  Overview
This project explores **quantitative forecasting methods** to predict product sales using a dataset of **10 stores and 50 products** spanning **2013–2017**.  
Both **time series** and **causal models** were implemented and evaluated using error metrics to identify the most effective forecasting technique.

---

##  Models Implemented
1. **Seasonal Naive Model** — baseline approach assuming sales repeat previous seasonal values.  
2. **Holt-Winters (Triple Exponential Smoothing)** — accounts for level, trend, and seasonality.  
3. **ARIMA & SARIMA** — captures autoregressive, differencing, moving average, and seasonal components.  
4. **Linear Regression** — causal model using feature selection (SelectKBest) to predict sales.  

---

##  Results
- Evaluated using **MAE, RMSE, and MAPE**.  
- **Linear Regression** outperformed others in capturing **trend and seasonality**.  
- Holt-Winters and SARIMA provided competitive results, but regression-based modeling proved more accurate for this dataset.  

---

##  Conclusion
- Demonstrated application of **time series** and **causal forecasting models**.  
- Showed the importance of considering **trend + seasonality** in real-world sales data.  
- Linear Regression was the most effective method for the dataset.  

---
