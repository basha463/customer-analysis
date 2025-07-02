Project Title
Customer Subscription and Churn Analysis

Description
This project aims to understand customer behavior by analyzing subscriptions, transactions, and churn patterns to identify key customer segments. It also tracks subscription patterns (active, expired, churned) to optimize retention strategies and assess plan type effectiveness. Furthermore, it analyzes transaction trends to measure purchasing behavior, revenue trends, and transaction types for business growth. Finally, the project identifies the main reasons for customer churn by region and plans targeted actions to reduce churn rates.




Files in this Repository
customer_churn_python.ipynb: A Jupyter Notebook containing the Python code for data loading, cleaning, analysis, and visualization.

Customer Subscription and Churn Analysis: A document outlining the SQL queries and insights derived from the analysis.

customer_churn_dashboard.png: An image of the customer churn dashboard, visualizing key metrics and findings.

Analysis Details
customer_churn_python.ipynb
This Jupyter Notebook performs an in-depth analysis of customer data, including:


Data Loading: Loads Customers.csv, Transactions.csv, Subscriptions.csv, and Churn.csv into pandas DataFrames.


Data Preprocessing: Converts relevant columns to datetime objects for proper time-series analysis.

Exploratory Data Analysis (EDA):

Examines the shape and information of each DataFrame to understand data types and null values.

Provides descriptive statistics for numerical columns in the 

transactions DataFrame.

Identifies customers from specific regions, such as North America.


Customer Behavior Analysis: Analyzes spending patterns per customer, identifies top customers by spend, and visualizes these insights.


Churn Analysis: Investigates churn rates and reasons across different customer segments and regions.


Visualizations: Uses matplotlib and seaborn to create various plots and charts to illustrate findings, such as customer spending and churn distribution.

Customer Subscription and Churn Analysis.docx
This document provides a detailed overview of the analysis, including:

SQL Queries: Presents the SQL queries used to extract and transform data for analysis.


Key Insights: Summarizes the findings related to customer behavior, subscription patterns, transaction trends, and churn reasons.

customer_churn_dashboard.png
This image provides a visual summary of the key metrics and insights derived from the customer churn analysis. It serves as a quick overview of customer subscription status, transaction trends, and churn drivers.
