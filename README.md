# 🚢 Titanic Survival Predictor

A Machine Learning project built using Python and Scikit-learn to predict whether a passenger survived the Titanic disaster.

## Project Overview

This project uses the Titanic dataset to predict passenger survival based on features such as:

* Passenger Class (Pclass)
* Sex
* Age
* Number of Siblings/Spouses (SibSp)
* Number of Parents/Children (Parch)
* Fare
* Embarked Port

The project helped me learn how to work with real-world data, perform data cleaning, handle missing values, encode categorical features, and train a Random Forest model.

---

## Dataset

The dataset contains passenger information from the Titanic.

Target Variable:

```text
Survived
```

Where:

```text
0 = Did Not Survive
1 = Survived
```

---

## Machine Learning Concepts Used

* Classification
* Features and Labels
* Train-Test Split
* Missing Value Handling
* Feature Selection
* Label Encoding
* Random Forest Classifier
* Feature Importance
* Model Evaluation

---

## Data Cleaning Performed

### Removed Columns

The following columns were removed because they were either identifiers or contained too many missing values:

* PassengerId
* Name
* Ticket
* Cabin

### Missing Values

Missing values in:

* Age
* Fare

were filled using the median value.

---

## Feature Encoding

Categorical features were converted into numerical values.

### Sex

```text
male   → 0
female → 1
```

### Embarked

```text
S → 0
C → 1
Q → 2
```

---

## Features Used

```text
Pclass
Sex
Age
SibSp
Parch
Fare
Embarked
```

Target:

```text
Survived
```

---

## Algorithm Used

### Random Forest Classifier

Random Forest combines multiple Decision Trees and uses voting to make final predictions.

Advantages:

* Reduces overfitting
* Improves prediction performance
* Handles complex patterns in data

---

## Feature Importance

The trained model identified the following important features:

```text
Sex      → Most Important
Fare
Age
Parch
Embarked
SibSp
Pclass
```

The feature **Sex** had the highest importance score and contributed the most to survival prediction.

---

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Jupyter Notebook
* Anaconda

---

## What I Learned

Through this project I learned:

* Data Cleaning
* Handling Missing Values
* Feature Encoding
* Random Forest Classifier
* Feature Importance
* Working with Real-World Datasets

---

## Future Improvements

* Compare Random Forest with Logistic Regression
* Perform Hyperparameter Tuning
* Use Cross Validation
* Create Visualizations for Feature Importance

---

## Author

Banty Kumar

Electrical Engineering Undergraduate at NIT Patna

Learning Machine Learning through hands-on projects and practical implementation.
