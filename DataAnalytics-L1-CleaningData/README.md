# Data Cleaning using Python

## Project Overview
This project focuses on cleaning the Titanic dataset using Python. The objective is to identify and handle missing values, check duplicate records, inspect data types, and save a cleaned dataset.

## Dataset
Titanic Dataset (`Titanic-Dataset.csv`)

- Original rows: 891
- Original columns: 12

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Cleaning Steps
1. Loaded the Titanic dataset using Pandas.
2. Checked missing values in each column.
3. Filled missing Age values using the median.
4. Filled missing Embarked values using the mode.
5. Removed the Cabin column because it contained many missing values.
6. Checked duplicate rows and data types.
7. Saved the cleaned dataset as `Cleaned_Titanic_Dataset.csv`.
8. Visualized missing values before and after cleaning.

## Results
- Original dataset: 891 rows and 12 columns.
- Missing Age values: 177.
- Missing Cabin values: 687.
- Missing Embarked values: 2.
- Duplicate rows: 0.
- Final dataset: 891 rows and 11 columns.
- Missing values after cleaning: 0.

## Conclusion
The dataset was cleaned successfully by handling missing values and checking duplicate records. The cleaned dataset is ready for further analysis.

**Author:** Bhavna Kamble
