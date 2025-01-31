# Yes Bank Stock Closing Price Prediction

## 📌 Project Overview

This project aims to predict the **closing price of Yes Bank's stock** using **regression models**. Stock market prices are highly volatile, and machine learning models can help identify trends and patterns for better decision-making.

## 📊 Dataset

- **Source:** (Specify source, e.g., Yahoo Finance, NSE, Kaggle)
- **Features:**
  - `Date` – Trading date
  - `Open` – Opening price
  - `High` – Highest price during trading
  - `Low` – Lowest price during trading
  - `Close` – Closing price (Target variable)

## 🛠 Data Preprocessing

- **Handling Missing Values** – Used interpolation or dropped missing records
- **Feature Engineering** – Added moving averages, volatility, etc.
- **Scaling** – Applied MinMaxScaler or StandardScaler

## 📈 Exploratory Data Analysis (EDA)

- **Visualized stock price trends over time** 📉
- **Correlation analysis** to check feature relationships 🔗
- **Moving averages & volatility analysis**

## 🤖 Model Selection & Training

### Models Implemented:

- **KNN Regression** – R² Score: **0.993115**
- **Linear Regression** – R² Score: **0.993082**
- **Ridge Regression** – R² Score: **0.993045**
- **Lasso Regression** – R² Score: **0.992825**
- **Elastic Net Regression** – R² Score: **0.992754**
- **Random Forest Regression** – R² Score: **0.985054**

### Model Evaluation Metrics:

- **R² Score** – Measures model fit


## 📊 Results & Performance

- **Best-performing model:** KNN Regression (**R² = 0.993115**)
- **Key observations:** KNN Regression achieved the highest accuracy, while Random Forest Regression performed slightly lower.

## 🔮 Future Scope

- Implement **LSTM (Long Short-Term Memory) networks** for deep learning-based predictions
- Use **real-time stock market data** with APIs 📡
- Apply **sentiment analysis** from financial news and social media 📰

## 🚀 How to Run the Project

### Prerequisites:

- Python 3.x
- Jupyter Notebook
- Required libraries: `pandas`, `numpy`, `matplotlib`, `scikit-learn`, `xgboost`

## 📜 License

This project is open-source and available under the **MIT License**.

---

**⭐ If you found this project useful, consider giving it a star on GitHub!** 🌟

