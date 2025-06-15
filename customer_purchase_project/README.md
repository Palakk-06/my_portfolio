# 🧼 Customer Purchase Data Cleaning Project

This project focuses purely on **data cleaning and preprocessing** of a complex customer purchase dataset using Python (Pandas) inside a Jupyter Notebook. It demonstrates practical data wrangling skills that are essential before any meaningful analysis or visualization can be performed.

---

## 📁 Files Included

- `customer_purchase_cleaned.ipynb` – Main Jupyter Notebook containing the full cleaning process
- `customer_purchase.csv` – Raw dataset
- `README.md` – Project documentation (this file)

---

## 🧰 Tools & Technologies

- **Python** (Pandas, NumPy)
- **Jupyter Notebook**

---

## 🔧 Cleaning Objectives

- Remove missing values
- Standardize inconsistent data entries
- Handle zero or invalid values
- Fix column data types
- Drop duplicates
- Reformat column names to snake_case

---

## 🔍 Cleaning Steps Performed

1. **Removed Columns**

   - Dropped columns with high null percentages or irrelevant information (e.g., unnamed index columns)

2. **Handled Missing Values**

   - Imputed missing values in fields like `customer_since`, `product_rating`, or `amount_spent`
   - Checked for missing or malformed dates and cleaned them

3. **Fixed Data Types**

   - Converted `order_date`, `signup_date`, etc. to datetime format
   - Converted numerical fields stored as text (e.g., `amount_spent`, `customer_age`) to appropriate types

4. **Standardized Categorical Variables**

   - Cleaned inconsistent values in `customer_segment`, `payment_method`, etc.
   - Converted text to lowercase or title case where needed

5. **Removed Duplicates**

   - Identified and removed duplicate customer or transaction records

6. **Cleaned and Renamed Columns**
   - Applied `snake_case` formatting for consistency
   - Removed trailing spaces or special characters in column names

---

## ✨ Outcome

- A fully cleaned and structured dataset ready for further analysis or visualization
- Demonstrates real-world data preprocessing skills as expected in data analyst roles

---

## 🧠 Skills Highlighted

- Data cleaning with Pandas
- Handling missing, inconsistent, and invalid data
- Preparing raw data for business analysis
- Writing reproducible and organized Python code

---

> 💡 Note: This project intentionally focuses only on data preparation — no visualizations or dashboarding — to showcase strong **data wrangling** capabilities.
