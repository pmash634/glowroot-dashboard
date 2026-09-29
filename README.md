# GlowRoot Naturals – Field Activation Performance Dashboard

## Overview
GlowRoot Naturals runs an in-store promoter campaign across multiple retail outlets in Lagos. This project turns a raw, task-level promoter activity log into a clean, single-page Excel dashboard that gives the Trade Marketing team a fast view of where field effort is going, how efficiently promoters are working, and how much logged activity is actually getting completed.

## Tools Used
- Microsoft Excel (PivotTables, PivotCharts, Slicers)
- Excel Tables for structured, dynamic data referencing

## Data Preparation
- Converted the raw dataset into a formatted Excel Table
- Verified no duplicate log entries or blank rows
- Confirmed the Date column was stored as a true date type
- Standardized capitalization and spacing across text fields (Promoter Name, Area, Outlet Name, Task Type, Status)

## Dashboard Components

**KPIs**
- Total Tasks Completed
- Average Completion Time
- Average Quality Score

**Visual 1 — Activity Concentration**
Which outlets are generating the most task activity, broken down by task type.
*PivotTable: Rows = Outlet Name, Columns = Task Type, Values = Sum of Tasks Completed*
*Chart: Clustered Column*

**Visual 2 — Promoter Efficiency**
Which promoters are taking the longest to complete tasks.
*PivotTable: Rows = Promoter Name, Values = Average Completion Time*
*Chart: Bar Chart*

**Visual 3 — Work Completion Health**
Proportion of tasks that are Completed, Overdue, or Pending.
*PivotTable: Rows = Status, Values = Count of Tasks*
*Chart: Doughnut Chart*

**Slicer**
A single Area slicer connected to all three PivotTables/PivotCharts, so the entire dashboard filters together by outlet location.

## Dashboard Preview
![Dashboard Screenshot](screenshot.png)

## Files
- `PurityMacharia.xlsx` — full working dashboard file with PivotTables, PivotCharts, KPIs, and slicer
- `screenshot.pdf` — static snapshot of the final one-page dashboard view