# Instagram Reach Analysis & Forecasting using Time Series (SARIMA)

This project focuses on analyzing and forecasting Instagram reach using time series analysis in Python.  
The goal is to understand how Instagram reach changes over time and how historical data can be used to predict future engagement.

---

## 📌 Project Overview

Instagram reach does not remain constant. It varies based on user behavior, content strategy, and time-related factors such as weekdays and seasonal patterns.

In this project, I:
- Analyzed historical Instagram reach data
- Identified trends, seasonality, and fluctuations
- Used SARIMA (Seasonal ARIMA) for time series forecasting
- Visualized future reach predictions

This project is useful for:
- Content creators
- Social media analysts
- Marketing and growth teams

---

## 📊 Key Analysis Performed

- Trend analysis with rolling averages
- Reach comparison by day of the week
- Distribution analysis using box plots
- Seasonal decomposition of time series data
- Autocorrelation (ACF) and Partial Autocorrelation (PACF) analysis
- SARIMA model training and forecasting

---

## 🧠 Model Used

**SARIMA (Seasonal ARIMA)**  
- p = 8 (Autoregressive)
- d = 1 (Differencing)
- q = 2 (Moving Average)
- Seasonal period = 12

SARIMA was chosen because Instagram reach shows both trend and seasonality.

---

## 📈 Results & Insights

- Instagram reach shows clear seasonal and time-based patterns
- Certain days of the week perform better consistently
- Reach peaked during mid-2022 and declined afterward
- Forecast suggests future reach may remain stable but lower unless strategy changes
- Forecasted values are smoother, focusing on long-term behavior rather than viral spikes

---

## 🛠️ Tools & Libraries Used

- Python
- Pandas
- NumPy
- Plotly
- Statsmodels
- Matplotlib

---

## 🔗 Medium Article

Detailed explanation of the analysis and results is available here:  
👉 **[Read the Medium article](https://medium.com/@ranganiroshini4/instagram-reach-analysis-and-forecasting-using-time-series-in-python-30d6b0c307c8)**

---

## 👩‍💻 Author

**Roshini Rangani**  


---

⭐ If you found this project useful, feel free to star the repository!

