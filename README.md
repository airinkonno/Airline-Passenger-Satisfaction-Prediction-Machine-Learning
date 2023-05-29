# Airline-Passenger-Satisfaction-Prediction-Machine-Learning
This project uses machine learning algorithms to predict airline passenger's satisfaction. There are only two levels of satisfaction with the airline the passenger belongs to:
1. Satisfied
2. Neutral or dissatisfied

Hence, this is a binary classification problem.

# Project Aim
Based on various characteristics of the passengers, their ratings on the airline's services (e.g. inflight wi-fi, seat comfort, online boarding), this project aims to predict whether the customer will be satisfied or dissatisfied using machine learning algorithms.

# Files
- Data 
  - test.csv
  - train.csv
- ML Project Workbook.ipynb
- Predicting Airline Passenger Satisfaction - ML Project.pptx
- README.md

# Dataset
You may find the dataset here: https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction

# Project Steps
1. Import packages and dataset.
2. Data pre-processing (drop unncessary columns, check for data imbalance, handle null values).
3. Exploratory data analysis.
4. Data encoding.
5. Feature scaling.
6. Using machine learning algorithms to train the data.
  - KNN
  - Decision Trees
  - Random Forest
  - Logistic Regression
  - XGBoost
  - ADA Boost
7. Narrowing it down to two models with the best accuracy (Random Forest Classifier and XGB Classifier).
8. Performing dimensionality reduction for both models (PCA).
9. Performing hyper parameter optimization for each model (grid search and randomized search CV).
10. Calculating the model performance, plotting confusion matrix, and ROC curve.
