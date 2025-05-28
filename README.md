# 🐦 Twitter Bot Detection

This is a Machine Learning project developed as the final submission for a university-level ML course. The goal of the project is to detect whether a given Twitter account is a **bot or a human** based on various account-related features.

## 🚀 Overview

With the increasing prevalence of bots on social media platforms, bot detection has become an important application of machine learning. This project builds and compares multiple classification models to identify bot accounts from human accounts on Twitter.

## 📊 Features

- Binary classification: **Bot vs. Human**
- Comparison of multiple ML models
- Hyperparameter tuning for optimal performance
- Evaluation based on accuracy, precision, recall, and F1-score

## 🧠 Models Used

The following classification algorithms were trained and evaluated:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- CatBoost Classifier

## 🔍 Hyperparameter Tuning

GridSearchCV and RandomizedSearchCV were used to fine-tune hyperparameters for the models to maximize performance.

## 🛠️ Tech Stack

- Python
- Scikit-learn
- CatBoost
- Pandas, NumPy
- Matplotlib, Seaborn (for visualization)
- Jupyter Notebook


## 📈 Evaluation Metrics

Each model was evaluated on the following metrics:
- Accuracy
- Precision
- Recall
- F1-score

## 📚 Dataset

The dataset used for this project was sourced from [Kaggle](https://www.kaggle.com/). It includes various features of Twitter accounts such as number of followers, following, tweet counts, and metadata which help distinguish bots from humans.
