# FicZon Lead Quality Prediction

This project aims to improve sales effectiveness for FicZon Inc. by predicting lead quality—classifying leads as **High Potential** or **Low Potential**—using machine learning.

## Problem Statement

FicZon Inc. relies heavily on digital channels and sales force effectiveness to generate leads. With rising competition, sales are dipping. Currently, lead quality categorization is manual and post-analysis based. This project uses ML to pre-categorize leads, enabling better prioritization and improved sales outcomes.

## Dataset Overview

The dataset includes lead details such as:

- **Created**: Lead generation date  
- **Product_ID**: Interested product  
- **Source**: Lead origin  
- **Sales_Agent**: Assigned sales representative  
- **Location**: Lead's geographic location  
- **Delivery_Mode**: Preferred delivery  
- **Status**: Lead status (e.g., Open, Converted, Junk Lead)

## Exploratory Data Analysis (EDA) Insights

- Certain sales agents have higher "Junk Lead" rates, indicating areas for training.  
- Bangalore is a key region with the most leads and high-potential leads.  
- Product ID 15 and Delivery Mode 5 are the most preferred options.

## Modeling and Results

Several classification models were tested, including Logistic Regression, Decision Tree, Random Forest, K-Nearest Neighbors, and XGBoost.

| Model             | Accuracy  |
|-------------------|-----------|
| XGBoost           | 70.83%    |
| Random Forest     | 68.10%    |
| K-Nearest Neighbors | 66.46%  |
| Decision Tree     | 65.71%    |
| Logistic Regression | 64.48%  |

XGBoost showed the best performance, making it the recommended model for lead classification.

## Conclusion

Using machine learning to predict lead quality enables FicZon to prioritize sales efforts, improve conversion rates, and stay competitive in a maturing market.

---

