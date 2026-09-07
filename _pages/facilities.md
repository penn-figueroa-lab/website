---
layout: single
title: ""
permalink: /facilities/
---

<section class="facilities-wrap">
  <!-- ===== INTRO (first paragraph) ===== -->
  <div class="fac-intro">
    <h2>Our Facilities</h2>
    <p>
      Figueroa Robotics Lab focuses on studying and developing the <b>physical and perceptual adaptive intelligence</b> necessary for robots to learn from and interact with humans. The goal is to develop robotic technologies that adapt to a wide-range of human capabilities, needs and ever-changing environments; achieving fluid human-robot collaborative autonomy; i.e., when humans and robots collaborate harmoniously.
    </p>
  </div>

  <!-- ===== GRID (not clickable) ===== -->
  <section class="fac-grid">
    <div class="fac-card">
      <div class="fac-img"><img src="{{ site.baseurl }}/assets/images/lab-pictures/main_lab.jpg" alt="Main Lab Space"></div>
      <h3>Main Lab Space</h3>
    </div>
    <div class="fac-card">
      <div class="fac-img"><img src="{{ site.baseurl }}/assets/images/lab-pictures/humanoid.jpg" alt="Humanoid Platforms"></div>
      <h3>Rescue Randy mannequin (GRASP shared resource), Unitree R1 Humanoid, OpenArm Humanoid Torso</h3>
    </div>
    <div class="fac-card">
      <div class="fac-img"><img src="{{ site.baseurl }}/assets/images/lab-pictures/kuka.jpg" alt="Manipulation & Kitchenette"></div>
      <h3>KUKA IIWA-14 with functional kitchenette in the background </h3>
    </div>
    <div class="fac-card">
      <div class="fac-img"><img src="{{ site.baseurl }}/assets/images/lab-pictures/franka.jpg" alt="Dual-Arm Manipulation"></div>
      <h3>Dual-arm setup of a Franka Research 3 and a Franka Panda Emika</h3>
    </div>
    <div class="fac-card">
      <div class="fac-img"><img src="{{ site.baseurl }}/assets/images/lab-pictures/franka_back.jpg" alt="Adjoint Lab Space"></div>
      <h3>Dual setup of 2 Franka Research 3 Arms</h3>
    </div>
    <div class="fac-card">
      <div class="fac-img"><img src="{{ site.baseurl }}/assets/images/lab-pictures/mobile.jpg" alt="Scout 2.0 (AgileX) and Fetch Mobile Manipulator"></div>
      <h3>Scout 2.0 (AgileX) and Fetch Mobile Manipulator</h3>
    </div>
  
  </section>

  <!-- ===== REMAINING TEXT (after grid) ===== -->
  <div class="fac-intro">
    <p>
      The lab is housed in a 825 square foot lab space in Levine 266 composed of a 666 square foot main lab space equipped with a 24-camera Optitrack Motion Capture System as well as a small-scale functioning kitchenette for experimentation with assistive robot household applications; and a smaller 159 square foot adjoint lab space where experimental robotic platforms are evaluated.
    </p>
    <p>
      The equipment that is used in this facility includes three redundant 7-DOF collaborative manipulators (two Franka Emika, one KUKA IIWA) with a wide range of payloads (from 2kg-14kg), one OpenArm 1.0 Bimanual Humanoid upper body, and one Unitree R1 Humanoid. During summer two additional collaborative manipulators (Franka Emika) are borrowed from the MEAM labs to experiment on dual-arm experiments.
    </p>
    <p>
      In addition, the lab has a myriad of robotics peripherals and sensors used with these robots which include: one LEAP 4-fingered hand, one QB 4-fingered compliant hand, one Robotiq 2-finger gripper, one Robotiq force/torque sensor, three Botasys force/torque sensors, one Telemed wearable ultrasonic sensor, one Bittium Neurone wet EEG device.
    </p>
    <p>
      The lab also experiments in social navigation with a 4WD All-Terrain Scout 2.0 Mobile Robot from AgileX and one Fetch Mobile Manipulator for indoor social navigation.
    </p>
    <p>
      Computational assets include 7 desktop PCs (GPUs: 4 Nvidia RTX 3070, 1 Nvidia RTX 3080, 2 Nvidia RTX 3090) and one Bambu Lab 3D printer.
    </p>
  </div>
</section>

<style>
/* 🔕 Hide pager & feed icon just on this page */
.pagination{ display:none!important; }
.page__footer-follow .social-icons a[href$="feed.xml"],
.page__footer-follow .social-icons a[href*="/feed"],
.page__footer-follow .social-icons .fa-rss{ display:none!important; }

/* tighten theme spacing */
.main .page__content{ padding-top:0.35rem; }

/* ===== Centered wrapper with bigger side margins =====
   Truly centered at every screen width — no manual pixel nudges. */
.facilities-wrap{
  width: min(82vw, 1100px);
  margin: 0 auto 1.5rem;
  padding: 0 12px;
}

/* ===== Intro ===== */
.fac-intro{
  width: 100%;
  text-align: justify;
  text-justify: inter-word;
}
.fac-intro h2{
  text-align:center;
  margin-bottom:0.7rem;
  font-weight:800;
  font-size:clamp(0.9rem, 0.9vw + 0.75rem, 1.25rem);
}
.fac-intro p{
  margin:0.6rem 0;
  line-height:1.6;
  font-size:clamp(0.9rem, 0.35vw + 0.78rem, 1rem);
}

/* ===== Grid ===== */
.fac-grid{
  margin-top:1.2rem;
  display:grid;
  gap: clamp(14px, 2vw, 26px);
  grid-template-columns: repeat(3, minmax(240px, 1fr));
  justify-items:center;
}
@media (max-width: 900px){
  .fac-grid{ grid-template-columns: repeat(2, minmax(220px, 1fr)); }
}
@media (max-width: 600px){
  .fac-grid{ grid-template-columns: minmax(210px, 1fr); }
}

/* ===== Cards ===== */
.fac-card{
  width:100%;
  max-width:420px;
  display:flex;
  flex-direction:column;
  align-items:center;
  text-align:center;
}
.fac-img{
  width:100%;
  aspect-ratio:16 / 9;
  border-radius:12px;
  overflow:hidden;
  box-shadow:0 6px 18px rgba(0,0,0,.06);
  background:#f3f4f6;
}
.fac-img img{
  width:100%;
  height:100%;
  object-fit:contain;
  display:block;
  transition:transform .25s ease, filter .25s ease;
}
.fac-card:hover .fac-img img{
  transform:scale(1.015);
  filter:brightness(1.02);
}
.fac-card h3{
  margin:0.6rem 0 0;
  font-weight:600;
  font-size:clamp(0.8rem, 0.35vw + 0.62rem, 0.95rem);
  line-height:1.35;
}
</style>
