# A

How do the out-of-sample $R^2$ compare to the in-sample $R^2$?

The out-of-sample $R^2$ are substantially lower than the in-sample $R^2$. In-sample, all predictors have small positive $R^2$ values. Out-of-sample, most predictors have $R^2$ values that are near zero or negative

Interpret what this means for the usefulness of these predictors in forecasting the market

These results suggest that the individual predictors are not very useful for forecasting the market in real time.Although they show small positive fit in-sample, their out-of-sample performance is mostly near zero or negative, meaning that using them to form forecasts generally does not improve on a simple historical-mean forecast and often makes it worse.


# B

Compare the out-of-sample $R^2$ here to those in part (a).

The multivariate regression with all predictors performs worse out of sample than the univariate forecasts in part (a). Here, the all-predictors regression produces an out-of-sample $R^2$ of about $-0.086$, which is much more negative than any of the univariate models.

How do the methods compare?

Overall, the OOS R^2 was near or below zero across all mode. The regularized models tended to have a more stable OOS R^2 compared to the volatility seen in the OLS OOS R^2.

What does this tell us about the predictability of market returns?

Given the lack of R^2 much different from zero, or even negative, the models do as well or worse in most cases than the historical mean.

# C

How do the results compare to the linear models? Interpret the importance of the number of features in the kernel expansion.

The RBF model with 1000 features produced the highest OOS R^2 when trained on the full sample. However, given the closeness of these results to zero, the usefulness of the model is still questionable.
