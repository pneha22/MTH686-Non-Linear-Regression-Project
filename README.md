# MTH686 Non-Linear Regression Project

This repository contains code and resources for exploring non-linear regression techniques as part of the MTH686 course.
# Nonlinear Regression Project (MTH686 Final)

This project explores parameter estimation in three nonlinear regression models using least squares, based on a dataset with 65 points. The models tested were:

- **Model 1:** Exponential sum: \( y(t) = \alpha_0 + \alpha_1 e^{\beta_1 t} + \alpha_2 e^{\beta_2 t} + \eta(t) \)
- **Model 2:** Rational linear: \( y(t) = \frac{\alpha_0 + \alpha_1 t}{\beta_0 + \beta_1 t} + \eta(t) \)
- **Model 3:** Polynomial (quartic): \( y(t) = \beta_0 + \beta_1 t + \beta_2 t^2 + \beta_3 t^3 + \beta_4 t^4 + \eta(t) \)

### Approach

- Used initial guesses and the Gauss-Newton method to estimate parameters.
- Compared models using AIC (Akaike Information Criterion) to avoid overfitting.
- Checked normality and independence of residuals with plots.
- Calculated confidence intervals using the Fisher information matrix.

### Results

- **Best model by AIC:** Model 2 (rational linear).
- All models fit the data well, with similar residual variance.
- Residuals were approximately normal and independent.

**Summary:**  
Least squares and model selection help find a good balance between fit and complexity. Rational linear (Model 2) was preferred, but exponential and polynomial models performed similarly.  
