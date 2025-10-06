---
layout: single
title: "About"
permalink: /about/
toc: true
toc_sticky: true
classes: wide
---


<!-- Scoped, minimal styles (won't affect other pages) -->
<style>
  /* Scope */
  #about-page { --max: 1280px; --gap: 1rem; --radius: 14px; --muted: #667085; }
  #about-page .wrap { max-width: var(--max); margin-inline: auto; padding-inline: 12px; }

  /* Cards grid — wider columns */
  #about-page .cards { display: grid; gap: var(--gap); }
  /* 1 col on mobile */
  #about-page .cards.cols-3 { grid-template-columns: 1fr; }
  #about-page .cards.cols-2 { grid-template-columns: 1fr; }

  /* 2 cols on tablet/desktop (wider cards even with TOC) */
  @media (min-width: 800px){
    #about-page .cards.cols-3 { grid-template-columns: repeat(2, minmax(0,1fr)); }
    #about-page .cards.cols-2 { grid-template-columns: repeat(2, minmax(0,1fr)); }
  }

  /* Only go to 3 cols on very wide screens */
  @media (min-width: 1400px){
    #about-page .cards.cols-3 { grid-template-columns: repeat(3, minmax(0,1fr)); }
  }

  /* Cards, pills, map (unchanged basics) */
  #about-page .card { background:#fff; border:1px solid #eee; border-radius: var(--radius); padding: 1rem; }
  #about-page .card h3 { margin: .2rem 0 .5rem; font-size: 1.02rem; }
  #about-page .muted { color: var(--muted); }
  #about-page .meta { color: var(--muted); font-size: .92rem; margin:.25rem 0 0; }
  #about-page .pills { display:flex; flex-wrap:wrap; gap:.55rem; }
  #about-page .pill { border:1px solid #e6e6e6; border-radius:999px; padding:.35rem .65rem; font-size:.92rem; }
  #about-page .map { position:relative; width:100%; aspect-ratio:21/9; min-height:260px; border:1px solid #e6e6e6; border-radius: var(--radius); overflow:hidden; background:#e6eef5; }
  #about-page .map iframe { position:absolute; inset:0; width:100%; height:100%; border:0; }
</style>


<section id="about-page">
  <div class="wrap">

## What VeyDigital Delivers

<div class="cards cols-3">
  <article class="card">
    <h3>Digital Analytics & Reporting</h3>
    <p>Automated dashboards that pull from web, ads, CRM, and sales so leaders get one clear view.</p>
    <p class="meta"><b>Deliverable:</b> Insight dashboards with weekly/monthly updates</p>
    <p class="meta"><b>Tools:</b> GA4, GTM, BigQuery, Power BI, cloud BI studio</p>
  </article>

  <article class="card">
    <h3>Conversion Optimization (CRO)</h3>
    <p>Structured A/B testing for pages, funnels, ads, and emails.</p>
    <p class="meta"><b>Deliverable:</b> Test plans, results, and next-step recommendations</p>
    <p class="meta"><b>Tools:</b> Optimizely/VWO, GA4 experiments</p>
  </article>

  <article class="card">
    <h3>Automation & Integration</h3>
    <p>Lightweight data pipelines to move marketing/sales data reliably.</p>
    <p class="meta"><b>Deliverable:</b> Documented ETL workflows (e.g., BigQuery/Supabase + automation tools)</p>
  </article>

  <article class="card">
    <h3>Governance & Tracking Standards</h3>
    <p>Clear UTM taxonomy, naming conventions, and campaign tracking.</p>
    <p class="meta"><b>Deliverable:</b> Tracking framework + onboarding guide</p>
  </article>

  <article class="card">
    <h3>Capacity Building & Training</h3>
    <p>Short workshops and reusable guides so teams can self-serve.</p>
    <p class="meta"><b>Deliverable:</b> Workshops/bootcamps, quick-reference manuals, skills assessments</p>
  </article>

  <article class="card">
    <h3>Performance Insights</h3>
    <p>Weekly or monthly briefs focused on what changed and what to do next.</p>
    <p class="meta"><b>Deliverable:</b> Strategy notes with prioritized actions</p>
  </article>
</div>

---

## Who Benefits

<div class="pills">
  <span class="pill">Nonprofits & NGOs</span>
  <span class="pill">E-commerce brands</span>
  <span class="pill">Startups & tech teams</span>
  <span class="pill">Education</span>
  <span class="pill">Healthcare</span>
  <span class="pill">Public sector</span>
  <span class="pill">Professional services</span>
  <span class="pill">Hospitality & travel</span>
</div>

---

## Sample Deliverables & Timelines

<div class="cards cols-2">
  <article class="card">
    <h3>KPI Dashboards</h3>
    <p>Connect CRM + analytics + paid media.</p>
    <p class="meta"><b>Timeline:</b> 8–12 weeks</p>
  </article>

  <article class="card">
    <h3>CRO Testing Roadmap</h3>
    <p>Hypotheses, test setup, readouts.</p>
    <p class="meta"><b>Timeline:</b> Quarterly cycles</p>
  </article>

  <article class="card">
    <h3>Training & Workshops</h3>
    <p>2-day bootcamp + refreshers.</p>
    <p class="meta"><b>Timeline:</b> within 3 months</p>
  </article>

  <article class="card">
    <h3>Data Governance Framework</h3>
    <p>Conventions + documentation + onboarding.</p>
    <p class="meta"><b>Timeline:</b> 6–8 weeks</p>
  </article>

  <article class="card">
    <h3>Automation Pipelines</h3>
    <p>Cloud data flows for marketing/CRM.</p>
    <p class="meta"><b>Timeline:</b> 3–4 months</p>
  </article>

  <article class="card">
    <h3>Ongoing Insights</h3>
    <p>Weekly or monthly optimization reports.</p>
    <p class="meta"><b>Timeline:</b> Continuous (retainer)</p>
  </article>
</div>

---

## Optional Add-Ons

<div class="pills">
  <span class="pill">SEO & site performance audits</span>
  <span class="pill">Donor/customer journey mapping</span>
  <span class="pill">Competitor benchmarking dashboards</span>
  <span class="pill">Predictive analytics (churn/retention)</span>
  <span class="pill">AI chat/content assistants with guardrails</span>
</div>

---

## Case in brief — Global NGO

<div class="cards cols-2">
  <article class="card">
    <h3>Problem</h3>
    <p>20+ countries, siloed web/ad/CRM data; messy UTMs; slow readouts.</p>
    <h3>Fix</h3>
    <p>Google’s cloud-native analytics layer + standardized KPIs/UTMs; daily brief with one action; secure, country-level views.</p>
    <h3>Triggers</h3>
    <p>Donate-drop nudges; lapsed-donor reactivation.</p>
  </article>

  <article class="card">
    <h3>Results (typical)</h3>
    <ul>
      <li><b>+10–20%</b> conversion</li>
      <li><b>−15–25%</b> cost per gift</li>
      <li><b>Same-day</b> anomaly detection</li>
      <li><b>2–4 hrs/week</b> saved per team</li>
    </ul>
  </article>
</div>

---

## Join the community

<p class="muted">Want closer, real-time conversation and quick feedback? Join us on Discord.</p>
<p><a class="btn" href="https://discord.gg/yourInviteCode" target="_blank" rel="noopener">Join our Discord ↗</a></p>
<p class="muted">Note: Discord is great for real-time chat, but it isn’t end-to-end encrypted. For sensitive topics, contact us directly.</p>

---

## Start here

<div class="pills">
  <a class="pill" href="/playbook/">Open the YC Startup Playbook →</a>
  <a class="pill" href="/videos/">Browse Videos (Upskill quickly) →</a>
  <a class="pill" href="/blog/">Read the latest on the Blog →</a>
</div>

---

## Based in Seattle, WA

<div class="map">
  <iframe
    title="Map: Seattle, WA"
    src="https://www.openstreetmap.org/export/embed.html?bbox=-122.4594%2C47.495%2C-122.224%2C47.734&layer=mapnik&marker=47.6062%2C-122.3321"
    loading="lazy" allowfullscreen></iframe>
</div>
<p class="muted"><a href="https://www.openstreetmap.org/?mlat=47.6062&mlon=-122.3321#map=12/47.6062/-122.3321" target="_blank" rel="noopener">Open full map ↗</a></p>

  </div>
</section>
