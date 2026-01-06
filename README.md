# House Price Prediction using Linear Regression

This project implements a simple house price prediction model using Linear Regression.  
The goal of this project is to understand the end-to-end machine learning workflow using a clean and minimal dataset.

---

## Problem Statement
Predict the price of a house based on basic numerical features such as:
- Area of the house
- Number of rooms

---

## Dataset
The dataset contains the following columns:
- `area` – size of the house
- `rooms` – number of rooms
- `price` – house price (target variable)

The dataset is intentionally simple to focus on learning model behavior rather than heavy data cleaning.

---

## Approach
1. Loaded the dataset using Pandas
2. Performed basic data cleaning
3. Selected numerical features for training
4. Split the data into training and testing sets
5. Trained a Linear Regression model
6. Evaluated the model using Mean Squared Error (MSE)
7. Predicted prices for unseen houses
8. Displayed the top 5 houses based on predicted prices

---

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn

---

## Model Evaluation
The model is evaluated using **Mean Squared Error (MSE)**.  
Since house prices are large values, MSE appears numerically high, which is expected.  
The project focuses on understanding prediction behavior rather than optimizing accuracy.

---

## Example Prediction
The model can predict the price of a new house given its area and number of rooms.

---

## Key Learnings
- Understanding the complete machine learning pipeline
- Importance of feature selection
- Effect of limited features on model performance
- Difference between prediction accuracy and interpretability
