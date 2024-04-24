# SC1015-Mini-Project
## About
This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on movies from [The Movies Database](https://www.kaggle.com/datasets/asaniczka/tmdb-movies-dataset-2023-930k-movies) dataset from Kaggle. For a detailed walkthrough, please view the source code in order from:  
  1. Data Preparation
  2. Exploratory Data Analysis
  3. Neural Network
  4. Linear Regression

## Contributors
- Navya Singhal - Data Preparation, Exploratory Data Analysis
- Rohit Kurup - Neural Networks, Exploratory Data Analysis
- Saanvi Khemka - Linear Regression, Exploratory Data Analysis

Group 8 - FCSE
NTU

## Problem Definition
- Can we predict how much revenue a movie will generate?
- Which model would be best to predict it?

## Models Used
1. Neural Networks
2. Linear Regression

## Conclusion 
- Budget has the strongest linear correlation with revenue, followed by vote count, popularity, adventure genre, and English language movies.
- Movie overview, age rating, release year, and average vote have the lowest linear correlation.
- The Neural Network model performed best with a very low learning rate.
- A dataset with more variables should be used, to increase the breadth of Neural Network learning.
- Linear Regression model works better than Neural Network to predict revenue with this data.
- Yes, it is possible to predict approximately how much revenue a movie will generate with an acceptable amount of accuracy.

## What did we learn from this?
- Analysing text data using TFIDF vectorizer
- Neural Networks, Keras, Tensorflow
- Standard Scaler from sklearn.preprocessing, Adam Algorithm
- Concepts about using vector scores to analyze text
- Word Cloud visualisation
- Collaboration using Github

## References
1. https://www.kaggle.com/datasets/asaniczka/tmdb-movies-dataset-2023-930k-movies/data
2. https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.TfidfVectorizer.html
3. https://www.learndatasci.com/glossary/tf-idf-term-frequency-inverse-document-frequency/
4. https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html
5. https://towardsdatascience.com/why-adamw-matters-736223f31b5d#:~:text=Adaptive%20optimizers%20like%20Adam%20have%20become%20a%20default%20choice%20for,to%20not%20generalize%20as%20well.
6. https://explained.ai/regularization/L1vsL2.html#:~:text=From%20a%20practical%20standpoint%2C%20L1,you%20have%20collinear%2Fcodependent%20features
7. https://medium.com/@nirajan.acharya666/choosing-between-mean-squared-error-mse-and-mean-absolute-error-mae-in-regression-a-deep-dive-c16b4eeee603

