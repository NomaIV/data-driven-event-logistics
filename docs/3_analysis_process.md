# Analysis Process Documentation

## Overview
This document outlines the analytical methodology used to determine event viability and optimize the Unilever Sports Day schedule for 1,000+ employees.

## Key Analytical Steps:

### 1. Data Collection & Cleaning
- Survey design using Microsoft Forms capturing:
  - Employee interest across 10+ sporting codes
  - Departmental affiliation
  - Availability confirmation
- Data validation and normalization in Excel

### 2. Viability Modeling
- Created Excel model using `FLOOR` function:
Teams Possible = FLOOR(Interested Count / Minimum Players Required, 1)
- Conditional formatting to flag non-viable activities
- Minimum threshold: Teams Possible ≥ 1

### 3. Resource Optimization
- Departmental participation heatmaps using PivotTables
- Time-slot scheduling matrix
- Venue capacity vs. demand analysis

### 4. Forecasting & Recommendations
- Participation rate forecasting (achieved 85% accuracy)
- Resource allocation optimization
- Risk assessment for logistics bottlenecks

## Technical Implementation:
- **Primary Tool:** Microsoft Excel
- **Key Formulas:** `FLOOR`, `COUNTIFS`, `AVERAGEIFS`, Conditional Formatting
- **Visualization:** PivotTables, Departmental Heatmaps
- **Decision Framework:** Objective viability thresholds

*Full detailed analysis workbook with sample data will be available by 24/02/2026.*

