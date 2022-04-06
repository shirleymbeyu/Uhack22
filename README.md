# UmojaHack Africa 2022: Monthly Insurance Claim Prediction Challenge (INTERMEDIATE)

# Research Question
Can you predict how much will be claimed per month?

# Objective
Create a machine learning model to predict how much a client will claim
from Zimnat per month for a whole year.

Eventually, this will aid Zimnat in being better prepared to address claims that 
are submitted, and improve customer satisfaction (by alerting clients to
possible claims they will make in the future).

# Evaluation
Error metric is the Mean Absolute Error(MAE)

# Getting Started
Create a python notebook

In the notebook,
Import libraries to be used;

import pandas as pd

import numpy as np

import matplotlib.pyplot as plt

import seaborn as sns

Upload the csv files from the competition's web to the notebook

# Prerequisites
Scikit-learn modules and classes for the Machine learning phase;

from sklearn.metrics import mean_absolute_error

from sklearn.model_selection import train_test_split

from sklearn.preprocessing import LabelEncoder


This was a regressor question, therefore regressor models were used e.g 

from sklearn.ensemble import RandomForestRegressor

from sklearn.linear_model import LinearRegression

from sklearn.neighbors import KNeighborsRegressor
etc...
