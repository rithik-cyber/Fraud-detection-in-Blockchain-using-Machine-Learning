# 🪙 Bitcoin Price Prediction using Machine Learning

## Introduction

This project focuses on predicting the price of **Bitcoin (BTC-USD)** using machine learning techniques. Utilizing historical data and supervised learning methods, the aim is to forecast future prices based on past trends. This is particularly useful for financial analysts, traders, and researchers exploring crypto markets.

## Files in This Project

| Filename         | Description |
|------------------|-------------|
| `BTC-USD.xls`    | Historical price data of Bitcoin (Open, High, Low, Close, Volume). |
| `class.xls`      | Additional labels or classes related to price prediction (possibly indicating price movement or other features). |
| `Untitled.ipynb` | Main Jupyter Notebook implementing preprocessing, visualization, model training, and prediction. |

## Tools & Libraries

- **Python 3.x**
- **Jupyter Notebook**
- **Pandas** – for data manipulation
- **NumPy** – numerical operations
- **Matplotlib / Seaborn** – data visualization
- **Scikit-learn** – machine learning algorithms
- *(Optional)* TensorFlow/Keras – for deep learning models like LSTM

## Workflow Overview

1. **Data Import & Cleaning**
   - Load `BTC-USD.xls` and `class.xls`
   - Handle missing values, data types, formatting

2. **Feature Engineering**
   - Extract relevant features like moving averages, price change percentage
   - Merge labels from `class.xls` if applicable

3. **Exploratory Data Analysis**
   - Visualize trends, volatility, and patterns

4. **Modeling**
   - Train regression/classification models (e.g., Linear Regression, Random Forest)
   - Evaluate with metrics like MAE, RMSE, R²

5. **Prediction**
   - Forecast future Bitcoin prices using test data

## How to Run

1. Clone or download the repository.

2. Make sure you have all dependencies installed:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
Launch the notebook:

bash
Copy
Edit
jupyter notebook Untitled.ipynb
Follow through the steps in the notebook:

Load and clean data

Run model training

Evaluate and plot predictions

📊 Evaluation Metrics
MAE (Mean Absolute Error)

MSE (Mean Squared Error)

RMSE (Root Mean Squared Error)

R² Score

📝 Sample Output
A graph comparing actual vs. predicted Bitcoin prices will be plotted in the notebook to visually evaluate model performance.

🚀 Future Enhancements
Integrate LSTM for better time series forecasting

Add live API for real-time price fetching

Deploy a dashboard using Streamlit or Flask



Email: kumarithik700@gmail.com



📄 License
This project is licensed under the MIT License. You are free to use, distribute, and modify it with proper credit.





