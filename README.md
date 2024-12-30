# Iris Flower Classification

## Project Overview

This project focuses on classifying iris flowers into three species: Setosa, Versicolour, and Virginica. Using the Iris dataset, a supervised machine learning model is developed to accurately predict the species based on features such as sepal length, sepal width, petal length, and petal width.

## Dataset

The Iris dataset consists of 150 samples and includes the following features:

Sepal Length (cm)

Sepal Width (cm)

Petal Length (cm)

Petal Width (cm)

Species: Target class (Setosa, Versicolour, Virginica)

## Approach

1. Data Exploration

   Summary Statistics: Examined the dataset to understand distributions and relationships between features.

   Visualization: Used scatter plots, histograms, and pair plots to identify patterns and separability among species.

2. Data Preprocessing

   Normalization: Scaled feature values to standardize input data.

   Train-Test Split: Divided the dataset into training (80%) and testing (20%) sets.

3. Model Building

   Algorithm Used: Random Forest Classifier

   Leveraged its ensemble technique for robust and accurate predictions.

   Tuned hyperparameters like the number of trees, maximum depth, and criterion for best performance.

4. Evaluation

   Evaluated the model using metrics such as accuracy, precision, recall, and F1-score.

   Performed cross-validation to ensure model generalization.

## Challenges

Ensuring proper separation of overlapping classes (Versicolour and Virginica).

Selecting optimal hyperparameters to avoid overfitting or underfitting.

## Summary of Performance

Model Used: Random Forest Classifier

Accuracy: 97%

Additional Metrics:

Precision: 96%

Recall: 97%

F1-Score: 97%

## Future Improvements

Experiment with additional machine learning algorithms like SVM or KNN.

Implement feature selection techniques to assess the importance of each feature.

Extend the project to include real-time classification from user-provided inputs.
