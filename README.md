Mine vs Rock Detection using Logistic Regression

This project focuses on detecting whether an object is a mine or a rock using sonar data. The classification is done using Logistic Regression, as the problem is a binary classification task.

📌 Project Overview

Dataset: Sonar signals data (each row represents energy received at different frequencies).

Goal: Classify objects as either Mine (M) or Rock (R).

Algorithm: Logistic Regression (chosen because logistic regression is well-suited for binary classification problems).

Evaluation: Model performance is measured using accuracy score after performing a train-test split.

⚙️ Features

Data preprocessing and exploration

Train-test data splitting for unbiased evaluation

Implementation of Logistic Regression for classification

Accuracy score calculation to measure performance

🚀 Tech Stack

Python

NumPy

Pandas

Scikit-learn (LogisticRegression, train_test_split, accuracy_score)

📊 Workflow

Load sonar dataset

Preprocess and explore data

Split dataset into training and testing sets using train_test_split

Train Logistic Regression model on training data

Evaluate model with accuracy score on testing data

Predict new values (optional test cases)

✅ Why Logistic Regression?

The dataset contains two possible outputs: Mine (M) or Rock (R)

Logistic Regression is designed for binary classification problems

Provides probabilistic interpretation of class predictions

Simple, efficient, and effective for this type of dataset

📈 Results

Achieved a good accuracy score on test data (depends on dataset split).
