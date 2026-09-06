---
layout: single
title: ""
permalink: /joining/
---


<section class="joining-wrap">
  <!-- ===== INTRO ===== -->
  <div class="rb-intro">
    <h1>Opportunities</h1>
    <p align="center">
      Information on how to join the Figueroa Robotics Lab will be posted soon!
    </p>
  </div>

  <!-- ===== NEW RESEARCH PROJECTS (Google Doc embed) =====
       This iframe uses Google Docs' "Publish to web" embed code.
       Currently pointing at the OLD doc as a placeholder/test —
       swap the src below for the new doc's published URL once
       it's finished, no other changes needed. -->
<!--   <div class="rb-gdoc">
    <h2>New Research Projects</h2>
    <div class="rb-gdoc-frame">
      <iframe src="https://docs.google.com/document/d/e/2PACX-1vS5m0OD5v2otO8EukJFPlaXsFMHuc-_StVhxLMznkSpHXddslt4k4IUyG2bGly2Bth81z33nfjHE-MP/pub?embedded=true" title="New Research Projects"></iframe>
    </div>
  </div> -->
</section>

<style>
/* 🔕 Hide pager & feed icon just on this page */
.pagination{ display:none!important; }
.page__footer-follow .social-icons a[href$="feed.xml"],
.page__footer-follow .social-icons a[href*="/feed"],
.page__footer-follow .social-icons .fa-rss{ display:none!important; }

/* tighten theme spacing (match research page) */
.main .page__content{ padding-top:0.35rem; }

/* ===== Centered wrapper with bigger side margins (match research) =====
   - Narrower width to create larger side gutters
   - Manual left shift on very wide screens (same idea as research page) */
.joining-wrap{
  width: min(82vw, 1200px);
  margin: 0 auto 1.5rem;
  padding: 0 12px;
}



/* ===== Intro (match research typography) ===== */
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

/* ===== Google Doc embed (New Research Projects) ===== */
.rb-gdoc{
  margin-top: 2rem;
}
.rb-gdoc h2{
  text-align: center;
  font-weight: 800;
  font-size: clamp(1.1rem, 1vw + .8rem, 1.4rem);
  margin-bottom: 0.8rem;
}
.rb-gdoc-frame{
  width: 100%;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 6px 18px rgba(0,0,0,.08);
  border: 1px solid #e5e7eb;
}
.rb-gdoc-frame iframe{
  width: 100%;
  height: 1000px;
  border: none;
  display: block;
}
@media (max-width: 600px){
  .rb-gdoc-frame iframe{ height: 700px; }
}
</style>
