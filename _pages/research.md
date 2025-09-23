---
layout: single
title: ""
permalink: /research/
---

<!-- ===== FULL-WIDTH INTRO ===== -->
<section class="rb-fullbleed">
  <div class="rb-intro">
    <h1>Our Research</h1>

    <p align="justify">
      Our goal is to study and develop the <b>physical and perceptual adaptive intelligence</b> necessary for robots to learn from and interact with humans, while being able to adapt to a wide-range of human capabilities, needs and ever-changing environments. We call this vision <b>fluid human-robot collaborative autonomy</b>; i.e., when humans and robots collaborate harmoniously.
    </p>

    <p align="justify">
      We focus on applications where such fluid collaboration is necessary or safety critical, such as teaching robots cumbersome dexterous manipulation tasks with minimal human effort, navigating swiftly and safely in busy human-centric spaces, physically assisting humans in heavy work and contact-rich activities, physical therapy and rehabilitation. We tackle these problems by developing novel and tightly coupled learning, control and estimation algorithms that enjoy from <b>stability, safety, efficiency and robustness guarantees</b>. This involves research at the intersection of control theory, machine learning, artificial intelligence, perception and biomechanics — with a physical human-robot interaction perspective.
    </p>

    <p align="justify">
      A summary of our contributions over the past three years at Penn can be found in Prof. Figueroa's
      <a href="https://nbfigueroa.github.io/data/nadia/Figueroa_Research_Statement_2024.pdf" target="_blank" rel="noopener">research statement</a>.
    </p>
  </div>

  <p align="center">
    <img src="{{ site.baseurl }}/assets/images/research-thursts.png" style="width:58%; max-width:820px;">
  </p>
</section>

<!-- ===== FULL-WIDTH GRID (not clickable) ===== -->
<section class="rb-grid">
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
</section>

<style>
/* 🔕 Hide the Minimal Mistakes pager on this page */
.pagination{ display:none !important; }

/* 🔕 Hide RSS/Feed icon on this page only (robust selectors; no :has needed) */
.page__footer-follow .social-icons a[href$="feed.xml"],
.page__footer-follow .social-icons a[href*="/feed"],
.page__footer-follow .social-icons .fa-rss,
.page__footer-follow .social-icons a[aria-label*="Feed"],
.page__footer-follow .social-icons a[title*="Feed"]{
  display:none !important;
}

/* keep the theme’s top spacing small */
.main .page__content { padding-top: 0.4rem; }

/* ---------- FULL-BLEED INTRO ---------- */
.rb-fullbleed{
  width: 100vw;
  margin-left: calc(50% - 50vw);
}
.rb-intro{
  max-width: 1000px;                   /* narrower */
  margin: 0 auto 1.4rem;
  padding: 0 18px;
  text-align: justify;
  text-justify: inter-word;
}
.rb-intro h1{
  text-align: center;
  margin-bottom: 0.7rem;
  font-weight: 800;
  font-size: clamp(1.2rem, 1.0vw + 0.9rem, 1.55rem);  /* smaller heading */
}
.rb-intro p{
  margin: 0 auto;
  line-height: 1.6;
  max-width: 860px;
  font-size: clamp(0.88rem, 0.35vw + 0.75rem, 0.98rem); /* smaller body text */
}

/* ---------- FULL-BLEED GRID (smaller cards) ---------- */
.rb-grid{
  width: 100vw;
  margin-left: calc(50% - 50vw);
  padding: 0 clamp(10px, 3.6vw, 28px);        /* less side padding */
  display: grid;
  gap: clamp(14px, 2.2vw, 26px);              /* tighter gaps */

  /* 3 columns wide screens, each at least 300px (down again) */
  grid-template-columns: repeat(3, minmax(300px, 1fr));
  justify-items: center;
}

/* fallbacks for smaller screens */
@media (max-width: 1100px){
  .rb-grid{ grid-template-columns: repeat(2, minmax(280px, 1fr)); }
}
@media (max-width: 760px){
  .rb-grid{ grid-template-columns: minmax(240px, 1fr); }
}

/* ---------- CARD (no link wrapper) ---------- */
.rb-card{
  width: 100%;
  max-width: 540px;                      /* down from 640px */
  display: flex;
  flex-direction: column;
  align-items: center;
  color: inherit;
}

/* image frame — smaller */
.rb-img{
  width: 100%;
  aspect-ratio: 16 / 9;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 8px 22px rgba(0,0,0,.06);
  background: #f3f4f6;
  display: flex;
  align-items: center;
  justify-content: center;
}
.rb-img img{
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
  transition: transform .28s ease, filter .28s ease;
}

.rb-card:hover .rb-img img{
  transform: scale(1.015);
  filter: brightness(1.02);
}

.rb-card h3{
  margin: 0.65rem 0 0;
  text-align: center;
  font-size: clamp(0.98rem, 1vw + .6rem, 1.28rem); /* smaller title */
  font-weight: 800;
}
</style>
