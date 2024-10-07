# Churn Prediction Project

## Table of Contents
1. [Introduction](#introduction)
2. [Overview](#overview)
3. [Tools](#tools)
4. [Methods](#methods)
5. [Algorithms](#algorithms)
6. [Results](#results)

## Introduction
This project focuses on customer churn prediction, which involves predicting whether customers will leave a service based on historical data. By using machine learning models, businesses can proactively address customer retention issues and improve their strategies to reduce churn rates.

## Overview
The dataset used for this project contains 64,374 customer records, including key features such as age, tenure, and usage. The project aims to test and evaluate different churn prediction models, allowing businesses to assess model performance and understand generalizability across unseen data.

## Tools
The project utilizes Python for data analysis and model training, with libraries such as Pandas for data manipulation, Scikit-learn for machine learning, and Optuna for hyperparameter optimization. Visualization tools like Matplotlib and Seaborn are used to explore and understand the data.

## Methods
Data was preprocessed using encoding techniques for categorical data, followed by splitting the data into training and testing sets. Feature engineering and data transformations were applied to improve model performance, and cross-validation techniques were employed to ensure model stability.

## Algorithms
Several machine learning algorithms were explored, including decision trees, random forests, and gradient boosting machines. Hyperparameter tuning was performed using Optuna to optimize model performance, with cross-validation used to measure the effectiveness of each algorithm.

## Results
The best-performing model was selected based on its accuracy, precision, recall, and F1-score. The results showed that the model could predict customer churn with significant accuracy, helping businesses identify high-risk customers and target retention efforts more effectively.

