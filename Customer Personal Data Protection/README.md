# Customer Personal Data Protection

## Description:

Personal data of bank customers have been provided, and a credit scoring model is built based on this data. The goal is to protect the data in a way that makes it difficult to reconstruct personal information while ensuring that the quality of machine learning models does not deteriorate. Finding the best model is not required.

## Research Objectives:

1. Develop a data transformation method that makes it difficult to reconstruct personal information from it.

2. Justify the correctness of this method's operation.

3. Verify the data transformation algorithm.

## Research Stages:

1. Data loading.

2. Data analysis.

3. Model building.

4. Data encoding.

5. Algebraic proof.

6. Data transformation algorithm.

7. Algorithm verification.

8. Conclusion.

## Libraries Used:

```python
import numpy as np
import pandas as pd
from sklearn.linear_model import LinearRegression
from sklearn.model_selection import train_test_split
from sklearn.metrics import r2_score
```
