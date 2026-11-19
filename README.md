# Uber Ride & Revenue Analytics Dashboard

An end-to-end **Power BI** analytics solution built to evaluate over **150,000 ride bookings**, uncovering revenue leakage from cancellations, high-performing vehicle categories, and peak demand corridors to support operational and driver performance decisions.

---

## Executive Summary & Key Findings

* **Scale Analyzed:** 150,000+ ride records tracked across total revenue, trip distance, and customer ratings.
* **Cancellation & Revenue Leakage:** Data cleaning and status segmentation in Power Query revealed that **nearly 30% of bookings were lost or canceled**, representing substantial unrealized revenue and supply-demand friction.
* **Vehicle Category Performance:** **Autos** emerged as the highest-earning vehicle category overall, outperforming other fleet segments in revenue contribution.
* **High-Traffic Corridors:** Route-level analysis surfaced high-volume corridors—including **Khandsa to Ashram**—providing clear targets to improve vehicle positioning, pickup availability, and driver utilization.

---

## Tech Stack & Tools

* **Power BI Desktop:** Interactive reporting, data modeling, DAX measures, and visual storytelling.
* **Power Query (M):** Data ingestion, cleansing, null/outlier handling, status standardization, and transformation.
* **DAX:** Custom business metrics, cancellation rates, revenue KPIs, and category/route breakdowns.
* **Microsoft Excel:** Initial data inspection, lookup/reference checks, and validation.
* **Data Modeling & Data Visualization:** Star-schema relationships, KPI cards, trend visuals, category comparisons, and route rankings.

---

## Data Preparation & Modeling

1. **Data Cleansing (Power Query):**
   * Standardized booking statuses (completed, canceled, lost/incomplete) to isolate the **~30% lost/canceled** share accurately.
   * Cleaned fare/revenue fields, trip distance values, timestamps, route pairs, and customer rating scores.
   * Handled missing values, duplicates, and formatting inconsistencies prior to loading into the model.
2. **Data Model:**
   * Structured tables around core ride transactions alongside supporting dimensions (such as vehicle category, booking status, time/date attributes, and route/location details) to keep DAX calculations fast and unambiguous.
3. **DAX Metrics:**
   * Calculated core KPIs including **Total Bookings**, **Total Revenue**, **Lost / Canceled Booking %**, **Average Trip Distance**, and **Average Customer Rating**, sliced by vehicle type, route, and time period.

---

## Dashboard Highlights

* **KPI Overview:** At-a-glance cards for total ride volume, revenue, cancellation/loss rate, average distance, and customer ratings.
* **Revenue & Cancellation Breakdown:** Visual comparison of completed vs. canceled/lost rides to highlight where revenue drops off.
* **Vehicle Category Comparison:** Side-by-side performance across vehicle types, spotlighting **Autos** as the top revenue generator.
* **Route & Demand Analysis:** Identification of high-demand routes such as **Khandsa to Ashram** to guide fleet allocation and driver incentives.

