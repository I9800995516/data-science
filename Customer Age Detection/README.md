# Customer Age Detection

## Description:

A network of supermarkets is implementing a computer vision system to determine the age of customers in the checkout area through image capture. A labeled dataset with customer photos and their ages is available for analysis.

## Research Objectives:

Build a model that can estimate a person's approximate age from a photo.

## Research Stages:

1. Data loading.

2. Exploratory data analysis.

3. Model training.

4. Analysis of the trained model (conclusion).

## Libraries Used:

```python
from tensorflow.keras.applications.resnet import ResNet50
from tensorflow.keras.preprocessing.image import ImageDataGenerator
from tensorflow.keras.layers import Conv2D, Flatten, Dense, MaxPooling2D, GlobalAveragePooling2D
from tensorflow.keras.models import Sequential
from tensorflow.keras.optimizers import Adam
import numpy as np
import pandas as pd
from PIL import Image
import matplotlib.pyplot as plt
```
