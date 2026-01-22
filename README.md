# Task 5 – Python Basics: Data Cleaning using Pandas

## 📌 Objective
The objective of this task is to perform basic data cleaning and preprocessing
using Python and Pandas. This task demonstrates how Python can be used instead
of Excel for efficient and scalable data cleaning.

---

## 📊 Dataset Used
**Titanic Dataset**

The dataset contains passenger information such as age, gender, fare,
and embarkation port, including missing and inconsistent values.

---

## 🛠 Tools & Technologies
- Python
- Pandas
- NumPy
- Google Colab / Jupyter Notebook

---

## 🔍 Cleaning Steps Performed
- Loaded dataset using `pandas.read_csv()`
- Inspected data using `.head()` and `.info()`
- Identified missing values using `isnull().sum()`
- Filled numerical missing values using median
- Filled categorical missing values using mode
- Dropped irrelevant column (`Cabin`)
- Removed duplicate records
- Converted datatypes for better analysis
- Created a new feature (`Age_Group`)
- Exported cleaned dataset to CSV

---

## 📁 Files Included
- `Task5_Cleaning.ipynb` – Jupyter Notebook with code and markdown notes
- `titanic.csv` – Original dataset
- `cleaned_data.csv` – Cleaned dataset
- `README.md` – Project documentation

---

## ✅ Final Outcome
This task provides hands-on experience with Pandas data cleaning techniques
and shows how Python simplifies data preprocessing compared to manual
Excel-based methods.
