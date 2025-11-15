Iris Flower Classification — Machine Learning Project
** Project Overview

This project focuses on predicting Iris flower species using four key measurements:

Sepal Length

Sepal Width

Petal Length

Petal Width

A Random Forest Classifier was used to build a robust classification model.
The goal was to analyze the dataset, explore relationships between features, and build a highly accurate prediction model.

** Dataset Information

Dataset Size: 150 samples

Features: 4 numeric measurements

Target: 3 species

Iris-setosa

Iris-versicolor

Iris-virginica

** Data Preprocessing Steps

Removed the Id column

Encoded the target variable (Species) using LabelEncoder

Split dataset using train_test_split

Performed EDA and created multiple visualizations

** Exploratory Data Analysis (EDA)
✔ Pairplot

Shows clear separation between Setosa, Versicolor, and Virginica.

✔ Correlation Matrix

Strong correlation between Petal Length and Petal Width

Weak correlation between Sepal-based features

Confirms that petal measurements are the strongest predictors of species

** Modeling
Model Used:

RandomForestClassifier(n_estimators=100, random_state=42)

Why Random Forest?

Handles non-linear relationships

Robust to noise

Reduces overfitting

Works extremely well on small, clean datasets like Iris

** Model Performance
✔ Accuracy: 100%

The model classified all test samples correctly.

✔ Classification Report:

All classes achieved:

Precision = 1.00

Recall = 1.00

F1-score = 1.00

✔ Confusion Matrix:

Perfect diagonal matrix — zero misclassifications.

** Feature Importance

According to the model:

Feature	Importance
Petal Length	Highest
Petal Width	Very High
Sepal Length	Low
Sepal Width	Lowest

** Conclusion:
The petal dimensions are the main distinguishing factors for Iris species.
