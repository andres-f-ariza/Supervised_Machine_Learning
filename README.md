# Supervised_Machine_Learning
• Machine learning models in Python using popular machine learning libraries NumPy and scikit-learn.
• Supervised machine learning models for prediction and binary classification tasks, including linear regression and logistic regression.
- Project: Prediction of house price according to a initial dataset.

1. 1_Model_Representation_Soln.py: Implementation of the model  𝑓(𝑤,𝑏)  for linear regression with one variable. 
This file makes use of tools like NumPy, a popular library for scientific computing and Matplotlib, a popular library for plotting data.
Problem Statement: simple data set with only two data points - a house with 1000 square feet(sqft) sold for $300,000 and a house with 2000 square feet sold for $500,000. These two points will constitute our data or training set. You would like to fit a linear regression model through these two points, so you can then predict price for other houses - like a house with 1200 sqft.
NOTE: the units of size are 1000 sqft and the units of price are 1000s of dollars.

2. 2_Cost_function_Soln.pynb: Implementation and exploration of the cost function for linear regression with one variable. 
This file makes use of tools like NumPy, Matplotlib, and lab_utils_uni.py which contain local plotting routines and is found in this repo.
Problem Statement: You would like a model which can predict housing prices given the size of the house.

3. 3_Gradient_Descent_Soln: automation of the process of optimizing  𝑤  and  𝑏  using gradient descent.
This file makes use of tools like NumPy, Matplotlib, and lab_utils_uni.py.
Problem Statement: You would like to automate the process of optimizing  𝑤  and  𝑏  using gradient descent.

4. 4_Python_Numpy_Vectorization_Soln.ipynb: Useful Numpy tools
- vectors/matrices creation.
- indexing/slicing on vectors/matrices.
- operations on vectors/matrices: negation, scalar product, sum of elements, mean of elements, potentiation of elements.
- vector vector operations: dot product.

5. 5_Multiple_Variable_Soln: Extend regression model routines to support multiple features
- Extend data structures to support multiple features
- Rewrite prediction, cost and gradient routines to support multiple features

