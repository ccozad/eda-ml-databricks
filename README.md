# Introduction

![Principle Component Analysis](./images/pca-4-classes.png)

This repo includes a comprehensive notebook that shows how to do exploratory data analysis (EDA) and machine learning on Databricks. You should be able to run this notebook on the Databricks free edition.

The notebook uses a small breast cancer dataset suitable for classification and is meant for single node or serverless deployments so it uses Pandas over Spark. The Spark approach is best for very large datasets that are difficult to fit on a single node.

# Exploratory Data Analysis

![Feature Distributions](./images/feature-distributions.png)

Topics covered include:

- Install additional visualization libraries
- Load CSV data from a file
- Display data
- Access data attributes
   - Row and column counts
   - Data types
   - Column names
   - Descriptive statistics
- Data clean up
   - Add new columns
   - Drop duplicate data
   - Transform for skew
- Data quality
   - Missing data, zeros, negatives, and duplicates
   - Visualize class distribution
   - Visualize data skew
   - Check for outliers
   - Visualize feature distribution by class
   - Feature separation
   - Visualize relationships between features
   - Principal component analysis

# Machine Learning

![Macro F1 Metrics](./images/macro-f1-by-model-mean-std-over-50-cv-fo.png)

- Classification models
    - Logistic regression
    - K Nearest Neighbor
    - Support Vector Machine
    - Random Forrest Classifier
- Compare models
- Confusion matrix (error matrix)
    - Accuracy
    - Precision
    - Recall
    - F1 Score
- ML Flow experiment tracking

