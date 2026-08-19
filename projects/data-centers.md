---
layout: page
---

<div class="project-shell">

<div class="project-hero">
  <h1>The Local Economic Impact of Data Centers</h1>
  <p class="project-subtitle">Graduate capstone project</p>
</div>

<img class="project-image" src="/assets/img/projects/map_dcs_2022.png" alt="Datacenter map">

<div class="project-copy">
  <p>
    This project examined how data centers are associated with local economic outcomes across counties in the contiguous United States. The analysis used public county-level datasets and a consistent NAICS 518 definition to study employment, income, construction activity, unemployment, and air quality outcomes.
  </p>

  <h2>What I built</h2>
  <ul>
    <li>A normalized PostgreSQL database integrating county-level data from multiple public sources.</li>
    <li>A reproducible data pipeline for cleaning, joining, and spatially transforming economic and environmental datasets.</li>
    <li>A county-level analytical workflow combining difference-in-differences regression, PCA, k-means clustering, and exploratory variational autoencoder modeling.</li>
    <li>A final report to communicate methods, findings, and limitations.</li>
  </ul>

  <h2>Key outcomes</h2>
  <ul>
    <li>Found that data centers are associated with mixed local impacts rather than uniformly positive or negative outcomes.</li>
    <li>Identified meaningful differences between counties with low and high concentrations of data centers.</li>
    <li>Demonstrated how public data can be used to study an industry that is usually difficult to analyze because of limited facility-level transparency.</li>
  </ul>
</div>

<img class="project-image-secondary" src="/assets/img/projects/did_clusters_poster.png" alt="Outcomes chart">

<div class="project-copy">
  <h2>Links</h2>
  <ul>
    <li><a href="https://github.com/wu-msds-capstones/The-Local-Economic-Impact-of-Data-Centers" target="_blank" rel="noopener noreferrer">GitHub Repository</a></li>
    <li><a href="https://wu-msds-capstones.github.io/The-Local-Economic-Impact-of-Data-Centers/" target="_blank" rel="noopener noreferrer">Project Report Webpage</a></li>
  </ul>
</div>

</div>