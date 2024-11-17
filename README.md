# Comprasion btweeen  Maximum Likelihood classifier and Minimum distance to mean classifier
This is the course project of GNR 607 - Satellite Image Processing course of CSRE, IIT Bombay.

# Code
Purpose: The code processes a .tif image, applies two classification methods (Maximum Likelihood Classifier and Minimum Distance to Mean Classifier), and visualizes the results based on the first two features (bands).

Data Loading: The .tif image is loaded and flattened into a 2D array where each row corresponds to a pixel and columns represent band intensities.

Classification:
MLC: Classifies pixels based on the likelihood of belonging to each class, using class means and covariance matrices.
MDC: Classifies pixels by computing the minimum Euclidean distance to the class means.

Output: Generates scatter plots comparing the results of the two classifiers, using colors to represent the predicted class for each pixel.

# Results

Tested with three type of satellite image

Input 


![Screenshot 2024-11-18 030537](https://github.com/user-attachments/assets/01a13e45-65ac-4eef-b2cf-20cfd6f77cb3)

Output 
![image](https://github.com/user-attachments/assets/2900da39-f9c1-4f38-be33-0086eceaeeda)


Input 

![image](https://github.com/user-attachments/assets/983abf68-5d67-4083-adf7-a8cd060bafe2)

Output

![image](https://github.com/user-attachments/assets/e366ca1f-b4ea-4230-8cd1-16cec1d984f4)

Input 


![image](https://github.com/user-attachments/assets/aba9d45d-eb7b-4b2c-980a-1730529ae1ef)


Output 







