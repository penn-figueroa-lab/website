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
    <img src="{{ '/assets/images/awards-presentations-grads/hojin_MS.jpg' | relative_url }}" alt="Hojin grad" class="hs-slide">    
    <img src="{{ '/assets/images/lab-pictures/IMG_4075.JPG' | relative_url }}" alt="Lab photo 2" class="hs-slide">
    <img src="{{ '/assets/images/lab-trips/girls_icra_2025.jpg' | relative_url }}" alt="Lab trip icra 2024 2" class="hs-slide">
    <img src="{{ 'assets/images/lab-trips/lab_ICRA_2025.jpeg' | relative_url }}" alt="Lab icra 2025" class="hs-slide">
    <img src="{{ '/assets/images/lab-pictures/IMG_4115.JPG' | relative_url }}" alt="Lab photo 3" class="hs-slide">
    <img src="{{ '/assets/images/lab-trips/lab_rss_2025.JPG' | relative_url }}" alt="Lab trip rss 2025" class="hs-slide">
    <img src="{{ 'assets/images/lab-trips/PINGPONG.jpeg' | relative_url }}" alt="Lab trip rss 2025" class="hs-slide">
    <img src="{{ '/assets/images/awards-presentations-grads/best-paper-award-team.jpg' | relative_url }}" alt="ICRA 2026 Best conference paper team" class="hs-slide">    
    <img src="{{ '/assets/images/awards-presentations-grads/best-paper-award.jpg' | relative_url }}" alt="ICRA 2026 Best conference paper" class="hs-slide"> 
    <img src="{{ '/assets/images/awards-presentations-grads/planning-award-team.jpg' | relative_url }}" alt="ICRA 2026 Best planning paper team" class="hs-slide">    
    <img src="{{ '/assets/images/awards-presentations-grads/planning-award.jpg' | relative_url }}" alt="ICRA 2026 Best planning paper" class="hs-slide">
    <img src="{{ '/assets/images/awards-presentations-grads/Vijay-Nadia-Yifei.jpg' | relative_url }}" alt="ICRA 2026 Best planning paper" class="hs-slide">    
    <img src="{{ '/assets/images/awards-presentations-grads/yihan_MS_2.jpg' | relative_url }}" alt="Yihan grad" class="hs-slide">
    <img src="{{ '/assets/images/awards-presentations-grads/farhad_PhD.jpg' | relative_url }}" alt="Yihan grad" class="hs-slide">           
  </div>

  <button class="hs-nav hs-next" aria-label="Next slide">›</button>
  <div class="hs-dots" role="tablist" aria-label="Choose slide"></div>
</div>

<!-- ===== SMALL SUB-HEADING UNDER SLIDER ===== -->
<div class="hero-subtext"> 
  <p style="font-size: 20px;"> <b> Established in Fall 2022.</b> We are a group within the Penn Engineering
  <a href="https://www.grasp.upenn.edu/" target="_blank" rel="noopener">GRASP Lab</a>.</p>
  <p style="font-size: 20px;"> We are building the next-generation of <span style="color: red;">human-centered robotic intelligence</span> through novel estimation, learning and control algorithms that are efficient, reliable, adaptive and safe.</p>
  
</div> 

<div class="hero-subtext funding-logos"> 
  <p style="font-size: 20px;"> We are grateful to our research sponsors:</p>
  <div class="funding-logos-row">
    <img src="{{ site.baseurl }}/assets/images/funding-logos/NSF_logo.png" alt="National Science Foundation">
    <img src="{{ site.baseurl }}/assets/images/funding-logos/nih-symbol.png" alt="National Institutes of Health">
    <img src="{{ site.baseurl }}/assets/images/funding-logos/Stacked-Full-Color-on-Light.png" alt="U.S. Department of Veterans Affairs">
    <img src="{{ site.baseurl }}/assets/images/funding-logos/Penn-ASSET1-Logo.png" alt="Penn Engineering ASSET Center">
  </div>
</div> 

<!-- ===== NEWS SECTION =====
     To add a new item: copy one <div class="news-item">...</div> block and
     paste it right after this comment, at the top of .news-list, so the
     newest news stays first. -->
<div class="news-wrap">
  <h2 class="news-heading">Latest News</h2>
  <div class="news-list">

    <div class="news-item">
      <div class="news-date">Aug 2026</div>
      <div class="news-body">
        <div class="news-title">:trophy: Zero-Shot Generalization paper named CASE 2026 Best Conference Paper Finalist</div>
        <p>Congratulations to Kilian Freitag, Alvin Combrink, and Prof. Figueroa on their paper being selected as a finalist for the <a href="https://2026.ieeecase.org/awards/" target="_blank" rel="noopener">Best Conference Paper Award</a> at IEEE CASE 2026 in Shenyang, China.</p>
      </div>
    </div>

    <div class="news-item">
      <div class="news-date">May 2026</div>
      <div class="news-body">
        <div class="news-title">:trophy::trophy: Two Best Paper Awards at ICRA 2026</div>
        <p>SymSkill won both the <a href="https://2026.ieee-icra.org/awards/" target="_blank" rel="noopener">Best Paper Award in Planning and Control and the overall Best Conference Paper Award</a> at IEEE ICRA 2026 in Vienna, Austria &mdash; congratulations to the team!</p>
      </div>
    </div>

  </div>
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
@media (max-width: 340px){
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

.hero-subtext.funding-logos{
  max-width: 1600px;
}
.funding-logos-row{
  display: flex;
  flex-wrap: nowrap;
  align-items: center;
  justify-content: center;
  gap: 1rem 1.5rem;
  padding: 0.5rem 0;
  width: 100%;
}
.funding-logos-row img{
  height: auto;
  width: auto;
  max-height: clamp(32px, 8vw, 70px);
  max-width: 25%;
  object-fit: contain;
  flex: 0 1 auto;
}

/* ---------- News section ---------- */
.news-wrap{
  max-width: 900px;
  margin: 2.2rem auto 1.5rem;
  padding: 0 0.8rem;
}
.news-heading{
  text-align: center;
  margin: 0 0 1rem;
  padding-bottom: 0.4rem;
  border-bottom: 2px solid #222;
  font-weight: 800;
  font-size: clamp(1.1rem, 1vw + .8rem, 1.5rem);
}
.news-list{
  display: flex;
  flex-direction: column;
  gap: 1.1rem;
}
.news-item{
  display: grid;
  grid-template-columns: 110px 1fr;
  gap: 1rem;
  text-align: left;
}
.news-date{
  font-weight: 700;
  color: #555;
  font-size: 0.9rem;
  white-space: nowrap;
  padding-top: 0.15rem;
}
.news-title{
  font-weight: 700;
  font-size: 1rem;
  color: #1a1a1a;
  margin-bottom: 0.2rem;
}
.news-body p{
  margin: 0;
  font-size: 0.92rem;
  line-height: 1.5;
  color: #333;
}
@media (max-width: 560px){
  .news-item{
    grid-template-columns: 1fr;
    gap: 0.2rem;
  }
  .news-date{ font-size: 0.82rem; }
}

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
