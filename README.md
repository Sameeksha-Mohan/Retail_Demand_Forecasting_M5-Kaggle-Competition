# 🛒 Retail Demand Forecasting for Walmart | M5 Kaggle Competition

This project was completed as part of a Predictive Analytics course, where I participated in the **M5 Forecasting Accuracy Kaggle Competition**. The objective was to forecast daily unit sales for thousands of Walmart products using historical sales, calendar events, and price data.

---

## 🧠 Problem Statement

Predict accurate daily demand across 30,000+ SKUs over a 28-day forecast horizon. The challenge involved working with:
- Sparse and hierarchical time series data
- Promotional effects and pricing changes
- Seasonality and calendar-based anomalies

---

## 📦 Dataset

The dataset is provided by Kaggle and includes:
- **Sales data**: Unit sales per day per item
- **Calendar data**: Holidays, events, weekdays
- **Pricing data**: Rolling prices and promotion signals

🔗 [M5 Forecasting Accuracy Dataset on Kaggle](https://www.kaggle.com/competitions/m5-forecasting-accuracy/data)

---

## 🔍 Key Highlights

- **Hosted 47M+ rows on Azure** to support large-scale, memory-efficient processing.
- Implemented multiple models for comparison:
  - `XGBoost` with **Optuna hyperparameter tuning**
  - Deep learning models: `LSTM` and `GRU`
  - `LightGBM` delivered the **best WRMSSE score of 0.74**
- Implemented **stacking/ensembling** to combine model strengths and further improve performance.
- Addressed key production challenges like runtime efficiency and model scalability.

---

## 🛠️ Tech Stack

- **Languages**: Python (Pandas, NumPy)
- **ML Libraries**: XGBoost, LightGBM, TensorFlow/Keras
- **Optimization**: Optuna
- **Cloud**: Microsoft Azure (for data hosting)

