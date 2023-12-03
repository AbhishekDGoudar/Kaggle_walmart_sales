# Kaggle_walmart_sales
Problem Statement 
Enhance forecasting capabilities by utilizing Weekly Sales to accurately predict the demands faced by Walmart Stores across United States.  Walmart is occasionally facing difficulty in meeting its demands due to low inventory.  Aim of this project is to see the impact of Holidays on the Weekly Sales of Walmart Stores. 

[Kaggle Problem Statement Link](https://www.kaggle.com/datasets/yasserh/walmart-dataset)



## Model Evaluation Metrics
Model | RMSE | R Squared | Adjusted R Squared | Mean Cross Validation Scores | StdDev CV Scores |
--- | --- | --- | --- |--- |--- |
Y1 = Bo + B1(X1) + B2(X2) +...+Bn(Xn) + E | 532904.3 | 10.56 | 10.60 | 9.79 | 0.0143 |
Y2 = Bo + B1(X1)^2 + B2(X2)^2 +...+Bn(Xn)^2 + E | 314873.3 | 69.06 | 69.06 | 9.79 | 0.0143 |
Y3 = Bo + B1(X1)^3 + B2(X2)^3 +...+Bn(Xn)^3 + E | 82009.85 | 97.86 | 98.30 | 95.31 | 0.0024 |
Y4 = Bo + B1(X1)^4 + B2(X2)^4 +...+Bn(Xn)^4 + E | 0.00 | 100.0 | 100.42 | 70.9 | 0.0277 |


