# Titanic-Classification
1.**Overview**
This project aims to predict the survival of passengers aboard the Titanic using machine learning techniques. The dataset used in this project is sourced from a Kaggle competition and contains information about passengers such as their age, gender, ticket class, fare, and survival status.

2.**Data Preprocessing**
Handled missing values by dropping the 'Cabin' column and filling missing values in the 'Embarked' and 'Age' columns.
Conducted feature engineering by creating a new feature 'family_size' representing the size of the passenger's family onboard.
Encoded categorical variables using one-hot encoding for 'Pclass', 'Sex', 'Embarked', and 'family_size'.

3.**Exploratory Data Analysis (EDA)**
Analyzed survival rates based on features such as 'Pclass', 'Sex', 'Embarked', and 'family_size'.
Utilized distribution plots to visualize the distribution of 'Age' and 'Fare' based on survival status.

4.**Model Training**
Implemented a Decision Tree Classifier for predicting survival.
Split the data into training and testing sets.
Fit the model to the training data and evaluated its performance using accuracy_score.
Generated predictions for survival on the test set.

5.**Results**
Achieved an accuracy of (0.8212290502793296) on the test set.
Outputted predictions in the form of a CSV file ('titanic survived.csv') containing 'PassengerId' and 'Survived' columns.

6.**Conclusion**
In conclusion, this project demonstrates the application of machine learning techniques for predicting survival on the Titanic dataset. The insights gained from exploratory analysis and model training provide valuable information about factors influencing survival rates. Further improvements could involve exploring different machine learning algorithms and fine-tuning model parameters to enhance prediction accuracy.
