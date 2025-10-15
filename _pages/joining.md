---
layout: single
title: ""
permalink: /joining/
---


<section class="joining-wrap">
  <!-- ===== INTRO ===== -->
  <div class="rb-intro">
    <h1>Joining</h1>
    <p align="center">
      Information on how to join the Figueroa Robotics Lab will be posted soon!
    </p>
  </div>
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

/* Ultra-wide manual nudge (adjust -300px as needed to match header alignment) */
@media (min-width: 1500px){
  .joining-wrap{
    margin-left: -300px;   /* manual left shift */
    margin-right: auto;
  }
}
/* Re-center below that breakpoint */
@media (max-width: 1499.98px){
  .joining-wrap{
    margin-left: auto;
    margin-right: auto;
  }
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
</style>
