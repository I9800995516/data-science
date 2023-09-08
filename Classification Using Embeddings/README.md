# Text Classification Using Embeddings

## Description:

This research focuses on text classification using feature embeddings. We have been provided with a corpus of tweets with labeled sentiment for analysis.

## Research Objectives:

1. Compare two "trimmed" RuBERT models (rubert-tiny and rubert by DeepPavlov) used for tokenizing the input texts and generating embeddings. Compare their processing speed.

2. Compare the prediction quality of several simple classification models using embeddings. Select the model with the best accuracy score.

## Research Stages:

1. Work plan.

2. Data loading and exploration.

3. Exploratory data analysis.

4. Embedding generation.

5. Splitting into datasets and feature extraction.

6. Machine learning.

7. Model analysis.

8. Conclusion.

## Libraries Used:

```python
import numpy as np
import pandas as pd
import torch
import transformers
from tqdm import notebook
from sklearn.model_selection import train_test_split
from sklearn.metrics import accuracy_score
from transformers import AutoTokenizer, AutoModel
import matplotlib.pyplot as plt
import seaborn as sns
import time
from sklearn.model_selection import GridSearchCV
from sklearn.linear_model import LogisticRegression
import lightgbm as lgb
from sklearn.ensemble import RandomForestClassifier
from catboost import CatBoostClassifier
pd.options.mode.chained_assignment = None
import warnings
warnings.filterwarnings("ignore")
```
