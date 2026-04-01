## Cyclistic Bike-Share Membership Conversion Analysis

### Overview

This project analyzes 12 months of Cyclistic bike-share data (March 2025 – February 2026) to uncover behavioral differences between members and casual riders.

The goal is to translate data into actionable insights that support membership growth and business decision-making.

### Business Objective
How can Cyclistic convert casual riders into annual members?

### Tools & Technologies
- **Python** (Pandas, NumPy) – data cleaning, transformation, and feature engineering
- **Tableau** – interactive dashboard and data visualization

### Dataset
- 12 monthly CSV files merged into a single dataset
- Includes ride timestamps, user type, bike type, and station information
- Data prepared and structured for time-based and behavioral analysis

### Data Cleaning & Preparation
- Merged multiple datasets into one unified dataset
- Removed duplicate records using ride_id
- Handled missing values (dropped critical fields, labeled others as “Unknown”)
- Converted timestamp columns into datetime format
- Removed invalid ride durations (negative or over 24 hours)
- Sorted dataset chronologically

### Dashboard
[View Interactive Dashboard](https://public.tableau.com/app/profile/marlon.kolivas/viz/CyclisticBikeShareAnalysisMembervsCasual/OGCyclisticDashboard) 

The dashboard highlights:
- Hourly, daily, monthly, and seasonal trends
- Ride duration patterns
- Bike type usage
- Member vs casual comparisons
- Conversion opportunity insights

### Recommendations
- Target commuter-like casual riders with tailored membership incentives
- Leverage seasonal peaks with marketing campaigns during high-usage months
- Promote cost savings and convenience of membership to frequent riders

### Conclusion
This analysis demonstrates how behavioral data can be used to identify high-value user segments and support strategic decision-making. By focusing on data-driven targeting, Cyclistic can effectively convert casual riders into long-term members and improve overall system utilization.

### Future Improvements
- Add geospatial analysis (station-level insights)
- Build predictive models for conversion likelihood
- Automate data pipeline for scalability

### Summary
End-to-end data analysis project demonstrating data cleaning, feature engineering, exploratory analysis, visualization, and business insight generation.
