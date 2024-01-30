# LoanPrediction

Loan Default Prediction - Solved! Welcome to the repository for my solution to the loan default prediction problem on a unique dataset of borrowers. Here, you'll find the code and analysis that led me to successfully predict which borrowers in the "test.csv" dataset are likely to default on their loans.

Data:

train.csv: Contains information about 255,347 borrowers, including loan details and whether they defaulted (ground truth). test.csv: Similar to train.csv, but for 109,435 borrowers without the default information (target variable). Solution:

I analyzed the train.csv data using various machine learning techniques to identify patterns and build a model capable of predicting the target variable in test.csv. The key steps involved:

Data Preprocessing: Cleaned and prepared the data for analysis, handling missing values, outliers, and feature engineering. Model Selection: Compared different machine learning algorithms like Logistic Regression, Random Forest, XGBoost, and others to find the best fit for this specific dataset. Model Training & Evaluation: Trained the chosen model on the train.csv data and evaluated its performance using metrics like accuracy, precision, recall, and AUC-ROC. Prediction: Used the trained model to predict the default probability for each borrower in test.csv. Results:

My final model accurately predicted loan defaults for a significant portion of borrowers in test.csv.

Sharing the Solution:

This repository includes the Jupyter notebook with detailed code for data preprocessing, model building, and prediction for anyone to explore and build upon.
