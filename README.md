## Predicting Employee Attrition

### Project Overview

This project involves building a **classification model** to predict whether an employee is likely to leave a company. Using IBM's HR analytics dataset, this project performs data preprocessing, EDA, and model training using Logistic Regression to analyze key factors influencing attrition- as part of CodeClause Internship.

---

### Dataset Information

* **Dataset Name:** WA\_Fn-UseC\_-HR-Employee-Attrition.csv
* **Source:** IBM HR Analytics Dataset
* **Target Variable:** `Attrition` (Yes/No)
* **Features:** Age, MonthlyIncome, JobRole, EnvironmentSatisfaction, etc.
* **Samples:** 1,470 employees
* **Problem Type:** Binary Classification

---

### Objective

* Perform exploratory data analysis on HR attrition data
* Encode categorical features and prepare the dataset
* Build and evaluate a predictive model
* Derive insights into what factors influence employee attrition

---

### Tools & Technologies Used

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* Google Colab

---

### Key Visualizations

* Distribution of attrition across job roles
* Correlation heatmaps
* Boxplots comparing salary and satisfaction by attrition status
* Confusion matrix

---

### ML Workflow

1. Load dataset and inspect structure
2. Encode categorical columns with `LabelEncoder`
3. Drop irrelevant or redundant columns
4. Split into train/test sets (80/20)
5. Train model using `LogisticRegression()`
6. Evaluate performance with accuracy, classification report, confusion matrix

---

### Model Performance

* **Model Used:** Logistic Regression
* **Accuracy:** \~84% (may vary slightly)
* **Evaluation Metrics:** Precision, Recall, F1-Score
* **Confusion Matrix:** Visualized using heatmap

---

### Key Findings

* Job Role, Monthly Income, Environment Satisfaction, and Work-Life Balance were highly correlated with attrition.
* Employees in certain roles and with lower satisfaction levels were more likely to leave.
* While Logistic Regression provided a solid baseline, further improvements are possible with ensemble models.

---

### 📁 File Structure

```
Predicting-Employee-Attrition/
│
├── Attrition_Prediction_Gaurav.ipynb   # Complete Colab notebook
├── WA_Fn-UseC_-HR-Employee-Attrition.csv  # Dataset (if hosted)
├── README.md                           # Project documentation
```

---


