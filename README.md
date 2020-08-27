# Python_Portfolio
Data Science Projects in Python

# [Project 1: Dating Match Classifier](https://github.com/rudymeza54/Python_Portfolio/blob/master/Dating_Classifier_Code.ipynb)
* I have included my analysis and the data downloaded from kaggle.
* The motivation for this project was to explore what certain features drive dating matches for participants in a speed dating environment.
* Used the Logistic Regression to properly classify matches for participants in Speed Dating.
* Total number of observations include 8,378
* Feature engineering includes log transformations and polynomial transformations.
* Applied the Synthetic Minority Oversampling Technique (SMOTE) to increase accuracy for imbalanced data
* Increased AUC from 52% to 71%
* The variables that drive matches are attraction, shared interests, intelligence, fun, and tuition. However, ambition, gender, age, and being sincere lower the probability of finding a match.

# The packages below were used to perform my analysis
* import numpy as np
* import pandas as pd
* import matplotlib.pyplot as plt
* from dfply import *
* import seaborn as sns #visualisation
* from sklearn.linear_model import LinearRegression
* from sklearn.linear_model import LogisticRegression
* from sklearn.model_selection import train_test_split
* from sklearn.metrics import r2_score, mean_squared_error
* %matplotlib inline
* sns.set(style="white")
* sns.set(style="whitegrid", color_codes=True)
