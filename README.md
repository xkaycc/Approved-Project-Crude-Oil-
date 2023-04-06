### Regression Analysis on Crude oil
## Introduction 
In this project, I conducted an analysis of crude oil data from over 27,000 different fuel generations. I utilized various features, did feature engineers on the data to make prics. The data was thoroughly cleaned, preprocessed, and modeled using three different algorithms. Among these algorithms, the best-performing one was selected for deployment and future use.

## Your business problem and stakeholders
To predict price of cruel oil for stakeholders without under/over pricing. 

### source of your data
Data was gotten from zindi africa

### Description of your data
The data contain 27,500 rows and 30 columns with the target variable (price actual)
[Link](https://github.com/xkaycc/SALES-PREDICTION/blob/main/Data_Cleaning_(2).ipynb) to the data file


#### Visualizations
In this analysis, the missing data were visualized using missingno and also the correlation of the target variable to the features was visualized using heatmap
![image](https://user-images.githubusercontent.com/120944468/227781895-00536716-8a94-4b75-bf87-2f6d610dd622.png)
The above figure shows the missing data in the sales prediction project
![image](https://user-images.githubusercontent.com/120944468/227781972-b12b8c82-50e3-410c-8214-e857fa9a4b92.png)
The second figure shows the relationships between the target variable (Item_Outlet_Sales) and the features variables

## Model
Regressions algorithms that were used for this project 
 - dummy regressor
 - Linear regression
 - Decision Tree
 - Bagged Tree
 - Random Forest

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
