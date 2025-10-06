
# Patil's Paint Business Analysis Dashboard

## Overview
This Power BI project visualizes and analyzes the business performance of **Patil's Paint** for the year 2024.  
It includes both **descriptive analysis** (past trends) and **predictive analysis** (forecast for the next quarter) to help understand revenue, profit, and sales trends.

---

## Dataset
- Source: Patil's Paint internal sales and profit data  
- Time Period: January 2024 – December 2024  
- Granularity: Daily revenue and profit data  
- Key Columns:
  - `Date` – Transaction date
  - `Revenue` – Total revnue by Product 
  - `Profit` – Daily profit
  - `Units Sold` – Number of units sold per day
  - `Product` – Product name/category
  - `type` - product type
  - `Profit` - Total Profit By product

---

## Descriptive Analysis

### Line Charts
The dashboard includes **three line charts** representing **Revenue**, **Profit**, and **Units Sold** over 2024.

**Observations:**

- **Quarterly Sales Trend:**  
  - The **first quarter (Q1)** and **last quarter (Q4)** show slightly lower units sold compared to **Q2 and Q3**, indicating a seasonal dip in sales volume.  
  - Despite this, **revenue remains nearly constant** across all quarters, suggesting that higher-value products contributed significantly in lower-sales periods.  

- **Profit Margin Analysis:**  
  - **Q2** dominates in profit margin, largely due to increased sales of **high-margin products** such as **oil-based primers** and other premium paints.  
  - In **Q3**, although units sold are almost equal to Q2 and higher than Q4, the **profit margin is lower**, because sales shifted slightly towards **lower-margin products** like **brush thinners and accessories**.  

- **Key Insight:**  
  - Revenue alone does not fully capture business performance. Understanding the **product mix and profit contribution** is crucial.  
  - High-margin product sales can maintain strong profitability even during periods of slightly lower overall sales.

---

### Pie and Donut Charts
The dashboard includes **Pie and Donut charts** to analyze **revenue distribution across paint brands** and **product categories**.

**Observations:**

- **Brand-wise Revenue Contribution:**  
  - **Nerolac** contributes the **largest share of revenue (~40%)**, driven primarily by **high-margin paints**.  
  - Despite lower unit sales, Nerolac generates high revenue due to its focus on premium products.  

- **Asian Paints:**  
  - Generates significant revenue from **accessories and supplementary products** rather than high-margin paints.  
  - Higher unit sales compared to Nerolac, but **profit margins are lower** due to the product mix.  

- **Berger:**  
  - Maintains a **balanced mix of paints and accessories**, resulting in moderate revenue and consistent profit across both categories.  

- **Key Insight:**  
  - Revenue share alone does not indicate profitability. Brands with **high-margin products** may contribute disproportionately to revenue.  

---

### Bar Charts
The dashboard includes **bar charts** highlighting **product-wise sales performance**.

**Observations:**

- **Top-Selling Products:**  
  - **Paints** dominate sales, confirming they are the **primary revenue drivers** for Patil's Paint.  

- **Lower-Selling Products:**  
  - **Accessories** (brushes, thinners, and other supplementary items) contribute less to overall sales.  

- **Key Insight:**  
  - Understanding **product-level performance** helps in inventory planning, marketing focus, and identifying opportunities to increase sales of lower-performing categories.  

---

## Predictive Analysis

The dashboard includes **forecasting for revenue and profit** to anticipate business performance in the next quarter.

**Revenue Forecast:**

- Revenue is projected to **increase by 6.27%** in the next quarter if current trends continue.  
- Growth is primarily driven by **high-margin paint products** and consistent demand.

**Profit Forecast:**

- Profit margin is expected to improve by **4.37%** from the last year to the next quarter.  
- Increase is supported by **better sales of high-margin products**, careful cost management, and consistent revenue growth.

**Key Insight:**

- While sales volume may fluctuate across quarters, focusing on **high-margin products** helps maintain strong profitability.  
- The predicted growth indicates that Patil's Paint is likely to **experience stable revenue and improved profit margins** in the upcoming quarter, providing actionable insights for planning and strategy.

---

## Recommendations & Action Taken

After discussing the findings with stakeholders, the following actions and observations were considered for Patil's Paint:

- **Predictive Analysis:**  
  - Conducted after reviewing historical trends and consulting with stakeholders to ensure actionable insights.  

- **Low-Margin Products Identified:**  
  - Accessories such as **brushes, thinners, and other supplementary items** were identified as **low-margin products**.  

- **Stakeholder Suggestion:**  
  - Some stakeholders suggested **removing accessories** due to their lower margins.  

- **Data-Driven Decision on Accessories:**  
  - Based on analysis, accessories should **not be removed**, because:  
    - Many customers purchase them as **supplementary products**, necessary for using the main paints.  
    - Eliminating accessories could **disrupt the overall sales process** and reduce customer satisfaction.  

- **Action Suggested by Analyst:**  
  - **Premier White and Grey paints** were identified as **low-margin products**.  
  - Recommendation: **consider reducing or dropping these products** to focus on higher-margin paints and improve overall profitability.  

- **Key Takeaway:**  
  - High-margin products remain the primary profit drivers, while essential low-margin products (accessories) are maintained.  
  - Predictive analysis combined with stakeholder discussion provides a **balanced, data-driven approach** for business planning.  

---

## Dashboard Layout

- **Line Charts:** Revenue, Profit, and Units Sold trends with quarterly comparison  
- **Pie/Donut Charts:** Revenue distribution across brands and product categories  
- **Bar Charts:** Top-selling products vs. lower-selling accessories  
- **KPI Cards:** Quick glance at predicted changes in revenue and profit  
- **Forecast Visualization:** Revenue and profit predictions for the next quarter with upper/lower bounds

---

## Conclusion

The Power BI dashboard provides a **comprehensive view of Patil's Paint’ business performance**, highlighting both historical trends and expected performance for the upcoming quarter.  
It can help in **decision-making, planning, and identifying areas for improvement**.

---

## Future Work

- Include **product-wise or region-wise analysis**  
- Incorporate **additional predictive models** (seasonality, moving averages)  
- Automate **data refresh for real-time forecasting**
