# Customer Churn Prediction

## Project Overview

Customer churn prediction helps businesses identify customers who are likely to leave a service. This project uses Machine Learning algorithms to predict whether a customer will churn based on demographic and banking information.

## Dataset

Dataset: Churn Modelling Dataset

Features include:

- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Is Active Member
- Estimated Salary

Target Variable:

- Exited
    - 1 = Customer Churned
    - 0 = Customer Retained

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

## Data Preprocessing

- Removed irrelevant columns
- Encoded categorical variables
- Applied feature scaling
- Split dataset into training and testing sets

## Machine Learning Models

### Logistic Regression

Used as a baseline classification model.

### Random Forest Classifier

Used to improve prediction accuracy and identify important features.

## Results

Model performance was evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report

Random Forest achieved higher performance compared to Logistic Regression.

## Visualizations

### Churn Distribution

![Churn Distribution](images/churn_distribution.png)

### Confusion Matrix

![Confusion Matrix](images/confusion_matrix.png)

### Feature Importance

![Feature Importance](images/feature_importance.png)

## Conclusion

The project successfully predicts customer churn using customer demographic and financial information. The Random Forest model provided strong predictive performance and highlighted the most influential factors contributing to customer attrition.

## Author

Sai Lekhana
