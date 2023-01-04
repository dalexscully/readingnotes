# Linear Regressions

<hr>

## Links and Resources

- [How to run Linear Regressions in Python Scikit-Learn](https://www.activestate.com/resources/quick-reads/how-to-run-linear-regressions-in-python-scikit-learn/)
- [Linear Regressions in Python](https://realpython.com/linear-regression-in-python/)
- [Introduction to simple Linear Regressions](https://www.youtube.com/watch?v=KsVBBJRb9TE)
- [Train & Test Splits](https://towardsdatascience.com/train-test-split-and-cross-validation-in-python-80b61beca4b6)
- [What is Linear Regressions](https://www.statisticssolutions.com/free-resources/directory-of-statistical-analyses/what-is-linear-regression/)

<hr>

- Scikit-learn is a python module for machine learning - It contains functions for regression, classification, clustering, model selection and dimensionality reduction.

- Y - "target" data in Python

- X - independent variables


- Important functions to keep in mind while fitting a linear regression model are:

  - lm.fit() -> fits a linear model
  - lm.predict() -> Predict Y using the linear model with estimated coefficients
  - lm.score() -> Returns the coefficient of determination (R^2). A measure of how well observed outcomes are replicated by the model, as the proportion of total variation of outcomes explained by the model.
  - You can also explore the functions inside lm object by pressing lm.