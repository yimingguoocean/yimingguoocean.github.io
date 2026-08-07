---
permalink: /
title: "Home"
excerpt: "Ocean, Lake, and Climate Dynamics"
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<style>
.hero {
  position: relative;
  margin: 0 0 2.5rem 0;
  border-radius: 18px;
  overflow: hidden;
  min-height: 360px;
  background: #0b1d2a;
}
.hero img {
  width: 100%;
  height: 360px;
  object-fit: cover;
  display: block;
  filter: brightness(0.72);
}
.hero-text {
  position: absolute;
  inset: 0;
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding: 2rem 2.5rem;
  color: #fff;
  max-width: 900px;
}
.hero-text h1 {
  font-size: clamp(2.2rem, 5vw, 4rem);
  line-height: 1.05;
  margin: 0 0 0.75rem 0;
  color: #fff;
}
.hero-text h2 {
  font-size: clamp(1.1rem, 2vw, 1.5rem);
  font-weight: 500;
  margin: 0 0 1rem 0;
  color: rgba(255,255,255,0.95);
}
.hero-text p {
  font-size: 1.05rem;
  line-height: 1.7;
  margin: 0 0 0.9rem 0;
  color: rgba(255,255,255,0.95);
  max-width: 760px;
}
.btn-row {
  display: flex;
  gap: 0.75rem;
  flex-wrap: wrap;
  margin-top: 0.75rem;
}
.btn-link {
  display: inline-block;
  padding: 0.75rem 1.05rem;
  border-radius: 10px;
  text-decoration: none;
  font-weight: 600;
  border: 1px solid rgba(255,255,255,0.25);
  background: rgba(255,255,255,0.12);
  color: #fff;
}
.btn-link:hover {
  background: rgba(255,255,255,0.2);
  text-decoration: none;
}

.section-title {
  font-size: 2rem;
  margin: 2.75rem 0 1rem 0;
}

.cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 1rem;
  margin-top: 1rem;
}
.card {
  border: 1px solid #e6e6e6;
  border-radius: 16px;
  padding: 1.15rem;
  background: #fff;
  box-shadow: 0 1px 10px rgba(0,0,0,0.04);
}
.card h3 {
  margin-top: 0.25rem;
  margin-bottom: 0.55rem;
  font-size: 1.1rem;
}
.card p {
  margin: 0;
  font-size: 0.96rem;
  line-height: 1.6;
}

.two-column {
  display: grid;
  grid-template-columns: 2fr 1fr;
  gap: 2rem;
  margin-top: 2rem;
}
.news-list {
  padding-left: 1.2rem;
}
.news-list li {
  margin-bottom: 0.6rem;
  line-height: 1.6;
}
.join {
  background: #f7f7f7;
  border-radius: 16px;
  padding: 1.25rem;
}

@media (max-width: 900px) {
  .two-column {
    grid-template-columns: 1fr;
  }
  .hero-text {
    padding: 1.5rem;
  }
  .hero {
    min-height: 320px;
  }
  .hero img {
    height: 320px;
  }
}
</style>

<div class="hero">
  <img src="/images/hero.jpg" alt="Hero image">
  <div class="hero-text">
    <h1>Ocean, Lake & Climate Dynamics Lab</h1>
    <h2>Understanding aquatic systems in a changing climate</h2>
    <p>
      I am an Assistant Professor at Illinois State University studying the physical processes
      that govern oceans, lakes, and the climate system. My research combines satellite remote
      sensing, in situ observations, reanalysis products, and high-resolution numerical models
      to investigate water dynamics, biogeochemistry, and climate variability across scales.
    </p>
    <p>
      I am particularly interested in ocean and lake dynamics, air–water interactions, carbon
      cycling, regional and global climate, and nature-based climate solutions.
    </p>
    <div class="btn-row">
      <a class="btn-link" href="/research/">Research</a>
      <a class="btn-link" href="/publications/">Publications</a>
      <a class="btn-link" href="/contact/">Contact</a>
    </div>
  </div>
</div>

<p>
  Welcome to my research website. My group uses observations, remote sensing, and modeling to
  better understand how aquatic systems respond to climate variability, long-term change, and
  extreme events.
</p>

<h2 class="section-title">Research Themes</h2>
<div class="cards">
  <div class="card">
    <h3>Ocean Dynamics</h3>
    <p>Mesoscale and submesoscale processes, circulation, heat transport, and climate variability.</p>
  </div>
  <div class="card">
    <h3>Lake Dynamics</h3>
    <p>Thermal structure, stratification, mixing, and climate impacts on inland waters.</p>
  </div>
  <div class="card">
    <h3>Remote Sensing</h3>
    <p>Satellite observations, field measurements, and multi-source data integration.</p>
  </div>
  <div class="card">
    <h3>Modeling & Prediction</h3>
    <p>Reanalysis, numerical models, machine learning, and future climate projections.</p>
  </div>
</div>

<div class="two-column">
  <div>
    <h2 class="section-title">News</h2>
    <ul class="news-list">
      <li><b>2026</b> — Add your latest paper, grant, or conference update here.</li>
      <li><b>2026</b> — Add a student or lab news item here.</li>
      <li><b>2026</b> — Add another short update here.</li>
    </ul>
  </div>

  <div class="join">
    <h2>Join Us</h2>
    <p>
      I welcome inquiries from prospective graduate students, postdoctoral researchers, and
      collaborators interested in oceans, lakes, climate, and remote sensing.
    </p>
    <p>
      <a href="/contact/">Learn more about opportunities →</a>
    </p>
  </div>
</div>

