# Task1_Solution

Dataset Link = "https://drive.google.com/file/d/1xcyZnBkHn-7EJAXPmnVkD3ZPEefsjSss/view?usp=sharing"


### Step 1: Initial Dataset Overview
Total Rows: 541,909

Columns:

InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

Missing Data:

Description: 1,454 missing

CustomerID: 135,080 missing

###  Step 2: Data Cleaning Plan

Remove rows with missing Description

Remove rows with Quantity <= 0 or UnitPrice <= 0

Convert InvoiceDate to datetime

Clean and standardize Country

Rename all columns to lowercase with underscores

Convert InvoiceNo, StockCode, and CustomerID to string

Remove duplicates

Add total_price = Quantity × UnitPrice
