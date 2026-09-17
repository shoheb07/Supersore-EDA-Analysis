# Superstore Sales & Profit EDA

## Project Overview

**Superstore Sales & Profit EDA** is an Exploratory Data Analysis
project that analyzes a retail Superstore dataset to understand sales
performance, profitability, customer behavior, product performance,
regional trends, and shipping patterns.

The project uses Python-based data analysis and visualization techniques
to transform raw transactional data into meaningful business insights.

## Objectives

-   Assess the quality and structure of the dataset
-   Identify missing values, duplicates, and inconsistencies
-   Analyze sales and profit distributions
-   Study yearly and monthly sales trends
-   Compare category and sub-category performance
-   Identify top and bottom-performing products
-   Analyze customer and regional performance
-   Study shipping modes
-   Analyze the relationship between discount and profit
-   Detect outliers and unusual observations
-   Generate business-oriented insights and recommendations

## Dataset

The dataset contains **9,994 records and 21 columns**.

### Main Columns

  Column          Description
  --------------- ---------------------------------
  Row ID          Unique row identifier
  Order ID        Order identifier
  Order Date      Date when the order was placed
  Ship Date       Date when the order was shipped
  Ship Mode       Shipping method
  Customer ID     Unique customer identifier
  Customer Name   Customer name
  Segment         Customer segment
  Country         Country
  City            Customer city
  State           Customer state
  Postal Code     Postal/ZIP code
  Region          Geographic region
  Product ID      Unique product identifier
  Category        Product category
  Sub-Category    Product sub-category
  Product Name    Product name
  Sales           Sales amount
  Quantity        Quantity ordered
  Discount        Discount applied
  Profit          Profit generated

## Technologies Used

-   Python
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn
-   Google Colab / Jupyter Notebook

## Project Workflow

### 1. Data Assessment

The dataset was examined to understand its structure and quality.

Activities include:

-   Checking dataset shape
-   Checking data types
-   Checking missing values
-   Checking duplicate records
-   Examining unique values
-   Generating descriptive statistics

### 2. Data Cleaning

The data-cleaning stage focuses on preparing the dataset for reliable
analysis.

Activities include:

-   Handling missing values
-   Checking duplicates
-   Correcting data types
-   Checking inconsistent categorical values
-   Validating numerical columns
-   Identifying potential outliers

### 3. Exploratory Data Analysis

#### Sales Analysis

-   Distribution of sales
-   Yearly sales performance
-   Monthly sales trends
-   Sales by category
-   Sales by sub-category
-   Top products by sales

#### Profit Analysis

-   Profit distribution
-   Yearly profit performance
-   Profit by category
-   Profit by sub-category
-   Top and bottom products by profit

#### Customer Analysis

-   Customer-wise sales
-   Customer-wise profit
-   Customer segment analysis
-   Top customers

#### Geographic Analysis

-   Sales by region
-   Profit by region
-   State-wise analysis
-   City-wise analysis

#### Shipping Analysis

-   Orders by shipping mode
-   Sales by shipping mode
-   Profit by shipping mode

#### Discount Analysis

-   Discount distribution
-   Discount vs. profit
-   Analysis of how discount levels relate to profitability

#### Statistical Analysis

-   Correlation analysis
-   Outlier analysis
-   Distribution analysis

## Key Visualizations

The notebook contains visualizations such as:

-   Sales Distribution
-   Yearly Sales and Profit
-   Monthly Sales Trend
-   Profit by Category
-   Sub-Category Analysis
-   Product Performance
-   Regional Performance
-   Customer Performance
-   Shipping Mode Analysis
-   Discount vs. Profit
-   Correlation Heatmap
-   Outlier Analysis

## Business Questions

The project aims to answer questions such as:

1.  How are sales and profit changing over time?
2.  Which categories generate the most profit?
3.  Which sub-categories perform best and worst?
4.  Which products generate the highest sales?
5.  Which products generate the highest profit?
6.  Which regions contribute the most sales and profit?
7.  Which customers contribute significantly to revenue?
8.  Which shipping modes are most commonly used?
9.  What is the relationship between discount and profit?
10. Are there products or categories with high sales but relatively low
    profit?

## Key Findings

The exploratory analysis provides several business-oriented
observations, including:

-   Sales show substantial growth in the later years of the analyzed
    period.
-   Profit also increases across the displayed yearly analysis.
-   Technology and Office Supplies contribute substantially to overall
    profit, while Furniture contributes comparatively less.
-   Sales values are highly right-skewed, with most transactions
    concentrated at lower sales values and a smaller number of
    high-value transactions.
-   Product, regional, customer, and discount-level analysis can reveal
    areas where revenue and profitability do not move together.

## Business Insights

The analysis demonstrates an important distinction between **sales
performance and profitability**. A product, category, or customer
generating high sales may not necessarily generate proportionally high
profit.

Therefore, business decisions should consider:

-   Revenue
-   Profit
-   Profit margin
-   Discount levels
-   Product performance
-   Customer contribution
-   Regional performance

rather than relying on sales alone.

## Project Structure

``` text
Superstore-EDA/
│
├── superstoreeda.ipynb
├── README.md
├── dataset/
│   └── superstore.csv
│
├── visualizations/
│   ├── sales_distribution.png
│   ├── yearly_sales_profit.png
│   ├── monthly_sales.png
│   └── category_profit.png
│
└── requirements.txt
```

## How to Run

### Using Google Colab

1.  Upload the dataset to Google Drive or Colab.
2.  Open `superstoreeda.ipynb`.
3.  Update the dataset path if required.
4.  Run the notebook cells sequentially.

### Using Jupyter Notebook

Install the required libraries:

``` bash
pip install pandas numpy matplotlib seaborn jupyter
```

Open the notebook:

``` bash
jupyter notebook superstoreeda.ipynb
```

## Skills Demonstrated

This project demonstrates practical skills in:

-   Data Assessment
-   Data Cleaning
-   Exploratory Data Analysis
-   Data Visualization
-   Statistical Analysis
-   Business Analysis
-   Python Programming
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn
-   Insight Generation

## Future Improvements

Possible extensions include:

-   Build an interactive Power BI dashboard
-   Perform RFM customer segmentation
-   Add customer lifetime value analysis
-   Develop sales and profit forecasting
-   Build predictive machine-learning models
-   Create an interactive web-based analytics dashboard

## Author

**Shoheb Mulla**

### Skills

`Python` `Pandas` `NumPy` `Matplotlib` `Seaborn` `EDA` `Data Cleaning`
`Data Visualization` `Business Analytics`
