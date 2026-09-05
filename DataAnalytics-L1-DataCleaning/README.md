# Task 3: Data Cleaning – Oasis Infobyte Internship

## 📌 Project Overview
This project involves cleaning a deliberately messy dataset to demonstrate professional-level data cleaning skills. The dataset contains 10,000 rows and 8 columns with missing values, inconsistent formatting, and outliers.

## 📊 Dataset Information
- **Source:** Dirty Cafe Sales Dataset (Kaggle)
- **Rows:** 10,000
- **Columns:** 8
  - Transaction ID
  - Item
  - Quantity
  - Price Per Unit
  - Total Spent
  - Payment Method
  - Location
  - Transaction Date

## 🔍 Cleaning Steps Performed
1. **Data Quality Report** – Identified nulls, duplicates, and data types.
2. **Standardisation** – Fixed inconsistent text formatting (e.g., "MeAt" → "Meat").
3. **Missing Data Handling** – Used mode for categorical, median for numeric, forward fill for dates.
4. **Duplicate Removal** – Removed duplicate rows.
5. **Data Type Correction** – Converted dates to datetime, IDs to string, numbers to float.
6. **Outlier Detection** – Used IQR method to detect and cap outliers.
7. **Before vs After Summary** – Compared data quality before and after cleaning.
8. **Save Cleaned Dataset** – Exported cleaned data as CSV.

## 📈 Before vs After Summary
| Metric | Before | After |
|--------|--------|-------|
| Null Values | 6,826 | 0 |
| Duplicate Rows | 0 | 0 |
| Row Count | 10,000 | 10,000 |

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Jupyter Notebook / Google Colab

## 📂 Repository Structure
DataAnalytics-L1-DataCleaning/
├── DataAnalytics-L1-DataCleaning.ipynb
├── dirty_cafe_sales.csv
├── dirty_cafe_sales_cleaned.csv
└── README.md

text

## 🚀 How to Run
1. Open the `.ipynb` file in Google Colab or Jupyter Notebook.
2. Run all cells sequentially.

**Oasis Infobyte – Data Analytics Internship**  
*Task 3 – Data Cleaning*  
📍 Completed by **Unnati Chavan**