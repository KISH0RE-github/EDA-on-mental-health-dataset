# Mental Health — Exploratory Data Analysis, Classification, and Regression

## Overview

This project performs a comprehensive **Exploratory Data Analysis (EDA)** and develops **predictive models** to study the relationship between technology usage and mental health indicators.
We analyze variables such as screen time, stress levels, sleep quality, and self-reported mental health to uncover insights into digital behavior and psychological well-being.

---

## Aim

To understand how daily technology habits (screen time, gaming hours, physical activity) influence mental health outcomes, and to develop predictive models for **mental health score** and **sleep hours** using machine learning techniques in **R**.

---

## Dataset Description

Each record in the dataset includes:

* User_ID — Unique identifier
* Age — Participant age
* Average Daily Screen Time (hrs)
* Gaming Hours (hrs)
* Self-reported Mental Health Score (1–4)
* Stress Level (1–3)
* Sleep Hours (hrs)
* Physical Activity Hours (hrs)

The dataset supports correlation and predictive studies between digital behavior and mental health patterns.

---

## Objectives

1. **EDA:**
   Analyze relationships between technology usage patterns and mental health indicators using descriptive statistics and visualizations.

2. **Regression:**
   Build predictive models (Linear Regression, Polynomial Regression, Random Forest, XGBoost) to forecast Sleep Hours.

3. **Classification:**
   Apply classification algorithms (Random Forest, SVM, Logistic Regression, Gradient Boosting) to categorize mental health states and analyze feature importance.

---

## Data Analysis Workflow

### 1. Data Preprocessing

* Import required libraries and dataset
* Handle missing values and clean data
* Validate data types and apply transformations
* Encode categorical variables (One-Hot, Label Encoding)

### 2. Exploratory Data Analysis (EDA)

* Analyze measures of central tendency and dispersion
* Perform correlation analysis (Pearson matrix)
* Visualize categorical vs numerical variables
* Conduct distribution fitting and normality testing:

  * Normal, Poisson, Exponential, and Gamma distributions
  * Q-Q plots, ECDF plots, and box plots

### 3. Statistical Testing

* **Chi-Square Test:** Independence of gender and stress level
* **Kolmogorov–Smirnov Test:** Normality test for sleep hours
* **Anderson–Darling Test:** Distribution validation

---

## Regression Analysis

**Goal:** Predict *Sleep Hours* using behavioral and demographic variables.

**Models Used:**

* Linear Regression
* Polynomial Regression (degrees 1–4)
* Random Forest Regressor
* Gradient Boosting Machine (GBM)
* XGBoost

**Evaluation Metrics:**

* RMSE (Root Mean Squared Error)
* MAE (Mean Absolute Error)
* R² Score

**Findings:**

* Higher-degree polynomial regression (degree 4) improved accuracy significantly.
* XGBoost and Random Forest showed the best generalization performance.

---

## Classification of Mental Health

**Objective:** Predict *Sleep Quality* and *Mental Health State* using multiple classification algorithms.

**Models Implemented:**

* Random Forest Classifier
* XGBoost Classifier
* Multinomial Logistic Regression
* Support Vector Machine (SVM)
* Decision Tree Classifier
* Gradient Boosting

**Evaluation Metrics:**

* Confusion Matrix
* Accuracy, Precision, Recall, and F1 Score
* Feature Importance Visualization

**Key Findings:**

* Ensemble models (Random Forest, XGBoost) outperformed individual classifiers.
* Technology usage hours, gaming hours, and physical activity had the highest influence.

---

## Visualization Highlights

* Correlation heatmaps
* Histogram and density plots
* Box plots and ECDF plots
* Feature importance plots
* Normality test visualizations (Q-Q plots)

---

## Conclusions

* Technology usage strongly correlates with stress and sleep quality.
* Screen time and gaming hours significantly affect mental health scores.
* Regression models effectively predict sleep hours, with ensemble methods performing best.
* Classification models accurately distinguish mental health states based on behavioral data.

**Key Insights:**

* Increased screen time is associated with higher stress levels.
* Sleep quality is a strong predictor of overall mental well-being.
* Data-driven insights can help identify high-risk individuals for early intervention.

---
