---
layout: single
title: About
permalink: /about/
---

<div class="vd-wide">
  <p>VeyDigital turns scattered marketing, web, CRM, and sales data into clear decisions.</p>
  <p>We build clean dashboards leaders trust, improve conversion with structured experiments, and automate the busywork so your team can focus on impact.</p>
</div>

/* Reduce space under the H1 “About” */
.page__title {
  margin-bottom: .35rem !important;
}

/* Tighten the first two paragraphs after the title */
.page__content > p:first-of-type {
  margin-top: 0 !important;
}
.page__content > p:first-of-type,
.page__content > p:nth-of-type(2) {
  margin: .4rem 0 .4rem !important;
  line-height: 1.55;
}

/* Slightly reduce space before the Deliverables heading */
.vd-wide-title {
  margin-top: .9rem !important;
  margin-bottom: .5rem !important;
}

/* Align H1, intro, section title, and table to the same left edge & width */
@media (min-width: 1024px){
  .page__title, .vd-wide, .vd-wide-title{
    position:relative;
    left:50%;
    transform:translateX(-50%);
    width:min(1400px,96vw);
    max-width:1400px;
    margin-left:auto;
    margin-right:auto;
    text-align:left;
  }
}

/* Simple, readable callout */
.vd-callout{
  border:1px solid #e6e9ef;
  border-radius:12px;
  padding:1rem 1.25rem;
  background:#f8fafc;
  margin:1rem 0;
}
.vd-callout strong{ color:#1E3A8A; }

/* Table styling */
table.vd-plain{ width:100%; border-collapse:collapse; font-family:Arial,Helvetica,sans-serif; }
table.vd-plain th, table.vd-plain td{ border:1px solid #e6e9ef; padding:10px 14px; vertical-align:top; line-height:1.5; }
table.vd-plain thead th{ background:#1E3A8A; color:#fff; text-align:left; font-weight:700; }
table.vd-plain tbody tr:nth-child(even) td{ background:#f8fafc; }

/* Keep only the Deliverables table wide */
@media (min-width:1024px){
  table.vd-delivers-wide{
    position:relative;
    left:50%;
    transform:translateX(-50%);
    width:min(1400px,96vw);
    max-width:1400px;
  }
}
</style>

<div class="vd-wide vd-intro">
  <p>VeyDigital turns scattered marketing, web, CRM, and sales data into clear decisions.</p>
  <p>We build clean dashboards leaders trust, improve conversion with structured experiments, and automate the busywork so your team can focus on impact.</p>
</div>


<h2 class="vd-wide-title">What VeyDigital Delivers</h2>

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
      <td>Weekly or monthly briefs focused on what changed and what to do next.</td>
      <td>Strategy notes with prioritized actions</td>
      <td>Google Sheets, Power BI, AI Assistant</td>
    </tr>
  </tbody>
</table>



## Join the community
<p><a href="https://discord.gg/yourInvite">Join our Discord ↗</a></p>
