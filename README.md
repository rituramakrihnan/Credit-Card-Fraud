# Credit Card Fraud Detection with Machine Learning

## Abstract
This project explores the detection of credit card fraud using machine learning techniques, addressing the increasing prevalence of fraud in online transactions. The study compares the performance of AdaBoost, CatBoost, XGBoost, and Light GBM models on a credit card transaction dataset, evaluating metrics such as accuracy, precision, recall, and F1-score.

## Table of Contents
1. [Introduction](#introduction)
2. [Related Work](#related-work)
3. [Solution and Scalability Justification](#solution-and-scalability-justification)
4. [Implementation Details](#implementation-details)
5. [Results](#results)
6. [Conclusion](#conclusion)
7. [References](#references)

## Introduction
With the rise of digital payments, credit card fraud has become a significant concern, leading to substantial financial losses globally. This project aims to develop and compare machine learning models capable of detecting fraudulent transactions in credit card data. The dataset used is sourced from Kaggle and includes transactions by European cardholders in September 2013.

## Related Work
Several studies have investigated various machine learning approaches for credit card fraud detection, emphasizing techniques like Random Forest, Decision Trees, and Neural Networks. This project builds upon previous research by evaluating newer algorithms like AdaBoost, CatBoost, XGBoost, and Light GBM.

## Solution and Scalability Justification
The selected models (AdaBoost, CatBoost, XGBoost, Light GBM) are known for their robustness in handling large datasets and maintaining high accuracy in complex scenarios. Each model's scalability and performance metrics such as F1-score are thoroughly compared, demonstrating their suitability for fraud detection in credit card transactions.

## Implementation Details
### Dataset
The dataset comprises transactions over two days, with a severe class imbalance where fraudulent transactions account for only 0.172% of the total. Features are predominantly numerical, derived from a PCA transformation, except for Time and Amount.

### Libraries Used
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- CatBoost
- LightGBM
- XGBoost

### Results
Detailed results including accuracy, precision, recall, and F1-score for each model (AdaBoost, CatBoost, XGBoost, Light GBM) are presented. Visualizations of feature importance and model performance metrics are included to facilitate comparison.

## Conclusion
The study concludes that XGBoost demonstrates the highest accuracy and recall among the models evaluated, making it particularly effective for detecting credit card fraud. However, the choice of model should consider specific project requirements and computational constraints.

## References
1. [A Comparative Analysis of Supervised Classifiers for Detecting Credit Card Frauds](#)
2. [A Survey on Detection of Fraudulent Credit Card Transactions Using Machine Learning Algorithms](#)
3. [A Convolutional Neural Network Model for Credit Card Fraud Detection](#)
4. [Analysis of Credit Card Fraud Detection using Machine Learning Techniques](#)
5. Dataset Source: [Kaggle - Fraud Detection Dataset](https://www.kaggle.com/datasets/kartik2112/fraud-detection?select=fraudTrain.csv)

