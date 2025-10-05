---
layout: single
title: "Videos"
permalink: /videos/
classes: wide   # <— wider page container so cards can be wider
---

<!-- Page-scoped styles with high specificity + !important -->
<style>
  /* Scope everything to this page only */
  #videos-page .vd-grid{
    display:grid !important;
    gap:1.1rem !important;
    align-items:start !important;
    grid-template-columns:1fr !important;                 /* 1 col mobile */
    max-width: 1500px !important;                         /* wider container = wider cards */
    margin-inline:auto !important;
    padding-inline:10px !important;
  }
  @media (min-width:768px){
    #videos-page .vd-grid{ grid-template-columns:repeat(2, minmax(360px, 1fr)) !important; }
  }
  @media (min-width:1100px){
    /* EXACTLY 3 columns, each with a wider minimum */
    #videos-page .vd-grid{ grid-template-columns:repeat(3, minmax(460px, 1fr)) !important; }
  }
  @media (min-width:1400px){
    #videos-page .vd-grid{ grid-template-columns:repeat(3, minmax(460px, 1fr)) !important; } /* lock at 3 */
  }

  /* Wider shape, not taller */
  #videos-page .vd-embed{
    position:relative !important;
    width:100% !important;
    aspect-ratio: 21 / 9 !important;                      /* wider than 16:9 to keep height down */
    min-height: 160px !important;                         /* prevents tall players */
    overflow:hidden !important;
    border-radius:.6rem !important;
    background:#000 !important;
  }
  #videos-page .vd-embed iframe{
    position:absolute !important;
    inset:0 !important;
    width:100% !important;
    height:100% !important;
    border:0 !important;
    display:block !important;
  }

  #videos-page .vd-card{ display:flex !important; flex-direction:column !important; gap:.5rem !important; }
  #videos-page h3.vd-title{ margin:.35rem 0 .1rem !important; font-weight:600 !important; font-size:.95rem !important; line-height:1.25 !important; }
</style>

<section id="videos-page">
  <div class="vd-grid">

    <!-- 1 -->
    <article class="vd-card">
      <div class="vd-embed">
        <iframe
          src="https://www.youtube.com/embed/CRraHg4Ks_g"
          title="Demis Hassabis On The Future of Work in the Age of AI"
          loading="lazy"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
          allowfullscreen></iframe>
      </div>
      <h3 class="vd-title">Demis Hassabis On The Future of Work in the Age of AI</h3>
    </article>

    <!-- 2 -->
    <article class="vd-card">
      <div class="vd-embed">
        <iframe
          src="https://www.youtube.com/embed/XaG2QNfiPnk"
          title="God Complex: Elon Musk vs Sam Altman and the AI Battle"
          loading="lazy"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
          allowfullscreen></iframe>
      </div>
      <h3 class="vd-title">God Complex: Elon Musk vs Sam Altman and the AI Battle</h3>
    </article>

    <!-- 3 -->
    <article class="vd-card">
      <div class="vd-embed">
        <iframe
          src="https://www.youtube.com/embed/dwyvBjBIDHQ"
          title="How is China using AI in the classroom? | The Take"
          loading="lazy"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
          allowfullscreen></iframe>
      </div>
      <h3 class="vd-title">How is China using AI in the classroom? | The Take</h3>
    </article>

    <!-- 4 -->
    <article class="vd-card">
      <div class="vd-embed">
        <iframe
          src="https://www.youtube.com/embed/UclrVWafRAI"
          title="The AI Safety Expert: These Are The Only 5 Jobs That Will Remain In 2030! — Dr. Roman Yampolskiy"
          loading="lazy"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
          allowfullscreen></iframe>
      </div>
      <h3 class="vd-title">The AI Safety Expert: These Are The Only 5 Jobs That Will Remain In 2030! — Dr. Roman Yampolskiy</h3>
    </article>

  </div>
</section>
