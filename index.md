---
layout: page
title: Ian Walsh
subtitle: Data Scientist
---


<style>
.home-hero {
  display: grid;
  grid-template-columns: 320px 1fr;
  gap: 3rem;
  align-items: center;
  margin: 2rem 0 3rem 0;
}

.home-portrait img {
  width: 100%;
  max-width: 320px;
  border-radius: 28px;
  display: block;
  object-fit: cover;
  box-shadow: 0 10px 30px rgba(0,0,0,0.10);
}

.home-intro h1 {
  font-size: 3rem;
  margin-bottom: 0.5rem;
}

.home-intro .lead {
  font-size: 1.2rem;
  color: #666;
  margin-bottom: 1.2rem;
}

.home-intro p {
  font-size: 1.05rem;
  line-height: 1.75;
  margin-bottom: 1rem;
}

.hero-meta {
  display: flex;
  flex-wrap: wrap;
  gap: 0.7rem;
  margin-top: 1.2rem;
}

.hero-meta span {
  display: inline-block;
  padding: 0.45rem 0.8rem;
  background: #f5f5f5;
  border: 1px solid #e2e2e2;
  border-radius: 999px;
  font-size: 0.92rem;
  color: #555;
}

.home-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 0.8rem;
  margin-top: 1.2rem;
}

.home-actions a {
  display: inline-block;
  padding: 0.7rem 1.1rem;
  border: 1px solid #b9b9b9;
  border-radius: 999px;
  text-decoration: none !important;
  color: #333 !important;
  transition: all 0.2s ease;
  background: #fff;
}

.home-actions a:hover {
  background: #f3f3f3;
  transform: translateY(-1px);
}

.section-divider {
  margin: 3rem 0 2rem 0;
  border: none;
  border-top: 1px solid #ddd;
}

.expertise-section h2 {
  text-align: center;
  margin-bottom: 0.5rem;
}

.expertise-section .section-note {
  text-align: center;
  color: #666;
  margin-bottom: 2rem;
}

.expertise-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 1.25rem;
}

.expertise-card {
  background: #fafafa;
  border: 1px solid #e6e6e6;
  border-radius: 18px;
  padding: 1.25rem;
  text-align: center;
  height: 100%;
}

.expertise-card .icon {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-bottom: 0.9rem;
}

.expertise-card .icon svg {
  width: 38px;
  height: 38px;
  stroke: #6b4b3e;
  stroke-width: 1.8;
}

.expertise-card h3 {
  font-size: 1.1rem;
  margin-bottom: 0.6rem;
}

.expertise-card p {
  font-size: 0.95rem;
  line-height: 1.6;
  color: #555;
  margin: 0;
}

.quick-links {
  margin-top: 3rem;
  text-align: center;
}

.quick-links h2 {
  margin-bottom: 1rem;
}

.quick-links-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 1rem;
}

.quick-link-box {
  border: 1px solid #e1e1e1;
  border-radius: 18px;
  padding: 1.2rem;
  background: #fff;
}

.quick-link-box h3 {
  margin-top: 0;
  margin-bottom: 0.5rem;
}

.quick-link-box p {
  font-size: 0.95rem;
  color: #666;
  margin-bottom: 0.8rem;
}

.quick-link-box a {
  text-decoration: none !important;
  font-weight: 600;
}

@media (max-width: 900px) {
  .home-hero {
    grid-template-columns: 1fr;
    text-align: center;
  }

  .home-portrait {
    display: flex;
    justify-content: center;
  }

  .home-actions {
    justify-content: center;
  }

  .hero-meta {
  justify-content: center;
  }

  .expertise-grid,
  .quick-links-grid {
    grid-template-columns: 1fr 1fr;
  }
}

@media (max-width: 600px) {
  .expertise-grid,
  .quick-links-grid {
    grid-template-columns: 1fr;
  }


  .home-intro h1 {
    font-size: 2.3rem;
  }
}
</style>

<div class="home-hero">
  <div class="home-portrait">
    <img src="/assets/img/2023_headshot.png" alt="Portrait of Ian Walsh">
  </div>

  <div class="home-intro">
    <h1>Ian Walsh</h1>
    <div class="lead">Data Scientist</div>

    <p>
    I’m a recent M.S. in Data Science graduate with a background in economics and healthcare analytics. My work focuses on machine learning, geospatial analysis, dashboard development, and applied statistical modeling.
    </p>

  </div>
</div>

<hr class="section-divider">

<div class="expertise-section">
  <h2>Areas of Expertise</h2>
  <p class="section-note">A few of the technical areas I most enjoy working in.</p>

  <div class="expertise-grid">
    <div class="expertise-card">
      <div class="icon">
        <i data-lucide="brain-circuit"></i>
      </div>
      <h3>Machine Learning</h3>
      <p>
        Building predictive and exploratory models with a focus on practical interpretation, structured workflows, and real-world decision support.
      </p>
    </div>

    <div class="expertise-card">
      <div class="icon">
        <i data-lucide="map-plus"></i>
      </div>
      <h3>Geospatial Analysis</h3>
      <p>
        Working with spatial data, mapping, and location-based analysis to understand infrastructure, regional patterns, and local impacts.
      </p>
    </div>

    <div class="expertise-card">
      <div class="icon">
        <i data-lucide="layout-dashboard"></i>
      </div>
      <h3>Dashboard Development</h3>
      <p>
        Designing interactive dashboards and decision-support tools that combine clear visuals, filtering, and practical storytelling for end users.
      </p>
    </div>

    <div class="expertise-card">
      <div class="icon">
        <i data-lucide="chart-spline"></i>
      </div>
      <h3>Statistical Modeling</h3>
      <p>
        Applying regression, causal inference, and economic analysis techniques to answer concrete questions with defensible methods.
      </p>
    </div>
  </div>
</div>

<div class="quick-links">
  <h2>Explore</h2>
  <div class="quick-links-grid">
    <div class="quick-link-box">
      <h3>Portfolio</h3>
      <p>Browse selected projects in analytics, dashboards, and applied data science.</p>
      <a href="/myprojects/">Open portfolio</a>
    </div>

    <div class="quick-link-box">
      <h3>About</h3>
      <p>Learn more about my background, technical interests, and professional path.</p>
      <a href="/about/">Read more</a>
    </div>

    <div class="quick-link-box">
      <h3>Resume</h3>
      <p>See my experience in healthcare analytics, graduate training, and technical work.</p>
      <a href="/resume/">View resume</a>
    </div>

    <div class="quick-link-box">
      <h3>Contact</h3>
      <p>Get in touch for opportunities, collaborations, or general questions.</p>
      <a href="/contact/">Contact me</a>
    </div>
  </div>
</div>

<script src="https://unpkg.com/lucide@latest"></script>
<script>
  lucide.createIcons();
</script>