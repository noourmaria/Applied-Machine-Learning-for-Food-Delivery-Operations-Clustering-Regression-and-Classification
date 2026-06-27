# Applied Machine Learning for Food Delivery Operations

## Overview

This project applies machine learning techniques to a food delivery operations dataset to analyse order patterns, predict delivery time, and model the likelihood of customer complaints.

The project demonstrates an end-to-end applied machine learning workflow, including exploratory data analysis, clustering, regression, classification, preprocessing, feature engineering, model comparison, hyperparameter tuning, and evaluation.

## Objectives

The project focuses on three main tasks:

* Perform exploratory data analysis to understand delivery patterns and operational factors
* Apply clustering to identify representative order types and system-load scenarios
* Build and evaluate machine learning models for:

  * delivery time prediction
  * customer complaint prediction

## Methods

The workflow includes:

* Data cleaning and preprocessing
* Missing value handling
* Feature engineering
* One-hot encoding and feature scaling
* K-Means clustering
* Regression modelling
* Binary classification
* Baseline model comparison
* Cross-validation and hyperparameter tuning
* Model evaluation using appropriate regression and classification metrics

## Key Insights

The analysis showed that delivery performance is strongly affected by operational workload and order characteristics. Features such as outstanding orders, busy delivery partners, order size, and order value were important for understanding delivery delays.

Clustering identified different operational scenarios, including high-load conditions, large high-value orders, and low-load small-order conditions.

For delivery time prediction, multiple regression models were compared, with the tuned gradient boosting model achieving the strongest performance among the tested models.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook / Google Colab

## Repository Structure

```text
.
├── report/
│   └── machine_learning_coursework_report.pdf
├── notebook/
│   └── food_delivery_ml_pipeline.ipynb
├── notebook-pdf/
│   └── food_delivery_ml_pipeline.pdf
├── LICENSE
└── README.md
```

## Academic Context

This project was completed as part of a university Machine Learning coursework assignment.

The full methodology, results, figures, model comparisons, and critical analysis are available in the project report.

