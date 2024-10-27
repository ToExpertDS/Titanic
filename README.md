# Titanic Survival Prediction

This project is a machine learning analysis on the Titanic dataset to predict survival using various classification models. The dataset comes from the famous [Titanic dataset](https://www.kaggle.com/c/titanic).

## Models Used:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Naive Bayes Classifier

The goal is to select the best-performing model and evaluate it on the test data.

## Dataset
The dataset used for this project is the Titanic passenger data, which includes features such as:
- `Pclass`: Passenger class
- `Sex`: Gender of the passenger
- `Age`: Age of the passenger
- `SibSp`: Number of siblings or spouses aboard
- `Parch`: Number of parents or children aboard
- `Fare`: Fare paid by the passenger
- `Embarked`: Port of embarkation (S, C, Q)

The target variable is `Survived`, which indicates whether the passenger survived (1) or not (0).

## Preprocessing Steps:
1. Dropped irrelevant columns (`Name`, `Ticket`, `Cabin`).
2. Filled missing values in `Age` with the mean and in `Embarked` with the most common value.
3. Converted categorical variables such as `Sex` and `Embarked` into numerical values.
4. Standardized the dataset for consistent scaling across models.

## Model Evaluation:
We tested four different models on the Titanic dataset:
- **Logistic Regression**
- **Decision Tree**
- **Random Forest**
- **Naive Bayes**

After training and evaluating the models, the best performing model was chosen based on its accuracy on the test set.

## Results:
- The best model was `Decision Tree` with an accuracy of 0.82 on the test set.
- A detailed classification report and confusion matrix are provided in the output.

## How to Run:
1. Clone the repository:
