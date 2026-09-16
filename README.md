# Bank Customer Churn Analysis

## Project Overview

This project analyzes customer churn for a banking dataset of 10,000 customers using Python Exploratory Data Analysis (EDA) and Power BI.

The objective is to identify customer segments associated with higher churn rates and convert the analysis into an interactive business dashboard.

## Business Problem

Customer churn can negatively impact revenue and customer lifetime value.

This project aims to answer:

- What is the overall customer churn rate?
- Which countries have higher churn?
- How does customer activity relate to churn?
- Which age groups have higher churn?
- Does the number of products relate to churn?
- Which customer segments should be investigated for retention?

## Dataset

The dataset contains 10,000 bank customers and includes information such as:

- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Credit Card ownership
- Activity status
- Estimated Salary
- Churn status

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Power BI
- DAX

## EDA Process

The analysis included:

1. Data understanding and validation
2. Missing-value analysis
3. Descriptive statistics
4. Overall churn analysis
5. Demographic analysis
6. Geography analysis
7. Customer activity analysis
8. Product analysis
9. Credit score analysis
10. Balance and salary analysis
11. Multi-dimensional segmentation
12. Correlation analysis
13. Business recommendations

## Key Findings

- Overall churn rate: **20.37%**
- Germany showed the highest overall churn rate among the three countries.
- Inactive customers had a higher churn rate than active customers.
- Customers aged 46–55 showed substantially higher churn than younger age groups.
- Female customers had a higher observed churn rate than male customers.
- Customers with 3 products showed very high observed churn.
- Older and inactive customer segments showed particularly high churn rates.

These findings represent associations in the available dataset and should not be interpreted as proof of causation.

## Power BI Dashboard

### Dashboard Preview

![Page 1 - Executive Churn Overview](page1.png)

![Page 2 - Customer Risk Segmentation](page2.png)

The Power BI dashboard contains two pages:

### Page 1 — Executive Churn Overview

Includes:

- Total Customers
- Churned Customers
- Overall Churn Rate
- Active Customers
- Inactive Customers
- Active Customer Churn Rate
- Inactive Customer Churn Rate
- Geography analysis
- Activity analysis
- Product analysis
- Age analysis
- Gender analysis
- Credit Score analysis
- Balance analysis

### Page 2 — Customer Risk Segmentation

Includes multi-dimensional analysis of:

- Age × Activity
- Geography × Activity
- Geography × Gender
- Age × Products
- Age × Geography
- High-impact churn segments
- Churn contribution by segment

## Business Recommendations

Based on the observed patterns:

- Investigate retention opportunities among inactive customers.
- Pay particular attention to older customer segments.
- Investigate Germany-specific customer experience and retention factors.
- Examine one-product customers for potential engagement opportunities.
- Use customer segmentation rather than relying only on overall churn rate.
- Combine churn analysis with transaction, service, pricing and product-level data to investigate potential root causes.

## Project Structure

```text
Bank-Customer-Churn-Analysis/
│
├── Churn_Modelling.csv
├── churn_modelling_EDA-2.ipynb
├── Churn_Modelling.pbix
└── README.md
