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

## Motivation
This project is meant to take advantage of a few datasets provided by airbnb which share information about the Seattle market of their rental properties. Overall we are free to take whatever approaches we wish to analyze the dataset. We must answer 3-5 questions related to the airbnb data and share our findings in a coherent manner through the blog post.

## Files
In this github repo is the notebook and the readme file. I don't believe I have the liberty to share the datasets, so those will have to be downloaded through the udacity site.

## Results Overview
I decided to tackle 3 questions.

1) what elements of a property affect the price that a host is able to charge.
-- what I found here was largely intuitive, but quantified the value of a privat room vs. a shared room. the value of having a property that can accomodate more people vs. has more bathrooms.

2) how does supply and demand vary throughout the week, year.
-- what I found here was that weekends are priced higher than weekdays and that summers are more high priced than the rest of the year. What I also found was that supply does not appear to vary by the day of the week.

3) what are the important elements of reviews.
-- It was very interesting to see the key pieces of reviews and give hosts the ability to focus on these elements in their properties.

## Acknowledgements
Thanks to Udacity and AirBnb for access to the datasets and considerate guidance.
