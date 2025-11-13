# Skinii® Weight-Loss Success Prediction  
Capstone Project – UC Berkeley AI & ML Program  
Author: Krista Thompson, Esq.

## Project Overview
This capstone project explores whether early-stage user behaviors can predict weight-loss success within the Skinii® telehealth and nutrition ecosystem. A synthetic dataset modeling realistic GLP-1 and lifestyle weight-loss patterns was generated for this analysis. The goal is to understand which behaviors most strongly influence results and to build a baseline predictive model.

## Business Problem
Skinii provides telehealth-guided weight management, GLP-1 support, and habit coaching. However, users experience varying levels of success depending on adherence and behavioral factors.

**Research Question:**  
Can we predict within the first 8 weeks whether a user will achieve at least 5% weight loss?

**Why this matters:**  
- Improves user success and retention  
- Enables personalized habit-nudging  
- Supports clinical monitoring  
- Reduces churn  
- Increases lifetime value  
- Strengthens Skinii’s competitive advantage in digital health

## Dataset Summary
A synthetic dataset of 5,000 Skinii users was generated inside the notebook.

**Features include:**  
age, bmi, activity_level, diet_type, glp1_use, weekly_checkins, water_intake, sleep_hours, stress_level

**Target:**  
outcome → 1 = achieved ≥5% weight loss, 0 = did not

The dataset is created programmatically inside the notebook and does not require uploading.

## Data Cleaning & Exploratory Data Analysis (EDA)
Completed tasks:
- Verified no missing values  
- Validated data types  
- Checked for duplicates  
- Outlier inspection  
- Summary statistics  
- Visualizations (histograms, bar plots, box plots, correlation heatmap)

**Key Insights:**
- Weekly check-ins show the strongest positive correlation with success  
- GLP-1 users achieve weight loss more consistently  
- Higher activity levels correlate with success  
- High stress predicts lower success  
- Sleep and water intake show moderate positive effects

## Baseline Machine Learning Model
Model developed: **Logistic Regression**

**Data preparation steps:**  
- One-hot encoding for categorical variables  
- Standard scaling of numeric features  
- Train/test split (75/25, stratified)

**Evaluation Metrics:**  
Accuracy and ROC-AUC

**Expected Performance Range:**  
- Accuracy: 0.72–0.80  
- ROC-AUC: 0.76–0.84  

**Interpretation:**  
Weekly check-ins, GLP-1 use, and activity level are strong positive predictors. Stress and BMI negatively influence outcomes. The baseline model successfully identifies high-risk users early.

## Repository Structure
capstone_part1_EDA/  
• Skinii_capstone.ipynb  
• README.md

## Actionable Findings for Skinii®
1. Encourage users to complete at least 3 weekly check-ins.  
2. Expand GLP-1 telehealth offerings, as GLP-1 usage strongly predicts success.  
3. Introduce stress-reduction tools in the app.  
4. Add hydration and sleep habit nudges.  
5. Implement a predictive risk-scoring system to personalize interventions.

## Next Steps (Module 24 / Final Capstone)
- Add additional models (Random Forest, Gradient Boosting, XGBoost, SVM)  
- Perform hyperparameter tuning  
- Add SHAP/feature-importance explanations  
- Build final optimized predictive model  
- Produce executive summary and final technical documentation  

## Contact
Krista Thompson, Esq.  
Founder, Skinii® & ThiinkMachine®
