# DevelopersHub-Corporation-Remote-Internship
Data Science &amp; Analytics Internship Tasks

# Data Analysis and Machine Learning Tasks (Mini Projects)

This repository contains five beginner-to-intermediate level data analysis and machine learning tasks, each focusing on real-world datasets and covering key data science skills such as data cleaning, visualization, regression/classification modeling, and evaluation.

---

## 📌 Task 1: Exploring and Visualizing the Iris Dataset

**Objective:**  
Understand how to read, summarize, and visualize a dataset.

**Approach:**  
- Loaded the Iris dataset using seaborn.
- Performed basic structure inspection with `.shape`, `.columns`, and `.head()`.
- Visualized feature relationships using scatter plots, histograms, and boxplots.

**Results & Insights:**  
- Petal length and width were highly discriminative between species.
- Model trained with Logistic Regression achieved over 95% accuracy.

---

## 📌 Task 2: Credit Risk Prediction

**Objective:**  
Predict whether a loan applicant is likely to default on a loan.

**Approach:**  
- Cleaned missing values in loan-related features.
- Explored variables like income, education, and loan amount through boxplots and histograms.
- Trained a Logistic Regression model and evaluated with accuracy and confusion matrix.

**Results & Insights:**  
- Higher income and credit history were strong indicators of loan approval.
- The model showed good predictive performance with clear class separability.

---

## 📌 Task 3: Bank Customer Churn Prediction

**Objective:**  
Identify customers who are likely to leave the bank.

**Approach:**  
- Encoded categorical features like geography and gender.
- Trained a Decision Tree classifier on encoded data.
- Analyzed feature importance to identify churn influencers.

**Results & Insights:**  
- Age, credit score, and balance had significant influence on churn.
- Feature importance helped reveal key customer segments at risk.

---

## 📌 Task 4: Predicting Insurance Claim Amounts

**Objective:**  
Estimate the medical insurance claim amount based on personal data.

**Approach:**  
- Visualized impact of BMI, age, and smoking on charges.
- Trained a Linear Regression model.
- Evaluated predictions using MAE and RMSE.
- Optionally classified charges into high/low for confusion matrix and F1-score.

**Results & Insights:**  
- Smoking and BMI had a major impact on claim amounts.
- Linear regression provided reasonably accurate estimates (low MAE and RMSE).

---

## 📌 Task 5: Personal Loan Acceptance Prediction

**Objective:**  
Predict which customers are likely to accept a personal loan offer.

**Approach:**  
- One-hot encoded features like job, marital status, and contact method.
- Trained a Decision Tree model.
- Analyzed customer segments and top influencing features.

**Results & Insights:**  
- Features like previous campaign contact, duration, and job type significantly influenced loan acceptance.
- Model achieved high accuracy and provided clear feature importance visualization.

---

## 🔧 Technologies Used

- Python 3
- Pandas, Seaborn, Matplotlib
- Scikit-learn
- Jupyter Notebook

---

---

## ✅ Summary

These mini-projects demonstrate essential data science steps including loading data, exploratory data analysis, feature engineering, predictive modeling, and evaluation. They serve as a great foundation for real-world machine learning problems.

