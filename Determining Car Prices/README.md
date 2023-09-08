# Determining Car Prices

## Description:

You have historical data from a car sales service, including technical specifications, configurations, and car prices. Using this data, you need to automatically determine the market value of "new" cars.

## Research Objectives:

Build a machine learning-based model to determine the price of a car.

Evaluate the quality and speed of the models and choose the best one.

## Research Stages:

1. Data loading and exploration.

2. Data preprocessing.

3. Exploratory data analysis.

4. Building machine learning models.

5. Model analysis.

6. Conclusion.

## Libraries Used:

```python
import pandas as pd
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import OrdinalEncoder
from sklearn.preprocessing import StandardScaler
from sklearn.metrics import mean_squared_error
from sklearn.linear_model import LinearRegression
from sklearn.ensemble import RandomForestRegressor
from catboost import CatBoostRegressor
from lightgbm import LGBMRegressor
import matplotlib.pyplot as plt
import time
```