# Excelerate Data Analysis & Predictive Modeling

## Overview

This project explores and models learner engagement with Excelerate's educational programs. It involves extensive data cleaning, exploratory data analysis (EDA), feature engineering, and building a machine learning model to predict learner status.

---

## Technologies Used

- Python  
- Pandas & NumPy  
- Seaborn & Matplotlib  
- Scikit-learn  
- Imbalanced-learn (SMOTE)

---

## Data Cleaning

- Removed duplicates and standardized column names  
- Normalized inconsistent gender values  
- Converted date strings to datetime objects  
- Extracted features like age, signup month, and signup hour  
- Saved cleaned data to `cleaned_slu_data.csv`

---

## Feature Engineering

Created meaningful features such as:

- **Signup hour/weekday/quarter**  
- **Age buckets**  
- **Completion time in days**  
- **Opportunity duration**  
- **Completion status (boolean)**

---

## Exploratory Data Analysis

Insights derived include:

- Temporal signup and completion trends  
- Demographic-based engagement patterns (e.g., gender, age)  
- Identification of outliers and low-performing segments

Visualizations include:

- Line plots (signup/completion trends)  
- Box plots (age by gender, completion times)  
- Correlation heatmaps

---

## Machine Learning

A **Gradient Boosting Classifier** was trained to predict learner status using engineered features.

- **Handling imbalance** with SMOTE  
- **GridSearchCV** for hyperparameter tuning  

Metrics:  
- Accuracy: `72.1%`  
- ROC AUC: `0.89`

Other evaluations:

- Classification report  
- Confusion matrix  
- ROC curves for multiclass classification  
- Feature importance analysis

---

## Key Recommendations

- Target high-signup days for campaigns  
- Analyze outliers with long completion times  
- Support learners in low-completion demographics  
- Monitor performance by opportunity type

---

## Conclusion

This project demonstrates how EDA and ML modeling can uncover actionable insights to improve learner engagement and program outcomes.

---

## Contact

For questions or collaboration opportunities, please contact:

**Name:** Katlego Masela 

**Email:** maselakatlego513@gmail.com 

