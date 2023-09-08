# Determining the Promising Telecom Tariff

## Description:

Preliminary analysis of customer data for a nationwide mobile operator. This analysis is based on a small sample of customers. The goal is to analyze customer behavior to determine the better of two offered tariffs.

## Research Objectives:

For each user, determine:

- The number of minutes used per month.
- The number of text messages sent per month.
- The volume of internet traffic used per month.
- The monthly revenue from each user.

Use statistical methods to test the following hypotheses:

- The average revenue of users on the "Ultra" and "Smart" tariffs.
- The average revenue of users in Moscow differs from the average revenue of users in other regions.

## Research Stages:

1. Data acquisition, preprocessing, and preliminary analysis (5 datasets).
2. Combining data into one table.
3. Calculating parameters.
4. Exploratory data analysis (for "Ultra" and "Smart" tariffs).
5. Hypothesis testing.
6. Conclusion.

## Libraries Used:

```python
import pandas as pd
%matplotlib inline
import matplotlib.pyplot as plt
import datetime
from pandas.plotting import scatter_matrix
import numpy as np
from scipy import stats as st
import math
```