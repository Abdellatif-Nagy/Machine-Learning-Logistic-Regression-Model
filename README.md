Logistic Regression on the Iris Dataset

This project implements Logistic Regression to classify the species of the Iris flower using the famous Iris dataset. Logistic regression is a powerful yet simple supervised learning algorithm used for classification tasks, and this project demonstrates its application on a well-known dataset.

Project Overview
This project aims to classify the Iris species (Setosa, Versicolor, and Virginica) based on four features: sepal length, sepal width, petal length, and petal width. The Iris dataset contains 150 records, evenly distributed across the three species, and is often used as an introductory dataset for machine learning models.

Key Features:
Dataset: The Iris dataset consists of:

Sepal length (cm)
Sepal width (cm)
Petal length (cm)
Petal width (cm)
Species (target variable: Setosa, Versicolor, Virginica)
Logistic Regression Model:

One-vs-Rest (OvR) multiclass classification is applied, where the model handles each species classification separately.
The sigmoid function is used to predict probabilities for each class.
Exploratory Data Analysis (EDA):

Data Preprocessing:

Feature scaling: Ensuring all features have the same scale to improve model performance.
Train-test split: The dataset is divided into training and testing sets to evaluate model performance on unseen data.
Model Evaluation:

Accuracy: Primary metric to evaluate the overall performance of the logistic regression model.

Dataset: https://www.kaggle.com/datasets/uciml/iris
Project Link: https://colab.research.google.com/drive/17heSumSIYkX4wj09pxvSa7TISOSnAaWh?usp=sharing
