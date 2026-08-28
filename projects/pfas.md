---
layout: page
---


<div class="project-shell">


<div class="project-hero">
  <h1>PFAS Concentration and Cancer Rates</h1>
  <p class="project-subtitle">Data science with R project</p>
</div>


<img class="project-image" src="/assets/img/projects/RegressionModel.png" alt="Regression plot showing cancer prevalence by PFAS type">


<div class="project-copy">
  <p>
    This project explored whether concentrations of PFOA, PFOS, and PFNA in drinking water were associated with adult non-skin cancer prevalence across U.S. ZIP codes. It combined EPA UCMR 5 drinking water data with CDC PLACES health data, then used multiple linear regression in R to examine whether PFAS concentrations remained significant after accounting for smoking prevalence, food insecurity, routine checkups, and adult population.
  </p>


  <h2>What I built</h2>
  <ul>
    <li>A cleaned and merged ZIP-code-level dataset combining EPA contaminant monitoring data with CDC health estimates.</li>
    <li>Data preparation steps to remove unusable fields, join public water systems to ZIP codes, replace below-reporting-level PFAS values with minimum reporting levels, and pivot contaminant measurements into analysis-ready columns.</li>
    <li>An exploratory analysis workflow in R using summary statistics, distribution checks, and visualizations of PFAS concentration and cancer prevalence.</li>
    <li>A multiple linear regression model with transformed PFAS variables and additional control variables, along with diagnostic checks for residual patterns, Q-Q behavior, leverage, and multicollinearity.</li>
  </ul>


  <h2>Key outcomes</h2>
  <ul>
    <li>The fitted model explained about 60% of the variation in cancer prevalence, but the regression assumptions were not adequately met.</li>
    <li>PFOA and PFOS were statistically significant in the model, but their coefficients pointed in opposite directions, while PFNA was not significant.</li>
    <li>Because of assumption violations and conflicting coefficient behavior, the project did not support rejecting the null hypothesis of no significant association between these PFAS concentrations and cancer prevalence.</li>
    <li>The analysis highlighted important limitations in environmental health data, especially minimum reporting level constraints, cross-sectional timing issues, and the difficulty of measuring total exposure from water alone.</li>
  </ul>

  <h2>Links</h2>
  <ul>
    <li><a href="https://github.com/ianwalsh19285/PFAS-and-cancer" target="_blank" rel="noopener noreferrer">GitHub Repository</a></li>
    <li><a href='{{ "/project-reports/pfas-report.pdf" | relative_url }}' target="_blank" rel="noopener noreferrer">Project Report Webpage</a></li>
  </ul>
</div>


</div>