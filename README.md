# Elevate_Labs_Task_1
# 🧹 Task 1 – Data Cleaning and Preprocessing

## 📁 Dataset Used
- **File Name:** `sales_data_sample.csv`
- **Source:** Sample Sales Data (from Kaggle or provided source)

## 🎯 Objective
To clean and preprocess raw sales data using Python and Pandas to make it analysis-ready by:
- Handling missing values
- Removing duplicates
- Standardizing text
- Formatting dates
- Renaming columns
- Correcting data types

---

## 🔧 Tools & Libraries
- Python 3.x
- Pandas

---

## ✅ Cleaning Steps Performed

| Step | Description |
|------|-------------|
| 1.   | Dropped sparse columns: `ADDRESSLINE2`, `STATE`, `TERRITORY` |
| 2.   | Removed rows with missing `POSTALCODE` |
| 3.   | Removed duplicate rows using `drop_duplicates()` |
| 4.   | Standardized values in `COUNTRY`, `STATUS`, and `DEALSIZE` (uppercase, stripped) |
| 5.   | Converted `ORDERDATE` to `datetime` format |
| 6.   | Renamed all columns to `lowercase_with_underscores` |
| 7.   | Ensured correct data types: `quantityordered` as `int`, `priceeach` as `float`, `postalcode` as `str` |

---

## 📄 Files in this Repository
- `sales_data_sample.csv` – Original dataset
- `cleaned_sales_data.csv` – Final cleaned dataset
- `Task_1_Data_Cleaning_and_Preprocessing.ipynb` – Jupyter notebook (optional)
- `README.md` – This file

---

## 📌 Author
- Internship Candidate – Data Analyst Track  
- Submission for: Task 1 – Data Cleaning
