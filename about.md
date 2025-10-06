---
layout: single
title: "About"
permalink: /about/
---

<!-- ===== About page (scoped) ===== -->
<style>
  #about-page{--container:1160px;--gap:1rem;--radius:14px;--muted:#667085;}
  #about-page .container{max-width:var(--container);margin-inline:auto;padding:0 12px;}
  #about-page .subnav{position:sticky;top:0;z-index:2;background:#fff;border-bottom:1px solid #eee;margin:-.5rem 0 1.25rem;padding:.5rem 0;}
  #about-page .subnav ul{display:flex;flex-wrap:wrap;gap:.5rem 1rem;list-style:none;margin:0;padding:0;}
  #about-page .subnav a{display:inline-flex;gap:.5rem;align-items:center;padding:.4rem .6rem;border-radius:10px;text-decoration:none;border:1px solid #eee;}
  #about-page .subnav a:hover{background:#f7f7f7}
  #about-page .lead{font-size:1.05rem;color:var(--muted);margin:.25rem 0 1rem}

  /* Grid + cards */
  #about-page .grid{display:grid;gap:var(--gap);}
  @media (min-width: 800px){#about-page .grid.cols-3{grid-template-columns:repeat(3,minmax(0,1fr));}}
  @media (min-width: 800px){#about-page .grid.cols-2{grid-template-columns:repeat(2,minmax(0,1fr));}}
  #about-page .card{background:#fff;border:1px solid #eee;border-radius:var(--radius);padding:1rem}
  #about-page .card h3{margin:.25rem 0 .4rem;font-size:1.05rem}
  #about-page .card .meta{color:var(--muted);font-size:.92rem;margin:.25rem 0 0}
  #about-page .pillset{display:flex;flex-wrap:wrap;gap:.5rem}
  #about-page .pill{border:1px solid #e6e6e6;border-radius:999px;padding:.35rem .6rem;font-size:.9rem}
  #about-page .bullet{margin:.25rem 0 0 .9rem}
  #about-page .kpis{display:grid;gap:.75rem}
  @media (min-width: 800px){#about-page .kpis{grid-template-columns:repeat(3,minmax(0,1fr));}}
  #about-page .kpi{border:1px dashed #e6e6e6;border-radius:12px;padding:.75rem}
  #about-page .kpi b{font-size:1.05rem}
  #about-page .cta-row{display:flex;flex-wrap:wrap;gap:.6rem}
  #about-page .btn{display:inline-flex;align-items:center;gap:.5rem;padding:.55rem .9rem;border-radius:10px;text-decoration:none;border:1px solid #ddd}
  #about-page .btn--primary{background:#111;color:#fff;border-color:#111}
  #about-page .btn:hover{opacity:.9}

  /* Map */
  #about-page .map-box{position:relative;width:100%;aspect-ratio:21/9;min-height:260px;border-radius:14px;overflow:hidden;background:#e6eef5;border:1px solid #e6e6e6}
  #about-page .map-box iframe{position:absolute;inset:0;width:100%;height:100%;border:0}

  /* Section spacing */
  #about-page section{margin:1.25rem 0 1.5rem}
  #about-page h2{margin:.25rem 0 .5rem}
  #about-page .muted{color:var(--muted)}
</style>

<section id="about-page">
  <div class="container">

    <!-- Sticky mini-nav -->
    <nav class="subnav">
      <ul>
        <li><a href="#deliver">What VeyDigital Delivers</a></li>
        <li><a href="#benefits">Who Benefits</a></li>
        <li><a href="#samples">Sample Deliverables</a></li>
        <li><a href="#addons">Optional Add-Ons</a></li>
        <li><a href="#case">Case in Brief</a></li>
        <li><a href="#start">Start Here</a></li>
        <li><a href="#location">Based in Seattle</a></li>
      </ul>
    </nav>

    <!-- Hero / overview -->
    <header>
      <h1>About VeyDigital</h1>
      <p class="lead">Practical AI, cloud-native analytics, and lightweight automations—so teams get clear insights and faster outcomes.</p>
      <div class="cta-row">
        <a class="btn btn--primary" href="/playbook/">Open the YC Startup Playbook</a>
        <a class="btn" href="/videos/">Browse Videos</a>
        <a class="btn" href="/blog/">Read the Blog</a>
      </div>
    </header>

    <!-- Delivers -->
    <section id="deliver">
      <h2>What VeyDigital Delivers</h2>
      <div class="grid cols-3">
        <article class="card">
          <h3>Digital Analytics & Reporting</h3>
          <p>Automated dashboards from web, ads, CRM, and sales—one clear view for leaders.</p>
          <p class="meta"><b>Deliverable:</b> Insight dashboards with weekly/monthly updates.</p>
          <p class="meta"><b>Tools:</b> GA4, GTM, BigQuery, Power BI, cloud BI studio.</p>
        </article>
        <article class="card">
          <h3>Conversion Optimization (CRO)</h3>
          <p>Structured A/B tests for pages, funnels, ads, and emails.</p>
          <p class="meta"><b>Deliverable:</b> Test plans, results, and next-step recommendations.</p>
          <p class="meta"><b>Tools:</b> Optimizely/VWO, GA4 experiments.</p>
        </article>
        <article class="card">
          <h3>Automation & Integration</h3>
          <p>Lightweight data pipelines to move marketing/sales data reliably.</p>
          <p class="meta"><b>Deliverable:</b> Documented ETL workflows (BigQuery/Supabase + automation).</p>
        </article>
        <article class="card">
          <h3>Governance & Tracking Standards</h3>
          <p>Clear UTM taxonomy, naming conventions, and campaign tracking.</p>
          <p class="meta"><b>Deliverable:</b> Tracking framework + onboarding guide.</p>
        </article>
        <article class="card">
          <h3>Capacity Building & Training</h3>
          <p>Short workshops and reusable guides so teams can self-serve.</p>
          <p class="meta"><b>Deliverable:</b> Workshops/bootcamps, quick-reference manuals, skills assessments.</p>
        </article>
        <article class="card">
          <h3>Performance Insights</h3>
          <p>Weekly/monthly briefs focused on what changed—and what to do next.</p>
          <p class="meta"><b>Deliverable:</b> Strategy notes with prioritized actions.</p>
        </article>
      </div>
    </section>

    <!-- Who benefits -->
    <section id="benefits">
      <h2>Who Benefits</h2>
      <div class="pillset">
        <span class="pill">Nonprofits & NGOs</span>
        <span class="pill">E-commerce</span>
        <span class="pill">Startups & Tech Teams</span>
        <span class="pill">Education</span>
        <span class="pill">Healthcare</span>
        <span class="pill">Public Sector</span>
        <span class="pill">Professional Services</span>
        <span class="pill">Hospitality & Travel</span>
      </div>
    </section>

    <!-- Samples -->
    <section id="samples">
      <h2>Sample Deliverables & Timelines</h2>
      <div class="grid cols-2">
        <article class="card">
          <h3>KPI Dashboards</h3>
          <p class="meta"><b>Timeline:</b> 8–12 weeks</p>
          <ul class="bullet">
            <li>Connect CRM + analytics + paid media</li>
          </ul>
        </article>
        <article class="card">
          <h3>CRO Testing Roadmap</h3>
          <p class="meta"><b>Timeline:</b> Quarterly cycles</p>
          <ul class="bullet">
            <li>Hypotheses, test setup, readouts</li>
          </ul>
        </article>
        <article class="card">
          <h3>Training & Workshops</h3>
          <p class="meta"><b>Timeline:</b> within 3 months</p>
          <ul class="bullet">
            <li>2-day bootcamp + refreshers</li>
          </ul>
        </article>
        <article class="card">
          <h3>Data Governance Framework</h3>
          <p class="meta"><b>Timeline:</b> 6–8 weeks</p>
          <ul class="bullet">
            <li>Conventions + documentation + onboarding</li>
          </ul>
        </article>
        <article class="card">
          <h3>Automation Pipelines</h3>
          <p class="meta"><b>Timeline:</b> 3–4 months</p>
          <ul class="bullet">
            <li>Cloud data flows for marketing/CRM</li>
          </ul>
        </article>
        <article class="card">
          <h3>Ongoing Insights</h3>
          <p class="meta"><b>Timeline:</b> Continuous (retainer)</p>
          <ul class="bullet">
            <li>Weekly or monthly optimization reports</li>
          </ul>
        </article>
      </div>
    </section>

    <!-- Optional add-ons -->
    <section id="addons">
      <h2>Optional Add-Ons</h2>
      <div class="pillset">
        <span class="pill">SEO & Performance Audits</span>
        <span class="pill">Journey Mapping</span>
        <span class="pill">Competitor Dashboards</span>
        <span class="pill">Predictive Analytics</span>
        <span class="pill">AI Chat/Content Assistants</span>
      </div>
    </section>

    <!-- Case in brief -->
    <section id="case">
      <h2>Case in Brief — Global NGO</h2>
      <div class="grid cols-2">
        <article class="card">
          <h3>Problem</h3>
          <p>20+ countries, siloed web/ad/CRM data; messy UTMs; slow readouts.</p>
          <h3>Fix</h3>
          <p>Google cloud-native analytics layer + standardized KPIs/UTMs; daily brief with one action; secure country-level views.</p>
          <h3>Triggers</h3>
          <p>Donate-drop nudges, lapsed-donor reactivation.</p>
        </article>
        <article class="card">
          <h3>Results (typical)</h3>
          <div class="kpis">
            <div class="kpi"><b>+10–20%</b> conversion</div>
            <div class="kpi"><b>−15–25%</b> cost per gift</div>
            <div class="kpi"><b>Same-day</b> anomaly detection</div>
            <div class="kpi"><b>2–4 hrs/week</b> saved per team</div>
          </div>
        </article>
      </div>
    </section>

    <!-- Community -->
    <section id="community">
      <h2>Join the Community</h2>
      <p class="muted">Want closer, real-time conversation and quick feedback? Join us on Discord.</p>
      <div class="cta-row">
        <a class="btn btn--primary" href="https://discord.gg/yourInviteCode" target="_blank" rel="noopener">Join our Discord ↗</a>
      </div>
      <p class="muted" style="margin-top:.5rem">Note: Discord is great for real-time chat, but it isn’t end-to-end encrypted. For sensitive topics, contact us directly.</p>
    </section>

    <!-- Start here -->
    <section id="start">
      <h2>Start Here</h2>
      <div class="cta-row">
        <a class="btn" href="/playbook/">Open the YC Startup Playbook →</a>
        <a class="btn" href="/videos/">Browse Videos (Upskill quickly) →</a>
        <a class="btn" href="/blog/">Read the latest on the Blog →</a>
      </div>
    </section>

    <!-- Location (mid-page, not buried) -->
    <section id="location">
      <h2>Based in Seattle, WA</h2>
      <div class="map-box">
        <iframe
          title="Map: Seattle, WA"
          src="https://www.openstreetmap.org/export/embed.html?bbox=-122.4594%2C47.495%2C-122.224%2C47.734&layer=mapnik&marker=47.6062%2C-122.3321"
          loading="lazy" allowfullscreen></iframe>
      </div>
      <p class="muted" style="margin-top:.4rem;"><a href="https://www.openstreetmap.org/?mlat=47.6062&mlon=-122.3321#map=12/47.6062/-122.3321" target="_blank" rel="noopener">Open full map ↗</a></p>
    </section>

  </div>
</section>
