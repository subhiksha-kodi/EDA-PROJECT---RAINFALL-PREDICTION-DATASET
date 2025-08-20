# 🌧️ Rainfall Prediction Dataset – WeatherAUS  

This project explores the **Rainfall Prediction Dataset** (Australia), performing **data cleaning, EDA, feature engineering, and predictive modeling**.  
The goal is to forecast whether it will rain **tomorrow** based on today’s weather conditions.  

---

## 📂 Dataset Overview  

- **Rows:** 145,460  
- **Columns:** 23  
- **Target Variable:** `RainTomorrow` (Yes/No)  

---

## 🔹 Data Cleaning  

- Converted categorical columns (`WindDir`, `RainToday`, `RainTomorrow`) → numeric.  
- Handled missing values in **Sunshine, Evaporation, Cloud**.  
- Normalized continuous variables like `Rainfall` and `WindSpeed`.  

---

## 🔹 EDA & Visualizations  

### 🌧️ Rainfall Distribution  
![Rainfall Distribution](plots/rainfall_distribution.png)  

### 💧 Humidity vs RainTomorrow  
![Humidity vs RainTomorrow](plots/humidity_vs_rainfall.png)  

### 📍 Rainfall per Location  
![Rainfall per Location](plots/rainfall_per_location.png)  

### 💧 Overall Humidity Distribution  
![Overall Humidity](plots/overall_humidity.png)  

### 📆 Yearly Rainfall Trend  
![Yearly Rainfall Trend](plots/yearly_rainfall_trend.png)  

### 🌬️ Wind Direction Analysis  
![Wind Direction](plots/wind_direction.png)  

### 🌞 Monthly Sunshine Trends  
![Monthly Sunshine](plots/monthly_sunshine.png)  

### 🌬️ Wind Speed Distribution  
![Wind Speed](plots/wind_speed.png)  

### 🔥 Correlation Heatmap  
![Correlation Heatmap](plots/correlation_heatmap.png)  

### 🌧️ Proportion of Rainy Days  
![Proportion of Rain Days](plots/proportion_raindays.png)  

---

## 🔹 Feature Engineering  

Created additional features for better modeling:  
- `Season` (from Date)  
- `Humidity_Diff` = Humidity9am – Humidity3pm  
- `Temp_Diff` = MaxTemp – MinTemp  
- `Rainfall_Category` (Low / Medium / High)  

---

## 🔹 Modeling  

- Logistic Regression (baseline)  
- Random Forest & XGBoost (best performers)  
- Class imbalance handled via **SMOTE** + class weights  

📌 **Result:** Random Forest achieved best recall and balanced accuracy.  

---

## 📌 Insights  

- 🌡️ Afternoon humidity is the **most important factor** for rainfall prediction.  
- 🌧️ If it rained today, it’s more likely to rain tomorrow.  
- 🌬️ Wind direction and strong gusts also impact rain probability.  
- ⚖️ Dataset is imbalanced (more “No Rain” days).  

---

## ✨ Conclusion  

- Weather variables contain **predictive signals** for rainfall forecasting.  
- **Feature engineering + tree-based models** improve accuracy.  
- Future scope: hyperparameter tuning, LSTM for time-series weather, deployment.  

---
