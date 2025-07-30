📈 Time Series Forecasting & Power BI Dashboard – Northwind Datase
Project Overview

This project focuses on performing time series analysis on the Northwind dataset using Python-based statistical models—ARIMA, Moving Average, and Exponential Smoothing—to forecast future sales trends. Additionally, a Power BI dashboard was created to visualize and analyze key customer insights, specifically identifying the Top 10 Customers by Total Sales.

⸻

 Tools & Technologies
	•	Python
	•	Pandas
	•	Matplotlib & Seaborn
	•	Statsmodels
	•	Power BI
	•	Jupyter Notebook
	•	Northwind Sample Dataset (SQL)

⸻

 Objective
	•	To analyze historical sales data and build accurate forecasting models.
	•	To compare different time series models and evaluate performance.
	•	To visualize top customers and their contributions to revenue through an interactive dashboard.

⸻

 Dataset Description

The dataset was sourced from the Northwind Traders sample database. Key tables used:
	•	Orders
	•	Order_Details
	•	Customers
	•	Products

Preprocessing involved:
	•	Merging multiple tables
	•	Aggregating sales over time (monthly)
	•	Handling missing values and setting a time index

⸻

 Time Series Models Applied

 Moving Average
	•	Used to smoothen short-term fluctuations and highlight longer-term trends or cycles.
	•	Visualized using rolling mean and standard deviation.

 Exponential Smoothing (Simple & Holt-Winters)
	•	Weighted moving average model that gives more weight to recent observations.
	•	Models both trend and seasonality (Holt-Winters).

 ARIMA (Auto-Regressive Integrated Moving Average)
	•	Selected after performing ADF (Augmented Dickey-Fuller) Test and analyzing ACF/PACF plots.
	•	Parameters (p, d, q) were optimized using grid search and AIC evaluation.
	•	Residual diagnostics confirmed model adequacy.

⸻

 Model Evaluation
	•	Performance Metrics: MAE, RMSE
	•	Compared actual vs. forecasted values
	•	Visual inspection of residuals for randomness

⸻

 Power BI Dashboard

Dashboard Insights:
	•	Top 10 Customers by Total Sales
	•	Region/Country-wise breakdown
	•	Sales Trends (Monthly)
	•	Customer Contribution % to Total Revenue

Features:
	•	Interactive filters
	•	Dynamic charts and KPIs
	•	Clean and business-friendly visuals
├── data/
│   └── northwind.sql
├── notebooks/
│   └── time_series_analysis.ipynb
├── dashboard/
│   └── top_10_customers.pbix
├── README.md

 Key Takeaways
	•	ARIMA gave the most accurate forecasts based on RMSE and residual analysis.
	•	Power BI dashboard provided quick business insight on top revenue-generating customers.
	•	This combination of statistical modeling and BI visualization supports better decision-making.

⸻

 Future Improvements
	•	Automate model selection using Auto-ARIMA
	•	Deploy dashboard using Power BI service or Flask (for web)
	•	Extend model to include exogenous variables (e.g., promotions)

⸻

 Contact

Olaniyan Kafayat Owoseni
Data Scientist | Analyst | BI Developer
 Olaniyan.kafayat@yahoo.com
 http://www.linkedin.com/in/kafayat-olaniyan-3
https://github.com/isakaffy ||
