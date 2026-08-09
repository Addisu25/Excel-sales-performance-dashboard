# Excel Sales Performance Dashboard

An interactive-style Excel portfolio project analysing 2,000 sales orders from 2026. The workbook converts transaction-level data into an executive dashboard covering revenue, order volume, regional performance, product mix and sales channels.

![Excel sales dashboard](assets/dashboard-preview.png)

## Business questions

- How much revenue was generated, and what was the average order value?
- How did revenue change month by month?
- Which regions and sales channels generated the most revenue?
- Which product categories and individual products performed best?
- Is the source data complete, unique and internally consistent?

## Key findings

- Total revenue was **$2.45 million** across **2,000 orders**.
- **5,552 units** were sold, with an average order value of **$1,226**.
- **November** recorded the highest monthly revenue at approximately **$274,000**.
- **North** was the leading region at approximately **$562,000**, narrowly ahead of Central.
- **Computers** generated about **55% of total revenue**.
- **Online** was the strongest channel at approximately **$792,000**.
- **Gaming Laptop** was the highest-revenue product at approximately **$433,000**.

## Excel skills demonstrated

- Excel Tables, filtering and structured source-data management
- Formula-driven KPI calculations and summary tables
- `SUM`, `COUNTA`, `SUMIF`, `SUMIFS` and `EDATE`
- Currency, percentage and date formatting
- Line, bar and doughnut charts
- Dashboard layout, KPI cards and executive insight summaries
- PivotTable field mapping and recommended slicer configuration
- Data-quality checks for missing values, duplicate order IDs and revenue consistency

## Workbook structure

| Worksheet | Purpose |
|---|---|
| `Sales Data` | Auditable transaction-level source table containing 2,000 records |
| `Pivot Analysis` | Formula-driven KPI and category summaries used by the dashboard |
| `Dashboard` | Executive sales performance dashboard |
| `PivotTable Guide` | Field placement, chart selection and slicer setup instructions |

## Data-quality validation

- 2,000 unique order IDs
- No missing values across the 12 source fields
- All revenue values reconcile to `Quantity × Unit Price × (1 − Discount)`
- Sales dates cover 1 January–31 December 2026

## Files

- `Sales_Performance_Dashboard_Excel.xlsx` — completed Excel workbook
- `assets/dashboard-preview.png` — dashboard preview
- `assets/analysis-preview.png` — supporting analysis preview

## How to use

1. Download and open the workbook in Microsoft Excel.
2. Review the `Dashboard` for the executive summary.
3. Use `Pivot Analysis` to audit the metrics behind each visual.
4. Follow `PivotTable Guide` to recreate the summaries as native PivotTables and add slicers for Region, Sales Channel, Customer Type and Product Category.

## Author

**Addisu Beyene**  
Public health researcher and data analyst with experience in Excel, Power BI, Stata, R, Python and health-data analytics.

