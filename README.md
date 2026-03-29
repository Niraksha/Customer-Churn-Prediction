# Customer-Churn-Prediction
Machine learning project to predict customer churn using XGBoost, SMOTE, and ensemble methods.
# Overview :
This project predicts whether a bank customer is likely to churn using machine learning. The goal was to identify at-risk customers early so the bank can take proactive steps to retain them.
# Dataset :
Source : Bank Customer Churn Prediction dataset
10,000 Customer Records
Target variable : churn (1 = churned , 0 = stayed)
# Tech Stack :
- Python
- Pandas & NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost, LightGBM , CatBoost
- Imbalanced-learn (SMOTE)
# Project Workflow :
1.	Data loading and exploration.
2.	Preprocessing – dropped irrelevant columns, one-hot encoding.
3.	Exploratory Data Analysis – identified key churn patterns.
4.	Handled class imbalance using SMOTE.
5.	Trained and compared 5 models.
6.	Hyperparameter Tuning on XGBoost using GridSearchCV.
7.	Evaluated using accuracy, recall, F1, ROC-AUC and PR Curve.
8.	Built a live prediction input using the final model.
# Models Used :
- Logistic Regression
- Random Forest
- XGBoost
- Voting Ensemble
- Tuned XGBoost
- Rule Based
# Best Selection Model :
Tuned XGBoost was selected as the final model. It correctly identified 273 out of 393 churners and had the highest churn recall of 0.69.
# Key Finding :
Churn Recall improved significantly after applying SMOTE. Logistic Regression recall jumped from 0.20 to 0.58 – proving the original poor performance was a data problem , not a model problem. 
Churn Recall improved significantly after applying SMOTE. Logistic Regression recall jumped from 0.20 to 0.58 – proving the original poor performance was a data problem , not a model problem. 
