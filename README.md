# Bartender Tips Prediction

## Project Overview

This project demonstrates a complete Machine Learning workflow using Python, Pandas, Matplotlib, and Scikit-Learn.

The objective is to predict the amount of tips earned during a bartender's shift based on factors such as:

* Number of customers served
* Hours worked
* Number of drinks sold
* Whether the shift was on a weekday or weekend

A synthetic dataset of 100 shifts was created for learning and practice purposes.

---

## Dataset Features

| Feature      | Description                                 |
| ------------ | ------------------------------------------- |
| Customers    | Number of customers served during the shift |
| Hours_Worked | Length of shift in hours                    |
| Drinks_Sold  | Total drinks sold                           |
| Day_Type     | Weekday or Weekend                          |
| Tips         | Total tips earned (£) (Target Variable)     |

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* Jupyter Notebook

---

## Machine Learning Workflow

1. Generate and load the dataset
2. Perform exploratory data analysis (EDA)
3. Visualize relationships between variables
4. Encode categorical data
5. Split data into training and testing sets
6. Train a Linear Regression model
7. Generate predictions
8. Evaluate model performance using:

   * Mean Absolute Error (MAE)
   * R² Score
9. Predict tips for new shifts

---

## Example Prediction

Input:

* Customers: 75
* Hours Worked: 8
* Drinks Sold: 220
* Weekend Shift

Predicted Output:

* Estimated Tips: £102.30

---

## Learning Objectives

This project was built to practice fundamental Machine Learning concepts, including:

* Feature selection
* Train/Test Split
* Linear Regression
* Model Evaluation
* Data Visualization
* Making Predictions with trained models

---

## Future Improvements

* Increase dataset size
* Add additional features such as food sales and weather conditions
* Compare Linear Regression with other algorithms
* Perform feature importance analysis
* Build a classification model to predict high-tip vs low-tip shifts
