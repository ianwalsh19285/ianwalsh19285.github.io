---
layout: page
title: About Me
subtitle: Background, experience, and the kind of work I want to do
---

<style>
.about-wrap {
  max-width: 980px;
  margin: 0 auto;
}

.about-intro {
  max-width: 780px;
  margin: 1.5rem auto 2.5rem auto;
  text-align: center;
}

.about-intro p {
  font-size: 1.06rem;
  line-height: 1.85;
  margin-bottom: 0;
}

.about-section {
  margin-bottom: 3rem;
}

.about-section h2 {
  margin-bottom: 1rem;
  text-align: center;
}

.pro-card-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1.25rem;
  align-items: stretch;
}

.pro-card {
  background: #fafafa;
  border: 1px solid #e6e6e6;
  border-top: 5px solid transparent;
  border-radius: 20px;
  padding: 1.35rem 1.4rem 1.25rem 1.4rem;
  box-shadow: 0 6px 18px rgba(0,0,0,0.04);
}

.pro-card h3 {
  margin-top: 0;
  margin-bottom: 0.75rem;
  font-size: 1.08rem;
}

.pro-card-summary {
  font-size: 0.98rem;
  line-height: 1.7;
  color: #444;
  margin-bottom: 1rem;
}

.pro-card-divider {
  height: 1px;
  background: rgba(0,0,0,0.08);
  margin: 0.95rem 0 1rem 0;
}

.pro-card ul {
  margin: 0;
  padding-left: 1.1rem;
}

.pro-card li {
  font-size: 0.95rem;
  line-height: 1.65;
  margin-bottom: 0.5rem;
  color: #555;
}

.epic-card {
  background: #f7f9fc;
  border-top-color: #88a3bf;
}

.msds-card {
  background: #f5faf7;
  border-top-color: #7fa98f;
}

.interests-wrap {
  max-width: 820px;
  margin: 0 auto;
}

.interests-text {
  font-size: 1rem;
  line-height: 1.8;
  color: #444;
  text-align: center;
  margin-bottom: 1.4rem;
}

.interests-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 0.9rem;
}

.interest-pill {
  background: #fafafa;
  border: 1px solid #e6e6e6;
  border-radius: 16px;
  padding: 0.9rem 1rem;
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 0.55rem;
  text-align: center;
  font-size: 0.95rem;
  line-height: 1.5;
  color: #555;
}

.interest-pill svg {
  width: 18px;
  height: 18px;
  stroke-width: 2;
  color: #6b7f94;
  flex-shrink: 0;
}

.personal-layout {
  display: grid;
  grid-template-columns: 280px 1fr;
  gap: 1.5rem;
  align-items: center;
  margin-top: 1.25rem;
}

.personal-photo img {
  width: 100%;
  border-radius: 22px;
  display: block;
  object-fit: cover;
  box-shadow: 0 10px 30px rgba(0,0,0,0.10);
}

.about-photo-caption {
  font-size: 0.92rem;
  line-height: 1.6;
  color: #666;
  margin-top: 0.75rem;
  text-align: center;
}

.personal-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1rem;
}

.personal-card {
  background: #fafafa;
  border: 1px solid #e6e6e6;
  border-radius: 18px;
  padding: 1.15rem 1.25rem;
  box-shadow: 0 4px 14px rgba(0,0,0,0.03);
}

.personal-card h3 {
  margin-top: 0;
  margin-bottom: 0.55rem;
  font-size: 1rem;
}

.personal-card p {
  margin: 0;
  font-size: 0.96rem;
  line-height: 1.65;
  color: #555;
}

@media (max-width: 900px) {
  .pro-card-grid,
  .personal-layout,
  .personal-grid,
  .interests-grid {
    grid-template-columns: 1fr;
  }

  .personal-photo {
    max-width: 300px;
    margin: 0 auto;
  }

  .about-intro,
  .interests-text,
  .about-section h2 {
    text-align: left;
  }
}
</style>

<div class="about-wrap">

  <div class="about-intro">
    <p>
      I’m a recent data science graduate with a background in economics, healthcare reporting, and dashboard development. I like work that turns messy data into something clear and useful. My greatest interests are in analytics, modeling, data visualization, and practical problem solving — especially in healthcare or other areas that have meaningful real-world impacts.
    </p>
  </div>

  <div class="about-section">
    <h2>Experience and Education</h2>

    <div class="pro-card-grid">
      <div class="pro-card epic-card">
        <h3>Epic Systems</h3>
        <div class="pro-card-summary">
          Spent two years as a Technical Solutions Engineer supporting pharmacy-related workflows in the Willow application and helping healthcare teams solve operational problems.
        </div>
        <div class="pro-card-divider"></div>
        <ul>
          <li>Built SQL-based reports and dashboards for pharmacy operations.</li>
          <li>Worked on the reporting team as both a developer and subject matter resource.</li>
          <li>Did analytical and reporting work directly for clients.</li>
          <li>Worked closely with end users and internal teams to solve workflow and data issues.</li>
        </ul>
      </div>

      <div class="pro-card msds-card">
        <h3>M.S. in Data Science</h3>
        <div class="pro-card-summary">
          Completed my master’s at Willamette University, where I built a stronger foundation in machine learning, data engineering, statistical modeling, and data visualization.
        </div>
        <div class="pro-card-divider"></div>
        <ul>
          <li>Built projects using Python, SQL, R, and many other tools common in the data science field.</li>
          <li>Worked with public data to study economic and environmental impacts of data centers for my capstone project.</li>
          <li>Focused on connecting technical methods to real-world interpretation.</li>
          <li>Strengthened my interest in applied analytical work.</li>
        </ul>
      </div>
    </div>
  </div>

  <div class="about-section">
    <h2>Outside of work</h2>

    <div class="personal-layout">
      <div class="personal-photo">
        <img src="/assets/img/percy.jpg" alt="My cat Percy">
        <div class="about-photo-caption">
          Meet Percy!
        </div>
      </div>

      <div class="personal-grid">
        <div class="personal-card">
          <h3>Percy</h3>
          <p>
            Percy is a friendly black cat with a lot of personality. He loves strangers, and his secret talent is playing fetch.
          </p>
        </div>

        <div class="personal-card">
          <h3>Weekends</h3>
          <p>
            Usually some combination of friends, trying new things, being outdoors, and doing something at least a little adventurous.
          </p>
        </div>

        <div class="personal-card">
          <h3>Games and trivia</h3>
          <p>
            I like anything a little interactive or competitive, from video games and board games to D&amp;D and trivia nights.
          </p>
        </div>

        <div class="personal-card">
          <h3>Other interests</h3>
          <p>
            I got into coffee and tea after working as a barista in high school, and I still like good cafés, time in nature, and the occasional trip somewhere new.
          </p>
        </div>
      </div>
    </div>
  </div>

</div>