Data description link: https://www.kaggle.com/c/santander-customer-transaction-prediction/overview

# Overview
At Santander their mission is to help people and businesses prosper. they are always looking for ways to help our customers understand their financial health and identify which products and services might help them achieve their monetary goals.

Their data science team is continually challenging our machine learning algorithms, working with the global data science community to make sure we can more accurately identify new ways to solve our most common challenge, binary classification problems such as: is a customer satisfied? Will a customer buy this product? Can a customer pay this loan?

In this challenge, the goal is to help us identify which customers will make a specific transaction in the future, irrespective of the amount of money transacted. The data provided here has the same structure as the real data.
# Data description
Anonymized dataset containing numeric feature variables with the binary target column, and a string ID_code column.
The task is to predict the value of target column in the test set.
# File descriptions
train.csv - the training set.
# Evaluation metric
Because the response variable is highly inbalanced, AUC_ROC score is been used.

