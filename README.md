# Financial Sample – Power BI Data Exploration

## Dataset Overview

- **Source:** Power BI Sample Dataset (Financial Sample)
- **Rows:** 700
- **Columns:** 16

---

## Column Description

The dataset contains financial sales data with the following columns:

- **Segment** – Customer segment (Consumer, Corporate, Home Office)
- **Country** – Country of the sale
- **Product** – Product sold
- **Discount Band** – Discount category applied
- **Units Sold** – Quantity of units sold
- **Manufacturing Price** – Production cost per unit
- **Sale Price** – Selling price per unit
- **Gross Sales** – Total sales before discounts
- **Discounts** – Discount amount applied
- **Sales** – Net sales after discounts
- **COGS** – Cost of Goods Sold
- **Profit** – Profit generated
- **Date** – Transaction date
- **Month Number** – Numeric month (1–12)
- **Month Name** – Month name
- **Year** – Year of transaction

---

## Data Quality Assessment (Power Query)

The dataset was loaded into Power Query Editor for inspection and cleaning.

### Missing Values
- No null values were identified in the dataset.

### Data Type Validation & Fixes

The following data type corrections were applied:

- `Date` → Date
- `Year` → Whole Number (Integer)
- `Units Sold` → Whole Number
- Financial fields (`Sales`, `Profit`, `COGS`, `Manufacturing Price`, `Discounts`) → Decimal Number

---

## Data Transformations

- Standardized column data types for consistency
- Ensured numerical fields are properly formatted for calculations
- Verified dataset integrity before analysis

---

## Summary

The dataset contains **700 rows and 16 columns** representing financial sales transactions. After inspection in Power Query, no missing values were found, and all columns were standardized to appropriate data types, ensuring the dataset is ready for further analysis and visualization in Power BI.
