# Indian Liver Patient Dataset (ILPD) Analytics
This repository contains a comprehensive analysis of the Indian Liver Patient Dataset (ILPD), focusing on data preprocessing, feature selection, classification, binning strategy, and clustering techniques.

## Purpose:
The primary goal of this project is to analyze the ILPD dataset to derive valuable insights into liver disease prediction. Through meticulous data preprocessing, feature selection, and model evaluation, the project aims to enhance understanding and predictive accuracy regarding liver disease diagnosis. Additionally, the utilization of advanced techniques such as binning and clustering provides deeper insights into the underlying patterns within the dataset.

## Main Features:

### Data Pre-processing:

- Identification and removal of missing values, duplicates, and outliers.
- Ensuring data integrity and reliability for subsequent analysis.

### Feature Selection:

- Evaluation of feature importance using Information Gain, Gain Ratio, and Correlation methods.
- Ranking of attributes based on predictive utility for liver disease diagnosis.

### Classification:

- Application of logistic regression and Naive Bayes classifiers for liver disease prediction.
- Assessment of classifier performance through T-tests and comparison of accuracy on original and modified datasets.

### Binning Strategy:

- Discretization of attributes to enhance interpretability and alignment with domain knowledge.
- Evaluation of logistic regression model performance on discretized data.

### Clustering:

- Implementation of K-means clustering to uncover inherent patterns within the dataset.
- Assessment of clustering performance through classification error analysis and confusion matrix evaluation.

## Methodology and Tools:
- Data preprocessing conducted using Weka MultiFilter and filters such as RemoveWithValues, RemoveDuplicates, and InterquartileRange.
- Feature selection performed using WEKA methods: Information Gain, Gain Ratio, and Correlation.
- Classification and model evaluation carried out using logistic regression, Naive Bayes, and T-tests.
- Binning strategy implemented using WEKA Discretize filter.
- Clustering analysis conducted with K-means algorithm in Weka.

## Project Summary
This project showcases proficiency in data preprocessing, feature selection, classification, binning, and clustering techniques applied to medical datasets. By leveraging advanced analytical methods, the project aims to contribute valuable insights to the field of liver disease diagnosis and treatment.
