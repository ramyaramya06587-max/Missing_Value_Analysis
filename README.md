# Task 21: Missing Value Analysis

### Veda Technology – AI & ML Internship

## 1. Project Overview

Missing Value Analysis is an important step in data preprocessing and data cleaning. It helps identify incomplete data and understand the quality of a dataset.

In this task, Python and Pandas are used to analyse missing values in the Titanic dataset. The analysis identifies missing values, calculates their counts and percentages, and highlights columns that require further treatment.

## 2. Objective

- Identify missing values in the dataset.
- Calculate the number of missing values in each column.
- Find the total number of missing values.
- Calculate the percentage of missing values.
- Identify columns that require data treatment.

## 3. Technologies Used

- Python
- Pandas
- Jupyter Notebook
- Visual Studio Code

## 4. Dataset Information

**Dataset:** Titanic Dataset  
**File:** `train.csv`

The dataset contains passenger details such as passenger ID, age, gender, ticket information, cabin details, passenger class and survival status.

## 5. Implementation

The following operations were performed:

1. Imported the Pandas library.
2. Loaded the Titanic dataset using `read_csv()`.
3. Displayed the first five records.
4. Checked the dataset dimensions.
5. Identified missing values using `isnull()`.
6. Calculated missing values column-wise.
7. Calculated the total number of missing values.
8. Computed the percentage of missing values in each column.
9. Created a summary table to identify columns requiring treatment.

## 6. Functions Used

| Function | Description |
|---|---|
| `pd.read_csv()` | Loads the CSV dataset |
| `head()` | Displays the first five records |
| `shape` | Returns dataset dimensions |
| `isnull()` | Identifies missing values |
| `sum()` | Counts missing values |
| `DataFrame()` | Creates a summary table |

## 7. Expected Results

The analysis produces:

- Dataset preview and dimensions.
- Column-wise missing-value counts.
- Total missing-value count.
- Missing-value percentages.
- List of columns requiring treatment.

## 8. Conclusion

Successfully performed Missing Value Analysis using Python and Pandas. Identified incomplete data, calculated missing-value counts and percentages, and generated a column-wise summary.

This task provided practical experience in data inspection, data quality analysis and preprocessing techniques.



## 9. Author

**Ramya J**  
AI & ML Intern  
Veda Technology