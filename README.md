# Telco_Churn_Prediction

# Project Description:

This project aims to predict customer churn based on customer behavior and service usage data. It involves preprocessing the dataset, balancing classes with SMOTE, training multiple machine learning models (Random Forest, XGBoost, LightGBM), and evaluating them using classification metrics and ROC-AUC scores.

# Problem Statement

1. Companies lose significant revenue when customers churn.

2. Predicting churn helps businesses take proactive steps to retain customers.

3. The dataset is highly imbalanced, which can mislead ML models.

# Technologies Used

1. Python (Pandas, Scikit-learn)

2. Imbalanced-learn (SMOTE)

3. XGBoost

4. LightGBM

5. Random Forest Classifier

6. Jupyter Notebook

# Dataset

1. Telco Customer Churn Dataset (Telco-Customer-Churn.csv)

2. Columns include customer demographics, service details, and churn status.

# Key Steps in the Project
🔹 1. Data Loading
Loaded dataset using pandas.

🔹 2. Data Preprocessing
Handled missing values (TotalCharges column had errors in numeric conversion).

Used LabelEncoder to encode categorical variables.

Scaled numerical features (tenure, MonthlyCharges, TotalCharges) using StandardScaler.

🔹 3. Handling Imbalanced Data
Used SMOTE to oversample the minority class (churned customers).

Balanced the training dataset to improve model fairness.

🔹 4. Train-Test Split
Split the dataset into training and testing sets (80%-20%) with stratification.

🔹 5. Model Training
Trained three models:

Random Forest

XGBoost

LightGBM

🔹 6. Model Evaluation
Evaluated models using:

Classification Report (Precision, Recall, F1-Score)

ROC-AUC Score (area under the ROC curve)



