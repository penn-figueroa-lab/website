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
    <img src="{{ site.baseurl }}/assets/images/research-thursts.png" style="width:54%; max-width:760px;">
  </p>
</section>

<!-- ===== FULL-WIDTH GRID (not clickable) ===== -->
<section class="rb-grid">
  <div class="rb-card"><div class="rb-img"><img src="{{ site.baseurl }}/assets/images/Assistive_Robotics.JPG" alt="Assistive Robotics & Biomechanics"></div><h3>Assistive Robotics &amp; Biomechanics</h3></div>

  <div class="rb-card"><div class="rb-img"><img src="{{ site.baseurl }}/assets/images/Control_Estimation.JPG" alt="Control & Estimation"></div><h3>Control &amp; Estimation</h3></div>

  <div class="rb-card"><div class="rb-img"><img src="{{ site.baseurl }}/assets/images/hardware.JPG" alt="Hardware"></div><h3>Hardware</h3></div>

  <div class="rb-card"><div class="rb-img"><img src="{{ site.baseurl }}/assets/images/Imitation_Learning.JPG" alt="Imitation Learning"></div><h3>Imitation Learning</h3></div>

  <div class="rb-card"><div class="rb-img"><img src="{{ site.baseurl }}/assets/images/Perception_for_manipulation.JPG" alt="Perception for Manipulation"></div><h3>Perception for Manipulation</h3></div>
</section>

<style>
/* 🔕 Hide pager & feed icon */
.pagination{display:none!important;}
.page__footer-follow .social-icons a[href$="feed.xml"],
.page__footer-follow .social-icons a[href*="/feed"],
.page__footer-follow .social-icons .fa-rss{display:none!important;}

/* keep theme spacing tight */
.main .page__content{padding-top:0.35rem;}

/* ---------- Intro ---------- */
.rb-fullbleed{width:100vw;margin-left:calc(50% - 50vw);}
.rb-intro{
  max-width:960px;
  margin:0 auto 1.2rem;
  padding:0 16px;
  text-align:justify;
  text-justify:inter-word;
}
.rb-intro h1{
  text-align:center;
  margin-bottom:0.6rem;
  font-weight:800;
  font-size:clamp(1.1rem,0.9vw + 0.85rem,1.4rem);
}
.rb-intro p{
  margin:0 auto;
  line-height:1.55;
  max-width:820px;
  font-size:clamp(0.84rem,0.35vw + 0.7rem,0.94rem);
}

/* ---------- Grid ---------- */
.rb-grid{
  width:100vw;
  margin-left:calc(50% - 50vw);
  padding:0 clamp(8px,3vw,24px);
  display:grid;
  gap:clamp(12px,2vw,20px);
  grid-template-columns:repeat(3,minmax(260px,1fr)); /* smaller min width */
  justify-items:center;
}
@media(max-width:1000px){.rb-grid{grid-template-columns:repeat(2,minmax(240px,1fr));}}
@media(max-width:700px){.rb-grid{grid-template-columns:minmax(210px,1fr);}}

/* ---------- Cards ---------- */
.rb-card{
  width:100%;
  max-width:460px;   /* narrower card */
  display:flex;
  flex-direction:column;
  align-items:center;
}
.rb-img{
  width:100%;
  aspect-ratio:16/9;
  border-radius:10px;
  overflow:hidden;
  box-shadow:0 6px 18px rgba(0,0,0,.06);
  background:#f3f4f6;
}
.rb-img img{
  width:100%;
  height:100%;
  object-fit:cover;
  display:block;
  transition:transform .25s ease,filter .25s ease;
}
.rb-card:hover .rb-img img{
  transform:scale(1.01);
  filter:brightness(1.02);
}
.rb-card h3{
  margin:0.55rem 0 0;
  text-align:center;
  font-size:clamp(0.9rem,0.9vw + 0.6rem,1.15rem);
  font-weight:800;
}
</style>
