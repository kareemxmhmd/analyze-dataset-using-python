# Superstore Dataset Analysis

A Python data analysis project that explores the Superstore sales dataset using pandas, matplotlib, and seaborn.

## Dataset

- **Source**: `Sample - Superstore.xlsx`
- **Records**: 9,994 transactions
- **Columns**: 21 fields including Order ID, Customer Name, Segment, City, State, Region, Category, Sub-Category, Sales, Quantity, Discount, Profit, etc.

## Features

- **Data Loading**: Reads Excel file and cleans column names
- **Missing Value Analysis**: Checks for null values across all columns
- **Summary Statistics**: Numerical summary (count, mean, std, min, max, quartiles)
- **Categorical Analysis**: Distribution of orders by segment, ship mode, region, category, and sub-category
- **Visualizations**: Charts for sales, profit, and category analysis

## Requirements

```
pandas
numpy
matplotlib
seaborn
openpyxl
```

## Usage

Open `main.ipynb` in Jupyter Notebook or VS Code and run the cells sequentially.

## Key Findings

- **Top States**: California (2,001), New York (1,128), Texas (985)
- **Top Cities**: New York City (915), Los Angeles (747), Philadelphia (537)
- **Categories**: Office Supplies (6,026), Furniture (2,121), Technology (1,847)
- **Segments**: Consumer (5,191), Corporate (3,020), Home Office (1,783)
- **Average Sales**: $229.86
- **Average Profit**: $28.66

Kareem

Data Science & Machine Learning Student Passionate about turning data into insights