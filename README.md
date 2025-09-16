# demand-forecasting-retail
# Problem Statement: 
Outbound Forecasting Model to optimize capacity and labor planning

# Dataset: 
Kaggle "Retail Demand Forecasting" dataset.
3 years of sales data across 100 products.

# Approach:
1. Data cleaning (handling missing values & duplicates) & feature engineering (holidays, promotions, lags).
2. Exploratory Data Analysis (sales trends, seasonality).
3. Visualizations with matplotlib and seaborn
4. Time series modeling: ARIMA, Prophet, and XGBoost.
5. Evaluation: RMSE, MAPE. Compare Baseline Vs ML Models

# Results:
1. XGBoost reduced forecast error by x% compared to baseline
2. Potential annual savings: ~$2.3M in reduced logistics costs

# Next Steps:
1. Deploy model as a Streamlit app (enter product ID → get 4-week forecast chart)
2. Integrate into BI dashboard

# Tech Stack: 
Languages: Python, pandas, scikit-learn 
Modeling: Prophet, SQL, Matplotlib
Visualization: matplotlib, seaborn, plotly  
Deployment: Streamlit, Flask (optional)  
Data Handling: SQL, CSV 
