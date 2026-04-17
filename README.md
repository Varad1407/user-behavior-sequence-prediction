# User Behavior Sequence Prediction using Machine Learning

## Example Prediction

Given:
- Previous Product: X
- Current Product: Y

Predicted Next Product: Z

## Overview
This project predicts the next product a customer is likely to purchase based on their previous behavior.

## Dataset
- Online Retail Dataset
- Contains real-world transaction data of customers

## Approach
- Cleaned dataset by removing missing values and returns
- Sorted transactions based on time
- Created user sequences of purchased products
- Converted sequences into (previous, current, next) patterns
- Encoded product names into numerical values
- Trained a Random Forest model

## Model
- Random Forest Classifier
- Input: Previous product + Current product
- Output: Next product

## Result
- Accuracy: ~21%
- Multi-class prediction problem (many possible products)
- Model performs better than random baseline

## Conclusion
This project demonstrates how sequential data can be used to model customer behavior and simulate recommendation systems.
