# Machine_learning-
📊 Walmart Sales Forecasting
This project aims to forecast weekly sales for Walmart stores using historical data, with special attention to holidays and economic factors. It applies end-to-end data analysis and modeling, including both machine learning and time series approaches.

🧠 Problem Statement
Walmart experiences significant sales variations due to holidays and seasonal trends. Understanding these patterns helps in optimizing inventory, revenue planning, and promotional strategies. Accurate forecasting can also boost investor confidence and streamline operations.

🎯 Goal & Objective
Goal: Predict future weekly sales of Walmart stores.

Objective: Evaluate the impact of holidays and other factors (e.g., temperature, CPI, unemployment) on sales, and build models to forecast future values.

📁 Dataset Overview
The dataset contains the following files:

train.csv - Historical sales data by store, department, and date.

test.csv - Test data without sales values.

stores.csv - Store information (type and size).

features.csv - Economic and marketing data like CPI, unemployment, fuel price, etc.

🔍 Exploratory Data Analysis (EDA)
Missing value handling and feature merging

Analysis of:

Sales trends across holidays (Christmas, Thanksgiving, etc.)

Department-wise and store-type-wise performance

Economic indicators (CPI, unemployment) vs. sales

Visualizations: Histograms, Boxplots, Time Series Trends, Barplots

🧪 Model Training
✅ Machine Learning Models:
Linear Regression

Random Forest Regressor

🔁 Time Series Model:
SARIMA (Seasonal ARIMA)

📈 Results & Insights
Holidays such as Christmas and Thanksgiving have a significant positive impact on sales.

SARIMA model performed well in capturing seasonality and weekly trends.

Forecasts can help Walmart plan inventory and staffing, reduce stockouts, and maximize revenue during peak times.

📌 Tools & Libraries Used
Python (Pandas, NumPy)

Matplotlib, Seaborn

Scikit-learn

Statsmodels (SARIMA)

Jupyter Notebook
