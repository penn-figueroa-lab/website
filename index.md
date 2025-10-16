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
    <img src="{{ '/assets/images/lab-pictures/IMG_4148.JPG' | relative_url }}" alt="Lab photo 1" class="hs-slide hs-current">
    <img src="{{ '/assets/images/lab-trips/lab_icra_2024.jpg' | relative_url }}" alt="Lab trip icra 2024 1" class="hs-slide">
    <img src="{{ '/assets/images/lab-trips/lab_icra_lunch_2024.jpg' | relative_url }}" alt="Lab trip icra 2024 2" class="hs-slide">
    <img src="{{ '/assets/images/lab-pictures/IMG_4075.JPG' | relative_url }}" alt="Lab photo 2" class="hs-slide">
    <img src="{{ '/assets/images/lab-trips/girls_icra_2025.jpg' | relative_url }}" alt="Lab trip icra 2024 2" class="hs-slide">
    <img src="{{ '/assets/images/lab-pictures/IMG_4115.JPG' | relative_url }}" alt="Lab photo 3" class="hs-slide">
    <img src="{{ '/assets/images/lab-trips/lab_rss_2025.JPG' | relative_url }}" alt="Lab trip rss 2025" class="hs-slide">
  </div>

  <button class="hs-nav hs-next" aria-label="Next slide">›</button>
  <div class="hs-dots" role="tablist" aria-label="Choose slide"></div>
</div>

<!-- ===== SMALL SUB-HEADING UNDER SLIDER ===== -->
<div class="hero-subtext"> 
  <p style="font-size: 20px;"> <b> Established in Fall 2022.</b> We are a group within the Penn Engineering
  <a href="https://www.grasp.upenn.edu/" target="_blank" rel="noopener">GRASP Lab</a>.</p>
  <p style="font-size: 20px;"> We are building the next-generation of <b style="color: red;">human-centered robotic intelligence</b> through novel estimation, learning and control algorithms that are efficient, reliable, adaptive and safe.</p>
  
</div> 

<div class="hero-subtext"> 
  <p style="font-size: 20px;"> Our research has been sponsored by:
      <p align="center">
      <img src="{{ site.baseurl }}/assets/images/funding-logos/NSF_logo.png" style="width:25%; max-width:860px;">
      <img src="{{ site.baseurl }}/assets/images/funding-logos/Penn-ASSET1-Logo.png" style="width:60%; max-width:860px;">
    </p>
  </p>
</div> 



<style>
/* ---------- Slider ---------- */
.hero-slider{
  position: relative;
  overflow: hidden;
  background: #fff;
}
.hero-slider.fullbleed {
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
  max-height: 70vh;
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
.hero-title h1 {
  margin: 0 auto;
  color: #fff;
  font-weight: 800;
  font-size: clamp(22px, 2.6vw + 6px, 42px);
  line-height: 1.1;
  text-align: center;
  text-shadow:
    0 2px 5px rgba(0,0,0,0.45),
    0 1px 2px rgba(0,0,0,0.35);
  max-width: 80%;          /* ✅ limit width to 80% of slider */
}

/* slightly tighter on mobile */
@media (max-width: 340px){
  .hero-title h1 {
    font-size: clamp(18px, 4.5vw + 6px, 32px);
    max-width: 90%;
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
.hs-nav {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  border: 1.5px solid rgba(0,0,0,0.25); /* ✅ subtle border for visibility on white */
  background: rgba(255,255,255,0.85);   /* ✅ light white background */
  color: #333;                          /* ✅ dark arrow for white background */
  width: 42px;
  height: 42px;
  border-radius: 50%;
  cursor: pointer;
  font-size: 22px;
  line-height: 38px;
  text-align: center;
  box-shadow: 0 2px 6px rgba(0,0,0,0.15);
  z-index: 4;
  transition: all 0.25s ease;
}

.hs-nav:hover {
  background: #fff;
  border-color: rgba(0,0,0,0.4);
  transform: translateY(-50%) scale(1.05);
}

/* ✅ bring buttons slightly inward */
.hs-prev { left: 24px; }
.hs-next { right: 24px; }

/* ---------- Dots ---------- */
.hs-dots {
  position: absolute;
  left: 50%;
  bottom: 14px;
  transform: translateX(-50%);
  display: flex;
  gap: 8px;
  z-index: 4;
}
.hs-dots button {
  width: 10px;
  height: 10px;
  border-radius: 50%;
  border: none;
  background: rgba(0,0,0,0.25);
  cursor: pointer;
}
.hs-dots button[aria-selected="true"] {
  background: #000;
}


/* Remove extra top padding under theme container */
.main .page__content { padding-top: 0; }

/* 🔕 Hide RSS/Feed icon just on this page */
.page__footer-follow .social-icons li:has(a[href$="feed.xml"]),
.page__footer-follow .social-icons li:has(.fa-rss),
.page__footer-follow .social-icons a[href$="feed.xml"],
.page__footer-follow .social-icons .fa-rss{
  display:none !important;
}



/* ===== Anchor slider UI to a centered max width ===== */
.hero-slider{
  --slide-max: 1200px;              /* adjust to your preferred content width */
  position: relative;
  background: #fff;                 /* keep white background */
}

/* Constrain the overlay title and the track/dots to the same center width */
.hero-slider .hero-title,
.hero-slider .hs-track,
.hero-slider .hs-dots{
  max-width: var(--slide-max);
  margin-left: auto;
  margin-right: auto;
  position: relative;
}

/* Keep images slightly smaller if you like */
.hs-slide{
  max-height: 68vh;                 /* tweak 60–70vh as desired */
  object-fit: contain;
}

/* ===== Nav buttons: center vertically and hug the image edges (not the viewport) ===== */
.hs-nav{
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  border: 1.5px solid rgba(0,0,0,0.25);
  background: rgba(255,255,255,0.9);
  color: #333;
  width: 42px; height: 42px;
  border-radius: 50%;
  cursor: pointer;
  font-size: 22px; line-height: 38px; text-align: center;
  box-shadow: 0 2px 6px rgba(0,0,0,0.15);
  z-index: 4;
  transition: all .25s ease;
}

/* ⚓ Position relative to centered content box */
.hs-prev{ left: calc(50% - (var(--slide-max) / 2) + 16px); }
.hs-next{ right: calc(50% - (var(--slide-max) / 2) + 16px); }

.hs-nav:hover{
  background:#fff; border-color: rgba(0,0,0,0.4);
  transform: translateY(-50%) scale(1.05);
}

/* Dots: keep centered under the constrained width */
.hs-dots{
  left: 50%;
  bottom: 14px;
  transform: translateX(-50%);
  display: flex; gap: 8px; z-index: 4;
}

/* Title: keep it narrower so it doesn’t span edge-to-edge */
.hero-title h1{
  max-width: 80%;
  margin: 0 auto;
}
@media (max-width: 640px){
  .hero-title h1{ max-width: 90%; }
  .hs-prev{ left: 12px; }           /* tuck arrows in a bit on small screens */
  .hs-next{ right: 12px; }
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
