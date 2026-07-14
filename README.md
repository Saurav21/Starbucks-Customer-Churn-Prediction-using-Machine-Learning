# Starbucks Customer Churn Prediction using Machine Learning

## Project Overview

Customer retention is one of the most important challenges faced by modern businesses. Understanding which customers are likely to stop purchasing enables organizations to launch proactive retention campaigns, improve customer satisfaction, and maximize customer lifetime value.

This project develops a machine learning model to predict customer churn using Starbucks customer ordering behavior and demographic information.

---

## Business Problem

The dataset does not contain a predefined churn label.

To simulate a real-world business scenario, customer churn was defined using a rule based on purchase inactivity. Customers who had not placed an order for more than **70 days** from the reference date were labeled as **Churned**, while the remaining customers were considered **Active**.

The objective is to identify customers at risk of leaving before they become inactive.

---

## Dataset

**Source:** Starbucks Customer Ordering Patterns [(Kaggle)](https://www.kaggle.com/datasets/likithagedipudi/starbucks-customer-ordering-patterns)

The dataset contains:

* Customer ordering history
* Order channels
* Beverage preferences
* Customer demographics
* Rewards membership
* Store information
* Customer satisfaction

---

## Project Workflow

* Data Cleaning and Preprocessing
* Customer-Level Feature Engineering
* Churn Label Creation
* Exploratory Data Analysis
* Feature Encoding
* Model Development using CatBoost
* Model Evaluation
* Feature Importance Analysis
* Business Recommendations

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* CatBoost

---

## Model Performance

| Metric   |               Value |
| -------- | ------------------: |
| Model    | CatBoost Classifier |
| Accuracy |          **60%** |

The objective of this project is not to maximize predictive accuracy but to demonstrate a realistic customer retention workflow using customer behavioral data.

---

## Key Business Insights

* Customer inactivity can be used to identify potential churn.
* Customer behavior provides valuable signals for retention modeling.
* Feature importance helps identify factors contributing to customer churn.
* Predictive analytics enables businesses to proactively target customers before they disengage.

---

## Business Value

This solution can help businesses:

* Identify customers at risk of churning
* Prioritize retention campaigns
* Improve customer engagement
* Optimize loyalty programs
* Support data-driven marketing decisions

---

## Repository Structure

```text
├── Starbucks_Customer_Churn_Prediction.ipynb
│    
├── data/
│   └── starbucks_customer_ordering_patterns.csv
├── README.md
└── requirements.txt
```



## Related Project

This project is part of a broader Marketing Analytics portfolio.

**Previous Project**

➡️ Starbucks Customer Segmentation for Personalized Marketing Campaigns using RFM Analysis

---

## Author

**Saurav Bhuyan**

