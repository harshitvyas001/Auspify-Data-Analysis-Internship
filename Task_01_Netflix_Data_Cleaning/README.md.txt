# Netflix Data Cleaning and Preparation

## Project Overview
This project focuses on cleaning and preparing the Netflix dataset using Python and Pandas.

The objective is to inspect the dataset, identify data quality issues, standardize text columns, and export a cleaned dataset for further analysis.

## Tools and Technologies
- Python
- Pandas
- Jupyter Notebook
- CSV Dataset

## Dataset Information
- Total Records: 8,790
- Total Columns: 10
- Dataset Type: Netflix Movies and TV Shows

## Data Cleaning Steps
1. Imported the dataset using Pandas.
2. Inspected the dataset structure and column information.
3. Checked for missing values.
4. Checked for duplicate records.
5. Inspected unique values in Type, Rating, and Country columns.
6. Applied whitespace standardization to the Country and Type columns.
7. Verified Rating column formatting.
8. Exported the cleaned dataset into a CSV file.

## Data Quality Results

| Check | Result |
|---|---:|
| Total Records | 8,790 |
| Total Columns | 10 |
| Missing Values (NaN) | 0 |
| Duplicate Rows | 0 |
| Country marked as "Not Given" | 287 |

**Note:** The 287 "Not Given" entries represent unavailable country information. They were preserved rather than deleted.

## Output
The cleaned dataset is saved at:

`output/Netflix_Cleaned.csv`

## Project Structure
- `data/` – Original dataset
- `output/` – Cleaned dataset
- `screenshots/` – Project execution screenshots
- `Netflix_Data_Cleaning.ipynb` – Jupyter Notebook containing the code
- `README.md` – Project documentation