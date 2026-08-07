---
permalink: /
title: " "
excerpt: "Ocean, Lake, and Climate Dynamics"
author_profile: true
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
  font-size: clamp(1.8rem, 4vw, 3rem);
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
  grid-template-columns: repeat(2, 1fr);
  gap: 2rem;
  margin-top: 1.5rem;
}

@media (max-width: 900px) {
  .cards {
    grid-template-columns: 1fr;
  }
}
  
.cards {
  display: grid;
  grid-template-columns: repeat(2, minmax(320px, 1fr));
  gap: 2rem;
  margin-top: 2rem;
}

.card {
  display: block;
  text-decoration: none;
  color: inherit;
  border-radius: 18px;
  overflow: hidden;
  background: #fff;
  box-shadow: 0 4px 14px rgba(0,0,0,.08);
  transition: all .25s ease;
}

.card:hover{
  transform: translateY(-6px);
  box-shadow:0 10px 24px rgba(0,0,0,.18);
  text-decoration:none;
}

.card img{
  width:100%;
  height:260px;
  object-fit:cover;
  display:block;
}

.card-body{
  padding:1.4rem 1.5rem 1.6rem;
}

.card h3{
  margin:0 0 .6rem;
  font-size:1.45rem;
  color:#1d3557;
}

.card p{
  margin:0;
  line-height:1.7;
  font-size:1.03rem;
  color:#555;
}

@media(max-width:900px){

.cards{

grid-template-columns:1fr;

}

.card img{

height:220px;

}

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
  <img src="/files/frontpage.png" alt="Hero image">
  <div class="hero-text">
    <h1>Climate-Ocean-Lake Dynamics (COLD) Lab</h1>
    <h2>Understanding aquatic systems in a changing climate</h2>
    <div class="btn-row">
      <a class="btn-link" href="/research/">Research</a>
      <a class="btn-link" href="/teaching/">Teaching</a>
      <a class="btn-link" href="/publications/">Publications</a>
      <a class="btn-link" href="/talks/">Talks</a>
    </div>
  </div>
</div>

<p>
  Welcome to the <strong>Climate–Ocean–Lake Dynamics (COLD) Lab</strong> at Illinois State University. We investigate the physical processes governing oceans, lakes, and the climate system by integrating satellite remote sensing, in situ observations, reanalysis products, and high-resolution numerical models. Our research focuses on aquatic dynamics, air–water interactions, carbon cycling, regional and global climate, and nature-based climate solutions, with the goal of improving understanding and prediction of a changing Earth system.
</p>

<h2 class="section-title">Research Themes</h2>

<div class="cards">

<div class="card" href="/research/ocean/">

<img src="/files/frontpage_ocean.png" alt="Ocean Dynamics">

<div class="card-body">

<h3>Ocean Dynamics</h3>

<p>
Investigating ocean circulation, mesoscale and submesoscale
processes, heat transport, and their roles in regional and
global climate variability.
</p>

</div>

</div>



<div class="card" href="/research/lake/">

<img src="/files/frontpage_lake.png" alt="Lake Dynamics">

<div class="card-body">

<h3>Lake Dynamics</h3>

<p>
Understanding thermal structure, stratification,
mixing, and climate impacts on inland waters
through observations and numerical modeling.
</p>

</div>

</div>



<div class="card" href="/research/remote-sensing/">

<img src="/files/frontpage_satellite.png" alt="Remote Sensing">

<div class="card-body">

<h3>Remote Sensing</h3>

<p>
Developing satellite-based approaches to monitor
aquatic environments and quantify climate-driven
changes across regional to global scales.
</p>

</div>

</div>



<div class="card" href="/research/modeling/">

<img src="/files/frontpage_prediction.png" alt="Modeling & Prediction">

<div class="card-body">

<h3>Modeling & Prediction</h3>

<p>
Combining numerical models, reanalysis products,
and machine learning to improve understanding
and prediction of aquatic systems.
</p>

</div>

</div>

</div>

<div class="one-column">
  
  <!--
  <div>
  #  <h2 class="section-title">News</h2>
  #  <ul class="news-list">
  #    <li><b>2026</b> — Add your latest paper, grant, or conference update here.</li>
  #    <li><b>2026</b> — Add a student or lab news item here.</li>
  #    <li><b>2026</b> — Add another short update here.</li>
  #  </ul>
 # </div>
  -->
  
  <div class="join">
    <h2>Join Us</h2>
    <p>
      I welcome inquiries from prospective graduate students, postdoctoral researchers, and
      collaborators interested in oceans, lakes, climate, and remote sensing.
    </p>
    
  <!--    
    #<p>
    #  <a href="/contact/">Learn more about opportunities →</a>
  # </p>
  -->
  
  </div>
</div>

