## Analyzing Simulated HRIS Dataset for Termination Prediction ##

**Context**

This dataset contains simulated HRIS data. The challenge is to predict individual terminations based on the information given.

**Content**

The data contains employee ID, employee record date (year of data), birth date, hire date, termination date, age, length of service, city, department, job title, store number, gender, termination reason, termination type, status year, status and business unit. This data was originally posted on Kaggle.com.

**Inspiration**

A lot of turnover analyses occur at an aggregate level-such as turnover rates. But few analyses concentrate on trying to identify exactly which individuals might leave based on patterns that might be present in existing data.

Machine learning algorithms often showcase customer churn examples. Those algorithms equally apply to employee churn.

**Techniques Used**

Kfold cross validation, hyperparameter tuning, logistic regression, support vector classifier, gradient boosting classifier, k-nearest 
