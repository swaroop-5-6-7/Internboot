📊 Sales Forecasting & Analysis using Python
📌 Project Overview

This project focuses on exploratory data analysis (EDA) and basic time-series forecasting techniques applied to real-world retail sales data.
The goal is to understand sales patterns and build baseline prediction models using simple, interpretable methods.

The project is structured as progressive tasks, moving from data understanding to forecasting and regression modeling.

📂 Dataset

Source: Kaggle – Store Sales Time Series Forecasting

Link: https://www.kaggle.com/competitions/store-sales-time-series-forecasting

⚠️ Note:
The dataset files (train.csv, test.csv) are not included in this repository due to GitHub file size limits.
Please download them directly from Kaggle before running the code.

🛠 Tech Stack

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

🧪 Tasks Implemented
✅ Task 1: Exploratory Sales Analysis

Loaded and cleaned sales data using Pandas

Handled missing values

Generated descriptive statistics (mean, median, mode)

Visualized sales trends and seasonality

Analyzed store-wise and product-wise performance

Learning Outcome:
Understanding data quality, trends, and seasonality before modeling.

✅ Task 2: Simple Sales Forecast using Moving Average

Aggregated daily sales

Computed:

7-day (weekly) moving average

30-day (monthly) moving average

Compared actual sales with smoothed trends

Visualized trend lines

Learning Outcome:
Understanding rolling windows, trend smoothing, and baseline forecasting.

✅ Task 3: Linear Regression for Sales Prediction

Feature engineering from date (year, month, day, weekday)

Included promotion data as a predictor

Performed train-test split

Built a Linear Regression model

Evaluated performance using MAE and RMSE

Learning Outcome:
First hands-on experience with regression modeling and evaluation.

📁 Project Structure
Internboot/
│
├── notebooks/            # Jupyter notebooks (EDA, forecasting, regression)
├── src/                  # Python scripts (if applicable)
├── README.md             # Project documentation
├── .gitignore            # Ignored large files & datasets

▶️ How to Run the Project

Clone the repository:

git clone https://github.com/swaroop-5-6-7/Internboot.git


Download the dataset from Kaggle

Place train.csv in your working directory (not tracked by Git)

Run the notebooks or Python scripts

📈 Results & Observations

Sales show clear seasonality and trend patterns

Moving averages effectively smooth noisy sales data

Promotions have a positive impact on sales

Linear Regression provides a strong baseline model, though more advanced models can improve accuracy

🚀 Future Improvements

Add holiday and event data

Try advanced models (ARIMA, Prophet, XGBoost)

Perform hyperparameter tuning

Improve feature engineering

👤 Author

Swaroop Yadiki
Internboot Project – Data Analysis & Machine Learning