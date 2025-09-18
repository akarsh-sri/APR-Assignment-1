# Assignment 1: Heart Attack Prediction using Logistic Regression
This is a submission for Assignment 1. It includes implementation of the **Logistic Regression** algorithm in Python to predict the likelihood of a heart attack.

## Dataset
The assignment uses the **Heart Attack Analysis & Prediction Dataset**, sourced via Google Dataset Search and hosted on Kaggle. It contains 14 attributes, including age, sex, cholesterol levels, and a binary target variable indicating the presence of heart disease.

## Algorithm
The Logistic Regression algorithm was built using only the NumPy library. The implementation includes:
- **Sigmoid Function**: To map outputs to a probability score.
- **Cost Function (Log Loss)**: To quantify the model's error.
- **Gradient Descent**: To iteratively optimize the model's parameters.

## How to Run
1.  Clone this repository.
2.  Download the dataset from [Kaggle](https://www.kaggle.com/datasets/mfarhaannazirkhan/heart-dataset?resource=download) and place `heart.csv` in the root directory.
3.  Ensure you have the required Python libraries:
    ```bash
    pip install numpy pandas scikit-learn matplotlib
    ```
4.  Run the script from your terminal:
    ```bash
    python logistic_regression_heart.py
    ```
