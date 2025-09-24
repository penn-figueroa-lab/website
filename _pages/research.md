---
layout: single
title: ""
permalink: /research/
---

<!-- ===== SHARED WRAP (text + grid) ===== -->
<section class="rb-wrap">
  <div class="rb-intro">
    <h1>Our Research</h1>

    <p align="justify">
      Our goal is to study and develop the <b>physical and perceptual adaptive intelligence</b> necessary for robots to learn from and interact with humans, while being able to adapt to a wide-range of human capabilities, needs and ever-changing environments. We call this vision <b>fluid human-robot collaborative autonomy</b>; i.e., when humans and robots collaborate harmoniously.
    </p>

    <p align="justify">
      We focus on applications where such fluid collaboration is necessary or safety critical, such as teaching robots cumbersome dexterous manipulation tasks with minimal human effort, navigating swiftly and safely in busy human-centric spaces, physically assisting humans in heavy work and contact-rich activities, physical therapy and rehabilitation. We tackle these problems by developing novel and tightly coupled learning, control and estimation algorithms that enjoy from <b>stability, safety, efficiency and robustness guarantees</b>. This involves research at the intersection of control theory, machine learning, artificial intelligence, perception and biomechanics — with a physical human-robot interaction perspective.
    </p>

    <p align="center" class="rb-figure">
      <img src="{{ site.baseurl }}/assets/images/research-thursts.png" alt="Research thrusts">
    </p>

    <p align="justify">
      A summary of our contributions over the past three years at Penn can be found in Prof. Figueroa's
      <a href="https://nbfigueroa.github.io/data/nadia/Figueroa_Research_Statement_2024.pdf" target="_blank" rel="noopener">research statement</a>.
    </p>
  </div>
</section>

<!-- ===== GRID (not clickable) — uses the SAME width wrapper ===== -->
<section class="rb-wrap">
  <div class="rb-grid">
    <div class="rb-card">
      <div class="rb-img">
        <img src="{{ site.baseurl }}/assets/images/Assistive_Robotics.JPG" alt="Assistive Robotics & Biomechanics">
      </div>
      <h3>Assistive Robotics &amp; Biomechanics</h3>
    </div>

    <div class="rb-card">
      <div class="rb-img">
        <img src="{{ site.baseurl }}/assets/images/Control_Estimation.JPG" alt="Control & Estimation">
      </div>
      <h3>Control &amp; Estimation</h3>
    </div>

    <div class="rb-card">
      <div class="rb-img">
        <img src="{{ site.baseurl }}/assets/images/hardware.JPG" alt="Hardware">
      </div>
      <h3>Hardware</h3>
    </div>

    <div class="rb-card">
      <div class="rb-img">
        <img src="{{ site.baseurl }}/assets/images/Imitation_Learning.JPG" alt="Imitation Learning">
      </div>
      <h3>Imitation Learning</h3>
    </div>

    <div class="rb-card">
      <div class="rb-img">
        <img src="{{ site.baseurl }}/assets/images/Perception_for_manipulation.JPG" alt="Perception for Manipulation">
      </div>
      <h3>Perception for Manipulation</h3>
    </div>
  </div>
</section>

<style>
/* 🔕 Hide pager & RSS on THIS page only */
.pagination{ display:none !important; }
.page__footer-follow .social-icons a[href$="feed.xml"],
.page__footer-follow .social-icons a[href*="/feed"],
.page__footer-follow .social-icons .fa-rss{ display:none !important; }

/* Keep theme spacing tight */
.main .page__content { padding-top: 0.35rem; }

/* ---------- Shared width container (matches your red margins) ---------- */
:root{
  --rb-max: 1120px;   /* <— adjust this number to match those red guides */
}
.rb-wrap{
  width: min(94vw, var(--rb-max));
  margin-inline: auto;         /* center */
}

/* ---------- Intro ---------- */
.rb-intro{
  margin: 0 auto 1.25rem;
  padding: 0 8px;
  text-align: justify;
  text-justify: inter-word;
}
.rb-intro h1{
  text-align: center;
  margin-bottom: 0.7rem;
  font-weight: 800;
  font-size: clamp(1.2rem, 1.2vw + 1rem, 1.55rem);
}
.rb-intro p{
  margin: 0.6rem auto 0;
  line-height: 1.55;
  font-size: clamp(0.9rem, 0.35vw + 0.8rem, 1rem);
  max-width: 78ch;   /* comfortable reading width; stays inside the container */
}
.rb-figure img{
  width: 100%;
  max-width: 900px;   /* image won’t exceed the text width */
  height: auto;
  display: block;
}

/* ---------- Grid (uses the same rb-wrap width) ---------- */
.rb-grid{
  display: grid;
  gap: clamp(12px, 1.8vw, 22px);
  grid-template-columns: repeat(3, minmax(260px, 1fr)); /* stays inside wrap */
  align-items: start;
}
@media (max-width: 1000px){
  .rb-grid{ grid-template-columns: repeat(2, minmax(240px, 1fr)); }
}
@media (max-width: 680px){
  .rb-grid{ grid-template-columns: minmax(220px, 1fr); }
}

/* ---------- Cards ---------- */
.rb-card{
  width: 100%;
  max-width: 520px;             /* card cannot exceed the wrap grid column */
  display: flex;
  flex-direction: column;
  align-items: center;
}
.rb-img{
  width: 100%;
  aspect-ratio: 16 / 9;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 8px 22px rgba(0,0,0,.06);
  background: #f3f4f6;
}
.rb-img img{
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
  transition: transform .25s ease, filter .25s ease;
}
.rb-card:hover .rb-img img{
  transform: scale(1.01);
  filter: brightness(1.02);
}
.rb-card h3{
  margin: 0.6rem 0 0;
  text-align: center;
  font-size: clamp(0.95rem, 0.9vw + 0.65rem, 1.2rem);
  font-weight: 800;
}
</style>
