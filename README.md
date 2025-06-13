# ⚡ Load Forecasting using Transformer Model (Nepal)

This project presents a **Transformer-based deep learning model** for short-term and long-term electricity load forecasting in **Nepal**, 
without applying Discrete Wavelet Transform (DWT) preprocessing. It aims to predict power consumption for the next 24 hours based on past power load data.

---

## 📌 Features

- Implemented using PyTorch and NumPy
- Predicts 24-hour electricity load
- Works without DWT preprocessing
- Includes data preprocessing, model training, and evaluation
- Easily extendable to other countries or datasets

## 🧠 Model

- Architecture: **Transformer**
- Input: `n_hours` sequence (e.g., 168 hours or 7 days)
- Output: 24-hour future power load prediction
- Loss Function: MSE
- Evaluation Metrics: RMSE, MAE, R² Score

