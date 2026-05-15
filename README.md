Predicting Tip Prices
The primary goal of the project if to predict the prices of tips. 

Data
The data set includes 244 rows 7 columns as below:
-numerical columns - total_bill, tip, size
-categorical columns - sex smoker day time

Since we are using simple regression, we will only use the numerical columns. 
The data was found to have no inconsisitencies like missing records or duplicates

Modelling
We used multiple linear regression to derive predictions.

Results
The R-squared value indicates that our model explains 47.4% of the variance in the tips. The mean squared error (RMSE) of 0.9 indicates that our simple regression model is off by 0.9 units in given tips prediction.  
Of the two variables used in modeling the tip prediction, the total_bill variable appears most influential because:
-It has a highet absolute t-statistic value (8.806) compared to that of the size(2.656), which indicates a stronger evidence that the total_bill matters.
-The statistical significance(P-value) of 0.000 shows that the total_bill is highly significant
This means that the more customers spend, the more they tip.# tips_prediction
