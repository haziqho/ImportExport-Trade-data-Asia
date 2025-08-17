# Asian Trade Analytics

Analyze Asian import export data with SQL, Excel, and Tableau.

## Overview
- Goal: find top 3 exporters and top 3 HS codes. Visualize trends.
- Result: one supplier has USD 353K+ trade value.
- Tools: MySQL or MariaDB, Excel, Tableau, VS Code.

## Data
- File: `ImportExport Trade data Asia.csv`.
- You can keep a copy in the `data` folder locally. Do not push private data.
- Suggested table name: `Import Export`.`importexport trade data asia`

## How to use
1. Load the CSV to your SQL database.
2. Run the SQL in `sql/queries.sql` to create views and answers.
3. Build charts in Tableau. Use the views or an extract.
4. Use Excel for quick checks and a pivot table.
5. Update the screenshot in `images/`.

## Key findings
- Top exporters and HS codes identified with SQL.
- USD 353K+ trade value from a single supplier.
- Trend chart shows monthly movement.
- You can redo the steps with the same scripts.

## SQL highlights
See `sql/queries.sql` for:
- Top 3 exporters by total value USD.
- Top 3 HS codes by total value USD.
- Supplier totals and the USD 353K+ check.
- Monthly trend.

## Repo structure
```
asian-trade-analytics/
  README.md
  sql/queries.sql
  images/screenshot.png
  excel/pivot_instructions.txt
  .gitignore
  LICENSE
```
## Tableau
- Import the views as data sources.
- Build:
  1. Bar chart: top exporters.
  2. Bar chart: top HS codes.
  3. Line chart: monthly trend.
- Export a PNG to `images/screenshot.png`.

## Excel
- Use a pivot table:
  - Rows: Exporter or HS code.
  - Values: Sum of total value USD.
  - Filter: Year or Month for trend.

## Notes
- Remove or mask any private data before publishing.
- Add your own insights to this README.

## Author
- Prepared 2025-08-17.
