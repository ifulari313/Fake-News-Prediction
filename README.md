# Fake-News-Prediction
Project - Fake News Prediction using ML  ( Logistic Regression )

Classify News in - Real news or Fake news
 0 means  - Real news
 1 means  - Fake News
 
 # Steps : - 
 1. step- Import Libbraries - 
 
import pandas as pd
import numpy as np
import re
from nltk.corpus import stopwords
from nltk.stem.porter import PorterStemmer
from sklearn.feature_extraction.text import TfidfVectorizer
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import accuracy_score

2. step :-

Data Preprocessing :-  Replce null values with null string,  Stemming of words : - process of reducing words to its root word.

3. step : - Train test Split

4. step - Model Building ( Logistic Regression )

5. step - Model Evaluation ( Accuracy Score calculation )  -

# Acuracy of training data is :  98.66
# Acuracy of test data is :  97.91

5 step - Bulding a predictive system :-  we have check our model prediction is correct or not by randomly giving a data from Xtest to model prediction.

As result our model predicted correctly in both cases.
