# Employee Attrition & Performance: IBM People Analytics 

The dataset uncover the factors that lead to employee attrition and explore important questions such as ‘show me a breakdown of 
distance from home by job role and attrition’ or ‘compare average monthly income by education and attrition’.

## Description

This project applies machine learning techniques to analyze employee data and uncover patterns linked to attrition and performance. 
Using Python, we explored the data lifecycle from cleaning and preprocessing to applying classification models and generating 
actionable insights for HR decision-making.

This transformation ensured the employee dataset was machine-readable and preserved categorical distinctions critical for analysis. 
Categorical variables, such as gender, job role, and marital status, were encoded using binary, ordinal, or one-hot encoding as 
appropriate. We applied feature scaling with StandardScaler to normalize numeric variables (e.g., age, monthly income) and prevent 
variables with larger scales from disproportionately influencing the model. Once preprocessed, we applied classification algorithms 
including logistic regression and decision trees from scikit-learn to predict attrition likelihood and categorize employee performance. 
We evaluated model performance using confusion matrices and classification reports, identifying precision and recall for both attrition 
and high-performance classes. This analysis revealed critical drivers of attrition, such as job satisfaction and work-life balance, 
and highlighted patterns in high-performance employees. The models provided HR with a data-backed foundation for designing retention 
strategies and performance improvement plans.

Key tasks include:

- Data cleaning and preprocessing using pandas and numpy
- Exploratory data analysis and visualization using matplotlib and seaborn
- Feature scaling using StandardScaler
- Applied logistic regression and decision tree classifiers for attrition and performance prediction
- Generated visual and statistical insights to inform HR strategy

## Outcome
- Cleaned and prepared employee data for machine learning
- Built and evaluated classification models for attrition and performance
- Delivered actionable insights for retention and talent management initiatives

## Installation

To set up this project locally:
1. Clone the repository:
   ```bash
   git clone https://github.com/ahmeraza/People-Analytics-Employee-Attrition-Performance.git
```