# 📈 Stock Market Prediction using MLP

## Overview
This project predicts the **next day’s Nifty closing price** using a **Multi-Layer Perceptron (MLP)** model trained on **1 year of Indian stock market data (Nifty200)**.  
We processed the data, normalized it, created rolling sequences of 30 days, and trained a deep neural network to forecast the following day’s value.  

## 🔑 Features
- **Preprocessing**: Cleans missing values and normalizes stock prices  
- **Sequence Modeling**: Uses past 30 days to predict the next day  
- **MLP Neural Network**: 4 hidden layers with ReLU activation  
- **Evaluation Metrics**: MAE, RMSE, R², MAPE, Accuracy  
- **Visualization**:
  - Loss curves across training epochs  
  - Actual vs Predicted next-day prices on real examples  

Model Performance:
MAE   : 69.56 points
RMSE  : 96.57 points
R²    : 0.9687
MAPE  : 0.52%
Accuracy ≈ 99.48%


<img width="567" height="455" alt="Nifty 200" src="https://github.com/user-attachments/assets/613cb4eb-6a28-4eec-b077-94a6b8f0da3b" />
<img width="1490" height="490" alt="Nifty200-1" src="https://github.com/user-attachments/assets/aebb199a-c8ec-488d-9d88-a7a53f5fff34" />

