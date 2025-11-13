# Capstone Project — Part 1: Exploratory Data Analysis (EDA)

**Course:** UC Berkeley AI & Machine Learning Program  
**Module:** 20.1 — Initial Report and Exploratory Data Analysis (EDA)  
**Student:** Krista Thompson, Esq.  
**Brand Dataset:** Skinii® Synthetic Telehealth and Nutrition Data  

---

## 🔍 Project Overview

This is the first phase of the Capstone Project, focused on **data cleaning**, **exploratory data analysis (EDA)**, and establishing a **baseline machine learning model**.  

**Research Question:**  
How can AI-driven analysis of telehealth and nutrition data improve patient outcomes and personalized product recommendations within the Skinii® ecosystem?

**Dataset:**  
A **synthetic dataset** representing Skinii® members' health and lifestyle metrics (5,000 records).  
It includes attributes such as age, BMI, activity level, diet type, GLP-1 use, sleep, water intake, and stress level — along with a target variable representing positive wellness outcomes.  

> ⚙️ *This dataset is generated automatically inside the notebook using NumPy and pandas — no external CSV upload is required for replication.*

---

## 📊 Key Findings

- Higher **activity levels**, **consistent GLP-1 use**, and **lower stress** are strongly correlated with positive health outcomes.  
- **BMI**, **sleep hours**, and **weekly check-ins** show the most predictive numerical relationships.  
- Clear relationships emerged between lifestyle patterns and overall outcome probability.  

These insights validate the dataset’s structure and confirm strong predictive relationships for further modeling.

---

## 🧠 Baseline Model

**Model Used:** Logistic Regression (Baseline Classifier)  
**Goal:** Predict wellness outcomes using Skinii® health and lifestyle data.  

**Evaluation Metrics:**  
- Accuracy  
- ROC-AUC  
- Precision  
- Recall  
- F1 Score  

A **ROC curve** and **confusion matrix** were included for model evaluation.  
This baseline model will serve as the foundation for advanced model comparison in Capstone Part 2 (Module 24).  

---

## 📁 Repository Contents

| File | Description |
|------|--------------|
| `capstone_part1_EDA.ipynb` | Main notebook with EDA, feature engineering, and baseline model |
| `README.md` | Summary report of findings and methodology |

---

## 🔗 Notebook Access

📘 **Open in Google Colab:**  
[**Open in Colab**](https://colab.research.google.com/github/ThiinkCo/UC-Berkeley-AI-Course/blob/main/capstone_part1_EDA/capstone_part1_EDA.ipynb)

📁 **GitHub Folder:**  
[**View Repository Folder**](https://github.com/ThiinkCo/UC-Berkeley-AI-Course/tree/main/capstone_part1_EDA)

---

## 🧩 Next Steps

1. Extend feature engineering and model tuning (Random Forest, Gradient Boosting).  
2. Apply SHAP and feature importance for interpretability.  
3. Translate predictive insights into business strategy for Skinii® telehealth and product personalization.  
4. Develop executive-level visual summaries and dashboards for non-technical stakeholders.  

