# Dataset Information

## Overview

This folder contains the datasets used for the Retail Sales Performance Analytics project.

The data represents international retail transactions and is used for revenue analysis, trend identification, product performance evaluation, and business insight generation.

---

## Files Included

### 1. online_retail.csv

Raw transactional dataset containing retail sales records.

**Key Fields:**
- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country

This file contains the original sales transaction data before preprocessing.

---

### 2. processed_online_retail.xlsx

Cleaned and processed version of the dataset used for analysis and dashboard creation.

**Processing Steps Performed:**
- Removed missing values in critical columns (Description, CustomerID)
- Removed cancelled transactions
- Removed negative and zero quantities
- Converted date column to datetime format
- Created derived fields:
  - Year
  - Month
  - Hour
  - Revenue (Quantity × UnitPrice)

This dataset was used for visualization and KPI calculation.

---

## Data Source

The dataset is based on the publicly available Online Retail Dataset from Kaggle:

https://www.kaggle.com/datasets/ulrikthygepedersen/online-retail-dataset

---

## Notes

- The dataset represents international e-commerce transactions.
- Revenue values were calculated as: Quantity × Unit Price.
- The processed file ensures consistency for dashboard analysis.
- Data is used strictly for educational and analytical purposes.
