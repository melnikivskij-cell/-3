# Practical Work No. 3 — Data Cleaning and Transformation

**Author:** Andrii Melnykivskyi, group KN-41

## Description
This work covers the main stages of data cleaning and preparation with Pandas: detecting and handling missing values, finding and removing duplicates, detecting outliers with the IQR method, converting data types (`to_datetime`), cleaning strings (`.str`), feature engineering from dates (`.dt`), one-hot encoding, min-max normalization and standardization, and saving a reproducible, cleaned dataset. It also includes answers to the self-check questions and a bonus `clean_dataset()` function.

## Dataset
`sales.csv` — a training dataset of coffee shop sales (300 transactions) with 6 columns: `date`, `datetime`, `cash_type`, `card`, `money`, `coffee_name`.

## Files
- `Melnykivskyi_Lb3.ipynb` — practical part (steps 1–10)
- `Zavdannya3_Melnykivskyi.ipynb` — individual tasks 1–7 and answers to the self-check questions
- `Dodatkove3_Melnykivskyi.ipynb` — bonus task ★ (`clean_dataset` function)
- `sales.csv` — dataset
- `cleaned_sales.csv`, `sales_cleaned_task2.csv`, `cleaned_dataset.csv` — saved results

## How to run
1. Upload `sales.csv` to your Google Drive (the `MyDrive` folder).
2. Open a notebook in Google Colab.
3. Run the cells in order; allow access to Google Drive when prompted.

Outside Colab, the notebooks fall back to the local files in the same folder.

## Requirements
Python 3, `pandas`, `numpy` (preinstalled in Google Colab).
