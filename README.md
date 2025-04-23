# 📈 Stock Prediction Using KNN, Naive Bayes, and Logistic Regression

## 📄 Abstract
This project aims to predict stock price movements using three machine learning models: **K-Nearest Neighbors (KNN)**, **Naive Bayes**, and **Logistic Regression**. The objective is to compare their performance and determine which model provides the most accurate forecasts based on historical stock data.

---

## 🔍 Introduction
The stock market is inherently volatile, making accurate prediction a challenging task. Leveraging **machine learning**, we attempt to forecast stock trends using historical data. This study focuses on three diverse algorithms—KNN, Naive Bayes, and Logistic Regression—to assess their effectiveness in financial prediction.

---

## 🎯 Objectives
- Implement and train KNN, Naive Bayes, and Logistic Regression models on historical stock data.
- Evaluate and compare model performance based on accuracy and efficiency.
- Identify the most suitable model for stock price prediction.

---

## 📊 Methodology

### 🧾 Data Collection
- Sourced from **[Kaggle](https://www.kaggle.com/)**

### 🧠 Feature Selection
- Price Change  
- Typical Price  
- Mean Deviation  
- Average Gain and Loss  
- RSI (Relative Strength Index)  
- CCI (Commodity Channel Index)  
- ROC (Rate of Change)  
- EMA12, EMA26 (Exponential Moving Averages)  
- MACD (Moving Average Convergence Divergence)  
- Bollinger Bands (BB_Middle, BB_Upper, BB_Lower)  
- Momentum  
- Label  

---

## 🧮 Model Implementation

### 📌 K-Nearest Neighbors (KNN)
- StandardScaler used for normalization.
- Trained with **k = 5** neighbors.
- Predicts stock movements based on historical similarity.

### 📌 Naive Bayes
- **Gaussian Naive Bayes** assumes features follow a normal distribution.
- Fast, probabilistic predictions using Bayes’ theorem.
- Assumes feature independence.

### 📌 Logistic Regression
- Features normalized before training.
- Predicts probability of stock price increase.
- Uses sigmoid function for binary classification.

---

## 🧪 Model Training
All models follow a common training pipeline:
- Data loading
- Preprocessing
- Feature scaling
- Train-test split
- Model training and evaluation

---

## 🧠 Challenges & Learnings
- **Data Imbalance**: Addressed using preprocessing and model evaluation techniques.
- **Model Selection**: Emphasized the trade-offs between model complexity and performance.

---

## ✅ Conclusion
This project showcased the potential of **machine learning in stock market analysis**. Among the models used, each had its strengths and limitations. Going forward, incorporating more complex models and diverse datasets will enhance predictive power and real-world applicability.

---

## 🔗 Inspiration
- [TradingView](https://www.tradingview.com/)
- [Binance](https://www.binance.com/)

