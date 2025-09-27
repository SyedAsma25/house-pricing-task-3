# house-pricing-task-# Linear Regression on Housing Dataset

## Overview

This project demonstrates how to apply **Linear Regression** on a housing dataset using Python and scikit-learn.
The task includes:

1. Importing and preprocessing the dataset.
2. Splitting the data into training and testing sets.
3. Fitting a Linear Regression model.
4. Evaluating model performance using MAE, MSE, and R² score.
5. Plotting a regression line for `area` vs `price` and interpreting the coefficients.

---

## Dataset

* **File:** `Housing.csv`
* **Target variable:** `price`
* **Features:** Mix of numerical (e.g., area, bedrooms, bathrooms) and categorical (e.g., mainroad, furnishingstatus).

---

## Requirements

Install the required dependencies:

```bash
pip install pandas scikit-learn matplotlib
```

---

## Steps

### 1. Import and Preprocess

* Load dataset with Pandas.
* Encode categorical features using OneHotEncoder.

### 2. Train-Test Split

* Split data into 80% training and 20% testing.

### 3. Fit Linear Regression

* Train a Linear Regression model using scikit-learn.

### 4. Evaluate

Metrics used:

* **MAE (Mean Absolute Error)**
* **MSE (Mean Squared Error)**
* **R² Score**

### 5. Plot and Interpret

* Plot regression line for **area vs price**.
* Interpret slope and intercept.

---

## Results

* **MAE:** ~9.7 Lakhs
* **R² Score:** ~0.65
* **Coefficient (slope for area):** ~425 → Each additional unit of area increases price by ~₹426.
* **Intercept:** ~₹25,12,254 → Base price when area = 0.

---

## Usage

Run the notebook:

```bash
jupyter notebook Linear_Regression_Housing.ipynb
```

Or run as Python script:

```bash
python linear_regression_housing.py
```
3
