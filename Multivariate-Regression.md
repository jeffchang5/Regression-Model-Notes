## Multivariate Regression

Goal is to reduce any chosen regressor from n variables to n-1 variables. 

####One variable linear regression
```r
lm(child ~ parent, galton)
```
___

When performing a regression with one variable, we have two coefficients, the first for the slope and the second for the intercept. The intercept has a special regressor value, 1, because the intercept is a constant.

For example, `5 + 7x`, the weights for the first term would be one multiplied by the constant value of 5. 

___

Use `rep(1,nrow(length(matrix))` to create a matrix of 1's  that is a 1 x the length of the  matrix.