
# Codveda Level 1 – Task 2: Data Cleaning & Preprocessing

## Project Overview

This project was completed as part of the **Codveda Technology Data Science Internship**. The objective was to perform data cleaning and preprocessing on a customer churn dataset and prepare the data for further machine learning analysis.

## Dataset

**Dataset:** Customer Churn Dataset  
**Records:** 2,666  
**Features:** 20

The dataset contains customer information such as account length, call usage, charges, voicemail plan, international plan, and churn status.

## Data Cleaning & Preprocessing

The following preprocessing steps were performed:

1. **Dataset Inspection**
   - Checked dataset dimensions and column names.
   - Examined data types and dataset information.

2. **Missing Value Detection**
   - Checked all columns for missing values.
   - No missing values were found.

3. **Duplicate Detection**
   - Checked for duplicate records.
   - No duplicate rows were found.

4. **Outlier Detection**
   - Used the **Interquartile Range (IQR)** method.
   - Outliers were identified in continuous numerical variables including call minutes and charges.

5. **Outlier Removal**
   - Removed observations falling outside the IQR-based lower and upper bounds.
   - Original dataset: **2,666 rows**
   - Cleaned dataset: **2,564 rows**
   - Rows removed: **102**

6. **Categorical Encoding**
   - Converted `International plan` and `Voice mail plan` from Yes/No into 0/1.
   - Applied one-hot encoding to the `State` column.

7. **Feature Standardization**
   - Applied `StandardScaler` to the feature variables.
   - Standardization transformed numerical features to a comparable scale.

## Final Dataset

| Stage | Rows | Columns |
|---|---:|---:|
| Original Dataset | 2,666 | 20 |
| After Outlier Removal | 2,564 | 20 |
| After Categorical Encoding | 2,564 | 70 |
| Final Standardized Dataset | 2,564 | 70 |

## Tools & Technologies

- Python
- Google Colab
- Pandas
- Scikit-learn
- Jupyter Notebook

## Repository Contents

- `Codveda_Level1_Task2_Data_Cleaning.ipynb` – Complete implementation of the data cleaning and preprocessing task.

## Outcome

The dataset was successfully cleaned, outliers were handled using the IQR method, categorical variables were encoded, and numerical features were standardized. The resulting dataset is ready for further machine learning analysis.

## Internship

**Codveda Technology – Data Science Internship**

Level: **1 – Basic**  
Task: **2 – Data Cleaning & Preprocessing**
