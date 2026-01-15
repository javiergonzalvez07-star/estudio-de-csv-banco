# 📊 Bank Customer Data Analysis (Python & Pandas)

## 📌 Project Overview

This project consists of an **exploratory data analysis (EDA)** of a real-world banking customer dataset using **Python** and **pandas**.  
It was developed as a **group academic project** for the course *Programming I* during the **first year of the Double Degree in Mathematical Engineering and Physics**.

The objective is to analyze customer behavior, clean and preprocess real data, explore statistical relationships between variables, and extract meaningful insights related to financial risk and customer activity.

---

## 🧑‍💻 Authors

- **Javier Gonzálvez Sempere**  
- Jairo Sánchez  
- Luis González  

---

## 🗂 Dataset

- **Source:** Kaggle (public dataset, independently selected by the authors)
- **Size:** 10,127 customers × 23 variables
- **Content:**  
  Demographic, financial, and behavioral information related to bank customers and credit card usage.

> ⚠️ The original CSV file may not be included in this repository due to licensing or sharing restrictions.  
> The analysis can be reproduced using the same dataset available on Kaggle.
Dataset link: <https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers>
---

## 🛠 Tools & Technologies

- Python  
- pandas  
- numpy  
- matplotlib  

---
## ▶️ How to Run

1. Clone the repository
2. Install dependencies:
   - `pip install pandas numpy matplotlib`
3. Open `bank_customers_data_analysis.ipynb` and run all cells.


## 🔧 Data Preprocessing

The dataset required several preprocessing steps to ensure consistency and statistical validity:

- Initial data inspection (shape, data types, head/tail)
- Detection and treatment of missing values and outliers
- Custom statistical imputation strategy:
  - **Median** for skewed distributions
  - **Mean** for symmetric distributions
- Conversion of categorical income ranges into numerical values
- Renaming columns to a cleaner and more maintainable format (`snake_case`)
- Removal of irrelevant or redundant variables

---

## 📈 Exploratory Data Analysis (EDA)

The exploratory analysis included:

- Descriptive statistics (mean, median, standard deviation) implemented through custom functions
- Visualization of distributions using histograms and boxplots
- Detection of outliers and unusual patterns
- Correlation analysis between numerical variables
- Heatmaps and scatter plots to identify linear and non-linear relationships

---

## 🔍 Key Findings

- **Variable Redundancy:**  
  A near-perfect linear correlation was found between *Credit Limit* and *Average Open to Buy*, indicating redundancy and potential multicollinearity in predictive models.

- **Customer Activity Patterns:**  
  The relationship between transaction count and total transaction amount revealed different customer profiles:
  - High-frequency, low-value users  
  - Moderate users  
  - Low-frequency, high-value users  

- **Financial Risk Indicators:**  
  An inverse relationship was identified between credit limit and utilization ratio, allowing early detection of customers at higher financial risk.

- **Synthetic Risk Indicators:**  
  New features were engineered to flag potential risk of churn or financial stress, transforming raw data into interpretable business indicators.

---

## ⚙️ Data Manipulation & Error Handling

The project also demonstrates core programming concepts through:

- Conditional filtering of data
- Creation of new columns based on multiple conditions
- Iteration using loops
- Use of `try-except` blocks to safely handle errors when processing or introducing new data
- Custom exception handling for invalid dataset structures

---

## 🎓 What I Learned

Through this project, I gained practical experience in:

- Working with real, imperfect datasets
- Applying statistical reasoning to data cleaning decisions
- Structuring an exploratory data analysis workflow
- Writing clearer and more maintainable data analysis code
- Connecting programming concepts with real-world data problems

---

## 📎 Notes

This is an **introductory academic project**, intended to demonstrate foundational skills in Python programming and data analysis rather than advanced modeling or machine learning.

---

### 🇪🇸 Resumen en español

**Análisis exploratorio de datos de clientes bancarios con Python (pandas).**  
Proyecto académico realizado en 1º de Ingeniería Matemática y Física.  
Incluye limpieza y preprocesado de datos reales, análisis estadístico, visualización, estudio de correlaciones y creación de indicadores de riesgo a partir de un dataset de Kaggle.
