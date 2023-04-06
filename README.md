## Regression Analysis on Crude oil
### Introduction 
In this project, I conducted an analysis of crude oil data from over 27,000 different fuel generations. I utilized various features, did feature engineers on the data to make prics. The data was thoroughly cleaned, preprocessed, and modeled using three different algorithms. Among these algorithms, the best-performing one was selected for deployment and future use.

### Your business problem and stakeholders
To predict price of cruel oil for stakeholders without under/over pricing. 

### source of your data
Data was gotten from zindi africa

### Description of your data
The data contain 27,500 rows and 30 columns with the target variable (price actual)
[Link](https://github.com/xkaycc/Approved-Project-Crude-Oil-/blob/main/crude%20oil.csv) to the data file

### Visualizations
In this analysis, scatter plot was used to check the relationship between the target variable and other features.
![image](https://user-images.githubusercontent.com/120944468/230381921-e9d89c04-fefe-417f-ab20-2bc202c2eb3e.png)
The above figure shows the missing data in the sales prediction project
![image](https://user-images.githubusercontent.com/120944468/230382346-4087e90e-7760-48e2-be2f-3487e123fd40.png)
The second figure shows the distribution of the target variable
![image](https://user-images.githubusercontent.com/120944468/230382575-01a264bc-21c0-4ad3-8e50-9064d3773168.png)
The image above show that the higher the hour, the more the price of crude oil is sold

### Model
Regressions algorithms that were used for this project 
 - CatboostRegressor
 - XgboostRegressor
 - KNeighbour Means

## Describe your final model
Random forest model performs well more than the four algorithms

## Report the most important metrics
Mean Squared Error (MSE), Mean Absolute Error (MAE), Root Mean Square Error(RMSE), R-Squared (R2):
These were the metrics that was used for the project. However I considered the RMSE and R2 for model built to determine the best model

## Refer to the metrics to describe how well the model would solve the business problem
Root Mean Squared Error: The lower the error scores for RMSE, the better the prediction of sales, 
R-Squared: The more the R2, the more the people are ready to buy the sales

## Recommendations:
Since Random Forest algorithm was the one that performs well, it will be advisable to deployed it
