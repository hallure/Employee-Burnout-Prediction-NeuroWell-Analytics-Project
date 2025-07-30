# Employee-Burnout-Prediction-NeuroWell-Analytics-Project

Overview
NeuroWell Analytics is a global leader in workplace well-being solutions, combining machine learning and psychological research to help companies reduce employee stress and improve productivity. Since 2015, they’ve partnered with organizations across various industries to deliver actionable mental health insights through data.

In this project, you'll use employee data to build predictive models that estimate burnout levels based on work environment, mental fatigue, and resource allocation.

🎯 Objective
Explore and understand burnout-related data

Preprocess and engineer relevant features

Build machine learning models to predict burnout (Burn Rate)

Provide insights and actionable recommendations for HR and leadership teams

📁 About the Dataset
Files:

train.csv

test.csv

Target Variable:

Burn Rate – rate of burnout or mental exhaustion

Key Features
Column Name	Description
Employee ID	Unique identifier for each employee
Date of Joining	Date the employee joined the company
Gender	Gender of the employee
Company Type	Type of company (e.g., Service-based, Product-based)
WFH Setup Available	Whether a proper remote work setup is available
Designation	Seniority level (coded numerically)
Resource Allocation	Daily work hours assigned
Mental Fatigue Score	Self-reported stress/fatigue level
Burn Rate	Target variable indicating burnout rate

🧠 Project Phases
🔎 Phase 1: Understanding the Problem
Research and summarize causes and consequences of employee burnout

Highlight the importance of predictive analytics in organizational well-being

📊 Phase 2: Exploratory Data Analysis (EDA)
Inspect structure and summary statistics

Visualize variable relationships (e.g., burnout vs. resource allocation)

Identify and plan for handling missing values

⚙️ Phase 3: Data Preprocessing
Encode categorical variables (e.g., Gender, Company Type)

Handle missing/inconsistent values

Normalize numeric columns (e.g., Resource Allocation)

Create new features like employee tenure from Date of Joining

🤖 Phase 4: Model Development
Train models like Linear Regression, Random Forest, Gradient Boosting

Evaluate using MAE, RMSE, and R²

Use hyperparameter tuning for performance improvement

📌 Phase 5: Insights & Recommendations
Interpret models using feature importance or SHAP values

Summarize burnout drivers and actionable insights

Recommend organizational changes to reduce burnout risk

🛠️ Tools & Libraries
Python (Pandas, NumPy)

Scikit-learn

Matplotlib / Seaborn

SHAP (for model interpretation)

✅ Status
Project includes modeling, interpretation, and solution recommendations for a real-world mental health challenge. Future work may involve dashboard development and deployment of predictive solutions for HR analytics.

