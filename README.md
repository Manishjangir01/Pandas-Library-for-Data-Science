# Pandas Library for Data Science

A hands-on guide to the Pandas library for data analysis and data
manipulation in Python, worked through on a car-sales dataset (428 rows,
15 columns).

## Topics covered

- Importing Pandas and reading CSV files
- DataFrame inspection (`head`, `tail`, `shape`, `info`, `describe`)
- Data types and column analysis (`dtypes`, `nunique`)
- Handling missing values (`isna`, `dropna`, `fillna`)
- Selecting and filtering data (`loc`, `iloc`, conditions, string matching)
- Data cleaning (removing `$` signs, changing data types)
- Renaming and dropping columns
- Sorting data
- Aggregation and `groupby`
- Applying functions (`apply`, `map`)
- Merging and concatenation
- Pivot tables and transpose
- Working with dates
- Exporting data to CSV

## Files

| File                 | Description                                              |
|----------------------|----------------------------------------------------------|
| `Panda’s library .pdf` | Printed Jupyter notebook (16 pages) with code and outputs |
| `requirements.txt`   | Python packages needed to run the examples               |

## Datasets

The notebook reads these CSV files, which are **not stored in this
repository**: `cars_data.csv`, `cars_data_row1.csv`, `cars_data_row2.csv`,
`cars_data_col1.csv`, `cars_data_col2.csv`, `cars_data_merge1.csv` and
`cars_data_merge2.csv`. To run the code yourself, place your own copies in the
same folder as the notebook.

## How to run

```bash
pip install -r requirements.txt
jupyter notebook
```

## Who is this for

- BCA / BSc / MCA students
- Data science beginners
- Internship tasks
- Interview preparation
