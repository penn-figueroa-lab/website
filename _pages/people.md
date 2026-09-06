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

/* ===== Centered wrapper (matches research/publications pattern) ===== */
.people-wrap{
  width: min(96vw, 1100px);
  margin: 0 auto;
  padding: 0 16px;
}


/* ===== Sections ===== */
.people-section{ padding: 1rem 0 .5rem; text-align: center; }
.people-section + .people-section{ margin-top: .75rem; }
.people-section h2{ font-size: 1.2rem; margin: .35rem 0 .7rem; font-weight: 700; }

/* ===== Grid (auto-fit, but max 4 per row) ===== */
.people-grid{
  /* auto-fit makes it responsive, wrapping as space allows */
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 1rem 1.1rem;
  justify-items: center;
  align-items: start;

  /* cap total grid width so no more than 4 cards fit */
  /* 4 * 200px cards + 3 * 1.1rem column gaps */
  max-width: calc(4 * 200px + 3 * 1.1rem);
  margin-left: auto;
  margin-right: auto;
}


/* ===== Cards ===== */
.person-card{
  width: 200px;
  display: flex; flex-direction: column; align-items: center;
  text-align: center;
  font-size: .8rem;
}
.person-card img{
  width: 200px; height: 200px;
  border-radius: 10px; object-fit: cover;
  background: #f3f4f6; margin-bottom: .4rem;
}
.person-card h3{
  font-size: .8rem; font-weight: 600;
  margin: .18rem 0; line-height: 1.18;
  word-wrap: break-word;
}
.person-card p{
  margin: .15rem 0 0;
  font-size: .7rem;
  color: #555;
}


/* ===== Alumni (list format) ===== */
.alumni-group{
  text-align: center;
  margin: 1.4rem 0 .5rem;
  font-size: 0.85rem;
  font-weight: 700;
  color: #333;
}
.alumni-group:first-of-type{ margin-top: 0.6rem; }

.alumni-list{
  max-width: 700px;
  margin: 0 auto 0.6rem;
  text-align: left;
}
.alumni-entry{
  padding: 0.6rem 0;
  border-bottom: 1px solid #e5e7eb;
}
.alumni-entry:last-child{ border-bottom: none; }
.alumni-name{
  font-weight: 700;
  font-size: 0.85rem;
  color: #1a1a1a;
}
.alumni-detail{
  margin-top: 0.15rem;
  font-size: 0.75rem;
  color: #555;
  line-height: 1.45;
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
        <p>Shalini and Rajeev Misra Presidential Assistant Professor, MEAM/ESE/CIS</p>
      </div>
    </div>
  </div>

  <!-- === PhD Students === -->
  <div class="people-section">
    <h2>Ph.D. Students</h2>
    <div class="people-grid">
      <div class="person-card"><a href="http://imtianyuli.com/"  target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/tianyu_li.JPG" alt="Tianyu Li"></a><a href="http://imtianyuli.com/" target="_blank" rel="noopener"><h3>Tianyu Li</h3></a><p>MEAM</p></div>
      <div class="person-card"><a href="https://www.linkedin.com/in/yifan-xue-523168178/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/yifan_xue_reduced.jpg" alt="Yifan Xue"></a><a href="https://www.linkedin.com/in/yifan-xue-523168178/" target="_blank" rel="noopener"><h3>Yifan Xue</h3></a><p>MEAM</p></div>
      <div class="person-card"><a href="https://www.linkedin.com/in/shafagh-keyvanian-609b607a/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/shafagh_keyvanian.jpg" alt="Shafagh Keyvanian"></a><a href="https://www.linkedin.com/in/shafagh-keyvanian-609b607a/" target="_blank" rel="noopener"><h3>Shafagh Keyvanian</h3></a><p>MEAM, Co-advised with Michelle Johnson</p></div>
      <div class="person-card"><a href="https://shaoyifei96.github.io/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/simon-800.jpg" alt="Yifei Simon Shao"></a><a href="https://shaoyifei96.github.io/" target="_blank" rel="noopener"><h3>Yifei Simon Shao</h3></a><p>CIS, Close collaborator co-advised by V. Kumar & P. Chaudhari</p></div>
      <div class="person-card"><a href="https://www.linkedin.com/in/ho-jin-choi-425856208/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/ho_jin_choi_reduced.jpg" alt="Ho Jin Choi"></a><a href="https://www.linkedin.com/in/ho-jin-choi-425856208/" target="_blank" rel="noopener"><h3>Ho Jin Choi</h3></a><p>MEAM</p></div>
      <div class="person-card">
        <a href="https://sunan-sun.github.io/" target="_blank" rel="noopener">
          <img src="{{ site.baseurl }}/assets/images/people/sunan_sun_reduced.jpg" alt="Sunan Sun"></a>
        <a href="https://sunan-sun.github.io/" target="_blank" rel="noopener"><h3>Sunan Sun</h3></a>
        <p>MEAM</p>
      </div>
      <div class="person-card">
        <a href="https://sites.google.com/seas.upenn.edu/sanghyub-lee" target="_blank" rel="noopener">
          <img src="{{ site.baseurl }}/assets/images/people/sanghyub_lee.JPG" alt="Paul (Sanghyub) Lee">
        </a><a href="https://sites.google.com/seas.upenn.edu/sanghyub-lee" target="_blank" rel="noopener"><h3>Paul(Sanghyub) Lee</h3></a>
        <p>MEAM</p>
      </div>
      <div class="person-card">
        <a href="https://mateuszjaszczuk.com/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/mateusz_jaszczuk_reduced.jpg" alt="Mateusz Jaszczuk"></a>
        <a href="https://mateuszjaszczuk.com/" target="_blank" rel="noopener"><h3>Mateusz Jaszczuk</h3></a>
        <p>MEAM</p>
      </div>      
    </div>
  </div>

  <!-- === Visiting Research Scholars === -->
  <div class="people-section">
    <h2>Visiting Research Scholars</h2>
    <div class="people-grid">
        <div class="person-card">
        <a href="https://www.linkedin.com/in/daniel-justino/"><img src="{{ site.baseurl }}/assets/images/people/daniel_justino.jpeg" alt="Daniel Da Silva Justino"></a>
        <a href="https://www.linkedin.com/in/daniel-justino/" target="_blank" rel="noopener"><h3>Daniel Da Silva Justino</h3></a>
        <p>Ph.D. Student at DLR (Germany)</p>
       </div>      
     </div>
    </div>

    <!-- === Research Engineers === -->
  <div class="people-section">
    <h2>Research Engineers</h2>
    <div class="people-grid">
        <div class="person-card">
        <a href="https://www.linkedin.com/in/nateykim/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/natey_kim_reduced.jpg" alt="Natey Kim"></a>
        <a href="https://www.linkedin.com/in/nateykim/" target="_blank" rel="noopener"><h3>Natey Kim</h3></a>
        <p>M.S. Robotics, 2026</p>
      </div>  
        <div class="person-card">
        <a href="https://navjotschahal.github.io/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/navjot.jpg" alt="Navjot Singh Chahal"></a>
        <a href="https://navjotschahal.github.io/" target="_blank" rel="noopener"><h3>Navjot Singh Chahal</h3></a>
        <p>M.S. EE, 2026</p>
      </div>
      <div class="person-card">
        <a href="https://www.linkedin.com/in/michaelgnorth/"><img src="{{ site.baseurl }}/assets/images/people/robot-member.png" alt="Michael North"></a>
        <a href="https://www.linkedin.com/in/michaelgnorth/" target="_blank" rel="noopener"><h3>Michael North</h3></a>
        <p>B.S. BE, 2026</p>
      </div>                  
    </div>
  </div>


  <!-- === M.Sc. Students === -->
  <div class="people-section">
    <h2>Master's Students</h2>
    <div class="people-grid">
      <div class="person-card">
        <a href="hhttps://www.linkedin.com/in/wantingyao/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/wanting_linkedin.png" alt="Wanting Yao<"></a>
        <a href="https://www.linkedin.com/in/wantingyao/" target="_blank" rel="noopener"><h3>Wanting Yao</h3></a>
        <p>ROBO, Thesis</p>
      </div>
      <div class="person-card">
        <a href="https://www.linkedin.com/in/aditya-vats42/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/AdityaVats.jpeg" alt="Aditya Vats"></a>
        <a href="https://www.linkedin.com/in/aditya-vats42/" target="_blank" rel="noopener"><h3>Aditya Vats</h3></a>
        <p>ROBO, Thesis</p>
      </div>
      <div class="person-card">
        <a href="https://www.linkedin.com/in/guanhua-ji-a96053374/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/guanhua_ji_reduced.jpg" alt="Guanhua Ji"></a>
        <a href="https://www.linkedin.com/in/guanhua-ji-a96053374/" target="_blank" rel="noopener"><h3>Guanhua Ji</h3></a>
        <p>ROBO, Thesis</p>
      </div>
      <div class="person-card">
        <a href="https://www.linkedin.com/in/tianyixia0618/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/tianyi_xia.jpg" alt="Tianyi Xia"></a>
        <a href="https://www.linkedin.com/in/tianyixia0618/" target="_blank" rel="noopener"><h3>Tianyi Xia</h3></a>
        <p>ROBO, Thesis</p>
      </div> 
      <div class="person-card">
        <a href="https://www.linkedin.com/in/dmitri-dobrynin-9b7b59385/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/robot-member.png" alt="Dmitri Dobrynin"></a>
        <a hhref="https://www.linkedin.com/in/dmitri-dobrynin-9b7b59385/" target="_blank" rel="noopener"><h3>Dmitri Dobrynin </h3></a>
        <p>ROBO, Thesis</p>
      </div>
       <div class="person-card">
        <a href="https://ilyrr.github.io/index.html" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/Ily.jpeg" alt="Ily Rafaeli"></a>
        <a hhref="https://ilyrr.github.io/index.html" target="_blank" rel="noopener"><h3>Ily Rafaeli </h3></a>
        <p>ROBO, Independent Study</p>
      </div>         
       <div class="person-card">
        <a href="https://www.linkedin.com/in/zhengmiao-huang/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/zhengmiao.jpeg" alt="Zhengmiao Huang"></a>
        <a hhref="https://www.linkedin.com/in/zhengmiao-huang/" target="_blank" rel="noopener"><h3>Zhengmiao Huang </h3></a>
        <p>ROBO, Independent Study</p>
      </div>      
      <div class="person-card">
        <a href="https://www.linkedin.com/in/dayoonsuh/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/dayoon_suh_reduced.jpg" alt="Dayoon Suh"></a>
        <a href="https://www.linkedin.com/in/dayoonsuh/" target="_blank" rel="noopener"><h3>Dayoon Suh</h3></a>
        <p>ROBO, Intern</p>
      </div>
      <div class="person-card">
        <a href=""  target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/robot-member.png" alt="Yifan Wu"></a>
        <a href=""  target="_blank" rel="noopener"><h3>Yifan Wu</h3></a>
        <p>ROBO, Intern</p>
      </div>
      <div class="person-card">
        <a href=""  target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/Ethan_NEW.jpeg" alt="Ethan Yang"></a>
        <a href=""  target="_blank" rel="noopener"><h3>Ethan Yang</h3></a>
        <p>ROBO, Intern</p>
      </div>
      <div class="person-card">
        <a href="https://liyifei1218.github.io/"  target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/yifei_bruce_li.jpg" alt="Yifei (Bruce) Li"></a>
        <a href="https://liyifei1218.github.io/"  target="_blank" rel="noopener"><h3>Yifei (Bruce) Li</h3></a>
        <p>ROBO, Intern</p>
      </div>
        <div class="person-card">
        <a href="https://www.linkedin.com/in/boyanz0417/"  target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/boyan_zhang.jpeg" alt="Boyan Zhang"></a>
        <a href="https://www.linkedin.com/in/boyanz0417/"  target="_blank" rel="noopener"><h3>Boyan Zhang</h3></a>
        <p>ROBO, Intern</p>
      </div>                             
    </div>
  </div>

  <!-- === Undergraduate Researchers === -->
  <div class="people-section">
    <h2>Undergraduate Research Interns</h2>
    <div class="people-grid">
      <div class="person-card">
        <a href="https://www.linkedin.com/in/haoqin-lily-zhang/"><img src="{{ site.baseurl }}/assets/images/people/lily_zhang.jpeg" alt="Lily Zhang"></a>
        <a href="https://www.linkedin.com/in/haoqin-lily-zhang/" target="_blank" rel="noopener"><h3>Lily Zhang</h3></a>
        <p>MEAM</p>
      </div>
      <div class="person-card">
        <a href="https://www.linkedin.com/in/adityapasumarthi/"><img src="{{ site.baseurl }}/assets/images/people/aditya_pasumarthi.jpeg" alt="Aditya Pasumarthi"></a>
        <a href="https://www.linkedin.com/in/adityapasumarthi/" target="_blank" rel="noopener"><h3>Aditya Pasumarthi</h3></a>
        <p>BE</p>
      </div>
      <div class="person-card">
        <a href="https://www.linkedin.com/in/jessica-luo-eng28/"><img src="{{ site.baseurl }}/assets/images/people/jessica_luo.jpeg" alt="Jessica Luo"></a>
        <a href="https://www.linkedin.com/in/jessica-luo-eng28/" target="_blank" rel="noopener"><h3>Jessica Luo</h3></a>
        <p>BE</p>
      </div>             
    </div>
  </div>


  <!-- === Alumni (list format) === -->
  <div class="people-section">
    <h2>Alumni</h2>
    <div class="alumni-group">Ph.D. Students</div>
    <div class="alumni-list">
      <div class="alumni-entry">
        <!-- <div class="alumni-name"><a href="https://sites.google.com/view/farhad-nawaz" style="text-decoration:none" target="_blank" rel="noopener">Farhad Nawaz</a> </div> -->
         <div class="alumni-name">Farhad Nawaz </div>       
        <div class="alumni-detail">ESE, 2026, Co-advised with Nikolai Matni</div>
        <div class="alumni-detail"><b>After Graduating:</b> Scientist at <a href="https://www.lila.ai/" style="text-decoration:none" target="_blank" rel="noopener">Lila Sciences</a>
          </div>
      </div>
    </div>
    <div class="alumni-group">Visiting Research Scholars</div>
    <div class="alumni-list">
      <div class="alumni-entry">
        <div class="alumni-name">Ze Zhang</div>
        <div class="alumni-detail">Ph.D. in Automation, Chalmers University of Technology, Sweden </div>
        <div class="alumni-detail">Advised by Knut Åkesson &mdash; Visited Fall 2024 </div>
        <div class="alumni-detail"><b>After Graduating:</b> Senior AI (Robotics) Engineer at  <a href="https://www.agile-robots.com/en/" style="text-decoration:none" target="_blank" rel="noopener">Agile Robots SE</a> </div>
      </div>
      <div class="alumni-entry">
        <div class="alumni-name">Enrico Martini</div>
        <div class="alumni-detail">Ph.D. in Computer Science, University of Verona, Italy </div>
        <div class="alumni-detail">Advised by Nicola Bombieri &mdash; Visited Spring 2024 </div>
        <div class="alumni-detail"><b>After Graduating:</b> Postdoctoral Researcher/Lecturer at  <a href="https://www.univr.it/en/university" style="text-decoration:none" target="_blank" rel="noopener">University of Verona</a></div>
      </div>
    </div>
    <div class="alumni-group">Research Engineers</div>
    <div class="alumni-list">
      <div class="alumni-entry">
        <div class="alumni-name">Zizhe Zhang</div>
        <div class="alumni-detail">M.S. Robotics, 2026</div>
        <div class="alumni-detail"><b>Next position:</b> Ph.D student at Johns Hopkins University advised by <a href="https://alliance-ai.cs.jhu.edu/" style="text-decoration:none" target="_blank" rel="noopener">Haimin Hu</a></div>
      </div>      
      <div class="alumni-entry">
        <div class="alumni-name">Jalaj Shukla</div>
        <div class="alumni-detail">M.S. MEAM, 2025</div>
        <div class="alumni-detail"><b>Next position:</b> Co-founder of <a href="https://www.intelligence-factory.com/" style="text-decoration:none" target="_blank" rel="noopener">f(i) Intelligence Factory</a></div>
      </div>
      <div class="alumni-entry">
        <div class="alumni-name">Davin Tjandra</div>
        <div class="alumni-detail">M.S. MEAM, 2025</div>
        <div class="alumni-detail"><b>Next position:</b> Robotics Software Engineer at <a href="https://www.intrinsic.ai/" style="text-decoration:none" target="_blank" rel="noopener">Google Intrinsic</a></div>
      </div>
      <div class="alumni-entry">
        <div class="alumni-name">Daudi Zein</div>
        <div class="alumni-detail">M.S. MEAM, 2025</div>
      </div>      
      <div class="alumni-entry">
        <div class="alumni-name">Yi-Hsuan Cheng</div>
        <div class="alumni-detail">M.S. Robotics, 2025</div>
        <div class="alumni-detail"><b>Next position:</b> Member of Technical Staff at <a href="https://www.roboforce.ai/" style="text-decoration:none" target="_blank" rel="noopener">RoboForce</a></div>
      </div>  
      <div class="alumni-entry">
        <div class="alumni-name">Harshil Parekh</div>
        <div class="alumni-detail">M.S. Robotics, 2023</div>
        <div class="alumni-detail"><b>Next position:</b> Robotics Solutions Engineer at <a href="https://www.path-robotics.com/" style="text-decoration:none" target="_blank" rel="noopener">Path Robotics</a></div>
      </div>
    </div>
    <div class="alumni-group">Master&rsquo;s Theses</div>
    <div class="alumni-list">
        <div class="alumni-entry">
          <div class="alumni-name">Mateusz Jaszczuk</div>
          <div class="alumni-detail">M.S. MEAM, 2026</div>
          <div class="alumni-detail"><em>&ldquo;Learning to Feel: Force-Aware Data-Driven Estimation and Control for Adaptive Physical Interactions&rdquo;</em></div>
          <div class="alumni-detail">:trophy: Outstanding Master's Researcher Award in MEAM</div> 
          <div class="alumni-detail"><b>After Graduating:</b> Ph.D. Student at Figueroa Robotics Lab</div>
       </div>
        <div class="alumni-entry">
          <div class="alumni-name">Ekaterina Skorniakova</div>
          <div class="alumni-detail">M.S. Robotics, 2026</div>
          <div class="alumni-detail"><em>&ldquo;Experimental Characterization of Oscillations in Passive Dynamical System Controllers and Design Guidance&rdquo;</em></div> 
          <div class="alumni-detail"><b>After Graduating:</b> Ph.D. Student at Cornell advised by <a href="https://geodesic.mae.cornell.edu/" style="text-decoration:none" target="_blank" rel="noopener">Jake Welde</a></div>
       </div>
        <div class="alumni-entry">
          <div class="alumni-name">Natey Kim</div>
          <div class="alumni-detail">M.S. Robotics, 2026</div>
          <div class="alumni-detail"><em>&ldquo;Real-time Human Limb Dynamics Tracking via HD-sEMG driven Musculoskeletal Digital Twin Modelings&rdquo;</em></div> 
          <div class="alumni-detail"><b>After Graduating:</b> Research Engineer at Figueroa Robotics Lab</div>
       </div>
        <div class="alumni-entry">
          <div class="alumni-name">Yihan Li</div>
          <div class="alumni-detail">M.S. Robotics, 2026</div>
          <div class="alumni-detail"><em>&ldquo;RoboHockey: A Robotic Benchmark for Dynamic Whole-body Contact-rich Tasks&rdquo;</em></div>
          <div class="alumni-detail"><b>After Graduating:</b> Ph.D. student at UT Austin advised by <a href="https://robin-lab.cs.utexas.edu/" style="text-decoration:none" target="_blank" rel="noopener">Roberto Martin-Martin</a></div>
       </div>     
       <div class="alumni-entry">
        <div class="alumni-name">Felix [Yuchen] Zheng</div>
        <div class="alumni-detail">M.S. Robotics, 2026</div>
        <div class="alumni-detail"><em>&ldquo;Predicate-Free Language-to-Plan Validation with Learnded 3D Operator World Models&rdquo;</em></div> 
        <div class="alumni-detail"><b>After Graduating:</b> Ph.D. student at Georgia Tech advised by <a href="https://www.gt-rail.com/" style="text-decoration:none" target="_blank" rel="noopener">Sonia Chernova</a></div>
      </div>     
      <div class="alumni-entry">
        <div class="alumni-name">George [Jiayuan] Gao</div>
        <div class="alumni-detail">M.S. Robotics, 2025</div>
        <div class="alumni-detail"><em>&ldquo;Visuomotor Object-Centric Out-Of-Distribution Recovery Policy&rdquo;</em></div>
        <div class="alumni-detail">:trophy: Outstanding Master's Researcher Award in Robotics</div> 
        <div class="alumni-detail"><b>After Graduating:</b> Research Staff Member at <a href="https://www.dyna.co/" style="text-decoration:none" target="_blank" rel="noopener">Dyna Robotics</a></div>
      </div>
      <div class="alumni-entry">
        <div class="alumni-name">Paul [Sanghyub] Lee</div>
        <div class="alumni-detail">M.S. Robotics, 2025</div>
        <div class="alumni-detail"><em>&ldquo;Towards Real-Time Muscle Health Monitoring and Muscle-in-the-Loop Robotic Assistants via AI-Driven Wearable Ultrasound Processing&rdquo;</em></div> <div class="alumni-detail"><b>After Graduating:</b> Ph.D. Student at Figueroa Robotics Lab</div>
      </div>      
      <div class="alumni-entry">
        <div class="alumni-name">Ho Jin Choi</div>
        <div class="alumni-detail">M.S. MEAM, 2024</div>
        <div class="alumni-detail"><em>&ldquo;Gaussian Process-Based Active Exploration Strategies in Vision and Touch&rdquo;</em></div> 
        <div class="alumni-detail">:trophy: Outstanding Master&rsquo;s Researcher Award in MEAM</div>
        <div class="alumni-detail"><b>After Graduating:</b> Ph.D. Student at Figueroa Robotics Lab</div>
      </div>
      <div class="alumni-entry">
        <div class="alumni-name">Zhiquan Zhang</div>
        <div class="alumni-detail">M.S. ESE, 2024</div>
        <div class="alumni-detail"><em>&ldquo;Real-Time Safety-Critical Passive Torque Control with Analytic and Learning-based Constraints&rdquo;</em></div> 
        <div class="alumni-detail">:trophy: Best Master&rsquo;s Thesis in ESE</div>
        <div class="alumni-detail"><b>After Graduating:</b> Ph.D. candidate at UIUC advised by <a href="https://mornik.web.illinois.edu/research/group/" style="text-decoration:none" target="_blank" rel="noopener">Melkior Ornik</a></div>
      </div>
      <div class="alumni-entry">
        <div class="alumni-name">Haihui Gao</div>
        <div class="alumni-detail">M.S. ESE &amp; MEAM, 2024</div>
        <div class="alumni-detail"><em>&ldquo;Advancing Dynamical Systems in Learning from Demonstration: A Novel Approach for Modeling Self-Crossing Trajectories&rdquo;</em> </div>
        <div class="alumni-detail"><b>After Graduating:</b> Ph.D. student at Polytechnique Montréal advised by <a href="https://bwyi.github.io/index.html" style="text-decoration:none" target="_blank" rel="noopener">Bowen Yi</a></div>
      </div>
      <div class="alumni-entry">
        <div class="alumni-name">Satyajeet Das</div>
        <div class="alumni-detail">M.S. ESE, 2024</div>
        <div class="alumni-detail"><em>&ldquo;Towards Vision-based Safety: A Real-Time Approach for Generating Barrier Functions using Depth Sensors&rdquo;</em></div>
        <div class="alumni-detail"><b>After Graduating:</b> Ph.D. student at University of Southern California advised by <a href="https://uscresl.org/" style="text-decoration:none" target="_blank" rel="noopener">Gaurav Sukhatme</a></div>
      </div>
      <div class="alumni-entry">
        <div class="alumni-name">Haoming Li</div>
        <div class="alumni-detail">M.S. ESE, 2024</div>
        <div class="alumni-detail"><em>&ldquo;Towards Robust SLAM with Neural Implicit Representations&rdquo;</em></div>
        <div class="alumni-detail"><b>After Graduating:</b> Ph.D. student at Arizona State University advised by <a href="https://faculty.engineering.asu.edu/yezhouyang/" style="text-decoration:none" target="_blank" rel="noopener">‘YZ’ Yezhou Yang</a></div>
      </div>
    </div>

      <!-- === Master's Research Interns === -->
<!--   <div class="people-section">
    <h2>Master's Research Interns</h2>
    <div class="people-grid">
      <div class="person-card">   
        <a href="https://zizhe.io/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/zizhe_zhang.JPG" alt="Zizhe Zhang"></a>
        <a href="https://zizhe.io/" target="_blank" rel="noopener"><h3>Zizhe Zhang</h3></a>
        <p>M.S. Robotics, 2026<br>2024–present<br><em>Research Intern Spring-Fall 2025</em></p>
      </div>
      <div class="person-card">   
        <a href="https://www.linkedin.com/in/jason-chen-2580621b7/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/jason_chen.JPG" alt="Jason Chen"></a>
        <a href="https://www.linkedin.com/in/jason-chen-2580621b7/" target="_blank" rel="noopener"><h3>Jason Chen</h3></a>
        <p>M.S. MEAM, 2026<br>2025–present<br><em>Research Intern Fall 2025</em></p>
      </div>
      <div class="person-card">   
        <a href="https://lintao-zheng.github.io/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/Lintao Zheng.JPG" alt="Lintao Zheng"></a>
        <a href="https://lintao-zheng.github.io/" target="_blank" rel="noopener"><h3>Lintao Zheng</h3></a>
        <p>M.S. Robotics, 2026<br>2025–present<br><em>Research Intern Fall 2025</em></p>
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
      </div> -->
  <!-- </div> -->
  <!--     <div class="people-grid">
      <div class="person-card">
        <a href="https://www.linkedin.com/in/daudizein/" target="_blank" rel="noopener"><img src="{{ site.baseurl }}/assets/images/people/daudi_zein.JPG" alt="Daudi Zein"></a>
        <a href="https://www.linkedin.com/in/daudizein/" target="_blank" rel="noopener"><h3>Daudi Zein</h3></a>
        <p>M.S. Robotics, 2025<br>2025-present<br><em>Research Engineer</em></p>
      </div> -->


  </div>

</div>
