# Machine Learning Project — Car Price & FIFA Player Analysis

An end-to-end machine learning project covering exploratory data analysis, preprocessing, regression, classification, model optimization, cross-validation, and ensemble learning using real-world car price and FIFA player datasets.

The project progresses from individual predictive models to a unified machine learning system designed for robust and stable predictions.

## Project Overview

The project consists of three progressive assignments:

* **Assignment 1:** Car Price Analysis
* **Assignment 2:** FIFA Players Performance Analysis
* **Assignment 3:** Unified Scouting System — Final Project

Across the three assignments, the project applies a complete machine learning workflow including data exploration, preprocessing, feature engineering, model development, hyperparameter optimization, validation, performance analysis, and model comparison.

---

## Assignment 1 — Car Price Analysis

The first assignment addresses two machine learning tasks using the same preprocessing pipeline:

### Regression

Predict the exact selling price of a car using **Linear Regression**.

### Classification

Classify cars into three price categories:

* Cheap
* Moderate
* Expensive

### Main Techniques

* Exploratory Data Analysis (EDA)
* Missing-value handling
* Categorical feature encoding
* Feature scaling
* Outlier detection and handling
* Linear Regression
* K-Nearest Neighbors (KNN)
* Grid Search
* K-Fold Cross-Validation
* Classification evaluation using Accuracy, Precision, Recall, and F1-score
* Confusion Matrix analysis
* Sensitivity analysis

The assignment also investigates the effect of removing highly correlated features, disabling feature scaling, and changing classification thresholds.

---

## Assignment 2 — FIFA Players Performance Analysis

The second assignment focuses on predicting player market value and classifying players into four performance tiers:

**Low | Mid | High | Elite**

### Regression — Player Market Value

The regression workflow includes:

* Baseline Linear Regression
* Polynomial Regression with multiple degrees
* Ridge Regression
* Lasso Regression
* Hyperparameter analysis using alpha sweeps
* Train/Test performance comparison
* Overfitting and generalization analysis

Regression models are evaluated using:

* MAE
* MSE
* RMSE
* R² Score

### Classification — Player Performance

The classification workflow includes:

* Logistic Regression
* L1 and L2 regularization
* Hyperparameter tuning using C sweeps
* Gaussian Naïve Bayes
* Bernoulli Naïve Bayes
* Complement Naïve Bayes
* Confusion Matrix analysis
* Accuracy, Precision, Recall, and F1-score

### Model Validation

To obtain more reliable performance estimates, the project applies:

* **5-Fold Cross-Validation** for regression
* **Stratified 5-Fold Cross-Validation** for classification
* Mean and standard deviation analysis
* Fold-by-fold performance comparison
* Model stability analysis

---

## Assignment 3 — Unified Scouting System

The final project evolves the previous FIFA prediction models into a **Unified Scouting System**.

Instead of relying on baseline models, the system focuses on improving predictive performance, reducing overfitting and variance, and building a more reliable machine learning pipeline.

### Model Selection

At least three diverse machine learning approaches are implemented and compared to capture non-linear relationships and complex patterns within the FIFA dataset.

### Model Optimization

Each model is systematically optimized using:

* Hyperparameter search
* Cross-validation
* Model comparison
* Bias and variance diagnosis
* Performance and stability analysis

### Committee of Models

The system introduces an ensemble-based **Committee of Models**, combining multiple learners to improve predictive performance and reliability beyond individual models.

### Unified Inference

A single inference workflow accepts a player's profile and produces:

* **Estimated player market value**
* **Predicted performance tier**

The preprocessing logic is kept consistent across the prediction tasks.

### Stability Assessment

The final system is evaluated across different subsets of the data to assess whether its performance remains consistent and reliable.

The advanced system is also compared against the baseline models from Assignment 2 to measure the improvement achieved through optimization and ensemble learning.

---

## Technologies

**Python | Pandas | NumPy | Scikit-learn | Matplotlib | Seaborn | Jupyter Notebook**

## Datasets

The project uses two real-world datasets:

* **Car Price Dataset** — used for exploratory analysis, price prediction, and price-category classification.
* **FIFA Players Dataset** — used for market value prediction, performance-tier classification, and the final unified scouting system.

## Project Structure

```text
Machine-Learning-Project/
│
├── Assignment-1/
│   ├── Documentation.pdf
│   ├── Code.ipynb
│   └── car-price.csv
│
├── Assignment-2/
│   ├── Documentation.pdf
│   ├── Code.ipynb
│   └── Fifa.csv
│
└── Assignment-3-Final-Project/
    ├── Documentation.pdf
    ├── Code.ipynb
    ├── Fifa.csv
    └── car-price.csv
```

## Key Learning Outcomes

This project provided hands-on experience with:

* Exploratory Data Analysis
* Data preprocessing and feature engineering
* Regression and classification
* Polynomial features and regularization
* Hyperparameter optimization
* Grid Search
* K-Fold and Stratified K-Fold Cross-Validation
* Bias and variance analysis
* Ensemble learning
* Model evaluation and stability analysis
* Building unified machine learning pipelines
* Translating raw data into actionable predictions

