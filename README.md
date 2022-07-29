# Regression_Metrics_Core

Regression Metrics Exercise (Core)
This link contains information about housing prices in the Boston area in 1978.  It is a modified version of a classic data set used to introduce machine learning.  This is the data dictionary for this data set:

          CRIM     per capita crime rate by town

          NOX      nitric oxides concentration (parts per 10 million)

          RM       average number of rooms per dwelling

          AGE      proportion of owner-occupied units built prior to 1940

          PTRATIO  pupil-teacher ratio by town

          LSTAT    % lower economic status of the population

          PRICE   Median value of owner-occupied homes in $1000's

The ultimate goal of this task is to predict the PRICE based on the available features using a linear regression model.

All of the features and the target are continuous variables. 

For now, you do not need to do any cleaning to this data set. You can use it "as is."

An important exploration step is to determine if there are any moderate or strong correlations in your variables.

1) Make a heatmap of the correlations.  Identify any features that have a correlation coefficient of magnitude 0.5 (could be + or -) or greater with price.   We will limit our analysis to these three features.

2) Select columns for your feature matrix (X) and select PRICE for your target vector (y).

3) Split your data into train and test groups. Please use random number 42 for consistency!

4) Instantiate your model and fit it on the training set.

5) Evaluate your model performance using R^2 on the training set and on the test set.  Is there a difference between model performance on the training data vs the test data?

6) Evaluate your model using mean absolute error (MAE).

7) Evaluate your model using mean squared error (MSE).  

8) Evaluate your model performance using RMSE on the training set and on the test set. This metric is useful because the units will be in the same units as your target vector. In this case 1,000 of dollars.  

