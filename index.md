---
layout: page
title: Ian Walsh
subtitle: Data Science Graduate
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
  gap: 3.75rem;
  align-items: center;
  margin: 1.25rem 0 3.4rem 0;
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
  max-width: 720px;
}

.home-intro h1 {
  font-size: 3.2rem;
  line-height: 1.06;
  margin-bottom: 0.45rem;
}

.home-intro .lead {
  font-size: 1.16rem;
  color: #666;
  margin-bottom: 1rem;
}

.home-intro p {
  font-size: 1.08rem;
  line-height: 1.85;
  margin-bottom: 0;
}

.section-divider {
  margin: 3rem 0 2.8rem 0;
  border: none;
  border-top: 1px solid #ddd;
}

.expertise-section,
.quick-links {
  text-align: center;
}

.expertise-section h2,
.quick-links h2 {
  margin-bottom: 0.55rem;
}

.expertise-section .section-note {
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

.quick-links-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 1.2rem;
  max-width: 900px;
  margin: 0 auto;
}

.quick-link-box {
  text-align: center;
  padding: 0.25rem 0;
}

.quick-link-box h3 {
  margin: 0 0 0.35rem 0;
  font-size: 1rem;
}

.quick-link-box a {
  text-decoration: none !important;
  font-weight: 600;
}

.quick-link-box a:hover {
  text-decoration: underline !important;
}

@media (max-width: 950px) {
  .home-hero {
    grid-template-columns: 1fr;
    text-align: center;
    gap: 1.8rem;
  }

  .home-portrait {
    display: flex;
    justify-content: center;
  }

  .home-intro {
    max-width: 100%;
    margin: 0 auto;
  }

  .expertise-grid,
  .quick-links-grid {
    grid-template-columns: 1fr 1fr;
  }
}

@media (max-width: 640px) {
  .expertise-grid,
  .quick-links-grid {
    grid-template-columns: 1fr;
  }

  .home-intro h1 {
    font-size: 2.35rem;
  }
}
</style>

<div class="home-wrap">
  <div class="home-hero">
    <div class="home-portrait">
      <img src="/assets/img/2023_headshot.png" alt="Portrait of Ian Walsh">
    </div>

    <div class="home-intro">
      <h1>Ian Walsh</h1>
      <div class="lead">Data Science Graduate</div>
      <p>
        I’m a recent data science graduate with a background in economics, healthcare reporting, and dashboard development. I like work that turns messy data into something clear and useful. My greatest interests are in analytics, modeling, data visualization, and practical problem solving — especially in healthcare or in areas that have meaningful real-world impacts.
      </p>
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

  <div class="quick-links">
    <h2>Explore</h2>
    <div class="quick-links-grid">
      <div class="quick-link-box">
        <h3>About</h3>
        <a href="/about/">Read more</a>
      </div>

      <div class="quick-link-box">
        <h3>Resume</h3>
        <a href="/resume/">View resume</a>
      </div>

      <div class="quick-link-box">
        <h3>Projects</h3>
        <a href="/projects/">Open portfolio</a>
      </div>

      <div class="quick-link-box">
        <h3>Contact</h3>
        <a href="/contact/">Contact me</a>
      </div>
    </div>
  </div>
</div>

<script src="https://unpkg.com/lucide@latest"></script>
<script>
  lucide.createIcons();
</script>