# Predictive Maintenance for Wind Turbine Generators
# Project Overview
This project aims to develop and optimize machine learning models to predict failures in wind turbine generators using sensor data. By predicting failures before they occur, the model helps in reducing maintenance costs and improving the efficiency of wind energy production.

# Data
Training Set: 40,000 observations
Test Set: 10,000 observations
Predictors: 40 features collected from sensors
Target Variable: Binary indicator of generator failure (1 = failure, 0 = no failure)

# Objectives
Build and tune various classification models to identify generator failures.
Reduce overall maintenance costs by predicting failures accurately.
Maximize the ratio of minimum possible maintenance cost to the actual maintenance cost associated with the model.

# Methodology
Data Preprocessing: Cleaned and prepared the data for modeling.
Model Development: Built several machine learning models including logistic regression, random forest, and XGBoost.
Model Tuning: Addressed class imbalance using techniques such as SMOTE and fine-tuned models using hyperparameter optimization.
Evaluation: Evaluated models based on maintenance cost, accuracy, precision, recall, and other relevant metrics.
Feature Importance: Identified key predictors of failure to focus on critical sensor data.

# Key Results
Final Model: XGBoost
Performance: Achieved a maintenance cost of 1.27 times the minimum possible cost, compared to 2.67 times without the model.
Top Features: V18, V39, V26, V3, V10

# Business Impact
Implementing the model can significantly reduce maintenance costs by accurately predicting failures.
Provides valuable insights for risk assessment in the maintenance process.

# Conclusion
The machine learning model built in this project demonstrates the potential to reduce maintenance costs in wind energy production. By identifying key predictors and optimizing the model, it provides a robust solution for predictive maintenance.