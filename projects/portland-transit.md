---
layout: page
---

<div class="project-shell">

<div class="project-hero">
  <h1>Portland Transit, Business Density, and Neighborhood Health</h1>
  <p class="project-subtitle">Spatial data engineering project</p>
</div>

<div class="project-overview">
  <div class="project-overview-image">
    <img class="project-image" src="/assets/img/projects/vulnerability_vs_businesses.png" alt="Transit dashboard screenshot">
  </div>

  <div class="project-overview-copy">
    <p>
      This project explored whether public transit presence in the Portland area is correlated with business activity and socioeconomic health indicators. It integrated GTFS transit data, business license records, and census geography to analyze how transportation infrastructure relates to neighborhood-level conditions.
    </p>
  </div>
</div>

<div class="project-copy">
  <h2>What I built</h2>
  <ul>
    <li>A structured schema with tables for routes, trips, stop times, transit stops, businesses, and vulnerability scores.</li>
    <li>Data cleaning for difficult transit and geographic edge cases, including post-midnight GTFS times, missing route names, duplicate business records, and inconsistent ZIP codes.</li>
    <li>GIS-assisted preprocessing using QGIS to align transit stops, ZIP codes, and census tract data, then loading them into PostgreSQL with PostGIS.</li>
    <li>An analytical dashboard to communicate findings.</li>
  </ul>

  <h2>Key outcomes</h2>
  <ul>
    <li>Found a positive correlation between public transit and business density.</li>
    <li>Found that transit stop presence was not clearly correlated with the socioeconomic indicators used in the analysis.</li>
    <li>Identified a negative relationship between business density and economic vulnerability.</li>
  </ul>
</div>

</div>