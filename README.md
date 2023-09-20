# Finance_Analytics_and_Report_Generation

## Overview

This project focuses on Finance Analytics and Report Generation, aimed at providing efficient and customized reporting solutions for critical decision-making. Leveraging SQL, the project streamlines the process by implementing stored procedures, user-defined functions, and optimizing queries.

## Key Features

**Customizable Reports:** Generate reports based on input parameters like in_fiscal_year, in_top_n, and customer_code.

**Insightful Metrics:** Extract key metrics including forecast accuracy, market badge, monthly gross sale for customers, and more.

**User-Friendly Design:** Emphasis on readability and simplicity in complex queries for easy comprehension.

## Project Structure

  **|-- /reports**

    |   |-- forecast_accuracy_by_fiscal_year.csv
    
    |   |-- monthly_gross_sales_by_customer.csv
    
    |   |-- top_n_customer_by_netsales.csv
    
    |   |-- top_n_markets_by_netsales.csv

    |   |-- top_n_markets_by_region_&_gross_sales.csv

    |   |-- top_n_products_by_netsales.csv

    |   |-- top_n_products_per_division_qty_sold.csv
    
    |
    
  **|-- /user_defined_functions**
    
    |   |-- get_fiscal_year.txt

    |   |-- get_fiscal_quarter.txt
    
    |
    
  **|-- /views**
    
    |   |-- gross_sales_view.txt
    
    |   |-- net_sales_view.txt
    
    |   |-- sales_postinv_discount_view.txt

    |   |-- sales_preinv_discount_view.txt
    
    |
    
  **|-- /stored_procedures**
    
    |   |-- get_forecast_accuracy_sp.txt
    
    |   |-- get_market_badge_sp.txt
    
    |   |-- get_monthly_gross_sales_for_customer_sp.txt

    |   |-- get_top_n_customer_by_net_sales_sp.txt

    |   |-- get_top_n_markets_by_net_sales_sp.txt

    |   |-- get_top_n_products_per_division_by_qty_sold_sp.txt

    |   |-- top_n_markets_by_gross_sales_&_fiscal_year_sp.txt

    |   |-- top_n_products_by_netsales_sp.txt
    
    |
    
  **|-- /Other Queries**
  
    |   |-- Queries Using Window Function, CTEs and more.txt

## Usage

**1. Generating Reports:**

Navigate to the queries directory and execute the desired SQL files to generate reports.
Input parameters such as in_fiscal_year, in_top_n, and customer_code as required.

**2. Viewing Reports:**

Access generated reports from the reports directory in CSV format.
