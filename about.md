---
layout: single
title: About
permalink: /about/
---

VeyDigital turns scattered marketing, web, CRM, and sales data into clear decisions.  
We build clean dashboards leaders trust, improve conversion with structured experiments, and automate the busywork so your team can focus on impact.

**What we’re great at**
- Analytics & Reporting — one clear view across web, ads, CRM, and sales  
- Conversion Optimization (CRO) — structured A/B testing that drives learnings  
- Automation & Integration — lightweight, reliable pipelines  
- Governance — consistent tracking, UTMs, and naming standards  
- Enablement — workshops, playbooks, and quick-reference guides  
- Ongoing Insights — what changed this week and what to do next

<h2 class="vd-wide-title">What VeyDigital Delivers</h2>

<style>
  /* Page-local styles (kept here to avoid Sass build errors) */

  /* Base table style */
  table.vd-plain {
    font-family: Arial, Helvetica, sans-serif;
    border-collapse: collapse;
    width: 100%;
    table-layout: auto;
    margin: 0 0 1.25rem 0;
  }
  table.vd-plain td,
  table.vd-plain th {
    border: 1px solid #e6e9ef;
    padding: 10px 14px;
    vertical-align: top;
    line-height: 1.5;
    white-space: normal;
    word-break: normal;
    hyphens: auto;
  }
  table.vd-plain thead th {
    background: #1E3A8A; /* VeyDigital blue */
    color: #fff;
    text-align: left;
    font-weight: 700;
    padding-top: 12px;
    padding-bottom: 12px;
  }
  table.vd-plain tbody tr:nth-child(even) td { background: #f8fafc; }
  table.vd-plain tbody tr:hover td { background: #f1f5fb; }

  /* Keep the H1 "About" in the normal content column */
  .page__title {
    text-align: left;
    position: static;
    transform: none;
    width: auto;
    max-width: none;
    margin-left: 0;
    margin-right: 0;
  }

  /* Widen ONLY the Deliverables table + align its section title */
  @media (min-width: 1024px) {
    table.vd-delivers-wide {
      position: relative;
      left: 50%;
      transform: translateX(-50%);
      width: min(1280px, 96vw); /* adjust 1200–1400 to taste */
      max-width: 1280px;
    }
    .vd-wide-title {
      text-align: left;
      position: relative;
      left: 50%;
      transform: translateX(-50%);
      width: min(1280px, 96vw);
      max-width: 1280px;
      margin: 0 0 .75rem 0;
    }
  }
<!-- ===== VeyDigital: Add-ons + Case in brief (styled cards) ===== -->
<div class="vd-callouts">
  <section class="vd-card">
    <h3>Optional add-ons</h3>
    <ul class="vd-pills">
      <li>SEO &amp; site-performance audits</li>
      <li>Journey mapping</li>
      <li>Competitor benchmarking dashboards</li>
      <li>Predictive analytics (churn/retention)</li>
      <li>AI chat/content assistants with guardrails</li>
    </ul>
  </section>

  <section class="vd-card">
    <h3>Case in brief — Global NGO</h3>
    <ul class="vd-brief">
      <li><span>Problem</span> 20+ countries with siloed web/ad/CRM data, messy UTMs, and slow readouts.</li>
      <li><span>Fix</span> Google Cloud–native analytics layer, standardized KPIs/UTMs, daily one-action brief, secure country views.</li>
      <li><span>Triggers</span> Donate-drop nudges; lapsed-donor reactivation.</li>
    </ul>

    <div class="vd-metrics">
      <div class="vd-metric">
        <div class="vd-num">+10–20%</div>
        <div class="vd-label">conversion</div>
      </div>
      <div class="vd-metric">
        <div class="vd-num">–15–25%</div>
        <div class="vd-label">cost per gift</div>
      </div>
      <div class="vd-metric">
        <div class="vd-num">Same-day</div>
        <div class="vd-label">anomaly detection</div>
      </div>
      <div class="vd-metric">
        <div class="vd-num">2–4 hrs/wk</div>
        <div class="vd-label">saved per team</div>
      </div>
    </div>
  </section>
</div>

<style>
/* ===== Page-local styles for the two cards (safe for Jekyll) ===== */
.vd-callouts{
  display:grid;
  grid-template-columns:1fr;
  gap:2rem;
  align-items:start;
  margin:1.25rem 0 0;
}
@media (min-width:1024px){
  .vd-callouts{ grid-template-columns:repeat(2,minmax(0,1fr)); }
}

/* Card */
.vd-card{
  background:#fff;
  border:1px solid #e6e9ef;
  border-radius:14px;
  padding:1.25rem 1.25rem 1rem;
  box-shadow:0 1px 2px rgba(16,24,40,.06);
}
.vd-card h3{
  margin:.25rem 0 1rem;
  font-size:1.25rem;
  line-height:1.3;
  position:relative;
  padding-left:.75rem;
}

</style>


<table class="vd-plain vd-delivers-wide">
  <thead>
    <tr>
    <th>Service</th>
    <th>Description</th>
    <th>Deliverable</th>
    <th>Tools</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Digital Analytics &amp; Reporting</strong></td>
      <td>Automated dashboards across web, ads, CRM, and sales so leaders get one clear view.</td>
      <td>Insight dashboards with weekly/monthly updates</td>
      <td>GA4, GTM, BigQuery, Power BI, Cloud BI Studio</td>
    </tr>
    <tr>
      <td><strong>Conversion Optimization (CRO)</strong></td>
      <td>Structured A/B testing for pages, funnels, ads, and emails.</td>
      <td>Test plans, results, and next-step recommendations</td>
      <td>Optimizely/VWO, GA4 Experiments</td>
    </tr>
    <tr>
      <td><strong>Automation &amp; Integration</strong></td>
      <td>Lightweight pipelines to move marketing/sales data reliably.</td>
      <td>Documented ETL workflows (e.g., BigQuery/Supabase + automation tools)</td>
      <td>BigQuery, Supabase, Power Automate, Zapier</td>
    </tr>
    <tr>
      <td><strong>Governance &amp; Tracking Standards</strong></td>
      <td>Clear UTM taxonomy, naming conventions, and campaign tracking.</td>
      <td>Tracking framework + onboarding guide</td>
      <td>Google Tag Manager, GA4, Data Studio</td>
    </tr>
    <tr>
      <td><strong>Capacity Building &amp; Training</strong></td>
      <td>Short workshops and reusable guides so teams can self-serve.</td>
      <td>Workshops/bootcamps, quick-reference manuals, skills assessments</td>
      <td>Power BI, Looker Studio, Custom LMS</td>
    </tr>
    <tr>
      <td><strong>Performance Insights</strong></td>
      <td>Weekly or monthly briefs focused on what changed — and what to do next.</td>
      <td>Strategy notes with prioritized actions</td>
      <td>Google Sheets, Power BI, AI Assistant</td>
    </tr>
  </tbody>
</table>




## Join the community
<p><a href="https://discord.gg/yourInvite">Join our Discord ↗</a></p>
