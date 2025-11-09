# Breast Cancer Wisconsin Dataset - Exploratory Data Analysis (EDA)

## Project Overview
This project performs an **Exploratory Data Analysis (EDA)** on the **Breast Cancer Wisconsin (Diagnostic) Dataset**, which is widely used for binary classification tasks (Malignant vs Benign tumors).  
The goal of this analysis is to explore the data distribution, visualize relationships between features, and gain insights that can assist in building predictive models for breast cancer diagnosis.

---

## Dataset Information
- **Source:** [UCI Machine Learning Repository - Breast Cancer Wisconsin (Diagnostic)](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))
- **Number of Instances:** 569  
- **Number of Features:** 30 numeric, predictive attributes + 1 target (Diagnosis)
- **Target Variable:**
  - `M` — Malignant
  - `B` — Benign  

Each record describes characteristics of the cell nuclei present in a digitized image of a fine needle aspirate (FNA) of a breast mass.

---

## Technologies Used
- **Python 3.x**
- **Jupyter Notebook**
- **Libraries:**
  - `pandas` — Data manipulation  
  - `numpy` — Numerical computation  
  - `matplotlib` & `seaborn` — Data visualization  
  - `scikit-learn` — Dataset loading 

---

## EDA Steps
1. **Data Loading and Inspection**
   - Loaded dataset from `sklearn.datasets`
   - Converted the dataset into a `pandas DataFrame`
   - Checked dimensions, column names, and target distribution  

2. **Data Cleaning**
   - Checked for null or duplicate values 

3. **Data Visualization**
   - **Feature Correlations:** Correlation Matrix of Breast Cancer Dataset 
   - **Histogram:** Explore the frequency distribution of features
   - **Regression Plot:** Explore the relationship between features

4. **Feature Insights**
   - Identified some features highly correlated with the target  
   - Observed that features like *mean radius* (also, *mean perimeter* and *mean area*) show strong separation between benign and malignant samples  

*(All visualizations produced with Seaborn & Matplotlib.)*

---

## Key Insights
- Malignant tumors generally have **larger mean radius, area, and perimeter** compared to benign ones.  
- There is strong correlation among geometric features (e.g., radius, perimeter, area).  
- Dimensionality reduction (e.g., PCA) could be useful for visualization or modeling.

---

## Future Work
- Apply **dimensionality reduction (PCA, t-SNE)** for better visualization  
- Build **predictive models** (e.g., Logistic Regression, Random Forest, SVM)  
- Evaluate model performance with metrics such as accuracy, precision, recall, and ROC-AUC  

---

## 🙌 Acknowledgments
- **Dataset:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))  
- **Inspired by:** Scikit-learn example datasets  

---

## Author
**Leila (Faezeh) Gerayeli**  
Biomedical Engineer | Aspiring Data Scientist  
leila.gerayeli@gmail.com  
[LinkedIn](http://www.linkedin.com/in/leila-gerayeli-biomed) | [GitHub](https://github.com/LeilaBioMed)

---

*This project is part of my portfolio to demonstrate data exploration and visualization skills.*

---

## How to Use

Clone this repository:
```bash
git clone https://github.com/LeilaBioMed/Synthetic_Biomedical_Dataset_EDA.git
cd biomedical-eda
