# Customer Activity Prediction

Machine learning project for predicting customer activity decline in an e-commerce platform.

## Project Overview

Customer retention is a key objective for online businesses, as retaining existing customers is generally more cost-effective than acquiring new ones. This project focuses on predicting customer activity decline to help identify users who may require personalized retention strategies.

## Objective

Develop and compare machine learning models to predict whether a customer's purchasing activity will decrease over the next three months based on behavioral, transactional, and marketing data.

## Dataset

The project uses an educational e-commerce dataset containing information about:

- customer purchasing behavior;
- website activity;
- marketing interactions;
- revenue history;
- customer profitability.

**Note:** The original dataset is not included in this repository in accordance with the educational platform policy.

## Project Workflow

- Data loading and validation
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Model training and comparison
- Hyperparameter tuning
- Model evaluation
- Feature importance analysis
- Customer segmentation
- Business recommendations

## Models

The following classification models were evaluated:

- K-Nearest Neighbors
- Decision Tree
- Logistic Regression
- Support Vector Classifier (SVC)
- Gradient Boosting

Model selection was performed using **ROC-AUC** as the primary evaluation metric.

## Results

| Metric | Value |
|---------|------:|
| Task | Binary Classification |
| Best Model | Support Vector Classifier (SVC) |
| ROC-AUC | **0.924** |

The Support Vector Classifier demonstrated the best predictive performance and generalization on the test dataset.

## Key Findings

- Customer browsing behavior was one of the strongest predictors of future activity.
- Website engagement metrics significantly influenced model performance.
- Customer segmentation helped identify high-value users at risk of reduced activity.
- Feature importance analysis improved model interpretability.

## Business Recommendations

The developed model can support customer retention strategies by identifying users with a high probability of reduced activity.

Recommended actions include:

- personalized marketing campaigns;
- targeted product recommendations;
- loyalty program optimization;
- proactive engagement with high-value customers.

## Tech Stack

- Python
- pandas
- NumPy
- matplotlib
- seaborn
- scikit-learn
- SHAP
- Phik
