# Pharma-Public-Safety-
This projects aims to develop a ML model to predict the sales of counterfeit medicines in the market

Overview:
This Jupyter Notebook implements a machine learning pipeline to predict counterfeit medicine sales using historical data. The program performs data preprocessing, feature engineering, and model training using a grid search approach to optimize performance.

Data Loading & Exploration:
The dataset is loaded from counterfeit_test.csv and counterfeit_train.csv using pandas.
Exploratory Data Analysis (EDA) is performed using .describe() and .head() to understand data distributions and structure.

Data Preprocessing:
Categorical variables are transformed using one-hot encoding.
Unnecessary columns (Medicine_ID, Counterfeit_Weight) are removed.
Missing values, if any, are handled appropriately.

Feature Engineering:
The dataset is combined to ensure consistency between training and testing sets.
The target variable (Counterfeit_Sales) is separated from the feature set.

Evaluation & Predictions:
The program ranks models based on validation scores.
The best model is used to predict counterfeit medicine sales on the test dataset.
The predictions are saved in a CSV file: "DebajyotiMandal_Submission.csv".
