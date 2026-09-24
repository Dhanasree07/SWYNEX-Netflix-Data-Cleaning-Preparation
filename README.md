# SWYNEX Netflix Data Cleaning & Preparation

## Project Overview

This project was completed as part of my internship task at SWYNEX Technologies.

The objective was to perform data cleaning and preparation on a public Netflix Movies and TV Shows dataset using Python and Pandas.

The project focuses on identifying and handling common data-quality issues such as missing values, duplicate records, inconsistent categorical values, and incorrect data types.

## Dataset

The dataset contains information about movies and TV shows available on Netflix.

Source:
Kaggle - Netflix Movies and TV Shows Dataset

https://www.kaggle.com/datasets/shivamb/netflix-shows

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- GitHub

## Data Quality Checks

The following checks were performed:

- Missing value identification
- Duplicate record detection
- Data type inspection
- Categorical value validation
- Text consistency checking
- Before-and-after data quality comparison

## Data Cleaning Performed

The following preprocessing steps were applied:

1. Removed duplicate records.
2. Removed unnecessary spaces from text fields.
3. Handled missing values in categorical/text columns using an `Unknown` category where appropriate.
4. Converted the `date_added` column into a proper datetime format.
5. Standardized categorical values such as content type and rating.
6. Validated content type values after cleaning.
7. Rechecked missing values and duplicate records after preprocessing.

## Project Files

| File | Description |
|---|---|
| `SWYNEX_Netflix_Data_Cleaning.ipynb` | Complete Python data cleaning notebook |
| `SWYNEX_cleaned_netflix_dataset.csv` | Cleaned Netflix dataset |
| `SWYNEX_final_data_quality_report.csv` | Final data quality report |
| `SWYNEX_before_after_comparison.csv` | Before and after cleaning comparison |

## Key Learning Outcomes

Through this project, I gained practical experience in:

- Data cleaning and preprocessing
- Missing-value analysis
- Duplicate detection and removal
- Data type conversion
- Data validation
- Exploratory data-quality analysis
- Python Pandas
- Data visualization
- Preparing datasets for further analysis

## Conclusion

This project demonstrates an end-to-end data cleaning workflow using Python and Pandas, from identifying data-quality issues to validating and exporting the cleaned dataset.
