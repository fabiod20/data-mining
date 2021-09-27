# Machine learning for Alzheimer's Disease Detection
This repository contains the solution proposed for the first Mini-Contest of the **Data Mining** course (AY 20/21) at the University of Naples Federico II.

## Assignment
The contest aims at exploiting Machine Learning for Alzheimer's disease detection. The task is to determine whether a patient has or not the disease, by means of a machine learning model trained on some medical high-level information. You can find more about the competition [here](https://www.kaggle.com/c/unina-data-mining-2021-minicontest-n1/overview).

## Solution
The solution shown in the (Notebook)[https://github.com/fabiod20/data-mining/blob/main/mini-contest-1-classification/Machine%20Learning%20for%20Alzheimer's%20Disease%20Detection.ipynb], implemented by means of **scikit-learn**, is made up of two main stages:
- **Preprocessing**: data cleaning and dealing with missing values.
- **Modeling**: compare several models, such as *Decision Tree*, *K-Nearest Neighbour (KNN)*, *Logistic Regression*, *Support Vector Machine* and *Multi-Layer Perceptron (MLP)*.

The final model choosed for the submission is an SVM that achieved an accuracy of 0.74482.
