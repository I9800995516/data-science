# Text Sentiment Classification Project

## Description:

There is a database from an online store with comments in English. Each comment is labeled with either 0 or 1, where 0 represents a positive comment, and 1 represents a negative comment. The store needs a tool that can detect toxic comments and send them for moderation.

## Research Objectives:

Train a model to classify comments as positive or negative.

## Research Stages:

1. Data loading and exploration.

2. Data preprocessing.

3. Creating Tf-idf features.

4. Training and testing models, selecting the best one.

5. Conclusion.

## Libraries Used:

```python
from tqdm import tqdm
import pandas as pd
import nltk
from nltk.corpus import stopwords as nltk_stopwords
from sklearn.feature_extraction.text import TfidfVectorizer
import numpy as np
from sklearn.linear_model import LogisticRegression
from sklearn.model_selection import train_test_split
from sklearn.metrics import accuracy_score
pd.options.mode.chained_assignment = None
from sklearn.metrics import f1_score
from pymystem3 import Mystem
m = Mystem()
import re
from sklearn.tree import DecisionTreeClassifier
from sklearn.ensemble import RandomForestClassifier
import spacy
from sklearn.svm import SVC
from sklearn.preprocessing import StandardScaler
from sklearn.datasets import make_classification
from sklearn.pipeline import Pipeline
from sklearn.model_selection import cross_val_score
from sklearn.feature_extraction.text import CountVectorizer
import matplotlib.pyplot as plt
```
