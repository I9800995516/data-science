# Taxi Order Forecasting

## Description:

A taxi service has collected historical data on taxi orders at airports. To attract more drivers during peak hours, the goal is to forecast the number of taxi orders for the next hour.

## Research Objectives:

Create features for predicting the target variable.

Build a machine learning-based model to predict the number of taxi orders for the next hour.

## Research Stages:

1. Data loading and exploration.

2. Data preparation.

3. Data analysis.

4. Model creation and training.

5. Model testing and selection.

6. Conclusion.

## Libraries Used:

```python
import pandas as pd
import numpy as np
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.metrics import mean_squared_error
import matplotlib.pyplot as plt
from sklearn.ensemble import RandomForestRegressor
from catboost import CatBoostRegressor
from lightgbm import LGBMRegressor
from statsmodels.tsa.seasonal import seasonal_decompose
```
