# Predict student's GPA based on given SAT marks using simple linear regression

# What is linear regression

Linear regression is a linear approach to modelling the relationship between a dependent variable (response) and one or more independent variables (explanatory).
To understand difference between dependent & independent, look at the equation:
Y = aX + b 
X can take any value from the sample space, and Y value depends on X value, and thus it is a dependent.

Linear regression can be divided into two divisions based on the number of independent variables, if we have one independent variable we call it simple linear regression model, other than that it is called multiple linear regression model.
The equation that describes how y is related to X is called the regression model!
There are different types of regression models:
Simple regression, Multiple regression, Polynomial regression, Support Vector Regression.
Our example looking at simple linear regression.
Keep in mind, regression only tries to find relationship out of the given information. Correlation doesn't prove causation!

# Installation

Python 3.8 + your preferred IDE.
I am using Anaconda with python 3.8 (Jupyter notebook).
Needed packages shown inside the code file.
Dataset is downloaded from Kaggle.

# Steps 
- Loading data from the csv file into arrays (X, Y).
- Cleaning data (missing data, pessimist values, etc)
- Splitting data into train data & test data.
- Import LinearRegression for actual training process, to learn a pattern from your data.
- Predict GPA from testing values.
- Visualize your predictions!
