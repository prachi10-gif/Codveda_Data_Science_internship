# Level 1 - Task 3: Exploratory Data Analysis

## Objective

Perform exploratory data analysis on a customer churn dataset to understand customer behavior, identify patterns, analyze relationships between variables, and discover factors associated with customer churn.

## Dataset

**Dataset:** `churn-bigml-80.csv`

- Rows: 2,666
- Columns: 20
- Missing values: None
- Duplicate records: None

## Tools & Libraries

- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab

## Analysis Performed

1. Dataset overview and summary statistics
2. Customer churn distribution
3. Distribution of total day minutes
4. Box plot of day minutes by churn status
5. Customer service calls by churn status
6. Correlation matrix of numerical variables
7. Scatter plot of day minutes vs. day charges
8. Churn rate by international plan
9. Average usage comparison between churned and non-churned customers

## Key Findings

- 85.45% of customers did not churn, while 14.55% churned.
- Churned customers had higher average daytime usage: 205.18 minutes compared with 175.10 minutes for non-churned customers.
- Churned customers had higher average evening and night usage.
- Churned customers made more customer service calls on average (2.21) than non-churned customers (1.45).
- Customers with an international plan showed a higher churn rate.
- Day minutes and day charges showed a strong relationship.
- Usage and customer service behavior appear to be useful indicators for understanding churn.

## Conclusion

The exploratory analysis identified meaningful differences between churned and non-churned customers. Higher usage and increased customer service interactions were particularly noticeable among churned customers. These findings can be used as a foundation for building a machine learning classification model to predict customer churn.

## Files

- `Codveda_Level1_Task3_EDA.ipynb` - Complete EDA notebook
- `README.md` - Project documentation
