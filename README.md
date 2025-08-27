# Financial Forecasting using Time Series & Regression :

Predicts future company revenues and expenses using historical data through regression and time series analysis. Includes Python models, Excel analysis, and Tableau dashboards for business insights and decision-making.

# Project Overview :

This project focuses on building a Financial Forecasting Model to predict future revenues and expenses using historical financial data. The goal is to support business analysts and decision-makers with insights into financial trends, growth opportunities, and potential risks.

We used Python (Time Series Analysis, Regression) and Excel/Tableau for analysis and visualization.

# Tools & Technologies :

Python: Pandas, NumPy, Matplotlib, Seaborn, Statsmodels, Scikit-learn

ML Model : Logistic Regression

Tableau: Interactive dashboards & visualizations

# Dataset :

Source: 50_Startups.csv (simulated company financial dataset)

Features include:

R&D Spend

Administration

Marketing Spend

Profit (Revenue)

We also extended it for time-series forecasting by creating a date column and preparing data for future predictions.

# Steps & Methodology :

1. Data Preprocessing

Cleaned dataset (handled categorical data like State)

Checked correlations between features

2. Exploratory Data Analysis (EDA)

Heatmap of correlations

Trend analysis of R&D, Marketing, and Revenue

3. Predictive Modeling

Multiple Linear Regression → to find key revenue drivers

Time Series Forecasting (ARIMA/ETS) → to predict future revenue trends

4. Evaluation Metrics

MAE (Mean Absolute Error)

RMSE (Root Mean Squared Error)

R² Score for model accuracy

5. Visualization (Tableau Dashboard)

Revenue vs Expenses trend over time

Forecasted revenue growth

Key feature impact on revenue

Regional/state-level performance

# Results :

Regression Findings:

R&D Spend is the strongest driver of Profit

Marketing Spend has a smaller but positive effect

Administration has little to negative impact

Forecasting:

Achieved an R² Score ≈ 0.90 for regression model

Time series forecasts indicate steady revenue growth

# Tableau Dashboard :

The interactive dashboard includes:

Revenue & Expense Trends

Forecasted Revenue (line chart with projections)

Top Performing States/Regions

Expense Breakdown

# How to Run the Project:

1. Clone Repository
git clone https://github.com/your-username/financial-forecasting.git
cd financial-forecasting

2. Install Dependencies
pip install -r requirements.txt

3. Run Jupyter Notebook
jupyter notebook Financial_Forecasting.ipynb

4. View Dashboard

Open the Tableau workbook (Financial_Forecast.twbx) or 
# access it via Tableau Public link : https://public.tableau.com/app/profile/sg1710/vizzes

# Business Recommendations :

Increase R&D Investment → strong correlation with higher profit

Optimize Marketing Spend → ensure ROI-driven campaigns

Control Administrative Costs → minimal impact on profit

🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request.
