Cloud Cost Prediction & Idle Resource Detection
Overview

This project implements a Machine Learning framework to predict monthly cloud infrastructure cost and detect idle cloud resources to optimize operational expenditure.

Objectives

Predict monthly cloud billing cost using regression models

Detect idle resources using classification models

Estimate potential cost savings

Provide scalable cloud optimization analytics

Dataset

2000 simulated cloud billing records

Monthly billing cycle (up to 720 uptime hours)

Features include CPU usage, memory usage, storage, network traffic, uptime, instance type, and region

Methodology
Cost Prediction

Random Forest Regressor

R² Score: 0.95 – 0.99

Low MAE & RMSE

5-Fold Cross Validation

Idle Detection

Random Forest Classifier

Accuracy > 97%

Evaluated using confusion matrix

Business Impact

Estimated monthly cost savings from identifying idle cloud resources.

Current Status

✔ Dataset Generated
✔ EDA Completed
✔ Regression Model Optimized
✔ Classification Model Built
✔ Cross-Validation Performed
✔ Cost Savings Simulated

Future Work

Integration with real cloud billing data

Time-series forecasting

Dashboard deployment

Real-time monitoring system
