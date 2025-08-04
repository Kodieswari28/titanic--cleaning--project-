# Titanic Dataset Cleaning Project 🛳️

This project focuses on cleaning and preprocessing the Titanic dataset using Python (Pandas, NumPy, Seaborn, Matplotlib). The cleaned dataset is saved for further analysis or machine learning modeling.

## 📁 Files Included

- 'titanic_cleaned.csv` – Jupyter Notebook with all preprocessing steps
- `titanic_cleaned.csv` – Final cleaned dataset
- `README.md` – Project documentation

## 📌 Tasks Completed

✔️ Removed missing values  
✔️ Filled `Age` with median  
✔️ Filled `Embarked` with mode  
✔️ Dropped `Cabin` column (too many nulls)  
✔️ Removed outliers in `Fare` using IQR method  
✔️ Saved the cleaned dataset as CSV

## 🛠️ Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

## ✅ Output

Cleaned dataset with reduced null values and no outliers, ready for model training.

## 📷 Sample Output
```python
Cleaned data saved as titanic_cleaned.csv
