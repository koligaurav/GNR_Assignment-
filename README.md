# Comprasion btweeen  Maximum Likelihood classifier and Minimum distance to mean classifier
This is the course project of GNR 607 - Satellite Image Processing course of CSRE, IIT Bombay.

# Code
Purpose: The code processes a .tif image, applies two classification methods (Maximum Likelihood Classifier and Minimum Distance to Mean Classifier), and visualizes the results based on the first two features (bands).

Data Loading: The .tif image is loaded and flattened into a 2D array where each row corresponds to a pixel and columns represent band intensities.

Classification:
MLC: Classifies pixels based on the likelihood of belonging to each class, using class means and covariance matrices.
MDC: Classifies pixels by computing the minimum Euclidean distance to the class means.

Output: Generates scatter plots comparing the results of the two classifiers, using colors to represent the predicted class for each pixel.






