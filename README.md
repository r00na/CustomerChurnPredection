# 📉 Customer Churn Analysis

## 🧾 Overview

This project analyzes customer churn using machine learning techniques.
The dataset used is the **Telco Customer Churn** dataset, which contains customer details and their churn status.

- 🎯 **Goal:** Build a model that predicts whether a customer is likely to churn.

## 🧹 Features & Processing

* 🔍 **Data Cleaning:**

  * Handled missing values
  * Converted categorical variables using Label Encoding

* 📏 **Feature Scaling:**

  * Applied Min-Max Scaling to numerical columns:

    * `tenure`, `MonthlyCharges`, `TotalCharges`

* ⚖️ **Handling Class Imbalance:**

  * Used **SMOTE** to balance the `Churn` class distribution


## 📊 Exploratory Data Analysis (EDA)

* 📌 Distribution of Churn variable
* 📦 Boxplots to detect outliers
* 🧪 Chi-square test to determine feature significance


## 🤖 Machine Learning Model

* **Model Used:**

  * ✅ Random Forest Classifier

* **Evaluation Metrics:**

  * 📈 Accuracy Score
  * 🧾 Classification Report (Precision, Recall, F1-Score)
  * 🧮 Confusion Matrix

* **Train-Test Split:**

  * 80% training
  * 20% testing
