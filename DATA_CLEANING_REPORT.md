
# DATA CLEANING AND PREPROCESSING

## 1. Introduction
This project focuses on cleaning and preprocessing
the Sample Superstore dataset using Python and Pandas.

## 2. Dataset Details
- Dataset: Sample Superstore
- Total Rows: 9994
- Total Columns: 21

## 3. Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab

## 4. Data Quality Inspection
- Missing values: 0
- Duplicate rows: 0
- Potential outliers identified using IQR.

## 5. Data Cleaning Activities
- Standardized column names.
- Removed unnecessary leading and trailing spaces.
- Checked missing values.
- Checked duplicate records.
- Converted order_date and ship_date to datetime.
- Converted postal_code to text.
- Identified potential outliers using IQR.

## 6. Outlier Analysis
- Sales: 1167
- Quantity: 170
- Discount: 856
- Profit: 1881

Potential outliers were identified and retained
because they were not confirmed to be data errors.

## 7. Final Validation
- Rows: 9994
- Columns: 21
- Missing values: 0
- Duplicate rows: 0

## 8. Conclusion
The dataset was inspected, cleaned and validated.
The final dataset is prepared for further data analysis.
