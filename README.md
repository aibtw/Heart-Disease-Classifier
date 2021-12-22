# Gradient Descent Implementation
__________________________________________

This project implements a logistic regression classifier with gradient descent algorithm for machine learning, as a part of 
**Introduction to Artificial Intelligence** course at **KAU**. The goal is to train the model to classify provided data
as "0" or "1" (doesn't have heart disease or has heart disease). 


## How to run using command line
    A- Training:
    1- python Heart-Disease-Classifier.py T1
            This commend will train linear model. it will output linear_thetas.npy file which is necessary for testing.
    2- python Heart-Disease-Classifier.py T2
            This commend will train 2nd ord model. it will output linear_thetas.npy file which is necessary for testing.
    
    B- Testing:
    1- python Heart-Disease-Classifier.py V1
            This command will test the trained linear model. output will be shown in cmd line + Output_Linear.csv file
    2- python Heart-Disease-Classifier.py V2
            This command will test the trained 2nd ord model. output will be shown in cmd line + Output_poly_ord2.csv
            file
