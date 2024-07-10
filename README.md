# Telco Customer Churn Prediction

## Motivation
Customer churn is the loss of clients of a company, and it is one of the most important metrics in a business setting. It costs less to retain a defecting customer then to acquire a new one. In this project the goal is to predict customer churn of a fictive telco, and classify its customers in two groups: those that would remain, and those that would leave. If a customer is predicted to be thinking of leaving the company, that will affect the revenue of the telco, so there should be a motivation to make the customer rethink their decision by offering them, for e.g., coupons, personalized discounts, etc.

## Methodology
This is a binary classification type of problem in which four gradient boosting algorithms were trained: Gradient Boosting, `XGBoost`, `LightGBM`, and `CatBoost`. As a single number evaluation metric F_1 is used, the most optimal model is `LightGBM` where F_1=0.882759 with its default set of parameters.