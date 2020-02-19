# Stock-Market-Direction-Prediction

It's a popular subject to predict the stock direction according to the history return and traded volume. In this project, we'll try different models such as logistic regression, linear discriminant analysis, quadratic discriminant analysis, and K-Nearest Neighbors to see which model get best performace.

The dataset we'll use is "Smarket" dataset, which consists of percentage returns for the S&P 500 stock index over 1250 days, from the beginning of 2001 until the end of 2005. For each date, we have recorded the percentage returns for each of the five previous trading days, **Lag1** through **Lag5** . We have also recorded **Volume** (the number of shares traded on the previous day, in billions), **Today** (the percentage return on the date in question) and **Direction** (whether the market was Up or Down on this date).

This dataset includes 1250 observations from 2001 to 2005. The variables are as following:

Target variable:
- **Direction**: whether the market was Up or Down on this date

Predictors:
- **Lag1**: percentage returns for 1 trading day before
- **Lag2**: percentage returns for 2 trading days before
- **Lag3**: percentage returns for 3 trading days before
- **Lag4**: percentage returns for 4 trading days before
- **Lag5**: percentage returns for 5 trading days before
- **Volume**: the number of shares traded on the previous day, in billions
