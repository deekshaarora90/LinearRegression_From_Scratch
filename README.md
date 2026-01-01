# Linear Regression from Scratch

This repository contains a Python implementation of a **Linear Regression** model built entirely from scratch. It demonstrates the core mechanics of regression—fitting data, computing weights, and making predictions—without relying on high-level libraries.

## Usage

Import the `LinearRegression` class from `Linear_regression.py` to get started.  
You can initialize the model, train it using the `fit()` method with your data, and then generate predictions with `predict()`.

```python
from Linear_regression import LinearRegression

model = LinearRegression()
model.fit(X_train, y_train)
predictions = model.predict(X_test)
