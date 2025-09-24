---
layout: single
title: ""
permalink: /people/
---

<style>
/* 🔕 Hide the Minimal Mistakes pager on this page only */
.pagination{ display:none !important; }

/* 🔕 Hide RSS/Feed icon just on this page (robust selectors) */
.page__footer-follow .social-icons a[href$="feed.xml"],
.page__footer-follow .social-icons a[href*="/feed"],
.page__footer-follow .social-icons .fa-rss,
.page__footer-follow .social-icons a[aria-label*="Feed"],
.page__footer-follow .social-icons a[title*="Feed"]{
  display:none !important;
}

/* ===== Centered page wrapper (“red margin” width) ===== */
.people-wrap{
  max-width: 1120px;   /* << match your desired content width */
  margin: 0 auto;
  padding: 0 20px;     /* small side padding so it breathes on phones */
}

/* Center the page title from the theme */
.page__title{ text-align:center !important; }

/* ===== Sections ===== */
.people-section{
  padding: 1rem 2rem;
  box-sizing: border-box;
  text-align: center;
}

/* Section heading (restored) */
.people-section h2{
  text-align: center;
  font-size: 1.6rem;
  margin: 0.6rem 0 0.9rem;
  font-weight: 700;
}

/* ===== Grid (restored to the roomy version) ===== */
.people-grid{
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  column-gap: 1.25rem;
  row-gap: 1rem;
  justify-content: center;
  justify-items: center;
  align-items: start;
}

/* ===== Card (restored) ===== */
.person-card{
  width: 220px;
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  font-size: 0.95rem;
}

/* Image (restored 220x220) */
.person-card img{
  width: 220px;
  height: 220px;
  border-radius: 8px;
  object-fit: cover;
  margin-bottom: 0.4rem;
  background: #f3f4f6;
}

/* Name (restored) */
.person-card h3{
  font-size: 1rem;
  font-weight: 600;
  margin: 0.2rem 0;
  line-height: 1.2;
  word-wrap: break-word;
  white-space: normal;
  max-width: 100%;
}

.person-card p{ margin: 0.15rem 0 0; }

/* ===== Alumni tables (same look, kept tidy) ===== */
.alumni-table{
  width: 100%;
  border-collapse: collapse;
  margin: 0.6rem 0 1.8rem 0;
  font-size: 0.95rem;
}
.alumni-table th, .alumni-table td{
  border-bottom: 1px solid #e5e7eb;
  padding: 0.5rem 0.75rem;
  text-align: left;
  vertical-align: top;
}
.alumni-table th{ font-weight: 700; }
.alumni-group{
  margin-top: 1.2rem;
  margin-bottom: 0.5rem;
  font-size: 1.06rem;
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
      <div class="person-card"><a href="http://imtianyuli.com/"  target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/tianyu_li.JPG" alt="Tianyu Li"></a><a href="http://imtianyuli.com/" target="_blank" rel="noopener"><h3>Tianyu Li</h3></a><p>MEAM, 2022–present</p></div>
      <div class="person-card"><a href="https://www.linkedin.com/in/yifan-xue-523168178/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/yifan_xue.JPG" alt="Yifan Xue"></a><a href="https://www.linkedin.com/in/yifan-xue-523168178/" target="_blank" rel="noopener"><h3>Yifan Xue</h3></a><p>MEAM, 2022–present</p></div>
      <div class="person-card"><a href="https://www.linkedin.com/in/shafagh-keyvanian-609b607a/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/shafagh_keyvanian.jpg" alt="Shafagh Keyvanian"></a><a href="https://www.linkedin.com/in/shafagh-keyvanian-609b607a/" target="_blank" rel="noopener"><h3>Shafagh Keyvanian</h3></a><p>MEAM, 2022–present<br><em>Co-advised with Michelle Johnson</em></p></div>
      <div class="person-card"><a href="https://www.linkedin.com/in/yifei-simon-shao/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/bio-photo.jpg" alt="Yifei Simon Shao"></a><a href="https://www.linkedin.com/in/yifei-simon-shao/" target="_blank" rel="noopener"><h3>Yifei Simon Shao</h3></a><p>CIS, 2023–present<br><em>Co-advised with V. Kumar & P. Chaudhari</em></p></div>
      <div class="person-card"><a href="https://sites.google.com/view/farhad-nawaz" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/farhad_nawaz.JPG" alt="Farhad Nawaz"></a><a href="https://sites.google.com/view/farhad-nawaz" target="_blank" rel="noopener"><h3>Farhad Nawaz</h3></a><p>ESE, 2023–present<br><em>Co-advised with Nikolai Matni</em></p></div>
      <div class="person-card"><a href="https://www.linkedin.com/in/ho-jin-choi-425856208/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/ho_jin_choi.JPG" alt="Ho Jin Choi"></a><a href="https://www.linkedin.com/in/ho-jin-choi-425856208/" target="_blank" rel="noopener"><h3>Ho Jin Choi</h3></a><p>MEAM, 2024–present</p></div>

      <div class="person-card">
        <a href="https://sunan-sun.github.io/" target="_blank" rel="noopener">
          <img src="{{ site.baseurl }}/assets/images/people/sunan_sun.JPG" alt="Sunan Sun">
        </a>
        <a href="https://sunan-sun.github.io/" target="_blank" rel="noopener"><h3>Sunan Sun</h3></a>
        <p>MEAM, 2025–present</p>
      </div>

      <div class="person-card">
        <a href="https://sites.google.com/seas.upenn.edu/sanghyub-lee" target="_blank" rel="noopener">
          <img src="{{ site.baseurl }}/assets/images/people/sanghyub_lee.JPG" alt="Paul (Sanghyub) Lee">
        </a>
        <a href="https://sites.google.com/seas.upenn.edu/sanghyub-lee" target="_blank" rel="noopener"><h3>Paul(Sanghyub) Lee</h3></a>
        <p>MEAM, 2025–present</p>
      </div>
    </div>
  </div>

  <!-- === Master's Thesis Students === -->
  <div class="people-section">
    <h2>Master's Thesis Students</h2>
    <div class="people-grid">
      <div class="person-card">
        <a href="https://mateuszjaszczuk.com/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/mateusz_jaszczuk.JPG" alt="Mateusz Jaszczuk"></a>
        <a href="https://mateuszjaszczuk.com/" target="_blank" rel="noopener"><h3>Mateusz Jaszczuk</h3></a>
        <p>M.S. MEAM, 2026<br>2024–present<br><em>Thesis: “Learning to Feel: Force-Aware Data-Driven Estimation and Control for Fluid Physical Interaction”</em></p>
      </div>

      <div class="person-card">  
        <a href="https://www.linkedin.com/in/ekaterina-skorniakova/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/ekaterina_skorniakova.JPG" alt="Ekaterina Skorniakova"></a>
        <a href="https://www.linkedin.com/in/ekaterina-skorniakova/" target="_blank" rel="noopener"><h3>Ekaterina Skorniakova</h3></a>
        <p>M.S. Robotics, 2026<br>2023–present<br><em>Thesis: “Coupled Passive Dynamical System Interaction Control on SE(3)”</em></p>
      </div>

      <div class="person-card">
        <a href="https://www.linkedin.com/in/nateykim/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/natey_kim.JPG" alt="Natey Kim"></a>
        <a href="https://www.linkedin.com/in/nateykim/" target="_blank" rel="noopener"><h3>Natey Kim</h3></a>
        <p>M.S. Robotics, 2026<br>2023–present<br><em>Thesis: “Real-time Human Limb Dynamics Tracking via HD-sEMG driven Musculoskeletal Digital Twin Modeling”</em></p>
      </div>

      <div class="person-card">  
        <a href="http://www.yihanli.io/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/yihan_li.JPG" alt="Yihan Li"></a>
        <a href="http://www.yihanli.io/" target="_blank" rel="noopener"><h3>Yihan Li</h3></a>
        <p>M.S. Robotics, 2026<br>2025–present<br><em>Thesis: “RoboHockey: A Robotic Benchmark for Dynamic Whole-body Contact-rich Tasks”</em></p>
      </div>

      <div class="person-card">
        <a href="{{ site.baseurl }}/people/"><img src="{{ site.baseurl }}/assets/images/people/bio-photo.jpg" alt="Felix Zheng"></a>
        <a href="{{ site.baseurl }}/people/"><h3>Felix [Yuchen] Zheng</h3></a>
        <p>M.S. Robotics, 2026<br>2025–present<br><em>Thesis: “Object-centric 3D Operator World Models for Planning Common Cooking Tasks”</em></p>
      </div>
    </div>
  </div>

  <!-- === Master's Research Interns === -->
  <div class="people-section">
    <h2>Master's Research Interns</h2>
    <div class="people-grid">
      <div class="person-card">   
        <a href="https://zizhe.io/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/zizhe_zhang.JPG" alt="Zizhe Zhang"></a>
        <a href="https://zizhe.io/" target="_blank" rel="noopener"><h3>Zizhe Zhang</h3></a>
        <p>M.S. ESE/Robotics, 2026<br>2025–present<br><em>Research Intern Spring-Fall 2025</em></p>
      </div>

      <div class="person-card">   
        <a href="https://www.linkedin.com/in/jason-chen-2580621b7/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/jason_chen.JPG" alt="Jason Chen"></a>
        <a href="https://www.linkedin.com/in/jason-chen-2580621b7/" target="_blank" rel="noopener"><h3>Jason Chen</h3></a>
        <p>M.S. MEAM, 2026<br>2025–present<br><em>Research Intern Fall 2025</em></p>
      </div>

      <div class="person-card">   
        <a href="http://www.linkedin.com/in/dhyey-shah-3039371b5" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/dhyey_shah.JPG" alt="Dhyey Shah"></a>
        <a href="http://www.linkedin.com/in/dhyey-shah-3039371b5" target="_blank" rel="noopener"><h3>Dhyey Shah</h3></a>
        <p>M.S. Robotics, 2026<br>2025–present<br><em>Research Intern Fall 2025</em></p>
      </div>
      
      <div class="person-card">   
        <a href="https://www.linkedin.com/in/yicong-wang-0a8b60324/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/yicong_wang.JPG" alt="Yicong Wang"></a>
        <a href="https://www.linkedin.com/in/yicong-wang-0a8b60324/" target="_blank" rel="noopener"><h3>Yicong Wang</h3></a>
        <p>M.S. Robotics, 2026<br>2025–present<br><em>Research Intern Fall 2025</em></p>
      </div>

      <div class="person-card">
        <a href="https://www.linkedin.com/in/guanhua-ji-a96053374/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/guanhua_ji.JPG" alt="Guanhua Ji"></a>
        <a href="https://www.linkedin.com/in/guanhua-ji-a96053374/" target="_blank" rel="noopener"><h3>Guanhua Ji</h3></a>
        <p>M.S. Robotics, 2027<br>2025–present<br><em>Research Intern Fall 2025</em></p>
      </div>

      <div class="person-card">
        <a href="https://www.linkedin.com/in/dayoonsuh/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/dayoon_suh.JPG" alt="Dayoon Suh"></a>
        <a href="https://www.linkedin.com/in/dayoonsuh/" target="_blank" rel="noopener"><h3>Dayoon Suh</h3></a>
        <p>M.S. Robotics, 2027<br>2025–present<br><em>Research Intern Fall 2025</em></p>
      </div>
    </div>
  </div>

  <!-- === Research Engineers === -->
  <div class="people-section">
    <h2>Research Engineers</h2>
    <div class="people-grid">
      <div class="person-card">
        <a href="https://www.linkedin.com/in/daudizein/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/daudi_zein.JPG" alt="Daudi Zein"></a>
        <a href="https://www.linkedin.com/in/daudizein/" target="_blank" rel="noopener"><h3>Daudi Zein</h3></a>
        <p>M.S. Robotics, 2025<br>2025-present<br><em>Research Engineer</em></p>
      </div>
    </div>
  </div>

  <!-- === Undergraduate Researchers === -->
  <div class="people-section">
    <h2>Undergraduate Researchers</h2>
    <div class="people-grid">
      <div class="person-card">
        <a href="{{ site.baseurl }}/people/"><img src="{{ site.baseurl }}/assets/images/people/bio-photo.jpg" alt="Michael North"></a>
        <a href="{{ site.baseurl }}/people/" target="_blank" rel="noopener"><h3>Michael North</h3></a>
        <p>B.S. BE, 2026<br>2024-present<br><em>Undergraduate Researcher</em></p>
      </div>
    </div>
  </div>

  <!-- === Alumni (completed/⋆) === -->
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
        <tr>
          <td>Paul [Sanghyub] Lee</td>
          <td>M.S. Robotics, 2025</td>
          <td>2023–2025</td>
          <td>“Towards Real-Time Muscle Health Monitoring and Muscle-in-the-Loop Robotic Assistants via AI-Driven Wearable Ultrasound Processing”; now Ph.D. candidate in MEAM (Penn)</td>
        </tr>
        <tr>
          <td>George [Jiayuan] Gao</td>
          <td>M.S. Robotics, 2025</td>
          <td>2024–2025</td>
          <td>“Visuomotor Object-Centric Out-Of-Distribution Recovery Policy”; <em>Outstanding Master’s Researcher Award in Robotics</em></td>
        </tr>
        <tr>
          <td>Ho Jin Choi</td>
          <td>M.S. MEAM, 2024</td>
          <td>2022–2024</td>
          <td>“Gaussian Process-Based Active Exploration Strategies in Vision and Touch”; <em>Outstanding Master’s Researcher Award in MEAM</em>; Summer 2024 intern at MERL; now Ph.D. candidate in MEAM (Penn)</td>
        </tr>
        <tr>
          <td>Zhiquan Zhang</td>
          <td>M.S. ESE, 2024</td>
          <td>2022–2024</td>
          <td>“Real-Time Safety-Critical Passive Torque Control with Analytic and Learning-based Constraints”; <em>Best Master’s Thesis in ESE</em>; now Ph.D. candidate at UIUC</td>
        </tr>
        <tr>
          <td>Haihui Gao</td>
          <td>M.S. ESE & MEAM, 2024</td>
          <td>2022–2024</td>
          <td>“Advancing Dynamical Systems in Learning from Demonstration: A Novel Approach for Modeling Self-Crossing Trajectories”; now Ph.D. candidate at University of Montreal</td>
        </tr>
        <tr>
          <td>Satyajeet Das</td>
          <td>M.S. ESE, 2024</td>
          <td>2023–2024</td>
          <td>“Towards Vision-based Safety: A Real-Time Approach for Generating Barrier Functions using Depth Sensors”; now Ph.D. candidate at USC (started Fall 2024)</td>
        </tr>
        <tr>
          <td>Haoming Li</td>
          <td>M.S. ESE, 2024</td>
          <td>2023–2024</td>
          <td>“Towards Robust SLAM with Neural Implicit Representations”; Research Engineer at the University of Pennsylvania</td>
        </tr>
      </tbody>
    </table>
  </div>

</div><!-- /.people-wrap -->
