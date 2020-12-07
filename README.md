# Risky Business

## Background

Mortgages, student and auto loans, and debt consolidation are just a few examples of credit and loans that people seek online. Peer-to-peer lending services such as Loans Canada and Mogo let investors loan people money without using a bank. However, because investors always want to mitigate risk, a client has asked that you help them predict credit risk with machine learning techniques.


In this assignment you will build and evaluate several machine learning models to predict credit risk using data you'd typically see from peer-to-peer lending services. Credit risk is an inherently imbalanced classification problem (the number of good loans is much larger than the number of at-risk loans), so you will need to employ different techniques for training and evaluating models with imbalanced classes. You will use the imbalanced-learn and Scikit-learn libraries to build and evaluate models using the two following techniques:

1. Resampling
2. Ensemble Learning



## Files
1. Resampling Starter Notebook

2. Ensemble Starter Notebook

3. Lending Club Loans Data

## Resampling

In the first part of the project, the following resampling techniques were used: 

1. Oversampling the data using the Naive Random Oversampler and SMOTE algorithms.


2. Undersampling the data using the Cluster Centroids algorithm.


3. Over- and undersample using a combination SMOTEENN algorithm.

For each method used, the following scores were calculated:

1. Balanced accuracy score

2. Confusion matrix

3. Imbalanced classification report.

## Ensemble Learning

In the second part of the project, I trained and compared two different ensemble classifiers to predict loan risk, **Balanced Random Forest Classifier** and the **Easy Ensemble Classifier**.