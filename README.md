# Task-03
Build a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. Use a dataset such as the Bank Marketing dataset from the UCI Machine Learning

# Decision Tree Classifier Project
## Overview

This repository contains code for building a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. The classifier is trained using the Bank Marketing dataset obtained from the UCI Machine Learning Repository.

## Dataset

The Bank Marketing dataset consists of demographic and behavioral data of customers, including features such as age, job, marital status, education, balance, housing loan status, etc. The target variable indicates whether a customer subscribed to a product or service (yes/no).

The dataset is fetched programmatically using the `ucimlrepo` library, which simplifies the process of downloading datasets from the UCI Machine Learning Repository.

## Usage

1. **Data Preparation**: Load the dataset using the `fetch_ucirepo` function from the `ucimlrepo` library.
2. **Feature Selection/Engineering**: Select relevant features or engineer new features if needed.
3. **Split Data**: Divide the dataset into training and testing sets.
4. **Model Training**: Train a decision tree classifier on the training data.
5. **Model Evaluation**: Evaluate the performance of the trained model on the testing data.
6. **Visualization**: Visualize the decision tree for interpretation.

## Requirements

- Python 3.x
- ucimlrepo
- scikit-learn
- pandas
- matplotlib
