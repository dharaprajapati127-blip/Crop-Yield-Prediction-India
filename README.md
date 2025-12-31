# 🌾 Crop Yield Prediction in India

## 📌 Project Overview
This project aims to predict agricultural crop yield in India using machine learning techniques based on economic and crop-related factors.

## 📊 Dataset
- Source: crop_cost_yield.csv
- Features include crop type, state, and various cultivation and production cost metrics.
- Target variable: Yield_capped (IQR-based outlier handled yield)

## ⚙️ Methodology
- Data cleaning and preprocessing
- One-hot encoding of categorical features
- Feature scaling using StandardScaler
- Model training and evaluation

## 🤖 Models Used
- Linear Regression (baseline)
- Random Forest Regressor (final model)

## 📈 Results
- Random Forest achieved superior performance with:
  - R² ≈ 0.95
  - MAE ≈ 3.87
  - RMSE ≈ 5.10

## 🔍 Feature Importance
Cost of production and cultivation emerged as the most influential factors affecting crop yield, followed by crop type and regional features.

## 💾 Model Saving
The trained model and scaler were saved using joblib for reproducibility and future deployment.

## 🚀 Conclusion
The project demonstrates the effectiveness of ensemble models in capturing non-linear relationships in agricultural data.

