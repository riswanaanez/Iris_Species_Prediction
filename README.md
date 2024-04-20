# **Iris Flower Species Prediction using K-Nearest Neighbor Classifier**

This repository contains Python code for predicting the species of Iris flowers using a supervised machine learning algorithm, specifically the K-Nearest Neighbor (KNN) classification model.

## **Project Overview**

The aim of this project is to predict the species of Iris flowers based on certain features such as sepal length, sepal width, petal length, and petal width. The steps followed in the project are as follows:

1. **Data Setup**: Importing datasets and essential libraries.
2. **Data Cleaning**: Preprocessing the data to handle any missing values or outliers.
3. **Data Partitioning**: Splitting the dataset into input features and target labels.
4. **Train-Test Split**: Dividing the data into training and testing sets for model evaluation.
5. **Data Normalization**: Normalizing the input features using Standard Scaler normalization.
6. **Model Creation**: Implementing the K-Nearest Neighbor classifier with a value of k set to 7.
7. **Performance Evaluation**: Assessing the model's performance using various metrics such as confusion matrix, accuracy score, recall, precision, and F1-score.

## **Dataset**

The dataset used in this project is the famous Iris dataset, which is included in many machine learning libraries and repositories. It contains 150 samples of Iris flowers, with each sample having four features: sepal length, sepal width, petal length, and petal width. The target variable consists of three species of Iris flowers: Setosa, Versicolor, and Virginica.

## **Insights**

The KNN classification model achieves an impressive accuracy score of 1.0, indicating that it accurately predicts the species of Iris flowers in the dataset.

## Dependencies

- Python 3.x
- NumPy
- Pandas
- Scikit-learn
