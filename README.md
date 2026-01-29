Customer Shopping Behavior Analysis 🛒

Project Overview
This project provides a comprehensive analysis of 3,900 customers to identify key drivers of revenue and shopping frequency. It demonstrates a complete data lifecycle: from Python-based ETL and PostgreSQL analysis to Power BI visualization.

Tech Stack
Python: Data cleaning and feature engineering (Pandas)
PostgreSQL: Advanced querying
Power BI: Interactive dashboards and KPI tracking.

Key Steps

1. Data Cleaning & Feature Engineering (Python)
Handled 37 missing values in Review Rating using category-specific median imputation.
Performed feature engineering to create age_group (e.g., Senior, Mid-Age, Adult).
Standardized column names and mapped categorical frequencies to numerical days for analysis.

2. Database Analysis (SQL)
Imported cleaned data into PostgreSQL to perform analysis.
Identified high-spending customers who used discounts but exceeded average purchase amounts.
Ranked the top 5 products by average review rating.

3. Data Visualization (Power BI)
Built an interactive dashboard tracking Total Revenue based on different variables.
Identified that the Senior age group is the highest revenue contributor ($88K).
Visualized customer loyalty, segmenting users into Brand Loyalists and New Customers.

Insights & Findings
Revenue Leaders: Clothing is the dominant category, generating $104K in revenue.
Growth Opportunity: Only 27% of customers are currently subscribers, suggesting room for targeted marketing.
Demographic Focus: Seniors and Mid-Age groups represent the most significant purchase volume.
