# Retail-Sales-Forecast-Dashboard

📊 Retail Sales Forecasting Dashboard (Power BI + Prophet)
🔍 Overview
This project uses Python’s Prophet library to forecast future retail sales and visualizes the results through a dynamic Power BI dashboard.

The goal is to help retail teams predict demand, plan inventory, and identify future trends using time-series forecasting and business intelligence tools.

🧠 Key Features
✅ Interactive KPI cards for avg/max/min forecasted sales

📅 Date slicer to filter the forecast by custom time ranges

📈 Line chart with confidence intervals (yhat ± CI)

📊 Bar chart showing forecasted sales by month/year

📋 Forecast table for daily predictions with lower/upper bounds

🛠 Tech Stack
Python: Data preprocessing + Prophet model (yhat, yhat_lower, yhat_upper)

Pandas: Data manipulation

Prophet: Time-series forecasting

Power BI Desktop: Dashboard creation

Power BI Template (.pbit): Shareable and reusable report format

📁 Files Included

File	Description
forecast_results.csv	Output of Prophet model (date, yhat, bounds)
Retail_Sales_Forecasting_Dashboard.pbit	Power BI dashboard template
README.md	This file
📈 How to Use the Template
Open Retail_Sales_Forecasting_Dashboard.pbit in Power BI Desktop

Load your own forecast_results.csv when prompted

Explore the dashboard using slicers, charts, and tables

📌 Example Use Cases
Retail demand planning

Sales forecasting for product lines

Inventory optimization

Seasonal trend analysis

🚀 Future Improvements
Add actual vs forecast comparison chart

Integrate automatic data refresh using Power Automate

Add geographic breakdown if regional data is available

👤 Author
Dylan Dizon

