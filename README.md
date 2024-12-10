This repository contains Python files for data cleaning and analysis of credit card data using pandas, numpy, matplotlib, and seaborn. The case study, titled "Credit Card Case Study," was conducted in Python 3.7 on Jupyter Notebook. The corresponding dataset is included in CSV format.

Objective: Analytics in the Credit Card Industry
Credit card data provides valuable insights into customer behavior, helping businesses optimize their operations through:

Understanding Customer Behavior: Identifying consumer spending patterns to design targeted marketing campaigns.
Personalized Offers: Tailoring promotions based on customer interests and location for increased sales.
Trend Analysis: Leveraging customer transaction trends to attract new customers.
Fraud Detection: Using data combined with AI to identify suspicious activity.
Chargeback Reduction: Detecting anomalies in transactions to prevent potential chargebacks.
Business Problem
PSPD Bank operates in 50+ countries. The CEO, Mr. Jim Watson, seeks insights into customer spending and repayment behaviors to address areas like bankruptcy, fraud, and collections. The dataset includes:

Customer Acquisition: Customer details at card issuance.
Spend Data: Credit card transactions by customers.
Repayment Data: Credit card payments by customers.
Tasks
Data Cleaning:
a. Replace age < 18 with the mean age.
b. Cap spending > limit at 50% of the customer’s limit.
c. Cap repayment > limit at the customer’s limit.

Analysis Summaries:

Total distinct customers and categories.
Average monthly spend and repayment.
Bank’s monthly profit based on a 2.9% interest rate.
Top 5 product types.
City with the highest spend.
Spending by age group.
Top 10 customers by repayment.
City-Wise and Product Analysis:

Yearly city-wise spend by product (with graphical representation).
Monthly comparison of total spend, city-wise.
Yearly spend comparison on air tickets.
Monthly spend by product to identify seasonality.
Custom Python Function:
Develop a user-defined function to identify the top 10 customers by repayment for each city, based on a specified product type (Gold/Silver/Platinum) and time period (monthly/yearly).
