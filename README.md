# Predict_travel_event
Using customer's demographic data and behavirol (debit/credit card transactions) data to predict next travel event, such that Business team can promote travel-related products to those who are likely to travel.

Business Usage: Identify who will travel in the near future, and proactively offer travel-related products.

Modelling Goal: Propensity model to predict the likelihood of travel booking in the next 3 months at a customer level.

1.Data
  1.1 Import Data (Step 0: Use Spark SQL to pull data in Apache Hive) 
  1.1.1 Data Overview & Manipulation 
  1.2.1 Data Manipulation - converting variables into the right type
  1.2.2 Data Manipulation - Missing value imputation 
2.Exploratory Data Analysis 
  2.1 Travel Booking in Data
  2.2 Variable Distribution in Travel Booking
3.Statistical Summary
4.Data Preprocessing
5.Correlation Analysis
6.Model Building
  6.1 Logistic regression as a baseline 
  6.2 Random Forest
  6.3 XGBOOST
    6.3.1 Spotting important features
    6.3.2 Bias/Variance trade-off
    6.3.3 Hyperparameter tuning using k-fold cross validation
    6.3.4 Adjust weights for imbalanced data
  6.5 Logisitc regression with Random Undersampling the Majority Class
  6.6 Recursive Feature Elimination 
  6.7 Univariate Selection
  6.8 Decision Tree based
  6.9 KNN Classifier
  6.10 Visualizing a decision tree from random forest classifier
  6.11 Gaussian Naive Bayes
  6.12 Support Vector Machine
    6.12.1 Tuning Parameters for Support Vector Machine
  6.13 LightGBM Classifier
7.Model Performance Matrics
  7.1 Compare Model Metrics 
  7.2 Confusion Matrices for models
  7.3 ROC-Curve for models
  7.4 Precision Recall Curves
  7.5 Lift/Gain Analysis
8.Variable Sensitivity Analysis 
  8.1 Permutation Feature Importance
  8.2 Partial Dependency Plot
9.Bias and Fairness Analysis
10.Monitoring 
  10.1 Population Stability Index 

