---
layout: single
title: ""
permalink: /publication/
---

<!-- ===== Wide, centered content band ===== -->
<section class="pub-wrap">

  <h2 class="pub-heading">Peer-Reviewed Journals and Transactions</h2>

  <div class="pub-table-wrapper">
    <table class="pub-table">
      <colgroup>
        <col style="width:7%">
        <col style="width:23%">
        <col style="width:40%">
        <col style="width:22%">
        <col style="width:6%">
        <col style="width:7%">
      </colgroup>
      <thead>
        <tr>
          <th>#</th><th>Authors</th><th>Title</th><th>Journal</th><th>Year</th><th>Notes</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>J1</td>
          <td>Sun, S., Gao, H., Li, T. and Figueroa, N.</td>
          <td><a href="https://ieeexplore.ieee.org/document/10530930" target="_blank" rel="noopener">Directionality-Aware Mixture Model Parallel Sampling for Efficient Linear Parameter Varying Dynamical System Learning</a></td>
          <td><em>IEEE Robotics and Automation Letters (RA-L)</em>, 9(7):6248–6255</td>
          <td>2024</td>
          <td></td>
        </tr>
        <!-- … your remaining journal rows … -->
      </tbody>
    </table>
  </div>

  <h2 class="pub-heading">Peer-Reviewed Conference Proceedings</h2>

  <div class="pub-table-wrapper">
    <table class="pub-table">
      <colgroup>
        <col style="width:7%">
        <col style="width:23%">
        <col style="width:40%">
        <col style="width:22%">
        <col style="width:6%">
        <col style="width:7%">
      </colgroup>
      <thead>
        <tr>
          <th>#</th><th>Authors</th><th>Title</th><th>Conference</th><th>Year</th><th>Notes</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>C1</td>
          <td>Jaszczuk, M. and Figueroa, N.</td>
          <td><a href="https://openreview.net/forum?id=2CIKnIwSta#discussion" target="_blank" rel="noopener">Rapid Mismatch Estimation via Neural Network Informed Variational Inference</a></td>
          <td>9th Conference on Robot Learning (CoRL)</td>
          <td>2025</td>
          <td>To appear</td>
        </tr>
        <!-- … your remaining conference rows … -->
      </tbody>
    </table>
  </div>

</section>

<style>
/* ===== Layout ===== */
.pub-wrap{
  width: min(96vw, 1400px);
  margin: 0 auto 1.6rem;
  padding: 0 0.8rem;
}
@media (min-width:1500px){
  .pub-wrap{ margin-left: -400px; margin-right: auto; }
}
@media (max-width:1499.98px){
  .pub-wrap{ margin-left: auto; margin-right: auto; }
}

/* ===== Headings ===== */
.pub-heading{
  margin: 1.4rem 0 0.55rem;
  text-align: center;
  font-size: clamp(1.1rem, 1.5vw + .6rem, 1.6rem); /* smaller */
  font-weight: 800;
}

/* ===== Table ===== */
.pub-table-wrapper{
  overflow-x: auto;
  -webkit-overflow-scrolling: touch;
}
.pub-table{
  width: 100%;
  border-collapse: collapse;
  margin: 0.4rem 0 1.4rem;
  font-size: 0.9rem;            /* smaller font */
  line-height: 1.4;
  table-layout: fixed;
}
.pub-table thead th{ font-weight: 700; }
.pub-table td, .pub-table th{
  border-bottom: 1px solid #e5e7eb;
  padding: 0.55rem 0.7rem;      /* tighter cells */
  text-align: left;
  vertical-align: top;
}
.pub-table td:nth-child(3),
.pub-table td:nth-child(4){
  word-break: normal;
  overflow-wrap: anywhere;
}

/* Mobile tweaks */
@media (max-width:980px){
  .pub-table{ table-layout: auto; }
  .pub-table col{ width: auto !important; }
  .pub-table td, .pub-table th{
    padding: 0.45rem 0.6rem;
    font-size: 0.88rem;         /* slightly smaller on phones */
  }
}

/* Hide pagination (next/prev) */
.pagination{ display:none !important; }

/* Hide RSS/Feed icon only on this page */
.page__footer-follow .social-icons li:has(a[href$="feed.xml"]),
.page__footer-follow .social-icons li:has(.fa-rss),
.page__footer-follow .social-icons a[href$="feed.xml"],
.page__footer-follow .social-icons .fa-rss {
  display: none !important;
}
</style>
