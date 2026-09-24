# Supermarket Sales Analysis

## Data Analytics Project

This project analyzes supermarket sales data to find useful insights
about products, branches, categories, customers, payment methods, and
customer ratings.

## Problem Statement

The aim of this project is to analyze supermarket sales data and find
useful information about products, branches, categories, customers,
payments, and ratings.

## Dataset

The dataset contains **500 sales transactions**. It includes product,
branch, city, customer type, quantity, price, payment method, rating,
and sales.

## Project Files

-   `supermarket_sales_project.ipynb` --- Jupyter Notebook containing
    the complete analysis.
-   `SUPER MARKET DATA - supermarket_sales_500_rows.csv` --- CSV dataset
    containing 500 sales transactions.

## Technologies Used

-   Python
-   Jupyter Notebook
-   Pandas
-   NumPy
-   Matplotlib

## Analysis Steps

1.  Load the CSV dataset.
2.  Check the data for missing or incorrect values.
3.  Calculate and verify **Sales = Quantity × Unit Price**.
4.  Group and summarize the data using totals, counts, and averages.
5.  Create charts to compare the results.
6.  Use the results to make business decisions.

## Analysis Performed

-   Product-wise sales analysis
-   Branch-wise sales analysis
-   Category-wise sales analysis
-   Payment method analysis
-   Member vs Normal customer spending
-   Customer rating analysis
-   Overall sales and transaction statistics

## Key Results

  Question                     Result
  ---------------------------- ----------------------------------
  Highest-sales product        Cheese --- ₹27,906.30
  Best-performing branch       Branch C (Mumbai) --- ₹72,469.45
  Highest-sales category       Beverages --- ₹56,108.24
  Most-used payment method     UPI --- 127 transactions
  Average Member transaction   ₹483.14
  Average Normal transaction   ₹497.07
  Average customer rating      3.99 / 5

## Business Decisions

-   Keep sufficient stock of high-selling products and categories.
-   Study the factors contributing to the strong performance of Branch C
    (Mumbai).
-   Continue supporting UPI payments.
-   Monitor customer ratings to identify opportunities for improving
    customer service.
-   Use customer spending patterns when planning membership offers.

## How to Run

### 1. Install required libraries

``` bash
pip install pandas numpy matplotlib jupyter
```

### 2. Keep the files in the same folder

``` text
supermarket_sales_project.ipynb
SUPER MARKET DATA - supermarket_sales_500_rows.csv
README.md
```

### 3. Start Jupyter Notebook

``` bash
jupyter notebook
```

Open `supermarket_sales_project.ipynb` and run the cells from top to
bottom.

## Conclusion

This project demonstrates how supermarket sales data can be converted
into practical business insights. The analysis helps understand sales
performance across products, branches, categories, customers, payment
methods, and ratings, supporting better inventory, branch, payment, and
customer-service decisions.
