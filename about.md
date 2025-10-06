---
layout: single
title: About
permalink: /about/
---

<h2 class="vd-wide-title">What VeyDigital Delivers</h2>

<style>
  /* Base table style */
  table.vd-plain {
    font-family: Arial, Helvetica, sans-serif;
    border-collapse: collapse;
    width: 100%;
    table-layout: auto;              /* natural sizing (no scroll) */
    margin: 0 0 1.25rem 0;
  }
  table.vd-plain td,
  table.vd-plain th {
    border: 1px solid #ddd;
    padding: 8px;
    vertical-align: top;
    white-space: normal;             /* wrap text, don’t cut it off */
    word-break: normal;
    hyphens: auto;
  }
  table.vd-plain tr:nth-child(even) { background-color: #f2f2f2; }
  table.vd-plain tr:hover { background-color: #ddd; }
  table.vd-plain th {
    padding-top: 12px;
    padding-bottom: 12px;
    text-align: left;
    background-color: #1E3A8A;       /* VeyDigital deep blue */
    color: #fff;
    font-weight: 700;
  }

  /* Widen ONLY the Delivers table on desktop + align titles to it */
  @media (min-width: 1024px) {
    table.vd-delivers-wide {
      position: relative;
      left: 50%;
      transform: translateX(-50%);   /* center on viewport */
      width: min(1400px, 96vw);      /* wider, but never beyond screen */
      max-width: 1400px;
    }

    /* Page H1 (“About”) and H2 above the table */
    .page__title,
    .vd-wide-title {
      text-align: left;
      position: relative;
      left: 50%;
      transform: translateX(-50%);
      width: min(1400px, 96vw);      /* match table width */
      max-width: 1400px;
      margin-left: auto;
      margin-right: auto;
    }
    .vd-wide-title { margin: 0 0 .75rem 0; }
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
      <td>Google Sheets, Power BI, AI Assis
