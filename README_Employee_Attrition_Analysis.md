
# 🧠 Employee Attrition Prediction & Analysis  

### 📊 Predicting Employee Turnover Using Python and HR Analytics  

This project analyzes employee attrition trends and predicts which employees are at risk of leaving the organization.  
It uses **data cleaning, visualization, and machine learning (Logistic Regression)** in Python, along with insights ready for a **Power BI dashboard**.  

---

## 🚀 Project Overview  

Employee retention is a key challenge in HR analytics.  
Using the IBM HR dataset, this project aims to:  
✅ Understand key drivers of attrition  
✅ Build a predictive model for employee turnover  
✅ Provide actionable insights via data visualization  

---

## 🧰 Tech Stack  

| Category | Tools Used |
|-----------|------------|
| **Language** | Python (Jupyter Notebook) |
| **Libraries** | Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn |
| **Visualization** | Power BI |
| **Dataset** | [IBM HR Analytics Employee Attrition Dataset (Kaggle)](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset) |

---

## 📁 Project Structure  

```
Employee-Attrition-Analysis/
│
├── project.ipynb                     ← Jupyter Notebook (EDA + Model)
├── cleaned_employee_attrition.csv     ← Cleaned dataset for Power BI
├── WA_Fn-UseC_-HR-Employee-Attrition.csv  ← Original dataset
├── requirements.txt                   ← Python dependencies
└── README.md                          ← Documentation
```

---

## 📈 Workflow  

### 1️⃣ Data Preprocessing  
- Loaded dataset and handled missing values  
- Cleaned categorical and numeric data  
- Encoded categorical columns using Label Encoding  

### 2️⃣ Exploratory Data Analysis (EDA)  
- Analyzed demographic trends (age, gender, department)  
- Visualized attrition by department, salary, and job satisfaction  
- Created correlation heatmaps and boxplots for insights  

### 3️⃣ Model Development  
- Scaled data using StandardScaler  
- Trained **Logistic Regression model**  
- Evaluated with accuracy, confusion matrix, and ROC curve  

### 4️⃣ Visualization  
- Exported cleaned dataset for Power BI  
- Designed Power BI dashboard with KPIs, charts, and trends  

---

## 📊 Key Visuals in Power BI  

| KPI | Description |
|-----|--------------|
| 💼 **Attrition Rate** | Percentage of employees who left |
| 💰 **Average Monthly Income** | Financial trend across departments |
| 🕒 **Average Tenure** | Retention duration insights |
| 📈 **Satisfaction vs Attrition** | Relationship analysis |
| 🧩 **Stacked Area Chart** | Attrition trend by Tenure & Department |

---

## 🧩 Key Insights  

- Attrition is **highest in Sales and HR** departments.  
- Employees with **low job satisfaction** and **high overtime** are more likely to leave.  
- **Younger employees (25–35 yrs)** show higher turnover rates.  
- Attrition peaks between **2–4 years of service**, suggesting mid-level burnout.  

---

## 🧠 Model Performance  

| Metric | Score |
|---------|-------|
| **Accuracy** | ~83% |
| **Precision** | ~0.79 |
| **Recall** | ~0.76 |
| **ROC-AUC Score** | Visualized using `RocCurveDisplay` |

---

## 🧮 Installation  

Clone this repo and install dependencies:  

```bash
git clone https://github.com/Pravs2025/Employee-Attrition-Analysis.git
cd Employee-Attrition-Analysis
pip install -r requirements.txt
```

Then open the notebook:
```bash
jupyter notebook project.ipynb
```

---

## 🧑‍💼 Author  

**Pravallika G**  
📍 Data Analyst | Python | SQL | Power BI  
🔗  www.linkedin.com/in/pravallika-ganta-67739538a
📧 pravallikaganta2025@gmail.com 

---

## 🌟 Highlights  

- End-to-End HR Analytics pipeline (Python + Power BI)  
- Predictive modeling integrated with visual insights  
- Business-focused storytelling for retention strategy  
