# Retail Sales Performance Dashboard

A mid-size retailer wants to track sales performance across regions, categories, and months. Leadership needs a single-page dashboard with drill-down capability, replacing manual reporting that takes hours.

### Excel features:
- Power Query for data cleaning (removing nulls, formatting dates).
- PivotTables with slicers for interactive filtering.
- Conditional formatting for visual alerts (e.g., red cells for regions below target).
- A KPI summary at the top (Revenue, Growth %, Top Product).

### Data sources
https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting

### Deliverable
A clean dashboard tab, assumptions tab, and raw data tab. A polished slide summarizing “Insights & Recommendations.”

--

### 1. Data Cleaning
#### 1.1 Check for duplicate and missing value
![Check-Duplicate](media/check-duplicate.png)

![Data-Cleaning](media/data-cleaning.png)

#### 1.2 Data type

If we change the data type directly from text to date, it might shows error like this 

![Error-Date](media/error-date.png)

Therefore the solution

