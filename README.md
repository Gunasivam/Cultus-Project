# Advanced Time Series Forecasting with Seq2Seq + Attention + Classical Baselines  

## 📌 Project Overview
This project demonstrates an **end-to-end time series forecasting pipeline** using:

- **Deep Learning Model**:  
  - Seq2Seq (Encoder–Decoder)  
  - Bidirectional LSTM Encoder  
  - LSTM Decoder  
  - Global Attention  
- **Classical Baseline Models**:  
  - SARIMAX  
  - Exponential Smoothing  
- **Synthetic Multivariate Time Series Dataset**  
  - ≥ 3000 timesteps  
  - ≥ 5 features  
  - Trend + seasonality + noise  
- **Full Evaluation & Visualization**

---

## ✅ Key Features

### 🔹 **1. Synthetic Dataset Generation**
- Multivariate time series  
- Multi-seasonal patterns (daily + weekly)  
- Smooth trend + noise  
- Automatically validated

### 🔹 **2. Preprocessing**
- Scaling (StandardScaler)  
- Sliding window generator  
- Variable input/output lengths  
- Train/Validation/Test split (80/10/10)

### 🔹 **3. Deep Learning Model (Seq2Seq + Attention)**
- Bidirectional LSTM encoder  
- Attention mechanism  
- Context vector → repeated for decoder  
- LSTM decoder for multi-step forecasting  
- TimeDistributed Dense output  
- RMSE, MAE, MAPE evaluation

### 🔹 **4. Baselines**
- **SARIMAX**  
- **Exponential Smoothing**  
- Forecast horizon identical to deep learning output  
- Comparison with DL predictions

### 🔹 **5. Evaluation Metrics**
- RMSE  
- MAE  
- MAPE  
- Multi-step prediction visualization  
- Test set plots

---

## 📁 Project Deliverables

This project delivers:

1. **Full end-to-end Python source code**
2. **Seq2Seq LSTM model with Attention**
3. **Baseline classical forecasting models**
4. **Predictions (DL vs. Baselines)**
5. **Model evaluation metrics**
6. **Visualizations for analysis**
7. **Reusable pipeline & clean modular structure**



