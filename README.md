# Deep Learning for Demand Forecasting in Retail

This project investigates and benchmarks various deep learning models for multi-step demand forecasting in the retail domain using the Warehouse and Retail Sales dataset (307,000+ rows). It evaluates model robustness under both clean and noise-injected settings, replicating real-world data uncertainty.

## 🧠 Models Implemented
- Linear Regression
- Feedforward Neural Network (FNN)
- LSTM
- GRU
- Transformer
- CNN-RNN Hybrid

## 📊 Dataset
- Source: [Data.gov - Warehouse and Retail Sales](https://catalog.data.gov/dataset/warehouse-and-retail-sales)
- Features: `YEAR`, `MONTH`, `SUPPLIER`, `ITEM TYPE`, `RETAIL SALES`, `WAREHOUSE SALES`, etc.

## 🔍 Key Steps
1. Data Cleaning & Imputation (Random Forest IterativeImputer)
2. Feature Engineering (Log Transform, Lag Creation, Scaling)
3. Time Series EDA & Seasonality Analysis
4. Synthetic Gaussian Noise Injection for Robustness
5. Training & Evaluation on Clean vs Noisy Data
6. Model Comparison via MSE, MAE, R², RMSE

## 📈 Results
- **Best Model (Clean & Noisy)**: **Transformer**
- **Runner-up**: **CNN-RNN Hybrid**
- Metrics show Transformer maintains top performance even under noisy input.

## Author
Padmavathi Moorthy
