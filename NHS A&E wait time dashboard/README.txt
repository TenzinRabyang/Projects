Overview

This repository contains a Power BI dashboard analyzing NHS A&E (Accident & Emergency) waiting times across 12 months (October 2024–September 2025). The dashboard visualizes key performance metrics, including the target performance, emergency admissions, breaches and decision-to-admit, using data sourced from NHS England. It demonstrates data cleaning, transformation, and visualization skills for healthcare analytics.

Project Details
Data Source: NHS England A&E Attendances and Emergency Admissions (monthly Excel files from https://www.england.nhs.uk/statistics/statistical-work-areas/ae-waiting-times-and-activity/ae-attendances-and-emergency-admissions-2025-26/).

Time Period: October 2024 to September 2025.
Tools: Power BI Desktop.

Key Metrics:

Average 4-hour performance (% of patients treated within 4 hours).
Total attendances and >4-hour breaches.
Emergency admissions.
Patients waiting >4 hours from decision to admit.

Features:
Details Drill Through page.
KPI metrics using CARD.
Trend analysis via line and area charts.
Regional comparisons ArcGIS maps and bar charts.
Target tracking with gauges.
Using buttons for more interactive such as filter reset.

Development Process

Data Collection: Downloaded and organized 12 monthly A&E Excel files.
Data Preparation: Combined files using Power Query, cleaned metadata, and appended the data.
Analysis: Created DAX measures (e.g., Breach %, Avg 4hr Performance %) to derive insights.
Visualization: Built a two-page dashboard with KPIs, charts, and interactivity.
Testing: Validated metrics against raw data.