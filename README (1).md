# IRIS Flower Classification
This repository contains code for classifying IRIS flowers based on their features using both Logistic Regression and Neural Network models in Python.

# Dataset
The dataset used for this classification task is loaded from the 'IRIS.csv' file. The dataset contains information about the sepal length, sepal width, petal length, petal width, and the species of IRIS flowers.

# Data Exploration
The code performs data exploration, including checking the dataset's shape, information, and handling any missing values. It also visualizes the data distribution using density plots.

# Preprocessing
The preprocessing steps include label encoding the target variable ('species'), applying power transformation to address skewness, and splitting the dataset into training and testing sets.

# Logistic Regression Model
The code builds a Logistic Regression model and trains it using the training data. It then evaluates the model's performance on the testing data, providing accuracy and a classification report.

# Neural Network Model
The code uses TensorFlow and Keras to build a neural network for the IRIS flower classification task. The model consists of multiple dense layers with ReLU activation functions and a softmax output layer.

# Model Evaluation
The neural network model is trained and evaluated on the testing data. The code calculates and displays the accuracy of the model.

Feel free to explore the code for IRIS flower classification using Logistic Regression and Neural Network models!

# Usage
Ensure you have the necessary dependencies installed:
pandas                   
numpy                    
scikit-learn                      
matplotlib                                  
tensorflow                  

Run the code to load the dataset, perform data exploration, and train the models.

Explore the classification results and model performance metrics.

# Note
Make sure to have the 'IRIS.csv' file in the same directory as the code for successful execution.
