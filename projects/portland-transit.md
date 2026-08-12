---
layout: page
title: Portland Transit, Business Density, and Neighborhood Health
subtitle: Spatial data engineering project
css-class: project-page
full-width: true
---

![Transit Dashboard Screenshot](/assets/img/projects/vulnerability_vs_businesses.png)

This project explored whether public transit presence in the Portland area is correlated with business activity and socioeconomic health indicators. It integrated GTFS transit data, business license records, and census geography to analyze how transportation infrastructure relates to neighborhood-level conditions.

## What I built

- A structured schema with tables for routes, trips, stop times, transit stops, businesses, and vulnerability scores.
- Data cleaning for difficult transit and geographic edge cases, including post-midnight GTFS times, missing route names, duplicate business records, and inconsistent ZIP codes.
- GIS-assisted preprocessing using QGIS to align transit stops, ZIP codes, and census tract data, then loading them into PostgreSQL with PostGIS.
- An analytical dashboard to communicate findings.

## Key outcomes

- Found a positive correlation between public transit and business density.
- Found that transit stop presence was not clearly correlated with the socioeconomic indicators used in the analysis.
- Identified a negative relationship between business density and economic vulnerability.
