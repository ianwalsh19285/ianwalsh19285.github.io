---
layout: page
title: Projects
subtitle:
full-width: true
---

<style>
.projects-wrap {
  max-width: 1180px;
  width: 94%;
  margin: 0 auto;
}

.projects-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1.5rem;
  margin-top: 1.5rem;
}

.project-card {
  display: block;
  text-decoration: none !important;
  color: inherit !important;
  background: #fafafa;
  border: 1px solid #e7e7e7;
  border-radius: 20px;
  overflow: hidden;
  box-shadow: 0 6px 18px rgba(0,0,0,0.04);
  transition: transform 0.15s ease, box-shadow 0.15s ease;
}

.project-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 10px 24px rgba(0,0,0,0.07);
}

.project-card img {
  width: 100%;
  height: 220px;
  object-fit: cover;
  display: block;
}

.project-card-title {
  padding: 1rem 1.1rem;
  font-size: 1rem;
  font-weight: 600;
  line-height: 1.5;
  text-align: center;
}

@media (max-width: 1000px) {
  .projects-grid {
    grid-template-columns: repeat(2, 1fr);
  }

  .project-card img {
    height: 240px;
  }
}


@media (max-width: 800px) {
  .projects-grid {
    grid-template-columns: 1fr;
  }


  .project-card img {
    height: 230px;
  }
}
</style>

<div class="projects-wrap">
  <div class="projects-grid">

    <a class="project-card" href="/projects/data-centers/">
      <img src="/assets/img/projects/map_dcs_2022.png" alt="Map showing data center distribution across the contiguous United States">
      <div class="project-card-title">M.S. Capstone — The Local Economic Impact of Data Centers</div>
    </a>

    <a class="project-card" href="/projects/prague-metro/">
      <img src="/assets/img/projects/milestone_5.png" alt="Screenshot of a dashboard analyzing Prague metro wait times">
      <div class="project-card-title">Prague Metro Analytics Pipeline</div>
    </a>

    <a class="project-card" href="/projects/healthcare-dashboard/">
      <img src="/assets/img/projects/medications.png" alt="Screenshot of healthcare analytics dashboard">
      <div class="project-card-title">Healthcare Analytics Dashboard</div>
    </a>

    <a class="project-card" href="/projects/portland-transit/">
      <img src="/assets/img/projects/vulnerability_vs_businesses.png" alt="Visualization of Portland transit and business density analysis">
      <div class="project-card-title">Portland Transit, Business Density, and Neighborhood Health</div>
    </a>

    <a class="project-card" href="/projects/linkedin-analysis/">
      <img src="/assets/img/projects/random_forest_confusion.png" alt="Random forest confusion matrix for salary bin classification">
      <div class="project-card-title">Job Salary Prediction Model</div>
    </a>

    <a class="project-card" href="/projects/covid-mental-health/">
      <img src="/assets/img/projects/regional_symptoms_over_time.png" alt="Regional line chart showing anxiety and depression symptom trends over time">
      <div class="project-card-title">Mental Health Trends After COVID-19</div>
    </a>

    <a class="project-card" href="/projects/pfas/">
      <img src="/assets/img/projects/RegressionModel.png" alt="Regression plot showing cancer prevalence by PFAS type">
      <div class="project-card-title">PFAS Concentration and Cancer Rates</div>
    </a>

  </div>
</div>