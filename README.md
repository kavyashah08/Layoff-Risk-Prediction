# 🤖 AI Impact on Jobs: Layoff Risk Prediction

A Machine Learning project that predicts the risk of employee layoffs based on factors such as AI adoption, task automation, job role characteristics, experience, and workplace requirements.

## 📌 Project Overview

With the increasing adoption of Artificial Intelligence across industries, many job roles are undergoing significant transformation. This project aims to analyze various job-related factors and predict the likelihood of layoffs using Machine Learning techniques.

The project involves:

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Training & Evaluation
- Comparison of Multiple ML Algorithms
- Feature Importance Analysis

---

## 📊 Dataset Information

- Total Records: **20,000**
- Features: **15**
- Target Variable: **Layoff_Risk**

### Features Used

- Age
- Industry
- Job Role
- Years of Experience
- AI Adoption Level
- AI Usage Hours Per Week
- Number of AI Tools Used
- AI Training Hours
- Education Level
- Company Size
- Job Level
- Human Interaction Level
- Creativity Requirement
- Tasks Automated Percentage
- Routine Task Percentage

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- Joblib

---

## 📈 Data Preprocessing

The following preprocessing steps were performed:

- Checked for missing values
- Checked for duplicate records
- Data type validation
- Label Encoding of categorical features
- Correlation Analysis
- Train-Test Split

---

## 🔍 Exploratory Data Analysis

EDA was performed to understand:

- Feature distributions
- Correlation between variables
- Impact of AI adoption on layoff risk
- Importance of automation-related features

---

## 🤖 Models Trained

### 1. Logistic Regression

Accuracy: **83.82%**

### 2. Random Forest Classifier

Accuracy: **88.92%**

### 3. XGBoost Classifier

Accuracy: **93.00%** ✅

XGBoost achieved the best performance and was selected as the final model.

---

## 🏆 Model Performance

| Model | Accuracy |
|---------|----------|
| Logistic Regression | 83.82% |
| Random Forest | 88.92% |
| XGBoost | **93.00%** |

---

## 📌 Key Insights

The analysis revealed that the most influential factors affecting layoff risk were:

- Tasks Automated Percentage
- Routine Task Percentage
- Creativity Requirement
- AI Usage Hours Per Week
- Number of AI Tools Used
- AI Training Hours

Jobs involving repetitive and highly automatable tasks showed a higher risk of layoffs, while roles requiring creativity and human interaction demonstrated lower risk.

---

## 💾 Model Saving

The final XGBoost model was saved using Joblib for future deployment and inference.

```python
import joblib

joblib.dump(xgb, "layoff_risk_xgboost.pkl")
```

---

## 🚀 Future Improvements

- Deploy using Streamlit
- Real-time Layoff Risk Prediction App
- Hyperparameter Tuning
- Feature Selection Optimization
- Advanced Model Explainability using SHAP

---

## 📂 Project Structure

```
Layoff-Risk-Prediction/
│
├── ai-impact-jobs-layoff-risk-dataset.csv
├── layoff_risk_xgboost.pkl
├── notebook.ipynb
├── README.md
├── requirements.txt
```

---

## 👨‍💻 Author

Kavy Shah

2nd Year CSE Undergraduate @ VIT Bhopal

Aspiring AI Engineer | Machine Learning Enthusiast | Building AI-Driven Solutions

---

### ⭐ If you found this project useful, consider giving it a star!
