# Titanic-Survival-Prediction
Overview
This project aims to predict the survival of passengers aboard the Titanic using machine learning techniques. By analyzing the Titanic dataset, which contains information about passengers' demographics and survival status, we explore various models to predict whether a passenger survived or not.

Dataset
The Titanic dataset consists of 891 rows and 12 columns, containing both numerical and categorical variables. Here's a brief overview of the columns:

PassengerId: Unique identifier for each passenger
Survived: Survival status (0 = Did not survive, 1 = Survived)
Pclass: Passenger class (1st, 2nd, or 3rd)
Name: Passenger's name
Sex: Passenger's gender
Age: Passenger's age
SibSp: Number of siblings/spouses aboard
Parch: Number of parents/children aboard
Ticket: Ticket number
Fare: Ticket fare
Cabin: Cabin number
Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

Project Structure
Exploratory Data Analysis (EDA): We begin by exploring the dataset to understand its structure and relationships between variables. This includes visualizations and statistical summaries to gain insights into the data.
Data Preprocessing: We handled missing values and perform feature engineering to prepare the data for modeling. This involves strategies such as imputation, encoding categorical variables, and scaling numerical features.

Models for Analysis: We explore multiple machine learning models, including:
Random Forest
Decision Trees
Logistic Regression
K-Nearest Neighbors (KNN)

Evaluation: Each model is evaluated using classification metrics such as precision, recall, and F1-score. Confusion matrices are also used to assess the model's performance.
Results
Random Forest Model: Achieved an accuracy of 79% with balanced performance in classifying both survival and non-survival cases.
Decision Tree Model: Achieved an accuracy of 74% with reasonable performance, although slightly lower than the Random Forest model.
Logistic Regression and KNN Models: These models achieved accuracies of 81% and 75%, respectively, with varying performance in precision, recall, and F1-score.

Conclusion
The analysis of the Titanic dataset provided valuable insights into factors influencing passenger survival. Through data exploration, preprocessing, and modeling techniques, we gained a deeper understanding of the dataset’s structure and predictive capabilities. This project demonstrates the power of data analysis and machine learning in uncovering patterns and making predictions from historical data.

