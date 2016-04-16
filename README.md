#Boston housing dataset

###Python libraries

numpy, Matplotlib, sklearn

###Problem statement

Analyze Boston Housing dataset and build a regressor to predict house price for unseen data point.
This is my first project for Udacity Machine Learning Engineer Program.

###Overview

Use grid algorithm on maximum depth of regressor tree to search for best model. 

The scoring function is mean squared error, and each regressor tree model is evaluated using 10-fold cross validation.

The best-performing model (with tree-depth = 6 and MSE=25) gives predictions within 25-40% range of the hypothetically "correct" value for unseen dataset.

###Installation

Load boston_housing.py.


