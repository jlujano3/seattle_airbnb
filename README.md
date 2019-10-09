# seattle_airbnb

## Description
This repository contains the data necessary to analyze air bnb data in Seattle. In addition it contains an IPython notebook which does some analysis regarding the key drivers of price, supply and demand and some preliminary analysis of reviews on Seattle air bnb. 

## Necessary Packages
```
import pandas as pd
import numpy as np
from sklearn.linear_model import LinearRegression
import statsmodels.formula.api as smf
import matplotlib.pyplot as plt
import matplotlib.colors as mcolors
from sklearn.metrics import r2_score
import re
from nltk.corpus import stopwords
from sklearn.feature_extraction.text import TfidfVectorizer
```
