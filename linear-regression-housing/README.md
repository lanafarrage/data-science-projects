Overview

This project implements a simple linear regression model from scratch and also uses scikit-learn's LinearRegression to analyze the relationship between car price and engine size. The goal is to predict the engine size based on the price of the car using gradient descent optimization.

Project Description

The dataset consists of two variables: Price (car price) and Engine_size (size of the engine).
A custom linear regression model is implemented using gradient descent to minimize the cost function (mean squared error).
The cost function and gradients are calculated manually for learning purposes.
Model parameters (weight and bias) are updated iteratively for 10,000 iterations with a learning rate of 0.001.
The project plots the cost function over iterations to visualize convergence.
The regression line learned by gradient descent is plotted against the original data points.
A prediction function is provided to estimate engine size for any given price.
How to Run

Prepare your Price and Engine_size data as numpy arrays.
Run the script to train the model using gradient descent.
Observe the printed cost values every 100 iterations to see progress.
Visualize the cost reduction and the regression line against the data using matplotlib plots.
Use the predict(price) function to get engine size predictions for new car prices.
Key Functions

cost_function(Price, Engine_size, weight, bias): Computes the cost (mean squared error).
gradient_calculation(Price, Engine_size, weight, bias): Computes gradients of cost w.r.t weight and bias.
gradient_decent(...): Runs the gradient descent algorithm to optimize weight and bias.
predict(price): Returns predicted engine size for a given price using the trained parameters.
Requirements

Python 3.x
Libraries: numpy, pandas, matplotlib, scikit-learn
Files Included

linear_regression.py: Contains the model implementation and plots.
Dataset (if external) or inline data arrays.
