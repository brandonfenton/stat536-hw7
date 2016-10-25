Tasks broken down by problem for HW7
======================================
## Problem 1:
* I think Allison did or mostly did this

## Problem 2:
* fit a `gam` from the `mgcv` package that includes a long-term trend based on a thin-plate spline with shrinkage that uses `k = #years, bs = "ts"` from the fractional year variable and a cyclic spline seasonal component
* fit the model
* plot the long-term trend and the seasonal component (use `plot(gam_model)`)
* discuss the estimated components, using both the plots and the EDF of each term

## Problem 3:
* Calculate the AIC of the GAM using the `AIC` function
* discuss how that result compares to your AICs in #1
* How is it similar or different in terms of information (degrees of freedom) used?

## Problem 4:
* Compare the fitted values of your GAM to those from your top model, plotting the two models's results and the responses vs time on the same plot

## Problem 5:
* Revisit your simulation with an AR(1) from HW 6 \# 10. Consider fitting a model with autocorrelation in it using `gls` from the `nlme` package that accounts for an MA(1) error and another that accounts for an AR(1) error.
* Run your simulation code, extracting the p-values from the two model summaries
* estimate the type I error rate in each situation and compare it to what you get from the regular linear model. 

## Problem 6:
* Answer Cryer and Chan question 2.4 (page 20)

## Problem 7:
* Use the rules for means and variances of linear combinations to find $E(y_t)$, $Var(y_t)$, and $Cov(y_t,y_{t-1})$. Do not worry about what happens at the edges of the time series (for t=1 or t=n), only worry about $t$ in general. 

## Problem 7: