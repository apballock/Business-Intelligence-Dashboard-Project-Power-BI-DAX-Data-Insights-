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

---

## First Visualization: Sales by Segment

### Objective

Create a bar chart to analyze total sales by customer segment.

---

## Visualization Created

A **Clustered Bar Chart** was created in Power BI to visualize total sales per segment.

### Configuration:
- **Y-Axis:** Segment  
- **X-Axis:** Sales (aggregated as Sum)  

Additional formatting:
- Bars sorted in descending order (highest to lowest sales)
- Chart title: *"Total Sales by Segment"*
- Custom bar color applied (non-default blue) for better visual clarity

---

## Business Insight

### Which segment has the highest total sales?
- **Government segment** shows the highest total sales.

### Which segment has the lowest total sales?
- **Channel Partners segment** has the lowest total sales.

---

## Key Takeaway

The analysis shows a strong concentration of revenue in the Government segment, indicating it is the primary driver of sales performance in this dataset. In contrast, Channel Partners contribute the least to total sales, suggesting a potential area for growth or strategic review.

---
