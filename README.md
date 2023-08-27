# Master-Thesis-Lawrence-Pham
### Predicting Default in P2P Lending: Leveraging Supervised Machine Learning and Macroeconomic Factors for Enhanced Risk Assessment

## Introduction
The purpose of these series of notebooks is to predict loan defaults in P2P lending by leveraging macroeconomic variables and utilizing ensemble machine learning techniques.

Therefore, each machine learning model is performed once without macroeconomic variables (model VI) and once with (model VII), in order to evaluate its effect on the overall prediction rate. 

Furthermore, random under-sampling techniques (RUS) were utilized to address data imbalance issues. So, separate notebooks with the same machine learning models but without any resampling techniques are considered the control (CTRL).

## Table of Contents
The notebooks are divided into 7 parts:

Part 1 is dedicated to exploratory data analysis and preliminary hypothesis testing.
Part 2 is dedicated to the logistic regression using the random under-sampling technique.
Part 3 is dedicated to the logistic regression without any resampling technique.
Part 4 is dedicated to the neural network using the random under-sampling technique.
Part 5 is dedicated to the neural network without any resampling technique.
Part 6 is dedicated to the hybrid model using the random under-sampling technique.
Part 7 is dedicated to the hyrid model without any resampling technique.

## Data
The main dataset that was utilised for this project was the loan dataset retrieved from https://www.kaggle.com/code/ovaizali/loan-defaulters-pycaret-automl.

In addition, other datasets were created for the macroeconomic indicators, this data was retrieved from several reliable governmental sources.

## Tools & Libraries
The project was entire developed with Visual Studio Code using Python 3.9.12.

In order to run the notebooks smoothly, it is essential to install the following libraries:

TensorFlow (tf)	: An open-source machine learning framework.
Keras: A high-level neural networks API, written in Python and capable of running on top of TensorFlow.
scikit-learn: A machine learning library for Python. It features various algorithms like support vector machine, random forests, and k-neighbours. It also supports Python numerical and scientific libraries like NumPy and SciPy.
NumPy (np): A library for the Python programming language, adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays.
pandas (pd): An open-source data analysis and manipulation tool. 
matplotlib.pyplot (plt): A plotting library for the Python programming language and its numerical mathematics extension NumPy.
seaborn (sns)	: A Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.
shap: A library to explain the output of machine learning models.
kerastuner: A library for hyperparameter tuning for Keras models.
ggplot: A plotting system for Python based on R's ggplot2 and the Grammar of Graphics.
Adam: An optimization algorithm that can be used instead of the classical stochastic gradient descent procedure to update network weights iterative based on training data.




