# Tariff Recommendation

## Description:

Analysis of historical data on the behavior of mobile operator customers. The goal is to build a system capable of recommending a new tariff to users: "Smart" or "Ultra."

## Research Objectives:

Build a machine learning-based model for classification. The model should select the appropriate tariff for the user.

## Research Stages:

1. Opening and exploring the file.

2. Data analysis.

3. Data splitting.

4. Model exploration, determining the best one.

5. Testing the model on the test set.

6. Checking the model for adequacy.

7. Conclusion.

## Libraries Used:

```python
import pandas as pd
%matplotlib inline
import matplotlib.pyplot as plt
import datetime
from pandas.plotting import scatter_matrix
from sklearn.tree import DecisionTreeClassifier
from sklearn.ensemble import RandomForestClassifier
from sklearn.linear_model import LogisticRegression
from sklearn.model_selection import train_test_split
from sklearn.metrics import accuracy_score
from sklearn.dummy import DummyClassifier
import warnings
```
