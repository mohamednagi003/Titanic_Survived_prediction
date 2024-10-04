# Titanic Survived Prediction - Machine Learning Project
Welcome to the Titanic Survived Prediction project! This project uses machine learning to predict whether a passenger survived or not during the Titanic disaster. The model leverages the Logistic Regression algorithm to classify passengers based on various features such as age, gender, ticket class, etc.

This README provides an overview of the project, the algorithm choice, how to set up the project, and how to use the model.
# Overview
The Titanic dataset is one of the most famous datasets in data science and machine learning. In this project, we aim to predict the survival of passengers based on key characteristics such as:

Passenger Class
Sex
Age
Fare
Embarked Port
Number of Siblings/Spouses Aboard (SibSp)
Number of Parents/Children Aboard (Parch)
The machine learning model uses Logistic Regression, a classification algorithm, to predict survival (binary outcome: 0 = did not survive, 1 = survived).

# Why Logistic Regression?
I chose Logistic Regression for this project because it’s a powerful and interpretable algorithm for binary classification problems, such as predicting survival. Here are some advantages of Logistic Regression:

Binary Classification:
Logistic Regression is specifically designed for binary classification problems, making it perfect for predicting whether a passenger survived or not.

Interpretability:
Logistic Regression provides clear insights into how each feature affects the probability of survival. The model's coefficients give us a direct understanding of how variables such as age, gender, or class influence the survival outcome.

Simplicity and Efficiency:
Logistic Regression is computationally efficient and works well with small to medium-sized datasets like the Titanic dataset. It's simple to implement, train, and test, making it an ideal starting point for this kind of problem.

Probabilistic Output:
The model provides probabilities for each prediction, allowing us to gauge how confident the model is in its classification of survival. This is helpful when we need more than just a binary result.

Handles Linearly Separable Data Well:
The Titanic dataset is not extremely complex in terms of feature interaction, which means Logistic Regression can produce robust predictions without the need for more advanced algorithms.
# Prerequisites
You will need Python 3.x and the following libraries to run the project:

pandas
numpy
scikit-learn
matplotlib
seaborn

# Model Performance
The Logistic Regression model achieves the following performance on the test set:

Accuracy: ~87%
Precision: 0.88
Recall: 0.86
F1-Score: 0.87

# Contact
If you have any questions or suggestions regarding this project, feel free to contact me:

Email: mohamed.nagi@ejust.edu.eg
GitHub: mohamednagi003
# Happy Coding!
