# Customer Churn Analysis

## Project Overview

This project analyzes customer churn data to identify the key factors that influence customer retention and churn. The analysis combines Python, SQL, and data visualization to generate meaningful business insights.

## Business Problem

Customer churn can significantly affect business revenue and growth. The objective of this project is to understand customer behavior and identify patterns associated with customer churn.

## Objectives

- Analyze overall customer churn
- Identify customer groups with higher churn rates
- Analyze churn by contract type
- Study the relationship between monthly charges and churn
- Analyze churn by internet service and payment method
- Identify high-risk customer segments
- Generate actionable business insights

## Dataset

The dataset contains customer information including:

- Customer demographics
- Tenure
- Contract type
- Internet service
- Payment method
- Monthly charges
- Total charges
- Churn status

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQL
- SQLite
- Jupyter Notebook
- VS Code

## Data Cleaning

The following preprocessing steps were performed:

- Converted `TotalCharges` into numeric format
- Handled missing values
- Checked duplicate records
- Checked data types
- Performed basic statistical analysis

## Exploratory Data Analysis

The project analyzes:

- Overall customer churn
- Churn by contract type
- Monthly charges vs churn
- Churn by customer tenure
- Churn by internet service
- Churn by payment method
- Churn by senior citizen status
- Partner and dependent analysis
- Correlation between numerical variables

## SQL Analysis

SQLite was used to perform business-oriented queries such as:

- Total customer count
- Churned vs retained customers
- Contract-wise churn
- Average monthly charges by churn status
- Identification of high-risk churned customers

## Key Insights

The analysis identified several important patterns:

- Month-to-month customers show higher churn compared with customers on longer-term contracts.
- Customers with shorter tenure are more likely to churn.
- Monthly charges are associated with differences in churn behavior.
- Churn rates vary across internet service types.
- Payment methods show different levels of customer churn.

## Business Recommendations

Based on the analysis:

- Encourage customers to move to longer-term contracts.
- Provide retention offers to high-risk customers.
- Focus on customers with short tenure and high monthly charges.
- Improve customer support and service experience.
- Develop personalized retention strategies using customer behavior.

## Project Structure
```text
Customer Churn Analysis
│
├── data
│   └── Telco-Customer-Churn.csv
│
├── notebooks
│   └── Customer_Churn_Analysis.ipynb
│
├── sql
│   └── customer_churn.db
│
├── visualizations
│   ├── churn_distribution.png
│   ├── churn_by_contract.png
│   ├── monthly_charges_vs_churn.png
│   ├── churn_by_internet_service.png
│   └── churn_by_payment_method.png
│
└── README.md
```

## Conclusion

This project provided practical experience in data cleaning, exploratory data analysis, SQL querying, data visualization, and converting data into actionable business insights.

## Author

B.Tech CSE 
