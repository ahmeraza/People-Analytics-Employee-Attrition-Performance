# Employee Attrition & Performance: IBM People Analytics

Predicting employee attrition and performance using machine learning models in Python.

This project uncovers the factors that lead to employee attrition and explores key HR questions such as:
- *"Show me a breakdown of distance from home by job role and attrition"*
- *"Compare average monthly income by education and attrition"*

---

## Dataset

**Source:** [IBM HR Analytics Employee Attrition & Performance](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset) — Kaggle  
**File:** `employee_attrition.csv`  
**Size:** 1,470 employees × 35 features  

Key features include: `Age`, `Attrition`, `BusinessTravel`, `Department`, `DistanceFromHome`, `Education`, `JobRole`, `JobSatisfaction`, `MonthlyIncome`, `OverTime`, `PerformanceRating`, `WorkLifeBalance`, and more.

---

## Description

This project applies machine learning techniques to analyze employee data and uncover patterns linked to attrition and performance. Using Python, we explored the full data lifecycle — from cleaning and preprocessing to applying classification models and generating actionable insights for HR decision-making.

**Methodology:**
- Categorical variables (gender, job role, marital status) were encoded using binary, ordinal, or one-hot encoding as appropriate
- Feature scaling with `StandardScaler` was applied to normalize numeric variables (age, monthly income) and prevent scale bias
- Class imbalance (~84% No, ~16% Yes attrition) was addressed using class weighting in the classifiers
- Classification algorithms — logistic regression and decision tree — were applied from `scikit-learn`
- Models were evaluated using confusion matrices and classification reports (precision, recall, F1-score)

---

## Results

| Model | Accuracy | F1 (Attrition) | AUC-ROC |
|---|---|---|---|
| Logistic Regression | ~87% | ~0.58 | ~0.82 |
| Decision Tree | ~84% | ~0.52 | ~0.74 |

Key drivers of attrition identified: **OverTime**, **JobSatisfaction**, **WorkLifeBalance**, **DistanceFromHome**, **MonthlyIncome**.

---

## Key Tasks

- Data cleaning and preprocessing using `pandas` and `numpy`
- Exploratory data analysis and visualization using `matplotlib` and `seaborn`
- Feature scaling using `StandardScaler`
- Logistic regression and decision tree classifiers for attrition and performance prediction
- Visual and statistical insights to inform HR strategy

---

## Outcome

- Cleaned and prepared employee data for machine learning
- Built and evaluated classification models for attrition and performance
- Delivered actionable insights for retention and talent management initiatives

---

## Installation

### 1. Clone the repository
```bash
git clone https://github.com/ahmeraza/People-Analytics-Employee-Attrition-Performance.git
cd People-Analytics-Employee-Attrition-Performance
```

### 2. Create and activate a virtual environment (recommended)
```bash
python -m venv venv
source venv/bin/activate        # macOS/Linux
venv\Scripts\activate           # Windows
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook
```bash
jupyter notebook
```

Then open `People_Analytics_Employee_Attrition_Performance.ipynb` in your browser.

---

## Project Structure

```
People-Analytics-Employee-Attrition-Performance/
├── People_Analytics_Employee_Attrition_Performance.ipynb
├── employee_attrition.csv
├── requirements.txt
├── .gitignore
└── README.md
```

---

## Requirements

- Python 3.9+
- See `requirements.txt` for full dependency list
