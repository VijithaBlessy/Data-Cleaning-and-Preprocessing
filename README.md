# Data Cleaning and Preprocessing – Sample Superstore Dataset

## Project Overview
This project focuses on cleaning and preprocessing the Sample Superstore dataset using Python and Pandas. The goal is to improve data quality and prepare the dataset for further analysis.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Google Colab
- Excel

## Dataset
- **Name:** Sample Superstore Dataset
- **Source:** [Kaggle – Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- **Original Size:** 9,994 rows and 21 columns

## Data Cleaning Steps
1. Standardized column names into lowercase with underscores.
2. Removed leading and trailing spaces from text columns.
3. Checked for missing values.
4. Checked for duplicate records.
5. Converted order_date and ship_date into datetime format.
6. Converted postal_code into string format.
7. Detected potential outliers using the IQR method.
8. Performed final data quality validation.

## Data Quality Results

| Check | Result |
|---|---:|
| Original rows | 9,994 |
| Columns | 21 |
| Missing values | 0 |
| Duplicate rows | 0 |
| Date columns converted | 2 |

**Outlier detection:** Potential outliers were identified in sales, quantity, discount, and profit. They were retained for further investigation rather than automatically removed.

## Project Files
- `Data_Cleaning_and_Preprocessing.ipynb` – Python notebook containing the cleaning process.
- `Cleaned_Superstore_Dataset.csv` – Cleaned dataset in CSV format.
- `Cleaned_Superstore_Dataset.xlsx` – Cleaned dataset in Excel format.
- `change_log.csv` – Summary of cleaning operations.
- `DATA_CLEANING_REPORT.md` – Final data cleaning report.

## How to Run
1. Download or clone this repository.
2. Open the Jupyter Notebook in Google Colab or Jupyter Notebook.
3. Upload the original Sample Superstore CSV dataset.
4. Run the notebook cells step by step.

## Conclusion
The dataset was checked and cleaned using Python Pandas. Missing values and duplicate records were not found. Date columns were converted into the correct datetime format, and potential outliers were identified for further review.

---
**Project Type:** Data Cleaning and Preprocessing  
**Internship Task:** VEDA Data Analytics Internship
