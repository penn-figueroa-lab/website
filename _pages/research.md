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
    <img src="{{ site.baseurl }}/assets/images/research-thursts.png" style="width:62%; max-width:900px;">
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

/* 🔕 Hide RSS/Feed icon only on this page */
.page__footer-follow .social-icons li:has(a[href$="feed.xml"]),
.page__footer-follow .social-icons li:has(.fa-rss),
.page__footer-follow .social-icons a[href$="feed.xml"],
.page__footer-follow .social-icons .fa-rss{
  display:none !important;
}

/* keep the theme’s top spacing small */
.main .page__content { padding-top: 0.5rem; }

/* ---------- FULL-BLEED INTRO ---------- */
.rb-fullbleed{
  width: 100vw;
  margin-left: calc(50% - 50vw);
}
.rb-intro{
  max-width: 1100px;                  /* slightly narrower */
  margin: 0 auto 1.6rem;
  padding: 0 20px;                    /* a bit tighter */
  text-align: justify;
  text-justify: inter-word;
}
.rb-intro h1{
  text-align: center;
  margin-bottom: 0.85rem;
  font-weight: 800;
  font-size: clamp(1.4rem, 1.2vw + 1.0rem, 1.8rem); /* smaller heading */
}
.rb-intro p{
  margin: 0 auto;
  line-height: 1.7;                   /* slightly tighter */
  max-width: 920px;                   /* a bit narrower */
  font-size: clamp(0.92rem, 0.4vw + 0.8rem, 1.02rem); /* smaller body text */
}

/* ---------- FULL-BLEED GRID (smaller cards) ---------- */
.rb-grid{
  width: 100vw;
  margin-left: calc(50% - 50vw);
  padding: 0 clamp(12px, 4vw, 36px);       /* slightly less padding */
  display: grid;
  gap: clamp(16px, 2.5vw, 32px);           /* slightly tighter gaps */

  /* 3 columns on wide screens, each at least 340px (down from 380px) */
  grid-template-columns: repeat(3, minmax(340px, 1fr));
  justify-items: center;
}

/* fallbacks for smaller screens */
@media (max-width: 1200px){
  .rb-grid{ grid-template-columns: repeat(2, minmax(320px, 1fr)); }
}
@media (max-width: 800px){
  .rb-grid{ grid-template-columns: minmax(280px, 1fr); }
}

/* ---------- CARD (no link wrapper) ---------- */
.rb-card{
  width: 100%;
  max-width: 640px;                     /* down from 720px */
  display: flex;
  flex-direction: column;
  align-items: center;
  color: inherit;
}

/* image frame — slightly smaller */
.rb-img{
  width: 100%;
  aspect-ratio: 16 / 9;
  border-radius: 14px;                  /* slightly less round */
  overflow: hidden;
  box-shadow: 0 10px 28px rgba(0,0,0,.07);
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
  transition: transform .3s ease, filter .3s ease;
}

.rb-card:hover .rb-img img{
  transform: scale(1.02);               /* slightly gentler hover */
  filter: brightness(1.02);
}

.rb-card h3{
  margin: 0.8rem 0 0;                   /* tighter */
  text-align: center;
  font-size: clamp(1.05rem, 1.1vw + .75rem, 1.45rem); /* smaller title */
  font-weight: 800;
}
</style>
