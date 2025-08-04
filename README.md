## 📊 Task 1: Data Cleaning and Preprocessing – Summary

1. **Handled Missing Values**  
   – Identified and filtered blank cells in columns like `director`, `country`, and `cast`  
   – Replaced missing values with "Unknown" using Excel formulas

2. **Removed Duplicates**  
   – Applied Remove Duplicates on all columns

3. **Standardized Text Columns**  
   – Cleaned columns like `type`, `country`, `rating` using `PROPER()`, `UPPER()`, and `TRIM()`  
   – Example: "usa" → "Usa"

4. **Converted Date Format**  
   – Converted `date_added` from long-form to `dd-mm-yyyy` using formula-based parsing

5. **Fixed Data Types**  
   – Ensured numeric columns like `release_year` are numbers  
   – Verified data using `ISNUMBER()` and `ISTEXT()`

6. **Structured the File Neatly**  
   – Adjusted widths, added filters, borders, and bold headers  
   – Removed extra rows/columns and renamed the sheet
