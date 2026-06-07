# AI-Powered Farm Yield Forecasting & Logistics Planning System

## Project Overview

This project predicts future farm production using Machine Learning and helps agricultural operations teams plan transportation and logistics based on expected yield.

The system analyzes farm environmental conditions and predicts crop production for the upcoming week, estimates the required number of transportation trucks, and calculates expected revenue.

---

## Business Problem

Agricultural companies often face challenges in planning logistics and supply chain operations due to uncertainty in future production volumes.

Incorrect forecasting may result in:

* Transportation shortages
* Unused logistics resources
* Increased operational costs
* Product waste

This project aims to improve planning accuracy using Machine Learning.

---

## Dataset Features

* Temperature
* Humidity
* Rainfall
* Irrigation
* Fertilizer Usage
* Yield (Target Variable)
* Waste Rate

Dataset Duration:

* 730 Days (2 Years)

---

## Exploratory Data Analysis (EDA)

Performed data analysis and visualization using:

* Pandas
* Matplotlib
* Seaborn

Key analyses:

* Yield Trends Over Time
* Correlation Matrix
* Feature Relationships

---

## Machine Learning Models Tested

1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor
4. Gradient Boosting Regressor
5. XGBoost Regressor

---

## Model Performance

| Model             | R² Score |
| ----------------- | -------- |
| Linear Regression | 0.920    |
| Random Forest     | 0.895    |
| Gradient Boosting | 0.890    |
| XGBoost           | 0.884    |
| Decision Tree     | 0.860    |

Best Model:

Linear Regression

---

## Weekly Forecast Results

Expected Production: 599.49 tons

Required Trucks: 40

Expected Revenue: 7,193,877 EGP

Model Accuracy (R²): 92%

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Joblib
* Jupyter Notebook

---

## Future Improvements

* Real Weather API Integration
* Power BI Dashboard
* n8n Automation
* Email Alert System
* GIS Farm Mapping
* Real-Time Forecasting
