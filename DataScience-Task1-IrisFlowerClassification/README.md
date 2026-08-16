# Iris Flower Classification

## OIBSIP Data Science Internship - Task 1

### Project Overview

This project focuses on building a machine learning classification model to identify the species of an iris flower based on its physical measurements.

The three iris species considered are:
- Setosa
- Versicolor
- Virginica

### Objective

The objective of this project is to explore the Iris dataset, visualize the relationships between its features, train multiple classification models, evaluate their performance, and identify the best-performing model.

### Dataset

The Iris dataset is built into the scikit-learn library and was loaded using `sklearn.datasets.load_iris()`.

The dataset contains 150 samples, 4 numerical features, and 3 target classes.

The four features are:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

No external dataset download was required.

### Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

### Exploratory Data Analysis

The following EDA steps were performed:
- Dataset shape
- Data types
- Null value check
- Descriptive statistics

### Data Visualization

The following visualizations were created:
- Pairplot to analyze relationships between features and species
- Box plots to compare feature distributions across species

### Feature Selection

Based on the visualizations, petal length and petal width appeared to be the most discriminative features for distinguishing the three iris species.

### Machine Learning Models

Two classification models were trained:
1. Logistic Regression
2. K-Nearest Neighbours (KNN)

An 80:20 train-test split was used for model training and evaluation.

### Model Evaluation

The models were evaluated using:
- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1-Score
- Classification Report

### Conclusion

The performance of Logistic Regression and K-Nearest Neighbours was compared using the evaluation metrics obtained on the test dataset.

The model performance and final results are presented in the Jupyter Notebook.

### Project File

- `Iris_Flower_Classification.ipynb` - Complete Jupyter Notebook containing data analysis, visualizations, model training, evaluation, and conclusion.
