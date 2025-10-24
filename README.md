# Fraudulent_Claim_Detection

Detecting potentially fraudulent insurance claims using historical customer and claim data.

🎯 Objective
To develop a machine learning model that accurately identifies fraudulent insurance claims, with a specific focus on maximizing recall — ensuring that as many true fraud cases as possible are flagged for further investigation, even at the cost of increased false positives.

📁 Repository Structure
- Fraudulent_Claim_Detection_Shreyas_Somani.ipynb  # Solution notebook with code, visuals and analysis
- README.md                                                    # This file

🧠 Methodology
The approach followed in the notebook and final solution includes:

Data Cleaning & Preprocessing

Handling missing values, outliers, inconsistent categories

Fixing datatypes and removing redundancies

Exploratory Data Analysis (EDA)

Identifying feature patterns associated with fraud

Target likelihood analysis for categorical variables

Feature Engineering

Combining sparse categories

Encoding and scaling

Creating derived features

Train-Validation Split (70:30)

Ensuring stratification to preserve class balance

Resampling only applied to training data

Model Building & Evaluation

Tried multiple models including Logistic Regression and Random Forest

Applied hyperparameter tuning

Evaluated using Recall, F1 Score, and AUC

Model Selection

Logistic Regression was chosen for final deployment due to:

Recall = 82.35%

F1 Score = 0.5957

Balanced ability to detect fraud without overfitting

📊 Business Value
The model helps the insurance company:

Detect more fraudulent claims early

Minimize financial loss

Save time by flagging only risky claims for manual investigation

👨‍💻 Contributors
This project was developed by

Shreyas Somani



