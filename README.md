# HR Attrition Analysis

A comprehensive analysis of employee attrition using exploratory data analysis (EDA), visualization, and machine learning. This project identifies the factors influencing employee turnover and predicts the likelihood of attrition.

---

## 📝 Project Overview

- **Objective:** Understand the reasons behind employee attrition and build a predictive model.  
- **Data Source:** WA_Fn-UseC_-HR-Employee-Attrition dataset.  
- **Key Analyses:**  
  - Attrition distribution by department, gender, and job role  
  - Work-life balance and job satisfaction impact  
  - Salary analysis by job level and department  
  - Tenure and age distribution related to attrition  

---
## Main Approach

```mermaid
flowchart TD
    A[Data Collection] --> B[Data Understanding]
    B --> C[Exploratory Data Analysis (EDA)]
    C --> D[Data Preprocessing (Encoding, Skew, Remove NZV)]
    D --> E[Feature Selection & Engineering]
    E --> F[Model Building (Random Forest)]
    F --> G[Hyperparameter Tuning]
    G --> H[Model Evaluation (Accuracy, AUC)]
    H --> I[Visualization & Insights]
    I --> J[Conclusion & Recommendations]
---
## 📊 Visualizations

1. **Employee Tenure vs Attrition** – Histogram with overlay and box plot  
2. **Age Distribution by Attrition** – Box plot  
3. **Department & Job Role Attrition** – Grouped bar charts  
4. **Median Annual Salary by Job Level & Attrition** – Grouped bar charts  
5. **Feature Importance from Random Forest Model** – Top predictors of attrition  

---

## 🛠️ Technologies Used

- Python  
- Pandas, NumPy, Scipy  
- Plotly, Seaborn, Matplotlib  
- Scikit-learn (Random Forest Classifier)  
- ResearchPy (for t-tests)  

---

## 📈 Model Performance

- **Model:** Random Forest Classifier  
- **Key Features:** Age, income, tenure, job history  
- **Validation AUC:** 0.774  
- **Test AUC:** 0.816  
- **Conclusion:** Model can reliably predict likelihood of attrition; additional data and handling class imbalance could improve performance further.  

---

## 🔍 Key Insights

- 16% of employees left in the previous quarter, mainly from R&D.  
- Women had highest turnover in Human Resources.  
- Employees with low work-life balance had ~25% attrition rate.  
- Median salary of former employees was ~$2,000/month lower than current employees.  
- Variables like education level, performance rating, and gender were less significant in predicting attrition.  

---

## 💡 Future Improvements

- Collect more data on former employees to balance classes.  
- Explore additional ML models (XGBoost, Gradient Boosting).  
- Build an interactive dashboard for real-time HR insights.  

---
