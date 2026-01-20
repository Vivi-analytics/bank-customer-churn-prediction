# bank-customer-churn-prediction
Predicting customer churn using machine learning (Random Forest, AUC optimization)

This project focuses on predicting customer churn using supervised machine learning techniques.
The objective is to identify customers at risk of leaving the bank and to understand the key drivers behind churn, supporting data-driven retention strategies.

The project follows a complete end-to-end data science workflow, including data exploration, feature engineering, model training, and evaluation.

# Approach
	Data exploration & profiling
	•	Analyzed numerical and categorical features to understand churn patterns
	•	Identified key differences between churned and retained customers
	Feature engineering
	•	Created ratio-based features (e.g. balance-to-income, income-per-product)
	•	Encoded categorical variables and prepared data for modeling
	Modeling & evaluation
	•	Trained and evaluated a Logistic Regression model as a baseline
	•	Trained and tuned a Random Forest model using cross-validation
	•	Compared models using accuracy, ROC–AUC, and precision–recall trade-offs
	•	Interpreted feature importance to identify main churn drivers

# Key results
	•	Random Forest achieved higher predictive performance than Logistic Regression
	•	Balance-related and engagement related variables were among the strongest churn predictors
	•	The analysis highlights how customer behavior and product usage influence churn risk

# Tools&technologies
	•	Python
	•	pandas, numpy
	•	scikit-learn
	•	matplotlib, seaborn

