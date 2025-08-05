## Diabetes-EDA
EDA on diabetes dataset using python and libraries

## Diabetes Dataset - Exploratory Data Analysis (EDA)

This project involves Exploratory Data Analysis (EDA) on the popular Diabetes dataset using Python libraries like Pandas, Matplotlib, and Seaborn. The goal is to uncover patterns, detect outliers, handle missing values, and understand the relationship between features and the outcome variable (diabetes presence).

---
## Dataset Description:
The dataset contains various medical predictor variables and one target variable (Outcome), indicating whether a patient has diabetes or not.

**Features include:**
- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age
- Outcome (0 or 1)

---

##  Libraries Used:
- `Pandas` – Data manipulation and cleaning
- `NumPy` – Numerical operations
- `Matplotlib` – Basic plotting
- `Seaborn` – Advanced visualizations

---

##  Steps Performed in EDA:

1. **Data Loading & Overview**
   - Loaded dataset and displayed first/last few rows
   - Checked shape, columns, and datatypes

2. **Missing Value Treatment**
   - Identified 0s in columns like Glucose, BloodPressure, etc.
   - Replaced 0s with `NaN` where applicable
   - Used imputation techniques (mean/median)

3. **Descriptive Statistics**
   - Mean, median, mode, std deviation for each feature
   - Summary statistics using `.describe()`

4. **Data Visualization**
   - **Histograms** to view distributions
   - **Boxplots** to detect outliers
   - **Countplots** for class distribution (Outcome)
   - **Pairplots** to view relationships between features

5. **Correlation Analysis**
   - Generated heatmap using Seaborn
   - Analyzed relationships between features (e.g., Age vs. Outcome)

6. **Outlier Detection**
   - Detected outliers using boxplots and IQR method
   - Optional: Removed or flagged them for modeling phase
   

---

## Key Insights:
- Imbalanced dataset (more non-diabetic than diabetic patients)
- Strong correlation between Glucose and Outcome
- Many 0 values in Insulin, SkinThickness columns – required imputation
- Outliers present in Age and Insulin
- BMI and Glucose are good indicators of diabetes risk

---

##  Files Included:
- `diabetes_eda.html` – Main analysis notebook (fully commented)
- `diabetes.csv` – Dataset 
- `README.md` – This documentation

---

##  Future Scope:
- Build predictive models (Logistic Regression, Random Forest,NAive bayes,SVM.)
- Feature engineering and scaling
- Deploy the model using Sckitlearning or Flask


