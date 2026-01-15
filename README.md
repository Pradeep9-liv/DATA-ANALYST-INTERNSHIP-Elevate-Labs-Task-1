# DATA ANALYST INTERNSHIP Elevate-Labs-Task-1
# Netflix Dataset - Data Cleaning & Formatting (Task 1)

## Project Overview
This project focuses on **cleaning and formatting a Kaggle Netflix dataset** using **Google Sheets / Excel**.  
The objective is to prepare a clean, well-structured dataset suitable for further analysis by following **professional data analyst practices**.

---

## Dataset
- **Source:** Kaggle - Netflix Titles Dataset  
- **Format:** CSV  
- **Records:** Movies and TV Shows available on Netflix  

---

## Task Objective
To perform **data cleaning and formatting** by:
- Handling missing values
- Checking duplicates
- Standardizing text
- Validating data formats
- Maintaining separation between raw and cleaned data

---

## Tools Used
- Google Sheets (Browser-based)
- Microsoft Excel (for final export)

---

## Data Cleaning Steps Performed

### **Step 1: Import Dataset**
- Downloaded the dataset in CSV format from Kaggle
- Imported into Google Sheets
- Ensured:
  - First row recognized as column headers
  - Correct delimiter (comma) used

---

### **Step 2: Freeze Headers & Apply Filters**
- Froze the header row for better navigation
- Applied filters on all columns to explore data efficiently

---

### **Step 3: Identify Missing Values**
- Used filters to detect blank values
- Applied conditional formatting to highlight missing values in key columns
- Decisions made based on column context:
  - Director / Cast --> left blank
  - Date Added / Rating --> flagged for review

---

### **Step 4: Detect Duplicates**
- Created a backup sheet to preserve raw data
- Checked duplicates using the primary key (`show_id`)
- No duplicate records found

---

### **Step 5: Standardize Text Fields**
- Removed extra spaces using `TRIM`
- Standardized names using `PROPER`
- Cleaned inconsistent text patterns in categorical fields

---

### **Step 6: Validate Data Formats**
- Converted date columns to proper date format
- Verified numeric columns contain only numbers
- Reviewed categorical columns for spelling and value consistency

---

### **Step 7: Create Cleaned_Data Sheet**
- Created a separate `Cleaned_Data` sheet
- Copied only cleaned values (no formulas)
- Maintained clear separation between raw and processed data

---

### **Step 8: Add Data Quality Notes**
- Added a `Data_Quality_Notes` column
- Documented observations such as:
  - Missing director names present
  - Rating values inconsistent
  - Mixed duration units

---

### **Step 9: Export Final Dataset**
- Exported cleaned data as:
  - `Cleaned_dataset.xlsx`
  - `cleaned_dataset.csv`
