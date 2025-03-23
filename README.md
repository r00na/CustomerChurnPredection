Customer Churn Analysis

Overview

This project analyzes customer churn using machine learning techniques. The dataset used is Telco Customer Churn, which contains customer details and their churn status. The goal is to build a model that predicts whether a customer is likely to churn.

Dataset

Source: Telco Customer Churn Dataset

Features and Processing

Data Cleaning: Handling missing values, converting categorical variables using Label Encoding

Feature Scaling: Min-Max Scaling for numerical columns (tenure, MonthlyCharges, TotalCharges)

Handling Class Imbalance: Used SMOTE to balance the Churn class distribution

Exploratory Data Analysis (EDA)

Distribution of Churn variable

Boxplots to detect outliers

Chi-square test to determine feature significance

Machine Learning Model

Model Used: Random Forest Classifier

Evaluation Metrics:

Accuracy Score

Classification Report (Precision, Recall, F1-Score)

Confusion Matrix

Train-Test Split: 80% training, 20% testing

Installation & Requirements

Prerequisites

Ensure you have Python and the following libraries installed:

pip install pandas numpy seaborn matplotlib scikit-learn imbalanced-learn

Running the Project

Clone the repository:

git clone https://github.com/yourusername/customer-churn-analysis.git

Navigate to the project directory:

cd customer-churn-analysis

Run the script:

python customer_churn.py

