# **Stock Market Price Prediction** 🚀

This project involves building a **machine learning model** to predict stock price movements using historical stock market data. By applying machine learning algorithms, data preprocessing, and evaluation techniques, the model helps in making data-driven decisions for stock market investments.

---

## **Project Overview**  
The goal of this project is to predict whether stock prices will go up or down based on historical market data. The model uses a **Random Forest Regressor** to make predictions, and it is evaluated with metrics like **Mean Squared Error (MSE)** and **R-squared**.

---

## **Features**  
- 📈 **Stock Movement Prediction**: Predicts stock price direction (up or down).
- 🔄 **Data Preprocessing**: Handles missing values, encodes categorical variables, and normalizes data.
- 🧠 **Machine Learning Model**: Trains a **Random Forest Regressor** to predict stock price trends.
- 📊 **Model Evaluation**: Evaluates the model using **MSE** and **R-squared** metrics.

---

## **Dataset**  
The dataset used in this project contains historical stock market data with the following attributes:  
- **Date**: Date of record.  
- **Stock Price**: Closing price of the stock.  
- **Volume**: Trading volume for the stock.  
- **Target Column**: Direction of the stock movement (up/down).

📁 **Dataset Path**: `dataset/stock_data.csv`

> **Note**: The dataset is large and tracked using **Git Large File Storage (Git LFS)**. Please refer to the [Git LFS installation guide](https://git-lfs.github.com/) to manage large files effectively.

---

## **Technologies Used**  
This project uses the following technologies:  
- **Python**  
- **pandas** and **numpy** for data manipulation  
- **scikit-learn** for machine learning  
- **joblib** for saving and loading the trained model  
- **Git LFS** for handling large datasets

---

## **Installation**  
Follow these steps to set up and run the project:

1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/stock-price-prediction.git
   cd stock-price-prediction
