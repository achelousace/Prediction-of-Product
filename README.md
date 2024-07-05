# Prediction of Product Sales
### This project is a data cleaning, wrangling, analysis, and ML Modeling for a prediction of product sales
#### By: Mohammad Abu Ayyash (May 2024)
#### This project aims to help the retailer understand the properties of products and outlets that play crucial roles in predicting sales.
#### Data:
dtypes: float64(4), int64(1), object(7) , 8523 entries,(total 12 columns),memory usage: 799.2+ KB
#### In this summary you'll find :
- a **general** distribution of data in the numerical columns of this data frame
![1](https://github.com/achelousace/Prediction-of-Product/assets/168934903/7ca75718-f700-4505-bfe2-8ae839502341)
- a **regplot** explains the correlation between item visibility and item outlet sales
![2](https://github.com/achelousace/Prediction-of-Product/assets/168934903/218ca313-35ca-4c85-9bb9-5c07b6ec25b5)
- a **scatter plot** explaining the different relationship between the item visibility and establishment year and the influence on sales

![3](https://github.com/achelousace/Prediction-of-Product/assets/168934903/c2e535f2-c3bd-4d75-b528-cfebba66f785)

#### Models used with their metrics:
Linear Regression Model (Testing Set):
MAE = 804.089
MSE = 1,194,326.602
RMSE = 1,092.853
R^2 = 0.567

Random Forest Regressor Model (Testing Set):
MAE = 765.671
MSE = 1,213,934.180
RMSE = 1,101.787
R^2 = 0.560

Tuned Random Forest Regressor Model (Testing Set):
MAE = 734.606
MSE = 1,118,768.607
RMSE = 1,057.719
R^2 = 0.594

#### Recommendations: 
The Final Model Chosen was the Random Forest Regressor Model hyperparameters tuned, Using this model to make predictions about increasing the sales income would be reliable since the target we are trying to predict had the highest score percentage for the test data which is 59.4%.

#### Much more useful information regarding this project is included in the ipynb.
