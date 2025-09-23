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
<div class="hero-subtext">
  We are a group within the
  <a href="https://www.grasp.upenn.edu/" target="_blank" rel="noopener">
    Penn Engineering GRASP Lab
  </a>.
</div>

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
  object-fit: contain;        /* never crop */
  max-height: 85vh;
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
  padding-bottom: 40px;
}
.hero-title h1{
  margin: 0;
  color: #fff;
  font-weight: 800;
  font-size: clamp(24px, 3vw + 8px, 48px);
  line-height: 1.12;
  text-align: center;
  text-shadow:
    0 2px 6px rgba(0,0,0,0.45),
    0 1px 2px rgba(0,0,0,0.35);
}
@media (max-width: 360px){
  .hero-title h1{ font-size: clamp(20px, 5vw + 6px, 36px); }
}

/* ---------- Sub-heading under slider ---------- */
.hero-subtext{
  max-width: 1000px;
  margin: 1.5rem auto 0;
  padding: 0 1rem;
  text-align: center;
  font-size: clamp(1rem, 1.2vw + 0.4rem, 1.25rem);
  line-height: 1.4;
  color: #333;
}
.hero-subtext a{
  color: #0066cc;              /* Penn blue-ish link */
  font-weight: 600;
  text-decoration: none;
}
.hero-subtext a:hover{
  text-decoration: underline;
}

/* ---------- Controls & dots ---------- */
.hs-nav{
  position: absolute; top: 50%; transform: translateY(-50%);
  border: none; background: rgba(0,0,0,0.5); color:#fff;
  width: 48px; height: 48px; border-radius: 50%; cursor: pointer; font-size: 24px;
  z-index: 4;
}
.hs-prev{ left: 16px; }
.hs-next{ right: 16px; }

.hs-dots{
  position: absolute; left: 50%; bottom: 16px; transform: translateX(-50%);
  display: flex; gap: 8px;
  z-index: 4;
}
.hs-dots button{
  width: 12px; height: 12px; border-radius: 50%;
  border: none; background: rgba(255,255,255,0.4); cursor: pointer;
}
.hs-dots button[aria-selected="true"]{ background:#fff; }

/* Remove extra top padding under theme container */
.main .page__content { padding-top: 0; }
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

    // Build dots
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

    // Touch swipe
    let startX = 0;
    track.addEventListener('touchstart', e => startX = e.touches[0].clientX, {passive:true});
    track.addEventListener('touchend', e => {
      const dx = e.changedTouches[0].clientX - startX;
      if (dx > 40) goTo(index - 1);
      if (dx < -40) goTo(index + 1);
    });

    // Autoplay (pause on hover)
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
