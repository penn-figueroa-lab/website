---
layout: single
title: ""
permalink: /people/
---

<style>
/* 🔕 Hide pager & feed icons just on this page */
.pagination{ display:none !important; }
.page__footer-follow .social-icons a[href$="feed.xml"],
.page__footer-follow .social-icons a[href*="/feed"],
.page__footer-follow .social-icons .fa-rss{ display:none !important; }

/* Center the page title */
.page__title{ text-align:center !important; }

/* ===== Centered wrapper ===== */
.people-wrap{
  width: min(96vw, 1400px);   /* roomy but constrained */
  margin: 0 auto;             /* center on page */
  padding: 0 16px;            /* small gutter */
}
/* Ultra-wide screens: subtle left nudge for alignment with header */
@media (min-width:1500px){
  .people-wrap{ margin-left: -380px; margin-right: auto; }
}
/* Re-center below that breakpoint */
@media (max-width:1499.98px){
  .people-wrap{ margin-left: auto; margin-right: auto; }
}

/* ===== Sections ===== */
.people-section{ padding: 1rem 0 .5rem; text-align: center; }
.people-section + .people-section{ margin-top: .75rem; }
.people-section h2{ font-size: 1.4rem; margin: .35rem 0 .7rem; font-weight: 700; }

/* ===== Grid ===== */
.people-grid{
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 1rem 1.1rem;
  justify-items: center;
  align-items: start;
}

/* ===== Cards ===== */
.person-card{
  width: 200px;
  display: flex; flex-direction: column; align-items: center;
  text-align: center;
  font-size: .9rem;
}
.person-card img{
  width: 200px; height: 200px;
  border-radius: 10px; object-fit: cover;
  background: #f3f4f6; margin-bottom: .4rem;
}
.person-card h3{
  font-size: .98rem; font-weight: 600;
  margin: .18rem 0; line-height: 1.18;
  word-wrap: break-word;
}
.person-card p{ margin: .15rem 0 0; }

/* ===== Alumni tables (centered) ===== */
.alumni-table{
  width: 90%;                 /* take most of wrapper width */
  max-width: 1000px;           /* cap width on large screens */
  margin: .6rem auto 1.6rem;   /* auto centers left/right */
  border-collapse: collapse;
  font-size: .9rem;
}
.alumni-table th, .alumni-table td{
  border-bottom: 1px solid #e5e7eb;
  padding: .5rem .7rem;
  text-align: left;
  vertical-align: top;
}
.alumni-table th{ font-weight: 700; }
.alumni-group{
  text-align: center;
  margin: 1.1rem 0 .5rem;
  font-size: 1.05rem;
  font-weight: 600;
}
</style>

<div class="people-wrap">

<!-- === Principal Investigator === -->
<div class="people-section">
  <h2>Principal Investigator</h2>
  <div class="people-grid">
    <div class="person-card">
      <a href="https://nbfigueroa.github.io/" target="_blank" rel="noopener">
        <img src="{{ site.baseurl }}/assets/images/people/nadia_figueroa_reduced.jpg" alt="Nadia Figueroa">
      </a>
      <a href="https://nbfigueroa.github.io/" target="_blank" rel="noopener"><h3>Dr. Nadia Figueroa</h3></a>
      <p>Shalini and Rajeev Misra Presidential Assistant Professor, MEAM</p>
    </div>
  </div>
</div>

<!-- === PhD Students === -->
<div class="people-section">
  <h2>PhD Students</h2>
  <div class="people-grid">
    <div class="person-card"><a href="http://imtianyuli.com/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/tianyu_li.JPG" alt="Tianyu Li"></a><a href="http://imtianyuli.com/" target="_blank" rel="noopener"><h3>Tianyu Li</h3></a><p>MEAM, 2022–present</p></div>
    <div class="person-card"><a href="https://www.linkedin.com/in/yifan-xue-523168178/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/yifan_xue.JPG" alt="Yifan Xue"></a><a href="https://www.linkedin.com/in/yifan-xue-523168178/" target="_blank" rel="noopener"><h3>Yifan Xue</h3></a><p>MEAM, 2022–present</p></div>
    <div class="person-card"><a href="https://www.linkedin.com/in/shafagh-keyvanian-609b607a/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/shafagh_keyvanian.jpg" alt="Shafagh Keyvanian"></a><a href="https://www.linkedin.com/in/shafagh-keyvanian-609b607a/" target="_blank" rel="noopener"><h3>Shafagh Keyvanian</h3></a><p>MEAM, 2022–present<br><em>Co-advised with Michelle Johnson</em></p></div>
    <div class="person-card"><a href="https://www.linkedin.com/in/yifei-simon-shao/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/bio-photo.jpg" alt="Yifei Simon Shao"></a><a href="https://www.linkedin.com/in/yifei-simon-shao/" target="_blank" rel="noopener"><h3>Yifei Simon Shao</h3></a><p>CIS, 2023–present<br><em>Co-advised with V. Kumar & P. Chaudhari</em></p></div>
    <div class="person-card"><a href="https://sites.google.com/view/farhad-nawaz" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/farhad_nawaz.JPG" alt="Farhad Nawaz"></a><a href="https://sites.google.com/view/farhad-nawaz" target="_blank" rel="noopener"><h3>Farhad Nawaz</h3></a><p>ESE, 2023–present<br><em>Co-advised with Nikolai Matni</em></p></div>  
    <div class="person-card"><a href="https://www.linkedin.com/in/ho-jin-choi-425856208/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/ho_jin_choi.JPG" alt="Ho Jin Choi"></a><a href="https://www.linkedin.com/in/ho-jin-choi-425856208/" target="_blank" rel="noopener"><h3>Ho Jin Choi</h3></a><p>MEAM, 2024–present</p></div>
    <div class="person-card"><a href="https://sunan-sun.github.io/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/sunan_sun.JPG" alt="Sunan Sun"></a><a href="https://sunan-sun.github.io/" target="_blank" rel="noopener"><h3>Sunan Sun</h3></a><p>MEAM, 2025–present</p></div>
    <div class="person-card"><a href="https://sites.google.com/seas.upenn.edu/sanghyub-lee" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/sanghyub_lee.JPG" alt="Paul (Sanghyub) Lee"></a><a href="https://sites.google.com/seas.upenn.edu/sanghyub-lee" target="_blank" rel="noopener"><h3>Paul(Sanghyub) Lee</h3></a><p>MEAM, 2025–present</p></div>
  </div>
</div>

<!-- === Master's Thesis Students === -->
<div class="people-section">
  <h2>Master's Thesis Students</h2>
  <div class="people-grid">
    <!-- Add thesis students here -->
  </div>
</div>

<!-- === Master's Research Interns === -->
<div class="people-section">
  <h2>Master's Research Interns</h2>
  <div class="people-grid">
    <!-- Add interns here -->
  </div>
</div>

<!-- === Research Engineers === -->
<div class="people-section">
  <h2>Research Engineers</h2>
  <div class="people-grid">
    <div class="person-card">
      <a href="https://www.linkedin.com/in/daudizein/" target="_blank" rel="noopener">
        <img src="{{ site.baseurl }}/assets/images/people/daudi_zein.JPG" alt="Daudi Zein">
      </a>
      <a href="https://www.linkedin.com/in/daudizein/" target="_blank" rel="noopener"><h3>Daudi Zein</h3></a>
      <p>M.S. Robotics, 2025<br>2025-present<br><em>Research Engineer</em></p>
    </div>
  </div>
</div>

<!-- === Alumni === -->
<div class="people-section">
  <h2>Alumni</h2>

  <div class="alumni-group">Research Engineers</div>
  <table class="alumni-table">
    <thead>
      <tr><th>Name</th><th>Degree</th><th>Years</th><th>Next step / Notes</th></tr>
    </thead>
    <tbody>
      <tr><td>Jalaj Shukla</td><td>M.S. MEAM, 2025</td><td>2025</td><td>Senior Software Engineer at Blue Sky Robotics</td></tr>
      <tr><td>George [Jiayuan] Gao</td><td>M.S. Robotics, 2025</td><td>2025</td><td>Research Engineer at Dyna Robotics</td></tr>
      <tr><td>Yi-Hsuan Cheng</td><td>M.S. Robotics, 2025</td><td>2025</td><td>ML-AI Robotics Engineer at RoboForce</td></tr>
      <tr><td>Davin Tjandra</td><td>M.S. MEAM, 2025</td><td>2025</td><td>Robotics Software Engineer at Intrinsic (Google)</td></tr>
      <tr><td>Harshil Parekh</td><td>M.S. Robotics, 2023</td><td>2022–2024</td><td>Robotics Software Engineer at BotBuilt</td></tr>
    </tbody>
  </table>

  <div class="alumni-group">Visiting Scholars</div>
  <table class="alumni-table">
    <thead>
      <tr><th>Name</th><th>Affiliation</th><th>Term</th><th>Notes</th></tr>
    </thead>
    <tbody>
      <tr><td>Ze Zhang</td><td>Automation, Chalmers University of Technology (Sweden)</td><td>Fall 2024</td><td>Ph.D. Candidate; Visiting Research Scholar (advised by Knut Åkesson)</td></tr>
      <tr><td>Enrico Martini</td><td>Computer Science, University of Verona (Italy)</td><td>Spring 2024</td><td>Ph.D. Candidate; Visiting Research Scholar (advised by Nicola Bombieri)</td></tr>
    </tbody>
  </table>

  <div class="alumni-group">Master’s Thesis</div>
  <table class="alumni-table">
    <thead>
      <tr><th>Name</th><th>Degree</th><th>Years</th><th>Thesis / Notes</th></tr>
    </thead>
    <tbody>
      <tr><td>Paul [Sanghyub] Lee</td><td>M.S. Robotics, 2025</td><td>2023–2025</td><td>“Towards Real-Time Muscle Health Monitoring and Muscle-in-the-Loop Robotic Assistants via AI-Driven Wearable Ultrasound Processing”; now Ph.D. candidate in MEAM (Penn)</td></tr>
      <tr><td>George [Jiayuan] Gao</td><td>M.S. Robotics, 2025</td><td>2024–2025</td><td>“Visuomotor Object-Centric Out-Of-Distribution Recovery Policy”; <em>Outstanding Master’s Researcher Award in Robotics</em></td></tr>
      <tr><td>Ho Jin Choi</td><td>M.S. MEAM, 2024</td><td>2022–2024</td><td>“Gaussian Process-Based Active Exploration Strategies in Vision and Touch”; <em>Outstanding Master’s Researcher Award in MEAM</em>; Summer 2024 intern at MERL; now Ph.D. candidate in MEAM (Penn)</td></tr>
      <tr><td>Zhiquan Zhang</td><td>M.S. ESE, 2024</td><td>2022–2024</td><td>“Real-Time Safety-Critical Passive Torque Control with Analytic and Learning-based Constraints”; <em>Best Master’s Thesis in ESE</em>; now Ph.D. candidate at UIUC</td></tr>
      <tr><td>Haihui Gao</td><td>M.S. ESE & MEAM, 2024</td><td>2022–2024</td><td>“Advancing Dynamical Systems in Learning from Demonstration: A Novel Approach for Modeling Self-Crossing Trajectories”; now Ph.D. candidate at University of Montreal</td></tr>
      <tr><td>Satyajeet Das</td><td>M.S. ESE, 2024</td><td>2023–2024</td><td>“Towards Vision-based Safety: A Real-Time Approach for Generating Barrier Functions using Depth Sensors”; now Ph.D. candidate at USC (started Fall 2024)</td></tr>
      <tr><td>Haoming Li</td><td>M.S. ESE, 2024</td><td>2023–2024</td><td>“Towards Robust SLAM with Neural Implicit Representations”; Research Engineer at the University of Pennsylvania</td></tr>
    </tbody>
  </table>
</div>
</div>
