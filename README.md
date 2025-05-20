# Comparative Analysis of Machine Learning and Deep Learning Models for Rainfall Prediction

This project presents a comprehensive comparative analysis of various machine learning and deep learning models for rainfall prediction using real-world weather data from the Australian Bureau of Meteorology. Five models—Linear Regression, LSTM, Gaussian HMM, Random Forest, and SVR—were implemented and evaluated based on Mean Squared Error (MSE), Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).


## 🔍 Key Features
- Preprocessing and feature standardization of weather data
- Implementation of five prediction models using Python (scikit-learn, TensorFlow, hmmlearn)
- Evaluation using standard error metrics (MSE, MAE, RMSE)
- Visual comparison of model performance
- Random Forest achieved the best overall accuracy; SVR showed the lowest MAE

## 📊 Results Summary
| Model             | MSE   | MAE  | RMSE |
| ----------------- | ----- | ---- | ---- |
| Linear Regression | 39.68 | 3.12 | 6.30 |
| LSTM              | 52.83 | 3.37 | 7.27 |
| Gaussian HMM      | 47.45 | 2.64 | 6.89 |
| Random Forest     | 34.68 | 2.46 | 5.89 |
| SVR               | 37.69 | 1.89 | 6.14 |
