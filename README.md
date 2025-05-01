# Pima-Indian-Diabetes-EDA-
The Pima Indian Diabetes dataset is a widely-used dataset for binary classification tasks, particularly to predict whether a patient is likely to develop diabetes based on diagnostic measures.
Exploratory Data Analysis (EDA)
The Pima Indian Diabetes dataset consists of medical diagnostic measurements of female patients of Pima Indian heritage. The objective is to predict whether a patient has diabetes (Outcome = 1) or not (Outcome = 0), based on various health-related attributes.

🔍 Dataset Summary
Total records: 768

Target variable: Outcome (binary classification)

Features-

Pregnancies: Number of times pregnant

Glucose: Plasma glucose concentration after 2 hours in an oral glucose tolerance test

BloodPressure: Diastolic blood pressure (mm Hg)

SkinThickness: Triceps skin fold thickness (mm)

Insulin: 2-hour serum insulin (mu U/ml)

BMI: Body Mass Index

DiabetesPedigreeFunction: Likelihood of diabetes based on family history

Age: Age in years

🧼 Data Cleaning Observations : 
Certain features (e.g., Glucose, BloodPressure, BMI, Insulin, SkinThickness) contain zero values which are medically implausible and likely represent missing data.

These values were either removed or replaced with more meaningful statistics (e.g., median).

📈 Key Distributions & Insights : 
Patients with diabetes (Outcome = 1) tend to have:

Higher glucose levels

Higher BMI

Higher age

Glucose shows the strongest correlation with the outcome variable.

A correlation heatmap revealed positive relationships between Outcome and features like Glucose, BMI, and Age.

⚖️ Class Imbalance
The dataset shows a mild class imbalance:

~65% patients are non-diabetic

~35% patients are diabetic

This is taken into account when evaluating model performance, particularly using recall and F1-score.

📌 EDA Summary :
EDA helped identify important features influencing diabetes prediction and uncovered the need for data preprocessing steps such as imputation and scaling. These insights informed feature selection and improved model performance.
