---
layout: home
title: SDET for Python Automation and Network Validation
description: SDET portfolio focused on Python automation, network systems validation, and QA tooling.
ticket_id: QA-PORT-001
ticket_type: Sanity Suite
status: In Progress
priority: High
component: Public Portfolio
owner: Tuan Wang
review_target: Hiring manager first pass
summary: SDET focused on Python automation, network systems validation, and QA tooling for teams that need repeatable release confidence.
objective: This site acts like a hiring sanity suite. It verifies role fit, hard-skill evidence, project judgment, written communication, and contact readiness without forcing a recruiter to decode a generic portfolio.
acceptance_criteria:
  - Role scope is obvious from the landing view.
  - Experience evidence includes measurable automation and validation work.
  - A project case study shows architecture, testing approach, and outcome.
  - Writing samples establish technical communication discipline.
  - Contact options are visible without digging.
  - Printable resume path exists for recruiter handoff.
execution_notes:
  - Styled closer to an editorial knowledge base than a generic developer template.
  - Jira and QA language is used deliberately so the site feels native to test engineering work.
  - Open placeholders are surfaced honestly as pending items rather than hidden behind fake links.
suite_links:
  - label: Resume Verification
    url: /resume/
    status: Pass
  - label: Project Evidence
    url: /projects/
    status: Pass
  - label: Writing Log
    url: /blog/
    status: Baseline
  - label: Contact Paths
    url: /contact/
    status: Needs Input
  - label: Printable Resume
    url: /resume-text/
    status: Pass
---
<section class="suite-section">
  <div class="section-heading">
    <p class="eyebrow">Recruiter Scan Path</p>
    <h2>Target role, proof, and next action in one pass</h2>
    <p>Current job search favors skills proof over vague branding. This page puts role fit first, then backs it with measurable automation work and project evidence.</p>
  </div>

  <div class="matrix-grid">
    <article class="matrix-card">
      <h3>Target role</h3>
      <p>SDET, QA Automation Engineer, or test-focused software engineer working near networking, infrastructure, systems, or release reliability.</p>
    </article>

    <article class="matrix-card">
      <h3>Core proof</h3>
      <p>100+ Python automation scripts, 600+ refactored tests, 3 internal QA tools, and networking validation experience across packet capture and control workflows.</p>
    </article>

    <article class="matrix-card">
      <h3>Best next click</h3>
      <p>Use Resume Verification for fast screening, Project Evidence for technical depth, or Printable Resume for handoff.</p>
    </article>
  </div>
</section>

<section class="suite-section">
  <div class="section-heading">
    <p class="eyebrow">Coverage Map</p>
    <h2>Sanity checks in scope</h2>
    <p>Use the site like a test run. Each section has a single job: verify one dimension of engineering signal and make that evidence easy to inspect.</p>
  </div>

  <div class="step-list">
    <article class="step-card">
      <div class="step-card__meta">
        <span>Step 01</span>
        <span class="status-pill status-pill--pass">Pass</span>
      </div>
      <h3><a href="{{ '/resume/' | relative_url }}">Verify experience record demonstrates SDET ownership and measurable execution.</a></h3>
      <p>Confirms role focus, automation volume, networking context, internal tooling work, and academic credentials in one structured review.</p>
    </article>

    <article class="step-card">
      <div class="step-card__meta">
        <span>Step 02</span>
        <span class="status-pill status-pill--pass">Pass</span>
      </div>
      <h3><a href="{{ '/projects/' | relative_url }}">Verify project evidence shows systems thinking, not just feature output.</a></h3>
      <p>The featured case study is framed around operational need, architecture, validation approach, and observed impact.</p>
    </article>

    <article class="step-card">
      <div class="step-card__meta">
        <span>Step 03</span>
        <span class="status-pill status-pill--baseline">Baseline</span>
      </div>
      <h3><a href="{{ '/blog/' | relative_url }}">Verify public writing exists and maps to automation, networking, and reliability themes.</a></h3>
      <p>The blog is intentionally early-stage, but it establishes a publishing lane for implementation notes and engineering retrospectives.</p>
    </article>

    <article class="step-card">
      <div class="step-card__meta">
        <span>Step 04</span>
        <span class="status-pill status-pill--needs-input">Needs Input</span>
      </div>
      <h3><a href="{{ '/contact/' | relative_url }}">Verify outreach paths exist, and flag the remaining profile links that still need user input.</a></h3>
      <p>Email and GitHub are ready now. LinkedIn and scheduling links are left as explicit follow-up items instead of broken placeholders.</p>
    </article>
  </div>
</section>

<section class="suite-section">
  <div class="section-heading">
    <p class="eyebrow">Observed Signals</p>
    <h2>Fast proof for a five-minute review</h2>
    <p>If the goal is quick signal extraction, these are the numbers and credentials worth seeing before deeper inspection.</p>
  </div>

  <div class="metric-grid">
    <article class="metric-card">
      <div class="metric-card__label">Automation Scope</div>
      <div class="metric-card__value">100+</div>
      <p>Python automation scripts built to increase coverage, reliability, and repeatability.</p>
    </article>

    <article class="metric-card">
      <div class="metric-card__label">Refactoring Reach</div>
      <div class="metric-card__value">600+</div>
      <p>Automated test cases reworked to improve maintainability and reduce redundant logic.</p>
    </article>

    <article class="metric-card">
      <div class="metric-card__label">Internal Tools</div>
      <div class="metric-card__value">3</div>
      <p>QA web applications built to streamline traffic generation, reporting, and system health checks.</p>
    </article>

    <article class="metric-card">
      <div class="metric-card__label">Credential Signal</div>
      <div class="metric-card__value">CCNA</div>
      <p>Networking fundamentals backed by certification and reinforced by product validation work.</p>
    </article>
  </div>
</section>

<section class="suite-section">
  <div class="section-heading">
    <p class="eyebrow">Execution Context</p>
    <h2>Primary validation areas</h2>
    <p>The work here is centered on test engineering that sits close to systems behavior, release reliability, and operator tooling.</p>
  </div>

  <div class="tag-grid">
    <section class="tag-cluster">
      <h3>Focus areas</h3>
      <div class="tag-list">
        <span class="tag">Python automation</span>
        <span class="tag">Network validation</span>
        <span class="tag">Synthetic traffic</span>
        <span class="tag">CI and release health</span>
        <span class="tag">QA tooling</span>
        <span class="tag">Reliability workflows</span>
      </div>
    </section>

    <section class="tag-cluster">
      <h3>Working stack</h3>
      <div class="tag-list">
        <span class="tag">Python</span>
        <span class="tag">Flask</span>
        <span class="tag">SQLite</span>
        <span class="tag">Gunicorn</span>
        <span class="tag">AWS</span>
        <span class="tag">RabbitMQ</span>
        <span class="tag">GitHub Actions</span>
        <span class="tag">Docker</span>
      </div>
    </section>
  </div>
</section>

<section class="suite-section">
  <div class="summary-band">
    <div class="summary-band__item">
      <span class="summary-band__label eyebrow">Current state</span>
      <span class="summary-band__value">Core portfolio path is working and presentable.</span>
    </div>
    <div class="summary-band__item">
      <span class="summary-band__label eyebrow">Main next fix</span>
      <span class="summary-band__value">Replace pending LinkedIn and scheduling placeholders with final URLs.</span>
    </div>
    <div class="summary-band__item">
      <span class="summary-band__label eyebrow">Best review order</span>
      <span class="summary-band__value">Resume -> Projects -> Blog -> Contact</span>
    </div>
  </div>
</section>
