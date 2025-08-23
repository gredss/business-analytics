# Project Management in Excel

This repository documents my learning journey in using **Microsoft Excel** as a project management tool. While many organizations rely on ERP systems, I explored how Excel can still deliver practical value for project tracking, visualization, and evaluation. Each section reflects not only the technical content but also **what I learned** as I worked through the material.

---

## 1. Introduction

### Driving Project Effectiveness with Excel

I learned that Excel can serve as a flexible alternative to specialized project management software, especially when accessibility and speed matter more than enterprise-wide integration.

### Positioning Excel in Project Management: Advantages over ERP Systems

I understood the trade-offs: ERP systems bring structure and scale, but Excel is often faster to set up, cheaper to use, and easier to adapt to different project contexts.

---

## 2. Project Tracking in Excel

### Structuring and Managing Data with Excel Tables

I learned how Excel Tables keep project data organized and dynamic. Structured references and filters make it easier to manage long task lists.

### Defining and Monitoring Project Metadata

I realized that adding metadata (owners, deadlines, status) is critical because it allows projects to be analyzed and filtered in meaningful ways.

### Leveraging Conditional Formatting to Flag Trends and Risks

I practiced using conditional formatting to automatically highlight overdue tasks or high-risk items. For example, I used formulas like `=TODAY()>[EndDate]` to flag delays.

### Delivering Executive Summaries with PivotTables

I learned how PivotTables can condense detailed task data into summaries for stakeholders, such as completion rates or workload distribution.

---

## 3. Data Visualization for Communicating Project Status

### Applying Descriptive Analytics to Project Reporting

I discovered how to calculate and report simple metrics, like completion percentage, using formulas such as:

```excel
=COUNTIF([Status],"Completed")/COUNTA([Status])
```

### Presenting Progress Through Visual Charts

I learned to build progress charts that translate raw data into visuals that managers can quickly interpret.

### Enhancing Insights with In-Cell Bar Charts

I experimented with sparklines and even text-based bar charts using `REPT("█",value)` to create quick, compact progress indicators.

### Tracking KPIs and Performance Metrics

I gained a clearer understanding of which KPIs matter (on-time delivery, budget variance, schedule adherence) and how to calculate them using SUMIF and PivotTables.

---

## 4. Gantt Charts to Visualize a Project Portfolio

### The Role of Gantt Charts in Project Management

I learned why Gantt charts are still widely used: they make dependencies, overlaps, and bottlenecks easy to spot.

### Building Effective Gantt Charts in Excel

I practiced creating a Gantt chart using a stacked bar chart, where one series represents start dates and the other represents task durations.

### Performing Scenario Analysis with Gantt Charts

I experimented with shifting task start dates to test different timelines, which gave me a hands-on sense of how sensitive projects are to small delays.

---

## 5. Calculating Earned Value Management in Excel

### Applying EVM to Assess Project Progress and Success

I learned the key EVM formulas:

* EV = Budget × % Complete
* PV = Budget × % Planned
* SPI = EV ÷ PV
* CPI = EV ÷ AC

This helped me see how to measure both schedule and cost efficiency.

### Developing an Excel-Based EVM Calculator

I built a small calculator that automatically computes SPI and CPI from task-level data, which made me appreciate how Excel can mimic more advanced project management tools.

---

## 6. Putting It All Together: Designing a Project Management Dashboard

### Familiarizing with Project Data Inputs

I learned that before building dashboards, the real work is cleaning and structuring the raw task data.

### Deriving Key Metrics and Performance Indicators

I identified the main metrics that stakeholders care about: completion %, schedule adherence, cost variance, and risk indicators.

### Structuring and Designing the Dashboard Layout

I practiced arranging KPI cards, charts, and the Gantt chart into a clean, executive-friendly layout.

### Integrating Gantt Charts into the Dashboard

I embedded my Gantt chart into the dashboard and linked it with slicers, learning how interactivity improves usability.

### Executing Scenario Analysis in Excel

I experimented with Excel’s Scenario Manager to test “what-if” cases such as delays or cost overruns, giving me insight into the decision-making side of project management.

---

## Conclusion

Overall, I learned that Excel, when structured well, is more than just a spreadsheet. It can serve as a **project management system**, covering tracking, visualization, earned value, and dashboards. While not a replacement for ERP systems, it provides flexibility and accessibility that make it a valuable tool for consultants, analysts, and project managers.

---
