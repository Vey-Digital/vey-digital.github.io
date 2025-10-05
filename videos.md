---
layout: single
title: "Videos"
permalink: /videos/
---
<style>
  /* Grid: 1 col (mobile) → 2 (tablet) → 3 (desktop), no more than 3 */
  .vd-grid{
    display:grid; gap:1rem; align-items:start;
    grid-template-columns:1fr;
    max-width:1140px;                 /* wider container = bigger cards */
    margin-inline:auto; padding-inline:8px;
  }
  @media (min-width:768px){  .vd-grid{ grid-template-columns:repeat(2,minmax(0,1fr)); } }
  @media (min-width:1100px){ .vd-grid{ grid-template-columns:repeat(3,minmax(0,1fr)); } }
  @media (min-width:1400px){ .vd-grid{ grid-template-columns:repeat(3,minmax(0,1fr)) !important; } }

  /* Bigger player (kept short-ish) */
  .vd-embed{
    position:relative; width:100%;
    aspect-ratio:16/9;
    min-height:220px;                 /* ↑ was 150px — increase size here */
    overflow:hidden; border-radius:.6rem; background:#000;
  }
  .vd-embed iframe{ position:absolute; inset:0; width:100%; height:100%; border:0; display:block; }

  .vd-card{ display:flex; flex-direction:column; gap:.5rem; }
  .vd-title{ margin:.4rem 0 .1rem; font-weight:600; font-size:.9rem; line-height:1.25; }
</style>


<!-- Inline CSS here so the page works even if your SCSS isn't loading -->
<style>
  .vd-grid{
    display:grid; gap:0.9rem; align-items:start;
    grid-template-columns:1fr; max-width:980px; margin-inline:auto; padding-inline:8px;
  }
  @media (min-width:768px){ .vd-grid{ grid-template-columns:repeat(2,minmax(0,1fr)); } }
  @media (min-width:1100px){ .vd-grid{ grid-template-columns:repeat(3,minmax(0,1fr)); } }
  @media (min-width:1400px){ .vd-grid{ grid-template-columns:repeat(3,minmax(0,1fr)) !important; } }

  .vd-card{ display:flex; flex-direction:column; gap:.5rem; }
  .vd-title{ margin:.6rem 0 .25rem; font-weight:600; }

  .vd-embed{ position:relative; width:100%; aspect-ratio:16/9; min-height:150px; overflow:hidden; border-radius:.6rem; background:#000; }
  .vd-embed iframe{ position:absolute; inset:0; width:100%; height:100%; border:0; display:block; }
</style>

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
