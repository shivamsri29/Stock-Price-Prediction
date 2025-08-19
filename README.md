# Stock-Price-Prediction
Built a time-series based stock prediction system using LSTM neural networks, achieving a prediction accuracy of 84.6% on historical stock datasets.
# 📈 Stock Price Prediction using LSTM

![Python](https://img.shields.io/badge/Python-3.10-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.9-orange)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-yellow)
![Matplotlib](https://img.shields.io/badge/Visualization-Matplotlib-green)

## 📖 Overview
A deep learning project that uses **Long Short-Term Memory (LSTM)** neural networks to predict stock prices.  
The model was trained on historical stock market datasets and evaluated against real-world stock data.

## 🛠️ Tech Stack
- **Language:** Python  
- **Libraries:** TensorFlow, Scikit-learn, Pandas, Matplotlib  
- **Data:** Historical stock datasets  

## 🚀 Features
- Preprocessing pipeline for **time-series normalization**  
- LSTM-based deep learning model  
- Visualization of **Actual vs Predicted** stock prices  
- Achieved **84.6% accuracy** on test data  

## 📊 Workflow
```mermaid
flowchart LR
A[Historical Stock Data] --> B[Data Preprocessing]
B --> C[LSTM Model Training]
C --> D[Evaluation & Metrics]
D --> E[Visualization & Predictions]
