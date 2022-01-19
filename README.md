# Logistic-Regression

Time for some learning.  This file contains my implementations of several methods used in creating and testing a binary logistic regression function.  
* A method for loading data into the design matrix.
* ... computing the sigmoid function,
* ... computing the gradient of the sigmoid function,
* ... computing the Hessian of the sigmoid function,
* ... computing the diagonal expected value matrix used in the Hessian computation,
* a steepest descent with and without a momentum term to update weights, and
* an iteratively reweighted least squares update method (bug: has problems with singular matrices).

The file also contains the following synthetic test material:
* A synthetic data constructor for normally distributed random vectors,
* labels generated for the synthetic data, and
* plots of 1-D regressor weights from the fitting process on the synthetic data.

The file also contains the following real-data tests:
* Data from the Donner Party taken from *Introduction to Regression Modeling by Abraham and Ledolter (2006), pg 368*
* A fitting of regressors on said data, and
* classifiers from SK-Learn for comparison and validation of the methods herein.

Lastly, the file contains my application of the logistic regression classifiers to the SE Data for Albany from a previous project.
