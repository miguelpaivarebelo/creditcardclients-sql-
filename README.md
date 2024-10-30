# Credit Card Default Prediction Analysis
This project focuses on understanding the factors influencing credit card default risk. Using SQL queries in Google BigQuery, we analyze a dataset from UCI Machine Learning Repository with 30,000 client records detailing demographic information, credit limits, payment history, and more.

## Objectives
Identify default patterns based on demographics, credit usage, and payment behaviors.
Explore key predictors of default risk, including payment history and billing amounts.

## Steps Taken
1. Data Importation and Preparation
The dataset was imported into Google BigQuery.
Initial data cleansing included removing duplicates, handling NULL values, and formatting date fields for consistency.
2. SQL Analysis
Demographic Distribution: Assessed age, education, marital status, and gender distributions among credit card holders.
Credit Limit Analysis: Analyzed credit limit distribution (LIMIT_BAL) and identified common credit amounts among clients.
Default Behavior by Demographics: Examined default patterns based on education and marital status to identify high-risk groups.
Payment History Exploration: Reviewed historical payment statuses (e.g., PAY_0, PAY_2, etc.) to understand trends in delayed payments.
Billing and Payment Amounts: Analyzed recent billing amounts and payments to assess financial stability and risk trends.
3. Insights Gained
Noted significant differences in default rates across demographic groups.
Observed that higher credit limits correlated with lower default rates for certain demographics.
Identified that consistent payment delays were strong predictors of default.
4. Future Steps
Visualization: Plan to create visual dashboards in Power BI for interactive exploration.
Modeling: Explore machine learning models to predict default risk based on key features.

## Technologies Used
SQL: For data querying, aggregation, and analysis.
Google BigQuery: Managed storage and processing of the dataset.
Power BI (planned): For visualizing results and enhancing interpretability.

## Dataset Details
Source: UCI Machine Learning Repository
Attributes: Includes client demographics, credit limit (LIMIT_BAL), payment history (PAY_0 to PAY_6), billing (BILL_AMT1 to BILL_AMT6), and default indication (default_payment_next_month).
