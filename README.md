# 🏥 Insurance Cost Prediction using Machine Learning

## 📌 Project Overview

This project uses Machine Learning to predict medical insurance charges based on customer details.

The model learns patterns from features like age, BMI, smoking status, gender, and number of children to estimate insurance costs.

## 🎯 Objective

The main objective of this project is to build a regression model that can accurately predict insurance charges.

## 📊 Dataset

The dataset contains customer information and their corresponding insurance charges.

### Dataset Features

| Feature | Description |
|---|---|
| age | Age of customer |
| sex | Gender of customer |
| bmi | Body Mass Index |
| children | Number of children |
| smoker | Smoking status |
| region | Residential area |
| charges | Insurance cost (Target Variable) |

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 🔄 Project Workflow

1. Import required libraries
2. Load dataset
3. Perform Exploratory Data Analysis (EDA)
4. Handle missing values and preprocessing
5. Split dataset into training and testing data
6. Train Machine Learning model
7. Make predictions
8. Evaluate model performance

## 🤖 Machine Learning Model

Algorithm Used:

### Linear Regression

Linear Regression is used because the target variable (`charges`) is continuous.

The model finds the relationship between input features and insurance cost.

## 📈 Model Evaluation

The model performance is measured using:

- R² Score

Example:

```python
model.score(X_test, y_test)
