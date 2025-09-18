# ⚡ Time Series Forecasting of Monthly Electricity Production

This project focuses on **forecasting monthly electricity production** using various time series models. It compares the performance of classical statistical models like **ARIMA** and **SARIMA** with regression-based models, including **Linear** and **Polynomial Regression**. The goal is to identify the most effective model for predicting future electricity production to support optimal resource allocation and long-term planning.

---

## 🌟 Key Features

- **🧹 Data Preprocessing and Exploratory Analysis**  
  Clean and prepare the monthly electricity production dataset. Visualizations help understand trends, seasonality, and stationarity.

- **🛠️ Model Implementation**  
  Implements four different forecasting models:
  - **📈 ARIMA (Autoregressive Integrated Moving Average)**
  - **📊 SARIMA (Seasonal ARIMA)**
  - **📝 Linear Regression**
  - **🔺 Polynomial Regression**

- **📏 Performance Evaluation**  
  Evaluates each model using metrics like:
  - Mean Absolute Percentage Error (**MAPE**) 📉
  - Mean Percentage Error (**MPE**) 📉
  - Root Mean Squared Error (**RMSE**) ⚖️
  - R-squared (**R²**) score 📊

- **📋 Comparative Analysis**  
  Compares the models' strengths and weaknesses based on test data performance.

---

## 🛠️ Technologies Used

This project is built with **Python** and the following libraries:

- **🐼 pandas** – Data manipulation and analysis  
- **🔢 numpy** – Numerical operations  
- **📊 statsmodels** – Statistical modeling (ARIMA, SARIMA)  
- **🤖 scikit-learn** – Regression models and performance metrics  
- **🧮 pmdarima** – Auto-fitting ARIMA models  
- **📉 matplotlib** & **🌈 seaborn** – Data visualization  

---

## ⚡ Setup and Installation

```sh
# Make sure you have Python installed (version 3.7+ recommended)

# Install required libraries
pip install pandas numpy statsmodels pmdarima scikit-learn matplotlib seaborn

# Clone this repository to your local machine

# Ensure the Electric_Production.csv dataset is in the same directory 
# as the Jupyter Notebook (TIME_SERIES_PROJECT.ipynb)

# Open the notebook and run the cells sequentially to perform analysis,
# train models, and view results
```
---
## 🚀 Usage

```sh
# Step 1: 🚀 Open the Jupyter Notebook
jupyter notebook TIME_SERIES_PROJECT.ipynb

# Step 2: ▶️ Run the cells sequentially

# Step 3: 📊 Check visualizations and metrics to evaluate and compare models
