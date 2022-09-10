# Code Created by: Rasandeep Singh Panag

## General Concept:
This repository that how we can use python in jupyter notebook and how we can perform Statistical approaches on a dataset. This dataset **file1.csv** is a collection of English sentence pairs. The crowd was asked about the truth value of the second sentence if the first sentence were true and to what extent the sentences are related on a scale of 1 to 5. The variance of this score over the crowd’s judgments is included as well. In this dataset I will make first 70% of my data as my training data, and the remaining data will be my Test data.

## Statistical Concepts Performed:
- **Simple Linear Regression**: regression model that estimates the relationship between one independent variable and one dependent variable using a straight line. Both variables should be quantitative.  
- **Mean Square Error**: defined as Mean or Average of the square of the difference between actual and estimated values.  
- **R-square**: statistical measure that represents the proportion of the variance for a dependent variable that's explained by an independent variable or variables in a regression model.  
- **Linear Discriminant Analysis**: a method used in statistics and other fields, to find a linear combination of features that characterizes or separates two or more classes of objects or events.  
- **KNN**: A k-nearest-neighbor algorithm is an approach to data classification that estimates how likely a data point is to be a member of one group or the other depending on what group the data points nearest to it are in.
- **Logistic Regression**: statistical analysis method to predict a binary outcome, such as yes or no, based on prior observations of a data set. A logistic regression model predicts a dependent data variable by analyzing the relationship between one or more existing independent variables.  
- **Feature Selection**: method of reducing the input variable to your model by using only relevant data and getting rid of noise in data. It is the process of automatically choosing relevant features for your machine learning model based on the type of problem you are trying to solve.
- **Cross Validation**: statistical method of evaluating and comparing learning algorithms by dividing data into two segments: one used to learn or train a model and the other used to validate the model.  
- **Lasso**: a regression analysis method that performs both variable selection and regularization in order to enhance the prediction accuracy and interpretability of the resulting statistical model.  

## Main Features Used:
- **Jupyter Notebook** is the original web application for creating and sharing computational documents. It offers a simple, streamlined, document-centric experience.  
- **pandas** is a fast, powerful, flexible and easy to use open source data analysis and manipulation tool, built on top of the Python programming language.   
- **Numpy** (Numerical python) is Python library used for working with arrays. It has functions for working in domain of linear algebra, Fourier transform and matrices. In Python we have lists that serve the purpose of arrays but they are slow to process. NumPy aims to provide an array object that is up to 50x faster than traditional Python lists.  
- **Matplotlib** is a comprehensive library for creating static, animated, and interactive visualizations in Python.  
- **Statsmodels** is a Python module that provides classes and functions for the estimation of many different statistical models, as well as for conducting statistical tests, and statistical data exploration. An extensive list of result statistics are available for each estimator.

## Other Relevant Information:
- There are total 10 feature and one outcome and 555 observations in the data.
- I am performing classification and regression on the data.
- As the outcome is provided by its feature so the data is supervised.
- Classification is better suited for this data because I am getting very less R-square with feature selection and feature subselection.

## Repository Contains:
- **Statiscal-Concepts-performed.ipynb** is jupyter notebook file in which all the Statical concepts mentioned above are performed and graphs are also shown in this file. The language used in python.   
- **file1.csv** is dataset that I have used.
