---
layout: page
title: Projects
subtitle: Selected work in data science, analytics, and dashboard development
---

## Project Portfolio

This page highlights selected projects in data science, data engineering, visualization, and applied analytics. 

---

## The Local Economic Impact of Data Centers

**Project type:** Graduate Capstone  
**Tools:** Python, pandas, numpy, plotly, seaborn, geopandas, PyTorch, scikit-learn, PostgreSQL  
[**GitHub**](https://github.com/wu-msds-capstones/The-Local-Economic-Impact-of-Data-Centers)  
[**Project Report Webpage**](https://wu-msds-capstones.github.io/The-Local-Economic-Impact-of-Data-Centers/)

### Overview
This project examined how data centers are associated with local economic outcomes across counties in the contiguous United States. The analysis used public county-level datasets and a consistent NAICS 518 definition to study employment, income, construction activity, unemployment, and air quality outcomes.  

### What I built
- A normalized PostgreSQL database integrating county-level data from multiple public sources.
- A reproducible data pipeline for cleaning, joining, and spatially transforming economic and environmental datasets.
- A county-level analytical workflow combining difference-in-differences regression, PCA, k-means clustering, and exploratory variational autoencoder modeling.
- A final report to communicate methods, findings, and limitations.

### Key outcomes
- Found that data centers are associated with mixed local impacts rather than uniformly positive or negative outcomes.
- Identified meaningful differences between counties with low and high concentrations of data centers.
- Demonstrated how public data can be used to study an industry that is usually difficult to analyze because of limited facility-level transparency.

![Datacenter Map](/assets/img/projects/map_dcs_2022.png)
*Map of data center distribution across the contiguous United States in 2022*

![Outcomes](/assets/img/projects/did_clusters_poster.png)
*Key difference-in-differences regression findings*

---

## Healthcare Analytics Dashboard

**Project type:** Data Visualization
**Tools:** R, Shiny, ggplot2 
<!-- **GitHub:** [Add GitHub repo link here]()  
**Live demo:** [Add live app link here]() -->

### Overview
This project is an interactive healthcare dashboard designed to demonstrate how clinical teams could explore patient activity, medications, deliveries, cardiac events, and mental health metrics in a single application. It uses synthetic CMS-style patient data to showcase dashboard design and filtering patterns across multiple healthcare use cases.

### What I built
- A multi-page Shiny dashboard with sections for summary metrics, urgent/emergency care, medications, deliveries, cardiac events, and mental health.
- Interactive filtering by time range, sex, and race/ethnicity across views.
- Visualizations including time series, boxplots, choropleth maps, Sankey flows, and searchable data tables.
- A themed dashboard UI with a consistent clinical-style layout and branded components.

### Key outcomes
- Built a dashboard that demonstrates capabilities across several healthcare analytics workflows.
- Combined static and interactive visualizations to support both quick monitoring and deeper exploration.
- Designed the app to communicate technical flexibility to non-technical stakeholders interested in custom dashboard services.

![Medications Page](/assets/img/projects/medications.png)
*'Medications' page of the dashboard*

---

## Portland Transit, Business Density, and Neighborhood Health

**Project type:** Data Engineering
**Tools:** PostgreSQL, PostGIS, QGIS
<!-- **GitHub:** [Add GitHub repo link here]()  
**Project materials:** [Add project link here]() -->

### Overview
This project explored whether public transit presence in the Portland area is correlated with business activity and socioeconomic health indicators. It integrated GTFS transit data, business license records, and census geography to analyze how transportation infrastructure relates to neighborhood-level conditions.

### What I built
- A structured schema with tables for routes, trips, stop times, transit stops, businesses, and vulnerability scores.
- Data cleaning steps for difficult transit and geographic edge cases, including post-midnight GTFS times, missing route names, duplicate business records, and inconsistent ZIP codes.
- GIS-assisted preprocessing using QGIS to align transit stops, ZIP codes, and census tract data, and loading into a PostgreSQL database using PostGIS.
- An analytical dashboard to communicate findings.

### Key outcomes
- Found a positive correlation between public transit and business density.
- Found that transit stop presence was not clearly correlated with the socioeconomic indicators used in the analysis.
- Identified a negative relationship between business density and economic vulnerability.

![Transit Dashboard Screenshot](/assets/img/projects/vulnerability_vs_businesses.png)
*Dashboard page analyzing census vulnerability scores versus business density in portland*