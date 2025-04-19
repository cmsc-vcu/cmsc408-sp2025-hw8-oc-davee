# cmsc408-sp2025-hw8

Homework 8 - World Bank Indicator Analysis

## Project Description
This assignment analyzes World Bank country data using SQL queries to:
- Explore country classifications by region and income group
- Identify data anomalies and correct them
- Create pivot tables for comparative analysis
- Calculate percentage distributions across categories

## Database Schema
The MySQL database contains the `world_bank_data.wdi_country` table with:
- Country identifiers (code, short/long names)
- Geographic classifications (region)
- Economic classifications (income group)
- Administrative codes (2-alpha, WB-2 codes)

## Key Features
- 21 analytical tasks progressing from basic to advanced SQL
- Data cleaning and validation procedures
- Multi-dimensional analysis using:
  - CASE statements
  - CTEs (Common Table Expressions)
  - Pivot table transformations
  - Percentage calculations
- Error handling for data inconsistencies

## Technical Requirements
- MySQL database connection
- Python 3.x with mysql-connector
- Quarto (for report generation)
- VS Code or similar IDE

## Usage
As this assignment is a report, we must ensure that we have `quarto` downloaded to generate the final product of this summary which would be `report.html`. The steps for downloading `quarto` are [here](https://quarto.org/docs/get-started/)

We can generate the `report.html` via these steps: 
1. Clone this project via this command:
```bash
git clone <https://github.com/cmsc-vcu/cmsc408-sp2025-hw5-oc-davee>

```
2. Move into the `reports` folder: 
```bash
cd cmsc408-sp2025-hw5-oc-davee/reports
```
3. Render the `report.qmd` file. This also generates an HTML file called `report.html`
```bash
quarto render report.qmd
```
4. View the `report.html` file in a web browser i.e Chrome, Safari, etc. 
- Mac:
```bash
open report.html
```
- Linux:
```bash
google-chrome report.html
```

