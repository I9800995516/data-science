# Telecom Customer Churn Analysis

## Description:

The telecom operator has a customer database and a service database. Using historical data, the goal is to predict the situation when a customer is about to terminate their cooperation with the company.

## Research Objectives:

Build a model for binary classification of the customer's current status (whether they are planning to leave or not).

## Research Stages:

1. Work plan.

2. Data import and processing.

3. Final table for machine learning, feature splitting.

4. Machine learning and model selection, identifying the best model.

5. Conclusion.

6. Solution report.

## Libraries Used:

```python
!pip install category_encoders

import pandas as pd
from sklearn.model_selection import train_test_split
from catboost import CatBoostClassifier
from sklearn.metrics import roc_auc_score
import category_encoders as ce
from statsmodels.stats.outliers_influence import variance_inflation_factor
import numpy as np
import matplotlib.pyplot as plt
from sklearn.preprocessing import OrdinalEncoder
from sklearn.metrics import roc_curve
from sklearn.ensemble import RandomForestClassifier
from sklearn.model_selection import GridSearchCV
import seaborn as sns
```
