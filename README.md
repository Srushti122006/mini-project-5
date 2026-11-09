# QuickCart Warehouse Inventory Stockout Risk Prediction

## Project Overview

QuickCart Warehouse Inventory Stockout Risk Prediction is a Data Science and Machine Learning project that focuses on identifying products that may run out of stock before the next supplier delivery.

The project uses historical inventory data, store details, product information, supplier reliability and festival-related demand to classify inventory into three categories:

- **Safe** – Sufficient stock is available.
- **At-Risk** – Stock levels are getting low.
- **Imminent** – The product may run out before the next delivery.

## Problem Statement

Managing inventory is an important challenge for quick-commerce businesses. Low stock can result in lost sales and customer dissatisfaction, while excessive ordering can increase storage costs.

This project aims to use machine learning to predict inventory stockout risks and support better stock management decisions.

## Project Objectives

- Analyze daily warehouse inventory data.
- Combine multiple datasets using common keys.
- Identify missing values and data inconsistencies.
- Perform Exploratory Data Analysis (EDA).
- Understand the impact of festivals and supplier reliability on stockouts.
- Perform feature engineering.
- Build and evaluate machine learning classification models.

## Dataset Description

The project contains five CSV datasets:

1. `dim_stores.csv` – Store information.
2. `dim_skus.csv` – Product information.
3. `dim_suppliers.csv` – Supplier information.
4. `dim_events.csv` – Festival and promotional information.
5. `fact_inventory_daily.csv` – Daily inventory records.

The main inventory dataset contains 21,600 records.

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Workflow

1. Dataset collection and loading
2. Data exploration
3. Data cleaning and preprocessing
4. Data integration and merging
5. Exploratory Data Analysis
6. Feature engineering
7. Training and testing data preparation
8. Machine learning model development
9. Model evaluation
10. Result analysis

## Machine Learning Algorithms

- Majority Classifier (Baseline)
- Logistic Regression
- Random Forest Classifier

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Special attention is given to the recall of the Imminent class because identifying potential stockouts is important for inventory planning.

## Expected Outcome

The project aims to develop a classification model that can identify stockout risks and help businesses make better inventory and replenishment decisions.

## Conclusion

This project provides practical experience in data preprocessing, data analysis, feature engineering and supervised machine learning. It demonstrates how data-driven techniques can be applied to real-world inventory management problems.

