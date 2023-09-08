# Customer Churn Prediction

## Description:

Analysis of historical data on customer behavior with a bank and the termination of contracts with the bank. The task is to build a model that predicts customer churn from the bank.

## Research Objectives:

Build a machine learning-based model that forecasts customer churn from the bank.

## Research Stages:

1. Data acquisition and evaluation.

2. Data preprocessing.

3. Feature preparation, target variable, and dataset splitting.

4. Building models, researching, and hyperparameter tuning.

5. Testing the best model.

6. Conclusion.

## Libraries Used:

```python
import pandas as pd
import numpy as np
%matplotlib inline
import matplotlib.pyplot as plt
from sklearn.tree import DecisionTreeClassifier
from sklearn.ensemble import RandomForestClassifier
from sklearn.metrics import accuracy_score
from sklearn.dummy import DummyClassifier
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler
from sklearn.metrics import f1_score
from sklearn.utils import shuffle
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import precision_score, recall_score
from sklearn.metrics import roc_auc_score
from sklearn.metrics import roc_curve
```
