---
layout: single
title: About
permalink: /about/
---

VeyDigital turns scattered marketing, web, and CRM data into clear decisions.  
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
  /* ---------------- Base table style (page-scoped) ---------------- */
  table.vd-plain {
    font-family: Arial, Helvetica, sans-serif;
    border-collapse: collapse;
    width: 100%;
    table-layout: auto;             /* natural sizing (no scroll) */
    margin: 0 0 1.25rem 0;
  }
  table.vd-plain td,
  table.vd-plain th {
    border: 1px solid #e6e9ef;
    padding: 10px 14px;
    vertical-align: top;
    white-space: normal;
    word-break: normal;
    hyphens: auto;
    line-height: 1.5;
  }
  table.vd-plain tr:nth-child(even) { background-color: #f8fafc; }
  table.vd-plain tr:hover { background-color: #f1f5fb; }
  table.vd-plain th {
    padding-top: 12px;
    padding-bottom: 12px;
    text-align: left;
    background-color: #1E3A8A;      /* VeyDigital deep blue */
    color: #fff;
    font-weight: 700;
  }

  /* Keep the H1 "About" in the normal content column (no centering/transform) */
  .page__title {
    text-align: left;
    position: static;
    transform: none;
    width: auto;
    max-width: none;
    margin-left: 0;
    margin-right: 0;
  }

  /* ---------- Widen ONLY the Deliverables table + match its section title ---------- */
  @media (min-width: 1024px) {
    table.vd-delivers-wide {
      position: relative;
      left: 50%;
      transform: translateX(-50%);
      width: min(1400px, 96vw);
      max-width: 1400px;
    }
    .vd-wide-title {
      text-align: left;
      position: relative;
      left: 50%;
      transform: translateX(-50%);
      width: min(1400px, 96vw);
      max-width: 1400px;
      margin: 0 0 .75rem 0;
    }
  }

  /* ---------------- Two-up grid for Optional Add-Ons + Case in Brief ---------------- */
  .vd-two-up {
    display: grid;
    grid-template-columns: 1fr;
    gap: 2rem;                    /* more breathing room between columns */
    align-items: start;
    margin-top: .5rem;
    margin-bottom: 1.25rem;
  }
  @media (min-width: 1024px) {
    .vd-two-up { grid-template-columns: minmax(0,1fr) minmax(0,1fr); }
  }
  .vd-two-up > * { min-width: 0; }         /* let tables shrink to fit side-by-side */
  .vd-two-up h3 { margin: 0 0 .75rem 0; }

  /* Card styling around each column for a professional look */
  .vd-two-up .vd-col {
    background: #fff;
    border: 1px solid #e6e9ef;
    border-radius: 12px;
    padding: 1rem 1rem .75rem;
    box-shadow: 0 1px 2px rgba(16,24,40,.04);
  }

  /* Fine-tune table spacing inside cards */
  .vd-two-up .vd-col table.vd-plain {
    width: 100%;
    border-collapse: separate;
    border-spacing: 0;
  }
  .vd-two-up .vd-col table.vd-plain th,
  .vd-two-up .vd-col table.vd-plain td {
    padding: 12px 16px;           /* nicer density for side tables */
    border-color: #e6e9ef;
    line-height: 1.55;
  }
  .vd-two-up .vd-col table.vd-plain thead th {
    background: #1E3A8A;
    color: #fff;
    font-weight: 700;
  }
  .vd-two-up .vd-col table.vd-plain tbody tr:nth-child(even) td { background: #f8fafc; }
  .vd-two-up .vd-col table.vd-plain tbody tr:hover td { background: #f1f5fb; }

  /* Rounded corners */
  .vd-two-up .vd-col table.vd-plain thead th:first-child { border-top-left-radius: 10px; }
  .vd-two-up .vd-col table.vd-plain thead th:last-child  { border-top-right-radius: 10px; }
  .vd-two-up .vd-col table.vd-plain tbody tr:last-child td:first-child { border-bottom-left-radius: 10px; }
  .vd-two-up .vd-col table.vd-plain tbody tr:last-child td:last-child  { border-bottom-right-radius: 10px; }

  /* Column width balance (desktop) */
  @media (min-width: 1024px) {
    /* Optional Add-Ons: label/content */
    .vd-two-up .vd-col:first-child table.vd-plain thead th:nth-child(1),
    .vd-two-up .vd-col:first-child table.vd-plain tbody td:nth-child(1) { width: 42%; }
    .vd-two-up .vd-col:first-child table.vd-plain thead th:nth-child(2),
    .vd-two-up .vd-col:first-child table.vd-plain tbody td:nth-child(2) { width: 58%; }

    /* Case in Brief: aspect/summary */
    .vd-two-up .vd-col:last-child table.vd-plain thead th:nth-child(1),
    .vd-two-up .vd-col:last-child table.vd-plain tbody td:nth-child(1) { width: 28%; }
    .vd-two-up .vd-col:last-child table.vd-plain thead th:nth-child(2),
    .vd-two-up .vd-col:last-child table.vd-plain tbody td:nth-child(2) { width: 72%; }
  }

  /* === FIX: Wide wrapper + clean 2-col grid (no width fighting) === */

/* Align this section to the same wide width as the Deliverables table */
.vd-wide {
  width: 100%;
  margin: 0 auto;
}
@media (min-width: 1024px) {
  .vd-wide {
    width: min(1400px, 96vw);
    max-width: 1400px;
  }
}

/* Two uniform columns with ample gap; stacks on mobile */
.vd-two-up {
  display: grid;
  grid-template-columns: 1fr;      /* mobile */
  gap: 2rem;                       /* comfortable spacing */
  align-items: start;
}
@media (min-width: 1024px) {
  .vd-two-up { grid-template-columns: repeat(2, minmax(0, 1fr)); }
}

/* Card look without shrinking content */
.vd-two-up .vd-col {
  background: #fff;
  border: 1px solid #e6e9ef;
  border-radius: 12px;
  padding: 1rem 1rem .75rem;
  box-shadow: 0 1px 2px rgba(16,24,40,.04);
  min-width: 0;                    /* let tables shrink inside columns */
}
.vd-two-up .vd-col h3 { margin: .25rem 0 .75rem; }

/* Tables inside the cards */
.vd-two-up .vd-col table.vd-plain {
  width: 100%;
  border-collapse: separate;
  border-spacing: 0;
}

/* Professional padding + readable line-height */
.vd-two-up .vd-col table.vd-plain th,
.vd-two-up .vd-col table.vd-plain td {
  padding: 12px 16px;
  line-height: 1.55;
  border-color: #e6e9ef;
  width: auto !important;          /* override any previous width rules */
}

/* Keep your brand header */
.vd-two-up .vd-col table.vd-plain thead th {
  background: #1E3A8A;
  color: #fff;
  font-weight: 700;
}

/* Gentle zebra + hover */
.vd-two-up .vd-col table.vd-plain tbody tr:nth-child(even) td { background: #f8fafc; }
.vd-two-up .vd-col table.vd-plain tbody tr:hover td { background: #f1f5fb; }

/* Rounded corners */
.vd-two-up .vd-col table.vd-plain thead th:first-child { border-top-left-radius: 10px; }
.vd-two-up .vd-col table.vd-plain thead th:last-child  { border-top-right-radius: 10px; }
.vd-two-up .vd-col table.vd-plain tbody tr:last-child td:first-child { border-bottom-left-radius: 10px; }
.vd-two-up .vd-col table.vd-plain tbody tr:last-child td:last-child  { border-bottom-right-radius: 10px; }
/* === FINAL ALIGNMENT FIX: two cards same width + same height === */

/* Make the two-up section use the same wide width as the big table */
.vd-wide {
  width: 100%;
  margin: 0 auto;
}
@media (min-width: 1024px) {
  .vd-wide { width: min(1400px, 96vw); max-width: 1400px; }
}

/* Two equal columns; cards stretch to the same height */
.vd-two-up {
  display: grid;
  grid-template-columns: 1fr;                 /* mobile */
  gap: 2rem;
  align-items: stretch;                       /* stretch items to equal row height */
}
@media (min-width: 1024px) {
  .vd-two-up { grid-template-columns: repeat(2, minmax(0, 1fr)); }
}

/* Cards fill the track height; content flows nicely */
.vd-two-up .vd-col {
  display: flex;
  flex-direction: column;
  height: 100%;
  box-sizing: border-box;
  background: #fff;
  border: 1px solid #e6e9ef;
  border-radius: 12px;
  padding: 1rem 1rem .75rem;
  box-shadow: 0 1px 2px rgba(16,24,40,.04);
  min-width: 0;                                /* prevent overflow from long content */
}

.vd-two-up .vd-col h3 {
  margin: .25rem 0 .75rem;
}

/* Tables inside cards take remaining height so both cards equalize */
.vd-two-up .vd-col table.vd-plain {
  flex: 1;                                     /* makes both cards the same height */
  width: 100%;
  border-collapse: separate;
  border-spacing: 0;
  table-layout: fixed;                         /* consistent column sizing */
}

/* Consistent, readable cell spacing */
.vd-two-up .vd-col table.vd-plain th,
.vd-two-up .vd-col table.vd-plain td {
  padding: 12px 16px;
  line-height: 1.55;
  border-color: #e6e9ef;
  white-space: normal;
  word-break: normal;
  overflow-wrap: anywhere;
}

/* Brand header */
.vd-two-up .vd-col table.vd-plain thead th {
  background: #1E3A8A;
  color: #fff;
  font-weight: 700;
}

/* Gentle zebra + hover */
.vd-two-up .vd-col table.vd-plain tbody tr:nth-child(even) td { background: #f8fafc; }
.vd-two-up .vd-col table.vd-plain tbody tr:hover td { background: #f1f5fb; }

/* Rounded corners */
.vd-two-up .vd-col table.vd-plain thead th:first-child { border-top-left-radius: 10px; }
.vd-two-up .vd-col table.vd-plain thead th:last-child  { border-top-right-radius: 10px; }
.vd-two-up .vd-col table.vd-plain tbody tr:last-child td:first-child { border-bottom-left-radius: 10px; }
.vd-two-up .vd-col table.vd-plain tbody tr:last-child td:last-child  { border-bottom-right-radius: 10px; }

/* Make both side tables use the SAME column split so widths match visually */
@media (min-width: 1024px) {
  .vd-two-up .vd-col table.vd-plain thead th:nth-child(1),
  .vd-two-up .vd-col table.vd-plain tbody td:nth-child(1) { width: 38% !important; }
  .vd-two-up .vd-col table.vd-plain thead th:nth-child(2),
  .vd-two-up .vd-col table.vd-plain tbody td:nth-child(2) { width: 62% !important; }
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

<div class="vd-two-up">
  <div class="vd-col">
    <h3>Optional Add-Ons</h3>
    <table class="vd-plain">
      <thead>
        <tr>
          <th>Category</th>
          <th>Details</th>
        </tr>
      </thead>
      <tbody>
        <tr><td><strong>Advanced Strategy &amp; Insights</strong></td><td>SEO &amp; site-performance audits</td></tr>
        <tr><td><strong>User Experience</strong></td><td>Journey mapping</td></tr>
        <tr><td><strong>Competitive Analysis</strong></td><td>Competitor benchmarking dashboards</td></tr>
        <tr><td><strong>Predictive Analytics</strong></td><td>Churn / retention modeling</td></tr>
        <tr><td><strong>AI Integration</strong></td><td>Chat + content assistants with compliance guardrails</td></tr>
      </tbody>
    </table>
  </div>

  <div class="vd-col">
    <h3>Case in Brief — Global NGO</h3>
    <table class="vd-plain">
      <thead>
        <tr>
          <th>Aspect</th>
          <th>Summary</th>
        </tr>
      </thead>
      <tbody>
        <tr><td><strong>Problem</strong></td><td>20+ countries, siloed web/ad/CRM data; messy UTMs; slow readouts</td></tr>
        <tr><td><strong>Fix</strong></td><td>Google Cloud-native analytics layer; standardized KPIs/UTMs; daily brief with one key action; secure country-level views</td></tr>
        <tr><td><strong>Triggers</strong></td><td>Donate-drop nudges; lapsed-donor reactivation</td></tr>
        <tr><td><strong>Results (typical)</strong></td><td>+10–20% conversion · –15–25% cost per gift · same-day anomaly detection · 2–4 hrs/week saved per team</td></tr>
      </tbody>
    </table>
  </div>
</div>

## Sample Deliverables &amp; Timelines

<table class="vd-plain">
  <thead>
    <tr>
      <th>Deliverable</th>
      <th>Timeline</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>KPI Dashboards</td><td>8–12 weeks</td></tr>
    <tr><td>CRO Testing Roadmap</td><td>Quarterly cycles</td></tr>
    <tr><td>Training &amp; Workshops</td><td>Within 3 months</td></tr>
    <tr><td>Data Governance Framework</td><td>6–8 weeks</td></tr>
    <tr><td>Automation Pipelines</td><td>3–4 months</td></tr>
    <tr><td>Ongoing Insights</td><td>Continuous</td></tr>
  </tbody>
</table>

## Join the community

<p><a href="https://discord.gg/yourInvite">Join our Discord ↗</a></p>



