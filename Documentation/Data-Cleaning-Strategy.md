# Data Cleaning Strategy

## Retail Sales Performance & Executive Decision Support System

**Version:** 1.0  
**Role:** Data Analyst  
**Tool:** Microsoft Excel Power Query

---

## 1. Objective

The objective of the data-cleaning process is to prepare reliable and consistent retail sales data before creating Pivot Tables, KPIs, charts and the executive dashboard.

Power Query is used to apply repeatable data transformation and cleaning steps.

---

## 2. Data Cleaning Rules

| Data Issue | Business Risk | Cleaning Action | Validation |
|---|---|---|---|
| Leading / Trailing Spaces | Duplicate or mismatched text values | Apply `TRIM` | Random sample check |
| Hidden Characters | Incorrect matching | Apply `CLEAN` | Lookup test |
| Inconsistent Capitalization | Inconsistent reporting | Standardize using `PROPER` where appropriate | Visual review |
| Incorrect Data Types | Calculation errors | Change to correct data type | Formula test |
| Duplicate Records | Inflated KPIs | Remove duplicates | Duplicate count |
| Blank Values | Incomplete analysis | Replace or filter where appropriate | Null count |
| Invalid Dates | Timeline and trend issues | Convert to valid Date type | Date filter test |
| Unused Columns | Unnecessary data and performance issues | Remove unnecessary columns | Refresh test |

---

## 3. Data Preparation Process

The general data preparation workflow is:

1. Load the source retail dataset into Power Query.
2. Review the structure and data types.
3. Remove unnecessary columns.
4. Clean text fields.
5. Correct data types.
6. Identify and handle duplicate records.
7. Review blank and null values.
8. Validate date fields.
9. Verify numerical fields.
10. Load the cleaned data for analysis.

---

## 4. Text Cleaning

Text fields are reviewed for:

- Leading spaces
- Trailing spaces
- Hidden characters
- Inconsistent capitalization

Power Query transformations such as `TRIM`, `CLEAN` and appropriate text standardization are used to improve consistency.

---

## 5. Data Type Validation

Each field is assigned an appropriate data type before analysis.

Important fields include:

- Dates
- Sales
- Profit
- Discount
- Quantity
- Shipping Cost
- Order ID
- Customer ID
- Product ID

Correct data types help prevent calculation and filtering errors.

---

## 6. Duplicate Records

Duplicate records can inflate sales, orders and other KPIs.

Duplicate records are therefore identified and removed where appropriate.

The duplicate count is checked after the transformation.

---

## 7. Blank and Null Values

Blank or null values are reviewed before analysis.

Depending on the field and business requirement, values may be:

- Filtered
- Replaced
- Retained when they represent valid business information

Unexpected null values are checked during validation.

---

## 8. Date Validation

Date fields are converted to the correct Date data type.

This is important for:

- Monthly analysis
- Sales trends
- Timeline filtering
- Time-based Pivot Tables

---

## 9. Post-Cleaning Validation

After the cleaning process, the following checks are performed:

- Record count is verified
- Duplicate records are checked
- Data types are verified
- Unexpected null values are reviewed
- Pivot Table totals are reconciled with source totals
- Dashboard refresh is tested successfully

---

## 10. Objective of the Cleaning Process

The final dataset should be consistent, accurate and suitable for:

- KPI calculations
- Pivot Tables
- Pivot Charts
- Dashboard visualizations
- Interactive filtering
- Business analysis
