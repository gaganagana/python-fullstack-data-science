# Data Science & Machine Learning Portfolio

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg?logo=python)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Library-Pandas-150458.svg?logo=pandas)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/Library-NumPy-013243.svg?logo=numpy)](https://numpy.org/)
[![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-F7931E.svg?logo=scikitlearn)](https://scikit-learn.org/)
[![Visualization](https://img.shields.io/badge/Visualization-Matplotlib%20%7C%20Seaborn-success.svg)](https://seaborn.pydata.org/)
[![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-F37626.svg?logo=jupyter)](https://jupyter.org/)

This repository contains practical **Data Science, Exploratory Data Analysis (EDA), and Machine Learning** projects developed during hands-on training at Genesis and academic coursework.

---

## 📊 Project 1: Supermart Grocery Sales Analysis

### 🎯 Overview & Objectives
An end-to-end Exploratory Data Analysis (EDA) on retail grocery transactions (`Supermart Grocery Sales - Retail Analytics Dataset.csv`) to extract business intelligence regarding product demand, revenue distribution, and profit margin dynamics.

### 🛠️ Key Analysis Steps (`MiniProject.ipynb`)
1. **Data Preprocessing & Cleaning**:
   - Ingested transactional retail sales data with customer and regional attributes.
   - Handled date parsing and temporal ordering using `pd.to_datetime(df['Order Date'], errors='coerce')`.
   - Verified schema structures, missing value distributions, and data type alignment.
2. **Exploratory Data Analysis (EDA)**:
   - Analyzed category-level sales volumes across Bakery, Beverages, Snacks, Produce, and Dairy.
   - Evaluated the relationship between discount percentages and net profit margins.
   - Assessed regional city-wise demand and seasonal sales patterns.
3. **Data Visualization**:
   - Built styled visualizations using **Matplotlib** and **Seaborn** to communicate revenue distribution and product profitability clearly.

---

## 📈 Project 2: Customer Churn Prediction & Segmentation

### 🎯 Problem Statement (`MiniProject4.ipynb`)
In customer-centric industries, customer churn directly undermines recurring revenue and increases customer acquisition costs. This project builds and evaluates predictive classification models to identify customers at high risk of churning based on usage patterns and demographic characteristics.

### 🛠️ Machine Learning Workflow
1. **Data Ingestion & Feature Engineering**:
   - Cleaned feature sets, encoded categorical attributes, and scaled numeric variables.
2. **Model Training & Comparison**:
   - **Logistic Regression**: Linear baseline probability model.
   - **Decision Tree Classifier**: Interpretable rule-based splitting.
   - **Random Forest Classifier**: Ensemble bagging for variance reduction and higher predictive accuracy.
3. **Evaluation Metrics**:
   - Evaluated models using Confusion Matrices, Precision, Recall, F1 Score, and ROC-AUC curves to ensure balanced detection of churners.
4. **Business Recommendations**:
   - Identified high-risk indicators to support targeted retention initiatives, contract adjustments, and proactive loyalty offerings.

---

## 📂 Repository Contents

| File | Description |
| :--- | :--- |
| **`MiniProject.ipynb`** | Supermart Grocery Sales Exploratory Data Analysis (EDA) & profit analysis |
| **`MiniProject4.ipynb`** | Customer Churn Prediction and Machine Learning classification models |
| **`Dataprepration&ML.ipynb`** | Data preprocessing, cleaning, and model preparation exercises |
| **`DS-DAY3.ipynb` / `DSDay4.ipynb` / `DSDay5.ipynb` | Core statistical analysis and Pandas / NumPy coursework |
| **`Supermart Grocery Sales - Retail Analytics Dataset.csv`** | Retail supermarket transaction dataset |
| **`Social_Network_Ads.csv` / `Salary_Data.csv`** | Supplementary datasets for classification and regression tasks |

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/gaganagana/python-fullstack-data-science.git
   cd python-fullstack-data-science
   ```
2. Set up a Python environment with required packages:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open `MiniProject.ipynb` or `MiniProject4.ipynb` and run all cells.
