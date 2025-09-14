# Retail Sales Performance Dashboard

This project develops an interactive Excel-based dashboard for a mid-size retailer to monitor and analyze sales performance across regions, product categories, and time periods. The goal is to provide leadership with a single-page view, drill-down capability, and automated reporting that replaces a previously manual process requiring several hours each cycle.

### Features and Functionality
- Power Query for data cleaning (removing nulls, formatting dates).
- PivotTables with slicers for interactive filtering.
- Conditional formatting for visual alerts (e.g., red cells for regions below target).
- A KPI summary at the top (Revenue, Growth %, Top Product).

### Data sources
The dataset used for this project is publicly available on Kaggle: https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting

### Deliverable
- Dashboard Tab – A clean, interactive dashboard that consolidates all key views.
- Assumptions Tab – Documentation of cleaning rules, calculated metrics, and business logic applied.
- Raw Data Tab – Original dataset for transparency and reproducibility.
- Insights & Recommendations Slide – A polished one-pager summarizing findings and actionable recommendations.

--

### 1. Data Cleaning Process
#### 1.1 Checking for Duplicates and Missing Values

Duplicates and null values are identified and removed using Power Query.

![Check-Duplicate](media/check-duplicate.png)

![Data-Cleaning](media/data-cleaning.png)

#### 1.2 Handling Data Types

Directly converting text to date formats can result in errors.

![Error-Date](media/error-date.png)

The issue is resolved by using locale-based formatting, ensuring dates are interpreted correctly.

![Locale](media/using-locale.png)
![Sol-Date](media/solution-date.png)

