# PySpark.ml-for-Titanic-Dataset-Analysis

## Overview
This project focuses on analyzing the famous Titanic dataset using the PySpark.ml package. The goal is to predict the survival of passengers on board the Titanic by applying the logistic regression model. PySpark.ml's pipeline and feature engineering tools will be utilized for efficient data processing.

## Dataset (https://www.kaggle.com/c/titanic/data)
The data has been split into two groups:
- training set (train.csv)
- test set (test.csv)
The training set should be used to build your machine learning models. For the training set, we provide the outcome (also known as the “ground truth”) for each passenger. Your model will be based on “features” like passengers’ gender and class. You can also use feature engineering to create new features.

The test set should be used to see how well your model performs on unseen data. For the test set, we do not provide the ground truth for each passenger. It is your job to predict these outcomes. For each passenger in the test set, use the model you trained to predict whether or not they survived the sinking of the Titanic.

## Project Structure
1. Load Data and data exploration using pyspark
2. Feature engineering: deal with missing value, create new column, converting data types
3. Assemble feature columns into a feature vector
4. Create the model: I use logistic regression
5. Define Pipeline
6. Fit the model and evaluate performance

## How to Use
- Clone the repository to your local machine.
- Download the Titanic dataset from the provided link.
- Set up your PySpark environment to execute the provided Jupyter Notebooks or scripts.

Contributions are welcome! If you have improvements, optimizations, or additional analyses to suggest, feel free to submit pull requests. 

