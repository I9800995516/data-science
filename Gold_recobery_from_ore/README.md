# Gold Recovery from Ore

## Description:

Provided are data regarding the technological process of gold recovery from gold-bearing ore. These data encompass parameters of gold extraction and purification. The objective is to optimize production to prevent running the facility at a loss.

## Research Objectives:

1. Verify the efficiency calculation of enrichment using a formula and compare it to the tabular value.
2. Develop a function to compute the final sMAPE.
3. Construct a model capable of predicting the gold recovery coefficient from gold-bearing ore at two key stages.

## Research Phases:

1. Data Description
2. Data Preparation
3. Recovery Verification
4. Data Analysis
5. Model Building and Selection
6. Adequacy Testing
7. Conclusion

## Utilized Libraries:

```python
import pandas as pd
from sklearn.metrics import mean_absolute_error
import matplotlib.pyplot as plt
from sklearn.model_selection import cross_val_score
from sklearn.linear_model import LinearRegression
from sklearn.metrics import make_scorer
from sklearn.model_selection import train_test_split
from sklearn.ensemble import RandomForestRegressor
