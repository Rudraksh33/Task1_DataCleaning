# Task 1 - Data Cleaning and Preprocessing

## Dataset

Netflix Movies and TV Shows Dataset

## Objective

Clean and preprocess a raw dataset by handling missing values, checking duplicates, standardizing data, and fixing data types.

## Cleaning Steps Performed

1. Loaded dataset using Pandas.
2. Inspected dataset structure using df.shape and df.info().
3. Identified missing values using df.isnull().sum().
4. Filled missing values in:

   * director
   * cast
   * country
   * rating
   * duration
5. Checked for duplicate rows.
6. Inspected text columns for consistency.
7. Removed extra spaces from the date_added column using str.strip().
8. Converted date_added to datetime format using pd.to_datetime().
9. Verified data types and final dataset quality.
10. Exported the cleaned dataset.

## Tools Used

* Python
* Pandas
* Kaggle Notebook

## Output

cleaned_netflix_titles.csv
