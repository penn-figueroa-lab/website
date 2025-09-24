---
layout: single
title: ""
author_profile: false
permalink: /
---

<!-- ===== FULL-BLEED HERO SLIDER WITH BOTTOM-CENTER TITLE ===== -->
<div class="hero-slider fullbleed" aria-label="Figueroa Robotics Lab Photo Gallery">

  <!-- Bottom overlay title (no background box) -->
  <div class="hero-title hero-title--bottom">
    <h1>Welcome to the Figueroa Robotics Lab</h1>
  </div>

  <button class="hs-nav hs-prev" aria-label="Previous slide">‹</button>

  <div class="hs-track" role="region" aria-live="polite">
    <img src="{{ '/assets/images/IMG_4148.JPG' | relative_url }}" alt="Lab photo 1" class="hs-slide hs-current">
    <img src="{{ '/assets/images/IMG_4075.JPG' | relative_url }}" alt="Lab photo 2" class="hs-slide">
    <img src="{{ '/assets/images/IMG_4115.JPG' | relative_url }}" alt="Lab photo 3" class="hs-slide">
  </div>

  <button class="hs-nav hs-next" aria-label="Next slide">›</button>
  <div class="hs-dots" role="tablist" aria-label="Choose slide"></div>
</div>

<!-- ===== SMALL SUB-HEADING UNDER SLIDER ===== -->
<!-- <div class="hero-subtext"> -->
  <p style="font-size: 20px;"> <b> Established in Fall 2022.</b> We are a group within the Penn Engineering
  <a href="https://www.grasp.upenn.edu/" target="_blank" rel="noopener">GRASP Lab</a>.</p>
<!-- </div> -->

<style>
/* ---------- Slider ---------- */
.hero-slider{
  position: relative;
  overflow: hidden;
  background: #f2f2f2;
}
.hero-slider.fullbleed{
  width: 100vw;
  max-width: 100vw;
  margin-left: 50%;
  transform: translateX(-50%);
  border-radius: 0;
}
.hs-track{
  display: flex;
  transition: transform 300ms ease;
  will-change: transform;
  position: relative;
  z-index: 1;
}
.hs-slide{
  flex: 0 0 100%;
  width: 100%;
  display: block;
  height: auto;
  object-fit: contain;
  max-height: 75vh;
}

/* ---------- Overlay Title ---------- */
.hero-title{
  position: absolute;
  inset: 0;
  display: grid;
  pointer-events: none;
  z-index: 3;
}
.hero-title--bottom{
  align-items: end;
  justify-items: center;
  padding-bottom: 30px;
}
.hero-title h1{
  margin: 0;
  color: #fff;
  font-weight: 800;
  font-size: clamp(22px, 2.6vw + 6px, 42px);
  line-height: 1.1;
  text-align: center;
  text-shadow:
    0 2px 5px rgba(0,0,0,0.45),
    0 1px 2px rgba(0,0,0,0.35);
}
@media (max-width: 360px){
  .hero-title h1{ font-size: clamp(18px, 4.5vw + 6px, 32px); }
}

/* ---------- Sub-heading under slider ---------- */
.hero-subtext{
  max-width: 900px;
  margin: 1.2rem auto 0;
  padding: 0 0.8rem;
  text-align: center;
  font-size: clamp(0.9rem, 1vw + 0.35rem, 1.1rem);
  line-height: 1.35;
  color: #333;
}
.hero-subtext a{
  color: #0066cc;
  font-weight: 600;
  text-decoration: none;
}
.hero-subtext a:hover{ text-decoration: underline; }

/* ---------- Controls & dots ---------- */
.hs-nav{
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  border: none;
  background: rgba(0,0,0,0.5);
  color:#fff;
  width: 40px;
  height: 40px;
  border-radius: 50%;
  cursor: pointer;
  font-size: 20px;
  z-index: 4;
}
.hs-prev{ left: 14px; }
.hs-next{ right: 14px; }

.hs-dots{
  position: absolute;
  left: 50%;
  bottom: 12px;
  transform: translateX(-50%);
  display: flex;
  gap: 6px;
  z-index: 4;
}
.hs-dots button{
  width: 10px;
  height: 10px;
  border-radius: 50%;
  border: none;
  background: rgba(255,255,255,0.4);
  cursor: pointer;
}
.hs-dots button[aria-selected="true"]{ background:#fff; }

/* Remove extra top padding under theme container */
.main .page__content { padding-top: 0; }

/* 🔕 Hide RSS/Feed icon just on this page */
.page__footer-follow .social-icons li:has(a[href$="feed.xml"]),
.page__footer-follow .social-icons li:has(.fa-rss),
.page__footer-follow .social-icons a[href$="feed.xml"],
.page__footer-follow .social-icons .fa-rss{
  display:none !important;
}
</style>

<script>
/* ===== Minimal, conflict-free slider JS ===== */
(function () {
  function init() {
    const slider = document.querySelector('.hero-slider');
    if (!slider) return;

    const track  = slider.querySelector('.hs-track');
    const slides = Array.from(slider.querySelectorAll('.hs-slide'));
    const prev   = slider.querySelector('.hs-prev');
    const next   = slider.querySelector('.hs-next');
    const dotsEl = slider.querySelector('.hs-dots');
    let index = 0;

    slides.forEach((_, i) => {
      const b = document.createElement('button');
      b.setAttribute('role', 'tab');
      b.setAttribute('aria-label', `Go to slide ${i + 1}`);
      b.addEventListener('click', () => goTo(i));
      dotsEl.appendChild(b);
    });

    function update() {
      track.style.transform = `translateX(-${index * 100}%)`;
      Array.from(dotsEl.children).forEach((b, i) =>
        b.setAttribute('aria-selected', i === index ? 'true' : 'false')
      );
    }
    function goTo(i){ index = (i + slides.length) % slides.length; update(); }

    if (prev) prev.addEventListener('click', () => goTo(index - 1));
    if (next) next.addEventListener('click', () => goTo(index + 1));

    let startX = 0;
    track.addEventListener('touchstart', e => startX = e.touches[0].clientX, {passive:true});
    track.addEventListener('touchend', e => {
      const dx = e.changedTouches[0].clientX - startX;
      if (dx > 40) goTo(index - 1);
      if (dx < -40) goTo(index + 1);
    });

    let timer = setInterval(() => goTo(index + 1), 5000);
    slider.addEventListener('mouseenter', () => clearInterval(timer));
    slider.addEventListener('mouseleave', () =>
      (timer = setInterval(() => goTo(index + 1), 5000))
    );

    update();
  }
  document.readyState === 'loading'
    ? document.addEventListener('DOMContentLoaded', init)
    : init();
})();
</script>
