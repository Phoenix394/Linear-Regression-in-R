# Linear-Regression-in-R
This is an example of regression analysis in R.

# We can use matrix notation to calculate the co-efficients of simple linear regression using design matrix and the following formula:

beta = solve(t(X) %*% X) %*% t(X) %*% y
beta
