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
Most days record very little rain (<5mm). Heavy rainfall is rare.  

![Rainfall Distribution](plots/rainfall_distribution.png)  

---

### 🌡️ Temperature Trends  
Temperatures mostly lie between **10°C and 25°C**.  

![Temperature Distribution](plots/temperature_distribution.png)  

---

### 💧 Humidity vs RainTomorrow  
High **afternoon humidity (>80%)** is strongly associated with rainfall the next day.  

![Humidity vs RainTomorrow](plots/humidity_vs_rainfall.png)  

---

### 🌞 Sunshine vs Rainfall  
Rainy days → fewer sunshine hours.  

![Sunshine vs Rainfall](plots/sunshine_vs_rain.png)  

---

### 📅 Seasonal Rainfall Trends  
Rainfall varies significantly across **months and regions**.  

![Monthly Rainfall Trends](plots/monthly_rainfall.png)  

---

### 🌬️ Wind & Rain  
Strong winds and certain directions (NW, W) are more linked to rainfall.  

![Wind Direction vs RainTomorrow](plots/wind_vs_ra)
