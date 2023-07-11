# Titanic-Survived-Analysis-with-Machine-Learning

## Filling Missing Values:

Filled the missing values in the "Embarked" column with the most common value, which is "C".
Filled the missing value in the "Fare" column with the mean fare value of passengers in the same Pclass (3rd class).
Visualization:

Created various visualizations to analyze the relationships between different features and the target variable ("Survived").
Plotted correlation matrices and explored the correlation between different numerical features.
Plotted bar plots and distribution plots to analyze the survival probabilities based on different categorical features such as "SibSp," "Parch," "Pclass," "Age," "Embarked," and "Fare."

## Feature Engineering:

Extracted the titles from the "Name" column and created a new "Title" feature.
Replaced rare titles with the label "other" and converted the titles into numeric categories.
Created a new feature "Fsize" representing the total family size by summing the "SibSp" and "Parch" columns.
Created a binary feature "Family_size" to indicate if the passenger has a small family size (less than 3).
Extracted information from the "Ticket" column and created multiple binary features based on different ticket prefixes.
Converted the "Pclass" and "Sex" columns into categorical variables and performed one-hot encoding.

## Model Training:

Dropped the "PassengerId" and "Cabin" columns as they were not needed for modeling.
Prepared the dataset for modeling with the target variable ("Survived") as the first column.
Split the dataset into input features (X) and the target variable (y).
Applied a machine learning model to train on the dataset.
