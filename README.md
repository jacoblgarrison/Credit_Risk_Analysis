# Credit_Risk_Analysis

## Overview

With the help of Machine-Learning, credit risk is an inherently unbalanced classification problem. Good loans outnumber risky ones by a large amount. Libraries such as imbalance-learn and sci-kit learn will help us create a model that will determine if we should predict credit risk.

## Results

The results for the machine learning models are below:

## Naive Random Oversampling

![Naive Random Oversampling](https://user-images.githubusercontent.com/95515322/168405784-92280223-5ad6-4b74-9ca0-3ca5d8aa6794.png)

Balanced Accuracy score: 0.6497536370265621

The precision is low for High-Risk loans and is high for Low-Risk loans

Recall: High-Risk: 0.62 | Low-Risk 0.68

## SMOTE Oversampling

![Smote Oversampling](https://user-images.githubusercontent.com/95515322/168405979-c57b7cc0-92a6-4144-a3fd-2578e899a1c4.png)

Balanced Accuracy score: 0.6443721269403855

The precision is low for High-Risk and is high for Low-Risk

Recall: High-Risk: 0.63 | Low-Risk: 0.66

## Undersampling

![Undersampling](https://user-images.githubusercontent.com/95515322/168406050-b87f34b5-539e-4df3-a9fa-019d9f9dce39.png)

Balanced Accuracy score: 0.6443721269403855

The precision is low for High-Risk and is high for Low-Risk

Recall: High-Risk: 0.61 | Low-Risk: 0.45

## Combination Over and Under Sampling

![Combination Over and Under Sampling](https://user-images.githubusercontent.com/95515322/168406124-ee3f0156-a851-4a38-a995-07850afbf2f9.png)

Balanced Accuracy score: 0.5292734810302525

The precision is low for High-Risk and is high for Low-Risk

Recall: High-Risk: 0.70 | Low-Risk: 0.57

## Balanced Random Forest Classifier

![Balanced random Forest Classifier](https://user-images.githubusercontent.com/95515322/168406178-48d8a41c-4a42-4fe9-8033-8dd86349c101.png)

Balanced Accuracy score: 0.7877672625306695

The precision is low for High-Risk and is high for Low-Risk

Recall: High-Risk: 0.67 | Low-Risk: 0.91

## Easy Ensemble AdaBoost Classifier

![Easy Ensemble AdaBoost Classifier](https://user-images.githubusercontent.com/95515322/168406240-432efa73-e82f-459e-8eab-9211eaa246ef.png)

Balanced Accuracy score: 0.925427358175101

The precision is low for High-Risk and is high for Low-Risk

Recall: High-Risk: 0.91 | Low-Risk: 0.94

## Summary

When looking at our models, we want to choose a model that has a number closest to 1. Our Easy Ensemble AdaBoost Classifier has the best balanced accuracy score of 0.93. 

The precision was just about the same for all models, with some being low for High-Risk and high for Low-Risk and other models having the inverse of this.

Our recall score is on the same scale of our balanced accuracy score, between 0 - 1 and the closer the number is to 1 the better. Our Easy Ensemble AdaBoost Classifier had the highest scores for both High-Risk and Low-Risk, letting us know that the Easy Ensemble AdaBoost Classifier is the best model for us to analyze credit. 
