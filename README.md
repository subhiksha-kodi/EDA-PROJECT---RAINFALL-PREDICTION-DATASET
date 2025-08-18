# 🌧️ Rainfall Prediction Dataset – WeatherAUS  

## 📖 Introduction  
Weather has always been one of the most unpredictable forces of nature.  
This dataset provides a rich collection of **daily weather observations** from different regions across Australia, making it a perfect playground for **climate analytics** and **machine learning experiments**.  

The primary goal is to answer the big question:  
👉 **Will it rain tomorrow?** 🌦️  

This binary prediction task is supported by multiple meteorological features, ranging from temperature and humidity to wind direction and pressure.  

---

## 📊 Dataset Summary  

- **Rows (observations):** 145,460  
- **Columns (features):** 23  
- **Geographical Coverage:** Multiple Australian cities/towns  
- **Temporal Coverage:** Historical daily observations (spanning multiple years)  
- **Target Variable:** `RainTomorrow`  

---

## 🗂️ Feature Glossary  

### 🌡️ Climate Indicators  
- `MinTemp`, `MaxTemp` → Minimum & maximum daily temperatures  
- `Humidity9am`, `Humidity3pm` → Morning & afternoon humidity levels  
- `Pressure9am`, `Pressure3pm` → Atmospheric pressure readings  

### ☔ Rainfall & Sunshine  
- `Rainfall` → Total daily rainfall (mm)  
- `Evaporation` → Water evaporated (mm)  
- `Sunshine` → Total sunshine hours  

### 🌬️ Wind Dynamics  
- `WindGustDir`, `WindDir9am`, `WindDir3pm` → Compass direction (e.g., N, NW, SE)  
- `WindGustSpeed`, `WindSpeed9am`, `WindSpeed3pm` → Wind speeds (km/h)  

### ☁️ Cloud Cover  
- `Cloud9am`, `Cloud3pm` → Fraction of sky covered (0–8 scale)  

### 🎯 Target & Helper Variables  
- `RainToday` → Did it rain today? (Yes/No)  
- `RainTomorrow` → **Target variable** – Will it rain tomorrow? (Yes/No ✅)  

---

## 🔍 Why This Dataset is Interesting?  

- 🌍 **Climate Research** → Understand rainfall dependency on humidity, pressure, and wind  
- 🤖 **Predictive Modeling** → Train ML models to forecast next-day rainfall  
- 🛠️ **Data Wrangling Challenge** → Handle missing values, imbalanced classes, and categorical encodings  
- 📊 **Visualization Playground** → Explore weather trends across seasons and regions  

---

## 🚀 Example Use-Cases  

### 📈 EDA & Visualization  
- Seasonal rainfall heatmaps 🌡️  
- Correlation between humidity & rainfall ☁️  
- City-wise rainfall comparison 📍  

### 🤖 Machine Learning Tasks  
- Classification models: Logistic Regression, Random Forest, XGBoost  
- Feature engineering: lag rainfall, moving averages  
- Imbalanced data handling: SMOTE, undersampling  

### 🌍 Real-World Applications  
- Early flood warning systems  
- Agriculture & irrigation planning 🌱  
- Urban water management 🚰  

---

✨ This dataset is more than just numbers — it’s a **story of weather patterns** and an opportunity to learn how data can forecast the unpredictable.  
