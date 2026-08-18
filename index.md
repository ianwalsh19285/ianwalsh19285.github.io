---
layout: page
title: Ian Walsh
subtitle: Data Scientist
full-width: true
---

<style>
.home-wrap {
  max-width: 1180px;
  width: 94%;
  margin: 0 auto;
}

.home-hero {
  display: grid;
  grid-template-columns: 390px 1fr;
  gap: 4.25rem;
  align-items: center;
  margin: 1.5rem 0 3.8rem 0;
}

.home-portrait img {
  width: 100%;
  max-width: 390px;
  border-radius: 28px;
  display: block;
  object-fit: cover;
  box-shadow: 0 12px 32px rgba(0,0,0,0.10);
}

.home-intro {
  max-width: 760px;
}

.hero-kicker {
  font-size: 0.95rem;
  font-weight: 700;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  color: #6b4b3e;
  margin: 0 0 1rem 0;
}

.hero-summary {
  font-size: 2rem;
  line-height: 1.35;
  font-weight: 600;
  margin: 0 0 1.2rem 0;
  max-width: 18ch;
}

.hero-detail {
  font-size: 1.08rem;
  line-height: 1.9;
  color: #4f4f4f;
  margin: 0 0 1.5rem 0;
  max-width: 58ch;
}

.hero-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 0.8rem;
}

.hero-button {
  display: inline-block;
  padding: 0.72rem 1.05rem;
  border: 1px solid #d8d8d8;
  border-radius: 999px;
  background: #fafafa;
  color: #404040 !important;
  text-decoration: none !important;
  font-size: 0.95rem;
  font-weight: 600;
  line-height: 1;
  transition: background 0.15s ease, border-color 0.15s ease, transform 0.15s ease, box-shadow 0.15s ease;
}

.hero-button:hover {
  background: #f2f2f2;
  border-color: #cfcfcf;
  transform: translateY(-1px);
  box-shadow: 0 6px 16px rgba(0,0,0,0.05);
}

.section-divider {
  margin: 3rem 0 2.8rem 0;
  border: none;
  border-top: 1px solid #ddd;
}

.expertise-section,
.featured-projects {
  text-align: center;
}

.expertise-section h2,
.featured-projects h2 {
  margin-bottom: 0.55rem;
}

.expertise-section .section-note,
.featured-projects .section-note {
  color: #666;
  margin-bottom: 2rem;
  font-size: 1rem;
}

.expertise-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 2rem;
  margin-bottom: 3rem;
}

.expertise-card {
  text-align: center;
}

.expertise-card .icon {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-bottom: 0.8rem;
}

.expertise-card .icon svg {
  width: 34px;
  height: 34px;
  stroke: #6b4b3e;
  stroke-width: 1.8;
}

.expertise-card h3 {
  margin-top: 0;
  margin-bottom: 0.45rem;
  font-size: 1.02rem;
}

.expertise-card p {
  margin: 0 auto;
  max-width: 20ch;
  font-size: 0.96rem;
  line-height: 1.7;
  color: #555;
}

.featured-projects {
  margin-bottom: 3.5rem;
}

.featured-projects-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1.5rem;
}

.featured-project-card {
  display: flex;
  flex-direction: column;
  text-decoration: none !important;
  color: inherit !important;
  background: #fafafa;
  border: 1px solid #e7e7e7;
  border-radius: 20px;
  overflow: hidden;
  box-shadow: 0 6px 18px rgba(0,0,0,0.04);
  transition: transform 0.15s ease, box-shadow 0.15s ease;
}

.featured-project-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 10px 24px rgba(0,0,0,0.07);
}

.featured-project-card img {
  width: 100%;
  height: 220px;
  object-fit: cover;
  display: block;
}

.featured-project-card-title {
  padding: 1.05rem 1.15rem 1.2rem 1.15rem;
  font-size: 1rem;
  font-weight: 600;
  line-height: 1.55;
  text-align: left;
}

@media (max-width: 950px) {
  .home-hero {
    grid-template-columns: 1fr;
    text-align: center;
    gap: 2rem;
  }

  .home-portrait {
    display: flex;
    justify-content: center;
  }

  .home-intro {
    max-width: 100%;
    margin: 0 auto;
  }

  .hero-summary,
  .hero-detail {
    max-width: 100%;
  }

  .hero-summary {
    font-size: 1.6rem;
  }

  .hero-actions {
    justify-content: center;
  }

  .expertise-grid {
    grid-template-columns: 1fr 1fr;
  }

  .featured-projects-grid {
    grid-template-columns: 1fr;
  }

  .featured-project-card-title {
    text-align: center;
  }
}

@media (max-width: 640px) {
  .expertise-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="home-wrap">
  <div class="home-hero">
    <div class="home-portrait">
      <img src="/assets/img/2023_headshot.png" alt="Portrait of Ian Walsh">
    </div>

    <div class="home-intro">
      <p class="hero-kicker">Recent M.S. in Data Science Graduate</p>

      <p class="hero-summary">
        I build analytical tools and models that make complex data easier to understand and use.
      </p>

      <p class="hero-detail">
        My background spans economics, healthcare reporting, and dashboard development, with strong interests in healthcare and other work with meaningful real-world impact.
      </p>

      <div class="hero-actions">
        <a class="hero-button" href="/about/">More About Me</a>
        <a class="hero-button" href="/resume/">My Resume</a>
        <a class="hero-button" href="/contact/">Contact Me</a>
      </div>
    </div>
  </div>

  <hr class="section-divider">

  <div class="expertise-section">
    <h2>Areas of Interest</h2>
    <p class="section-note">A few of the technical areas I most enjoy working in.</p>

    <div class="expertise-grid">
      <div class="expertise-card">
        <div class="icon"><i data-lucide="brain-circuit"></i></div>
        <h3>Machine Learning</h3>
        <p>Modeling, prediction, and practical analytical workflows.</p>
      </div>

      <div class="expertise-card">
        <div class="icon"><i data-lucide="map"></i></div>
        <h3>Geospatial Analysis</h3>
        <p>Spatial data, mapping, and place-based analysis.</p>
      </div>

      <div class="expertise-card">
        <div class="icon"><i data-lucide="chart-column-increasing"></i></div>
        <h3>Data Visualization</h3>
        <p>Dashboards, reporting, and clear visual communication.</p>
      </div>

      <div class="expertise-card">
        <div class="icon"><i data-lucide="chart-spline"></i></div>
        <h3>Statistical Modeling</h3>
        <p>Regression, inference, and applied quantitative analysis.</p>
      </div>
    </div>
  </div>

  <hr class="section-divider">

  <div class="featured-projects">
    <h2>Featured Projects</h2>
    <p class="section-note">Key projects that best reflect my interests in applied analytics, dashboards, and policy-oriented data work.</p>

    <div class="featured-projects-grid">
      <a class="featured-project-card" href="/projects/data-centers/">
        <img src="/assets/img/projects/map_dcs_2022.png" alt="Map showing data center distribution across the contiguous United States">
        <div class="featured-project-card-title">M.S. Capstone — The Local Economic Impact of Data Centers</div>
      </a>

      <a class="featured-project-card" href="/projects/healthcare-dashboard/">
        <img src="/assets/img/projects/medications.png" alt="Screenshot of healthcare analytics dashboard">
        <div class="featured-project-card-title">Healthcare Analytics Dashboard</div>
      </a>

      <a class="featured-project-card" href="/projects/portland-transit/">
        <img src="/assets/img/projects/vulnerability_vs_businesses.png" alt="Visualization of Portland transit and business density analysis">
        <div class="featured-project-card-title">Portland Transit, Business Density, and Neighborhood Health</div>
      </a>
    </div>
  </div>
</div>

<script src="https://unpkg.com/lucide@latest"></script>
<script>
  lucide.createIcons();
</script>