>>> Sales Data Quality, Insights & CSV Operations

A beginner-level Python project developed as part of the **AI Engineering Bootcamp – Module 02 Sunday Project**.

>>> Project Overview

This project focuses on sales data cleaning, data quality checking, revenue analysis, visualization, and CSV file operations using Python and Pandas.

The main objective is to transform raw sales data into a clean and structured dataset, extract meaningful business insights, and perform additional data manipulation.

>>> Technologies Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- PyCharm

>>> Project Tasks

>>> Part A – Data Quality & Insights

- Loaded and explored the raw sales dataset.
- Checked dataset shape, column names, and data types.
- Identified missing values and duplicate records.
- Standardized region and category names.
- Handled missing and invalid values.
- Removed duplicate records.
- Calculated revenue using quantity and unit price.
- Analyzed revenue by region and category using `groupby()`.
- Created two revenue visualization charts.
- Exported the cleaned dataset as `cleaned_sales.csv`.

>>> Part B – CSV Operations

- Loaded the cleaned dataset.
- Calculated a 5% tax amount on revenue.
- Increased Books category prices by 10% using `.loc[]`.
- Recalculated revenue and tax.
- Removed a selected transaction using its transaction ID.
- Created and removed a temporary `review_status` column.
- Exported and verified the final dataset as `sales_updated.csv`.

>>> Project Files

| File | Description |
|---|---|
| `Sunday_Project.ipynb` | Complete project notebook |
| `sales_raw.csv` | Original sales dataset |
| `cleaned_sales.csv` | Cleaned dataset with revenue |
| `sales_updated.csv` | Updated dataset with tax and modifications |
| `revenue_by_region.png` | Revenue visualization by region |
| `revenue_by_category.png` | Revenue visualization by category |

>>> Key Findings

- North region generated the highest revenue.
- Stationery category generated the highest revenue.

>>> How to Run the Project

1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install pandas matplotlib
   ```

3. Open `Sunday_Project.ipynb` in Jupyter Notebook or PyCharm.
4. Keep the CSV files in the same project folder as the notebook.
5. Run all notebook cells sequentially.

>>> Learning Outcomes

- Understanding data quality and preprocessing.
- Working with Pandas DataFrames.
- Handling missing values and duplicates.
- Performing data aggregation and analysis.
- Creating data visualizations.
- Reading and writing CSV files.
- Applying practical data manipulation techniques.