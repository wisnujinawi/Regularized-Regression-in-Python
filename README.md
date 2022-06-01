# Regularized-Regression-in-Python

The data is about predicting housing price (medv) in 
Boston city, features:
○ Criminal rate (crim)
○ Residential land zoned proportion (zn)
○ Non-retail business acres proportion (indus)
○ Is bounds with river (chas)
○ Nitrogen oxides concentration (nox)
○ Number rooms average (rm)
○ Owner age proportion (age)
○ Weighted distance to cities (dis)
○ Accessibility index (rad)
○ Tax rate (tax)
○ Pupil-teacher ratio (ptratio)
○ Black proportion (black)
○ Percent lower status (lstat)



#Instructions:

1. Split data: train - validate - test 
2. Draw correlation plot on training data and perform feature selection on highly correlated features
3. Fit models on training data (lambdas = [0.01, 0.1, 1, 10]) 
    a. Ridge regression 
    b. LASSO 
4. Choose the best lambda from the validation set 
    a. Use RMSE as metric
    b. Interpret a sample of the coefficients of the best model
        i. Ridge regression
        ii. LASSO
5. Evaluate the best models on the test data (+ interpretation) 
    a. MAE
    b. MAPE
    c. RMSE 

