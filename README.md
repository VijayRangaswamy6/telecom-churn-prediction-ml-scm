# Telecom Customer Churn Prediction using Machine Learning

> Predicting high-value telecom customer churn using Machine Learning and optimizing customer retention through a Supply Chain-inspired decision framework.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## Project Overview

Customer churn is one of the biggest challenges faced by telecom companies. Acquiring new customers is significantly more expensive than retaining existing ones, making churn prediction an important business problem.

This project develops an end-to-end Machine Learning pipeline to identify high-value customers who are likely to churn. In addition to predictive modeling, the project introduces a Supply Chain-inspired retention strategy that prioritizes customers based on churn risk and business value, enabling more efficient allocation of retention resources.

---

## Objectives

- Predict telecom customer churn using Machine Learning.
- Identify high-value customers with a higher probability of leaving.
- Compare multiple classification algorithms.
- Improve prediction accuracy through feature engineering and dimensionality reduction.
- Develop a data-driven retention strategy using Supply Chain Management concepts.

---

## Dataset

The dataset consists of telecom customer behavioral data collected over multiple months.

**Dataset Characteristics**

- 99,999 customer records
- 226 features
- Monthly telecom usage data
- Recharge behavior
- Call and internet usage
- Customer activity patterns

> **Note:**  
> The dataset is not included in this repository due to GitHub file size limitations. Please download it separately and place it inside the `dataset/` directory.

---

## Machine Learning Workflow

```
Raw Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Missing Value Treatment
      │
      ▼
Feature Engineering
      │
      ▼
High Value Customer Selection
      │
      ▼
Churn Definition
      │
      ▼
Train/Test Split
      │
      ▼
Model Training
      │
      ▼
Model Evaluation
      │
      ▼
Customer Retention Strategy
```

---

## Models Evaluated

The following machine learning algorithms were implemented and compared:

- Logistic Regression
- Logistic Regression with PCA
- Decision Tree Classifier
- Random Forest Classifier

Performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

The Random Forest model demonstrated the strongest predictive performance and was selected for the final retention framework.

---

## Supply Chain Optimization

Beyond churn prediction, this project integrates Supply Chain Management principles into customer retention.

Customers are segmented based on:

- Churn probability
- Customer value
- Business impact

This enables:

- Prioritized retention campaigns
- Efficient marketing budget allocation
- Improved customer lifetime value
- Data-driven business decision making

---

## Repository Structure

```
telecom-churn-prediction-ml-scm/

├── dataset/
├── images/
├── notebooks/
│   └── telecom_churn_prediction_portfolio.ipynb
├── presentations/
├── report/
├── results/
├── src/
└── README.md
```

---

## Technologies Used

### Programming

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

### Machine Learning

- Logistic Regression
- Principal Component Analysis (PCA)
- Decision Tree
- Random Forest

### Development

- Jupyter Notebook
- Git
- GitHub

---

## Results

Key outcomes of the project include:

- Comprehensive data preprocessing pipeline
- High-value customer identification
- Feature engineering for churn prediction
- Comparative evaluation of multiple ML models
- Supply Chain-inspired customer retention framework

---

## Future Improvements

- Hyperparameter optimization using GridSearchCV
- XGBoost and LightGBM implementation
- Model deployment using Flask/FastAPI
- Interactive dashboard using Streamlit
- Real-time churn prediction API

---

## Contributors

This project was completed as part of an academic group project.

---

## Acknowledgements

This project was developed as part of the B.Sc. Data Science & Analytics curriculum at **M. S. Ramaiah University of Applied Sciences**.

---


