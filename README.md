# AIinventoryPredictor
# 📈 AI Inventory Predictor: Smart Retail Logistics for the German Market

## 📋 Project Overview
This project addresses a classic supply chain challenge for small-to-medium enterprises (SMEs) in Germany: **Demand Forecasting**. Using machine learning, this tool predicts inventory needs for the next 30 days while accounting for unique German market constraints, such as Sunday retail closures (*Sonntagsruhe*) and seasonal fluctuations.

## 🚀 Key Features
* **Time Series Forecasting:** Predicts daily sales volume for high-turnover retail goods.
* **German Market Logic:** Automatically handles zero-sales on Sundays and accounts for public holidays.
* **Predictive Features:** Uses 'Lags' and 'Rolling Averages' to capture short-term trends.
* **Actionable Ordering:** Generates an automated "Order Alert" list based on predicted stockouts.

## 🛠️ Tech Stack
* **Python 3.10+**
* **Pandas & NumPy:** Data manipulation and feature engineering.
* **Scikit-Learn:** Random Forest Regressor for demand prediction.
* **Matplotlib & Seaborn:** Data visualization and seasonality analysis.

## 📊 Results
The model achieved a **Mean Absolute Error (MAE) of 6.20 units**, successfully predicting the "December Rush" for seasonal products like Glühwein with high accuracy.

## 📁 Project Structure
* `german_retail_data.csv`: Synthetic dataset of 2 years of German retail sales.
* `analysis.ipynb`: Exploratory Data Analysis (EDA) and visualization.
* `predictor.py`: The machine learning pipeline and 30-day forecast script.
* `README.md`: Project documentation.

## 📉 Visualizations
*(Pro-tip: Upload your 'combined_dashboard.png' to GitHub and link it here!)*
![Inventory Dashboard](combined_dashboard.png)
