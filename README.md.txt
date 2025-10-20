# 🧹 Task 1: Data Cleaning and Preprocessing


## 🎯 Objective
Clean and preprocess a raw sales dataset by handling missing values, removing duplicates, standardizing text formats, and correcting data types.  
The cleaned dataset is ready for analysis or visualization.


---


## 🧰 Tools Used
- Python (Pandas, NumPy)
- Faker (for sample data generation)
- Jupyter Notebook / VS Code


---


## 📊 Dataset Details
- **Rows:** 100  
- **Columns:** 7 (`order_id`, `customer_name`, `gender`, `product`, `order_date`, `sales`, `country`)  
- **Date Range:** 2023 – 2025  
- **Countries:** USA, UK, Canada, Australia, India  


---


## 🧼 Data Cleaning Steps


| Step | Action | Description |
|------|---------|-------------|
| 1 | Remove Duplicates | Dropped duplicate rows |
| 2 | Handle Missing Values | Filled missing names and genders with `"Unknown"` and sales with median value |
| 3 | Standardize Text | Fixed inconsistent capitalization and spacing |
| 4 | Fix Date Format | Converted all dates to `dd-mm-yyyy` |
| 5 | Rename Columns | Used lowercase with underscores |
| 6 | Correct Data Types | Ensured numeric and datetime consistency |


---



