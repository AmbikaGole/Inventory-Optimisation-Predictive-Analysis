# Inventory Optimization: Predicting Dead Stock Probability

## Overview
This project analyzes manufacturing inventory data across Australian warehouse facilities to classify items as "Dead Stock" (items with zero sales activity over several months) using machine learning models.

## Objectives
To identify key features influencing inventory obsolescence and build predictive models to support data-driven warehouse management and capital recovery.

## Dataset
Manufacturing Retailer Inventory Dataset (3,000 observations)

## Methodology

- Logistic Regression (Linear Classification)
- Decision Tree Classifier (Non-linear Classification)
- Feature engineering using One-Hot and Ordinal Encoding

## Key Results

- Decision Tree Accuracy: 96%
- Logistic Regression Accuracy: 94.3%
- Key predictive feature: % of Over 2 Year Stock

## Key Insights

- High inventory turn and lower stock age are the strongest indicators of healthy inventory.
- Decision Tree models better capture the non-linear relationship between warehouse location and stock demand.
- Predictive modeling enables proactive markdown strategies to reduce holding costs.

## Tools Used
- Language: Python
- Libraries: Pandas, NumPy, Scikit-learn, Matplotlib
- Environment: Jupyter Notebook
