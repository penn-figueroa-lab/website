<style>
/* Center the page content — no manual nudge */
.research-wrap{
  width: min(96vw, 1200px);   /* cap width, keep responsive */
  margin: 0 auto;             /* center */
  padding: 0 20px;            /* side gutter so text never hugs edges */
  box-sizing: border-box;
}

/* Intro */
.rb-intro{
  width: 100%;
  text-align: justify;
  text-justify: inter-word;
}
.rb-intro h1{
  text-align:center;
  margin-bottom:0.7rem;
  font-weight:800;
  font-size:clamp(1.2rem, 1.1vw + 0.95rem, 1.6rem);
}
.rb-intro p{
  margin:0.6rem 0;
  line-height:1.65;
  font-size:clamp(0.92rem, 0.35vw + 0.8rem, 1.02rem);
}
/* Make any images behave */
.rb-intro img{
  display:block;
  max-width:100%;
  height:auto;
  margin: 0 auto;
}

/* Grid (unchanged, just centered by wrapper) */
.rb-grid{
  margin-top:1.2rem;
  display:grid;
  gap: clamp(14px, 2.5vw, 28px);
  grid-template-columns: repeat(3, minmax(280px, 1fr));
  justify-items:center;
}
@media (max-width: 1000px){ .rb-grid{ grid-template-columns: repeat(2, minmax(260px, 1fr)); } }
@media (max-width: 680px){ .rb-grid{ grid-template-columns: minmax(240px, 1fr); } }

.rb-card{ width:100%; max-width:520px; display:flex; flex-direction:column; align-items:center; text-align:center; }
.rb-img{ width:100%; aspect-ratio:16/9; border-radius:12px; overflow:hidden; box-shadow:0 8px 22px rgba(0,0,0,.06); background:#f3f4f6; }
.rb-img img{ width:100%; height:100%; object-fit:cover; display:block; }
.rb-card h3{ margin:0.7rem 0 0; font-weight:800; font-size:clamp(1rem, 1vw + .75rem, 1.35rem); }

/* Keep the pager/feed hidden if you had those rules */
.pagination{display:none!important;}
.page__footer-follow .social-icons a[href$="feed.xml"],
.page__footer-follow .social-icons a[href*="/feed"],
.page__footer-follow .social-icons .fa-rss{display:none!important;}
</style>
