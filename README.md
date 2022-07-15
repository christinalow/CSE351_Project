# CSE 351: Introduction to Data Science - Final Project

Contributers: [Amara Im](https://github.com/amaraim22) & [Christina Low](https://github.com/christinalow)

View our presentation at [https://tinyurl.com/cse351project](https://tinyurl.com/cse351project)
View code on Google colab: [https://colab.research.google.com/drive/1r6dJAHsoR7BB5b4a8JuahteT5gFbE0wl?authuser=1#scrollTo=o4ZMC6f7AOa-](here)

## Background

#### What makes people in a country happy?

The World Happiness Report is a landmark survey of the state of global happiness that ranks countries by how happy their citizens perceive themselves to be. The report gains global recognition as governments, organizations and civil society increasingly use happiness indicators to inform their policy-making decisions. This project allows us to gain insight into the state of happiness in the world today.

## Datasets

The "World Happiness Report" found on [Kaggle](https://www.kaggle.com/datasets/unsdsn/world-happiness) contains the happiness data for different countries from year 2015 to year 2019. We will treat data of year 2015 to year 2018 as the training set, and year 2019 data as the test set. Description of the data fields can be found on the FAQ page of World Happiness Report at [https://worldhappiness.report/faq/](https://worldhappiness.report/faq/)

## Python Libraries

* [Pandas](https://pandas.pydata.org/) - Data Analysis
* [NumPy](https://numpy.org/) - Scientific Computing
* [Matplotlib](https://matplotlib.org/) - Data Visualization
  *   [Seaborn](https://github.com/mwaskom/seaborn) - Statistical Visualization in Matplotlib
* [scikit-learn](https://scikit-learn.org/stable/) - Machine Learning
  * [XGBoost](https://github.com/dmlc/xgboost) - Gradient Boosting

## Exploratory Data Analysis

* Merge and clean the data. 
* What are the central tendencies of happiness score over the years? Did they increase or decrease?
* Which countries have stable rankings over the years? Which countries improved their rankings?
* Visualize the relationship between happiness score and other features such as GDP, social support, freedom, etc.
* If you are the president of a country, what would you do to make citizens happier?

## Modeling - Machine Learning

* [Linear Regression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html) - finds the linear relationship between x (input) and y (output) and predicts the dependent variable (y) based on the independent variable (x).
* [Random Forest](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html) - creates a set of decision trees from a few randomly selected subsets of the training set and picks predictions from each tree.
* [XGBoost](https://xgboost.readthedocs.io/en/stable/) - minimizes a regularized (L1 and L2) objective function that combines a convex loss function (based on the difference between the predicted and target outputs) and a penalty term for model complexity (in other words, the regression tree functions).
