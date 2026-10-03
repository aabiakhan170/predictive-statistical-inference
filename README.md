# High-Dimensional Predictive Data Modeling & Statistical Inference

This repository contains a robust implementation of **Multiple Linear Regression** and **Gradient Descent Optimization** built completely from scratch using Python and core mathematical matrices. 

Rather than relying on black-box machine learning libraries, this project manually computes the foundational statistical metrics necessary to perform rigorous academic data inference.

## Mathematical Implementations
1. **The Normal Equation:** Solves for model parameters ($\beta$) analytically by minimizing the sum of squared residuals:
   $$\beta = (X^T X)^{-1} X^T y$$
2. **Gradient Descent:** Optimizes feature weights iteratively using multivariate calculus and localized learning rates.
3. **Statistical Inference Engine:** Manually derives the complete coefficient profile:
   * **Standard Errors ($se$):** Calculated via the estimated noise variance $\sigma^2$ and the parameter covariance matrix.
   * **T-Statistics & P-Values:** Computed to validate parameter significance.
   * **F-Test & Adjusted $R^2$:** Measures global model variance and structural data fit.

## Performance Profiles
* Evaluates Train vs Test set error metrics (RMSE, MAE) to actively track data overfitting.
* Generates residual distribution plots to verify variance homoscedasticity.

## Author
* **Name:** Aabia Khan
* **Academic Track:** B.Sc. Mathematics Student
