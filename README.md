# Plagiarism-Detection
*Plagiarism Detection: Udacity - Machine Learning Engineer Nanodegree*

## Project Overview

This project explores Machine Learning solutions to the problem of plagiarism. by performing binary classification, we are able to determine weither a file is plagiarised or not. Furthermore, it showcases how a machine learning model can be deployed to amazon sagemaker cloud service allowing the model to be accessible through web or mobile applications using REST API.

&nbsp;

___There are 7 files associated with the project:___
1. Plagiarism_Feature_Engineering.ipynb: code for handling the data.
2. Training_a_Model.ipynb code for training the model and deploying it to the cloud.
3. helpers.py: contains functions that help with organizing the data from row files to a dataframe.
4. problem_unittests.py: contains test functions for several parts of the project.
5. model.py: contains the class for the pytorch model.
6. train.py: code for training the pytorch model.
7. predict.py: code for using the trained model to make predictions.

files numbered 5, 6 and 7 are found in source_pytorch directory.
"Plagiarism_Feature_Engineering" notebook should be run first to prepare the data before running "Training_a_Model" notebook

&nbsp;

## Software and Libraries
The project is coded in python 3 and it uses the following libraries:
* numpy
* pandas
* sklearn
* sagemaker
* boto3
