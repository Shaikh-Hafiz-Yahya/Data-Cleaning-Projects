# 🏥 Healthcare Records Cleaning & Outlier Detection

Data quality is critical for AI and Machine Learning models. In this project, I have processed raw, messy medical records to make them "Model-Ready." This workflow demonstrates professional data preprocessing techniques using Python.

## 📋 Project Overview
Healthcare datasets often contain human entry errors, inconsistent labels, and missing values. My goal was to clean the data while maintaining its statistical integrity so it can be used for reliable medical analysis and AI training.

## 🛠️ Key Tasks Performed

### 1. Outlier Detection & Treatment
Using **Seaborn Boxplots**, I identified abnormal values in the `Blood_Pressure` column (e.g., values of 400+ which are medically impossible). I handled these outliers using logic-based replacement to ensure the dataset remains realistic.

### 2. Categorical Standardization
The dataset had inconsistent gender labels like 'M', 'F', and 'female'. I standardized these into uniform **'Male'** and **'Female'** categories to ensure categorical consistency.

### 3. Statistical Missing Value Imputation
I addressed missing values in the `Glucose_Level` and `Blood_Pressure` columns using **Mean/Median Imputation**. This ensures that the data distribution remains robust even after filling gaps.

### 4. Data Validation & Profiling
I generated comprehensive cleaning reports using `df.describe()` and `df.info()` to verify that all data types are correct and no null values remain.

---

## 📊 Visual Analytics & Data Profile

To ensure the dataset was cleaned effectively, I utilized visualization tools and statistical summaries:

### **Outlier Detection Visualization**
*This Boxplot was used to identify extreme values that lie outside the normal medical range.*
![Outlier Detection Plot]()

### **Data Statistical Summary**
*A snapshot of the data distribution, counts, and types verified during the cleaning process.*
![Data Statistical Summary](Screenshot%202026-04-09%20131648.png)

---

## 📂 Files in this Folder
* **`Messy_HealthCare_Data.csv`**: The original raw dataset containing errors and null values.
* **`Clean_HealthCare.csv`**: The finalized dataset, fully cleaned and optimized for analysis.
* **`Healthcare_Analysis.ipynb`**: Jupyter Notebook containing the complete Python source code and step-by-step logic.

## 🛠️ Tools Used
* **Python** (Pandas, NumPy)
* **Matplotlib & Seaborn** (Data Visualization)
