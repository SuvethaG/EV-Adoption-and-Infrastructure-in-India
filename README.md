# Electric Vehicle (EV) Adoption & Infrastructure Readiness – Power BI Dashboard

## A Data Analytics Project using Power BI, Power Query, and DAX

### Project Overview

This project analyzes the growth of Electric Vehicle (EV) registrations in India and evaluates charging infrastructure readiness across states. The dashboard provides insights into trends, adoption patterns, state-level performance, charging station expansion, and EV vs. PCS (Public Charging Stations) correlation and forecasting.

### Objectives

The dashboard answers the following key questions:
* How have EV registrations grown from 2014 to 2023?
* Which states lead in EV adoption and EV share?
* How rapidly are public charging stations (PCS) growing (2017–2025)?
* Is EV adoption aligned with infrastructure expansion?
* What is the EV-to-charging-station load ratio by state?
* How is future EV adoption expected to grow?

### Dataset Information

This project uses following datasets from VAHAN Dashboard / Ministry of Road Transport & Highways (MoRTH):
* State-wise EV Registrations (2014–2023)
*  State-wise Total EVs registered as a percentage of Total Vehicles registered
* Public Charging Station Deployment (2017–2025)
* EV Segment Share under FAME India (2W, 3W, 4W)
* Year-wise EV registration from 2014-2023

### Data Preparation (Power Query):

* Removed duplicates & null values
* Standardized state names
* Created relationships between EV and PCS datasets
* Added date table for time-series analysis
* Derived YoY growth fields

### Key KPIs

* 4M – Total EVs registered
* 2M – Latest-year EVs (2023)
* 2.53% – YoY Growth in EVs
* 2023 – Maximum EV registration year
* Top State: Uttar Pradesh – 249K EVs
* Highest EV Share: Delhi – 7.72%


### Key Insights

* EV registrations show strong growth from 2014–2023, peaking in 2023.
* Uttar Pradesh leads in total EVs, while Delhi has the highest EV share (~7.7%).
* Public Charging Stations are increasing but still lag behind EV growth in several states.
* States like Chandigarh, Bihar, Assam, Tripura show higher EV load per charging station (need more PCS).
* 2-wheelers dominate EV adoption with 88% share.
* Forecasting indicates strong EV growth till 2030.

### Tools & Technologies

* Power BI Desktop
* Power Query for data cleaning
* DAX for KPIs, ratios, YoY calculations
* Forecasting tool in Power BI visuals
* Card, Line, Bar, Map, and Scatter visuals

### How to Open the Dashboard

* Download the .pbix file
* Open in Power BI Desktop
* Refresh if dataset paths change
