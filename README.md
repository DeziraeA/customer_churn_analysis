# Customer Churn Analysis & Prediction

## Project Overview

This project analyzes customer churn for a bank using Python, machine learning, and Tableau. The goal is to identify customer characteristics associated with churn, build a predictive model to identify customers at risk of leaving, and communicate the findings through an interactive dashboard.

The project combines exploratory data analysis, predictive modeling, customer risk segmentation, and data visualization to translate customer data into actionable retention insights.

## Dashboard

![Customer Churn Dashboard](images/Churn%20Dashboard.png)

The Tableau dashboard provides an overview of customer churn patterns and model predictions, including churn by geography, activity status, age group, customer risk level, and model performance.

## Business Objective

Customer churn can directly affect revenue and customer lifetime value. This analysis focuses on three main questions:

- Which customer groups have the highest churn rates?
- What characteristics are associated with an increased likelihood of churn?
- Can machine learning help identify customers who may be at risk of leaving?

The results can help a business prioritize customer retention efforts toward higher-risk segments.

## Dataset

The dataset contains 10,000 bank customers and includes demographic, financial, and account information such as:

- Age
- Geography
- Gender
- Credit score
- Account balance
- Tenure
- Number of products
- Credit card ownership
- Activity status
- Estimated salary
- Churn status

The target variable, `Exited`, indicates whether a customer stayed with or left the bank.

## Tools & Technologies

- **Python** — data cleaning, exploratory analysis, and predictive modeling
- **Pandas** — data manipulation and analysis
- **Matplotlib** — data visualization
- **Scikit-learn** — preprocessing and machine learning
- **Logistic Regression** — churn prediction
- **Tableau** — interactive dashboard and business intelligence visualization
- **Jupyter Notebook** — analysis and model development
- **Git/GitHub** — version control and project documentation

## Business Recommendations

Based on the analysis, the bank could:

- Prioritize retention campaigns for customers classified as high risk.
- Investigate the substantially higher churn rate among German customers to identify potential regional service or product issues.
- Develop engagement strategies for inactive customers, who showed considerably higher churn.
- Pay particular attention to customers aged 51–60, the age group with the highest observed churn rate.
- Use churn probability as a prioritization tool rather than relying solely on broad customer demographics.

## Repository Structure

```text
customer_churn_analysis/
│
├── data/
│   ├── Churn_Modelling.csv
│   └── churn_predictions.csv
│
├── images/
│   ├── Churn Dashboard.png
│   └── balanced_confusion_matrix.png
│
├── notebooks/
│   └── Customer_Churn_Analysis.ipynb
│
├── tableau/
│   └── Customer_Churn_Analysis.twbx
│
└── README.md
```

## Key Takeaway

The project demonstrates how exploratory data analysis, machine learning, and business intelligence can be combined to move from raw customer data to actionable retention insights. While the balanced model sacrifices some overall accuracy, its significantly higher recall makes it more useful for identifying customers who may require proactive retention efforts.