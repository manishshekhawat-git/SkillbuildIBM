Telecom Customer Churn Analysis and AI-Based Churn Prediction
IBM SkillsBuild Data Analytics with AI Internship – Final Project
1. Project Overview
This project analyzes customer churn in a telecommunications dataset and develops machine-learning models to predict whether a customer is likely to churn.
The project demonstrates an end-to-end Data Analytics and AI workflow:
Data loading and inspection
Data cleaning and preprocessing
Exploratory Data Analysis (EDA)
Data visualization
Feature engineering
Classification modeling
Model evaluation
Feature/model interpretation
Business-oriented insights and recommendations
2. Dataset
Dataset: Telco Customer Churn
Source: Kaggle — IBM Sample Data Sets
Kaggle dataset: https://www.kaggle.com/datasets/blastchar/telco-customer-churn
The dataset contains 7,043 customer records and 21 columns. The target variable is Churn.
The data includes:
Customer demographics
Tenure
Phone and internet services
Online security and backup services
Device protection and technical support
Streaming services
Contract information
Payment method
Monthly and total charges
Churn status
3. Project Objective
The project addresses the following questions:
What customer characteristics and services are associated with churn?
Which customer groups have higher churn rates?
Can machine-learning models predict customer churn?
How do Logistic Regression, Decision Tree, and Random Forest compare?
What practical business insights can be derived from the analysis?
4. Technologies Used
Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
5. Project Structure
.
├── YourName_TelecomCustomerChurn.ipynb
├── requirements.txt
├── YourName_ProjectReport.docx
├── README.md
└── WA_Fn-UseC_-Telco-Customer-Churn.csv
The CSV dataset should be downloaded separately from Kaggle and placed in the same directory as the notebook.
6. Setup Instructions
Step 1 — Install Python
Use Python 3.9 or later.
Step 2 — Install dependencies
Open a terminal in the project folder and run:
pip install -r requirements.txt
Step 3 — Download the dataset
Download the Telco Customer Churn CSV from:
https://www.kaggle.com/datasets/blastchar/telco-customer-churn
Place:
WA_Fn-UseC_-Telco-Customer-Churn.csv
next to the Jupyter Notebook.
Step 4 — Start Jupyter
jupyter notebook
Open:
YourName_TelecomCustomerChurn.ipynb
and run the cells from top to bottom.
7. Data Processing
The notebook performs:
Dataset inspection
Duplicate checking
Missing-value checking
Conversion of TotalCharges from text to numeric
Handling of missing TotalCharges
Removal of the customer ID from the predictive feature set
Categorical encoding
Numerical scaling
Train/test splitting with stratification
8. Exploratory Analysis
The project examines:
Overall churn distribution
Tenure
Monthly charges
Total charges
Contract type
Internet service
Payment method
Paperless billing
Customer services
Churn by tenure group
Numerical correlations
9. Machine Learning
Three classification models are evaluated:
Logistic Regression
Decision Tree
Random Forest
The models are evaluated using:
Accuracy
Precision
Recall
F1-score
ROC-AUC
Confusion matrix
ROC curve
The notebook selects the model with the highest ROC-AUC for detailed evaluation.
10. Reproducibility
A fixed random_state=42 is used for the train/test split and machine-learning models where applicable.
The preprocessing steps are implemented inside scikit-learn pipelines to ensure that transformations are learned from the training data rather than leaking information from the test set.
11. Limitations
The dataset is an educational/sample dataset.
It represents a customer snapshot rather than a complete longitudinal history.
Statistical association does not establish causation.
Results may not generalize to another telecom provider or future customer population.
Model predictions should support analysis and prioritization, not automatically determine customer treatment.
12. Author
Student Name: Manish Shekhawat 
Program: IBM SkillsBuild Data Analytics with AI Internship 2026
Project: Telecom Customer Churn Analysis and AI-Based Churn Prediction
