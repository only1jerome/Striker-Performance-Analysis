# Striker-Performance-Analysis
This repository contains a data analysis and machine learning project focused on evaluating football strikers' performance metrics. The analysis includes data preprocessing, clustering, statistical analysis, and predictive modeling.

# Project Overview
This project utilizes an Excel dataset (Strikers_performance.xlsx) containing detailed statistics about football strikers to:
  - Handle missing values and preprocess the data.
  - Perform descriptive analysis and visualizations.
  - Conduct clustering analysis to categorize strikers into distinct performance groups.
  - Develop a logistic regression model to predict striker types.

# Analysis Highlights
  # Preprocessing Steps
  - Missing Value Imputation: Median strategy for numeric columns and mode strategy for nominal columns.
  - Data Type Assignment: Ensured correct data types for all columns.
    # Feature Engineering:
  - Created a Total Contribution Score by summing relevant metrics.
  - Encoded categorical variables (Footedness, Marital Status, Nationality).
 # Clustering
  # KMeans Clustering:
  - Determined the optimal number of clusters using the elbow method.
  - Categorized strikers into two groups: Best strikers and Regular strikers.
 # Statistical and Descriptive Insights
  - Distribution analysis of key features like footedness and nationality.
  - Statistical tests for correlations and group differences.
 # Machine Learning
  # Logistic Regression Model:
  - Trained on engineered features to classify striker types.
  - Achieved accuracy percentage and visualized the confusion matrix.

# Dependencies
  - Python 3.8+
  - Required libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - scipy

# Results
The project identified and classified strikers based on their performance metrics.
**Clustering revealed two distinct groups:**

  - Best Strikers: High overall contribution and performance scores.
  - Regular Strikers: Moderate performance scores.

- The logistic regression model demonstrated an accuracy of 96.00%.

# Contributing
Feel free to contribute by:
  - Adding new features.
  - Refining analysis techniques.
  - Improving documentation.
