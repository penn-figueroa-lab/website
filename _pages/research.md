---
layout: single
title: ""
permalink: /research/
---

<section class="research-wrap">
  <!-- ===== INTRO ===== -->
  <div class="rb-intro">
    <h1>Our Research</h1>

    <p>
      Our goal is to study and develop the <b>physical and perceptual adaptive intelligence</b> necessary for robots to learn from and interact with humans, while being able to adapt to a wide-range of human capabilities, needs and ever-changing environments. We call this vision <b>fluid human-robot collaborative autonomy</b>; i.e., when humans and robots collaborate harmoniously.
    </p>

    <p>
      We focus on applications where such fluid collaboration is necessary or safety critical, such as teaching robots cumbersome dexterous manipulation tasks with minimal human effort, navigating swiftly and safely in busy human-centric spaces, physically assisting humans in heavy work and contact-rich activities, physical therapy and rehabilitation. We tackle these problems by developing novel and tightly coupled learning, control and estimation algorithms that enjoy from <b>stability, safety, efficiency and robustness guarantees</b>. This involves research at the intersection of control theory, machine learning, artificial intelligence, perception and biomechanics — with a physical human-robot interaction perspective.
    </p>

    <p>
      A summary of our contributions over the past three years at Penn can be found in Prof. Figueroa's
      <a href="https://nbfigueroa.github.io/data/nadia/Figueroa_Research_Statement_2024.pdf" target="_blank" rel="noopener">research statement</a>.
    </p>

    <p align="center">
      <img src="{{ site.baseurl }}/assets/images/research-thursts.png" style="width:75%; max-width:860px;">
    </p>
  </div>

  <!-- ===== GRID (not clickable) ===== -->
  <section class="rb-grid">
    <div class="rb-card">
      <div class="rb-img"><img src="{{ site.baseurl }}/assets/images/Assistive_Robotics.JPG" alt="Assistive Robotics & Biomechanics"></div>
      <h3>Assistive Robotics &amp; Biomechanics</h3>
    </div>

    <div class="rb-card">
      <div class="rb-img"><img src="{{ site.baseurl }}/assets/images/Control_Estimation.JPG" alt="Control & Estimation"></div>
      <h3>Control &amp; Estimation</h3>
    </div>

    <div class="rb-card">
      <div class="rb-img"><img src="{{ site.baseurl }}/assets/images/hardware.JPG" alt="Hardware"></div>
      <h3>Hardware</h3>
    </div>

    <div class="rb-card">
      <div class="rb-img"><img src="{{ site.baseurl }}/assets/images/Imitation_Learning.JPG" alt="Imitation Learning"></div>
      <h3>Imitation Learning</h3>
    </div>

    <div class="rb-card">
      <div class="rb-img"><img src="{{ site.baseurl }}/assets/images/Perception_for_manipulation.JPG" alt="Perception for Manipulation"></div>
      <h3>Perception for Manipulation</h3>
    </div>
  </section>
</section>

<style>
/* 🔕 Hide pager & feed icon just on this page */
.pagination{ display:none!important; }
.page__footer-follow .social-icons a[href$="feed.xml"],
.page__footer-follow .social-icons a[href*="/feed"],
.page__footer-follow .social-icons .fa-rss{ display:none!important; }

/* tighten theme spacing */
.main .page__content{ padding-top:0.35rem; }

/* ===== Centered wrapper with bigger side margins =====
   - Narrower width to create larger side gutters
   - Manual left shift on very wide screens (same idea as publications) */
.research-wrap{
  width: min(82vw, 1200px);
  margin: 0 auto 1.5rem;
  padding: 0 12px;
}

/* Ultra-wide manual nudge (adjust -400px as needed to match header alignment) */
@media (min-width: 1500px){
  .research-wrap{
    margin-left: -400px;   /* manual left shift */
    margin-right: auto;
  }
}
/* Re-center below that breakpoint */
@media (max-width: 1499.98px){
  .research-wrap{
    margin-left: auto;
    margin-right: auto;
  }
}

/* ===== Intro ===== */
.rb-intro{
  width: 100%;
  text-align: justify;
  text-justify: inter-word;
}
.rb-intro h1{
  text-align:center;
  margin-bottom:0.7rem;
  font-weight:800;
  font-size:clamp(1.2rem, 1.1vw + 0.95rem, 1.55rem);
}
.rb-intro p{
  margin:0.6rem 0;
  line-height:1.6;
  font-size:clamp(0.9rem, 0.35vw + 0.78rem, 1rem);
}

/* ===== Grid ===== */
.rb-grid{
  margin-top:1.2rem;
  display:grid;
  gap: clamp(14px, 2vw, 26px);
  grid-template-columns: repeat(3, minmax(240px, 1fr));
  justify-items:center;
}
@media (max-width: 900px){
  .rb-grid{ grid-template-columns: repeat(2, minmax(220px, 1fr)); }
}
@media (max-width: 600px){
  .rb-grid{ grid-template-columns: minmax(210px, 1fr); }
}

/* ===== Cards ===== */
.rb-card{
  width:100%;
  max-width:420px;
  display:flex;
  flex-direction:column;
  align-items:center;
  text-align:center;
}
.rb-img{
  width:100%;
  aspect-ratio:16 / 9;
  border-radius:12px;
  overflow:hidden;
  box-shadow:0 6px 18px rgba(0,0,0,.06);
  background:#f3f4f6;
}
.rb-img img{
  width:100%;
  height:100%;
  object-fit:cover;
  display:block;
  transition:transform .25s ease, filter .25s ease;
}
.rb-card:hover .rb-img img{
  transform:scale(1.015);
  filter:brightness(1.02);
}
.rb-card h3{
  margin:0.7rem 0 0;
  font-weight:800;
  font-size:clamp(0.95rem, 0.9vw + .7rem, 1.25rem);
}
</style>
