# Retail Sales Analysis | Python & Pandas

## Project Overview

This project explores retail sales performance using a scenario-based dataset containing transactional and customer information from 2025.

The objective was to consolidate multiple datasets, investigate data quality issues, prepare the data for analysis and identify business insights across sales channels, customer segments, geographical regions and monthly performance.

## Tools & Technologies

- Python
- Pandas
- Jupyter Notebook

## Project Workflow

**1. Data Ingestion & Consolidation**
- Imported multiple monthly CSV files.
- Combined datasets into a consolidated structure.
- Preserved the original data for comparison.

**2. Data Cleaning**
- Standardized text and numeric fields.
- Handled inconsistent date formats.
- Investigated missing values and duplicate customer records.

**3. Data Preparation**
- Integrated customer information using left joins.
- Applied product-level median imputation for missing unit prices.
- Applied product-level mean imputation for missing quantities.
- Retained flags to identify imputed records.

**4. Business Analysis**
- Calculated revenue and average order value.
- Analysed revenue by sales channel.
- Compared customer segment and regional performance.
- Examined monthly revenue and product performance.

## Key Findings

- Regular customers contributed approximately 50.06% of total revenue.
- Marketplace was the leading sales channel, contributing 21.75%.
- Central was the highest-revenue region, contributing 38.22%.
- September recorded the highest dated monthly revenue.
- Sheet-103 was the highest-revenue SKU.

## Project Summary

| Metric | Result |
|---|---:|
| Completed transaction rows | 2,904 |
| Unique orders | 2,877 |
| Unique customers | 396 |
| Unique products | 20 |
| Total calculated revenue | Rs. 8.80 million |
| Estimated units sold | 7,767.26 |
| Average order value | Rs. 3,060.02 |

## Data Quality & Limitations

- 209 missing unit prices were estimated using product-level medians.
- 24 missing quantities were estimated using product-level means.
- 34 transactions had unresolved order dates and were excluded from the monthly trend analysis.
- Revenue and units sold include estimated values from imputation.

The dataset is scenario-based and does not represent the financial performance of an actual company.

## Conclusion

This project provided an opportunity to apply Python and Pandas to an end-to-end retail analytics exercise, combining data preparation, validation and business-focused analysis.
