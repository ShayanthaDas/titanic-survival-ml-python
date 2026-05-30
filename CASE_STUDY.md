# Titanic Survival Prediction – Case Study

## 1. Background

The Titanic disaster is one of the most studied datasets in machine learning. It contains passenger information and whether they survived or not.

This project uses that dataset to understand what factors influenced survival and how machine learning can be used for prediction.

---

## 2. Problem

The main question was simple:

Can we predict whether a passenger survived the Titanic disaster based on available features?

To answer this, we used classification models on structured passenger data.

---

## 3. Dataset

The dataset includes:

* Passenger ID
* Name
* Age
* Gender
* Ticket class (Pclass)
* Fare
* Cabin (if available)
* Number of family members onboard
* Survival status (target variable)

Some values were missing and needed cleaning before modeling.

---

## 4. Approach

### Data cleaning

* Filled missing age values
* Removed or handled missing cabin data
* Converted categorical variables into numerical form

### Exploratory analysis

Looked at:

* Survival rate by gender
* Survival rate by passenger class
* Age distribution of survivors and non-survivors

### Feature engineering

Created or adjusted features like:

* Family size
* Encoded gender and class
* Simplified categorical variables

---

## 5. Model building

Tested a few basic classification models:

* Logistic Regression
* Decision Tree
* Random Forest

Each model was evaluated using accuracy and basic performance metrics.

---

## 6. Findings

### Gender was the strongest factor

Females had a much higher survival rate compared to males.

---

### Passenger class mattered

People in first class had a better chance of survival compared to lower classes.

---

### Age played a role

Children had a slightly higher survival rate compared to adults.

---

### Model performance improved after cleaning

Better preprocessing improved accuracy more than changing the model itself.

---

## 7. Conclusion

This project shows how basic machine learning can be used to understand patterns in historical data.

Even a simple dataset like Titanic can reveal meaningful insights when analyzed properly.

---

## 8. What this project taught me

* How to handle missing data
* How to build and compare ML models
* How feature engineering affects results
* How to move from raw data to predictions

---
