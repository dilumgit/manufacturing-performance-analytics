# Manufacturing Performance Analytics

## Overview
A portfolio project demonstrating manufacturing data analysis using Databricks, PySpark, SQL, and Power BI. The project analyzes production output, quality defects, and machine downtime to identify operational performance patterns and support data-driven recommendations.

**Note:** This project uses simulated manufacturing data. It is not real company data.

## Business Objectives
- Monitor overall production output and defective units.
- Compare defect rates across machines.
- Analyze machine downtime.
- Explore daily production trends.
- Communicate findings through a Power BI dashboard.

## Technology Stack
- **Databricks:** Data processing and Delta table storage
- **PySpark:** Data validation, aggregation, and KPI calculations
- **SQL:** Manufacturing performance analysis
- **Power BI:** KPI cards and interactive visualizations

## Dataset
The simulated dataset contains 360 records covering 90 days, from January to March 2026, across four machines.

Key fields:
- `production_date`
- `machine_id`
- `product_type`
- `units_produced`
- `defective_units`
- `downtime_minutes`

## Key Performance Indicators
- Total production
- Total defective units
- Overall defect rate
- Machine-level defect rate
- Total machine downtime
- Daily production output

## Key Findings
- Total production: **409,334 units**
- Total defective units: **18,892**
- Overall defect rate: **4.62%**
- Machine M003 has the highest observed defect rate (**7.88%**) and downtime (**15,057 minutes**) in this simulated dataset.

These findings are exploratory. They do not establish the causes of defects or downtime.

## Recommendations
1. Review quality inspection records for machines with higher defect rates.
2. Examine maintenance logs and downtime reasons for machines with higher downtime.
3. Investigate daily production fluctuations using additional operational data.
4. Monitor defect rate and downtime KPIs regularly.

## Power BI Dashboard
The dashboard includes:
- Production, defect, and defect-rate KPI cards
- Daily production trend
- Defect rate by machine
- Machine downtime by machine

_Add the Power BI dashboard screenshot here._

## Project Status
- [x] Generate simulated manufacturing data
- [x] Perform data quality checks
- [x] Calculate machine-level KPIs using PySpark
- [x] Store data in a Databricks Delta table
- [x] Analyze performance using SQL
- [x] Build a Power BI dashboard
- [ ] Add notebook source code and dashboard screenshot
- [ ] Document the complete workflow

## Future Improvements
- Add production targets and performance comparisons.
- Analyze downtime categories and defect types.
- Connect Power BI directly to a suitable data source.
- Extend the analysis with more operational variables.

## Disclaimer
This is an educational portfolio project using simulated data. The results should not be interpreted as actual manufacturing performance.
