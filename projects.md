---
layout: page
title: Project Evidence
permalink: /projects/
ticket_id: QA-PRJ-003
ticket_type: Case Study Review
status: Pass
priority: High
component: Public Project Record
owner: Tuan Wang
review_target: Hiring manager technical follow-up
summary: Verify that the featured public project demonstrates architecture judgment, test-driven thinking, and measurable outcome.
objective: Present one flagship project like a proper engineering case study instead of a shallow portfolio tile, with enough detail to show how the system worked and why it mattered.
checks:
  - Verify the project starts with an operational problem, not a vague demo description.
  - Confirm the architecture and technology choices are explicit.
  - Confirm validation method is described in terms of scenarios and workflows.
  - Confirm outcome is visible through placement, usefulness, or speed of execution.
evidence:
  - AWS-based traffic generation workflow
  - RabbitMQ-backed orchestration
  - Scenario-driven network testing use case
  - 3rd place finish out of 20+ teams
---
<section class="suite-section">
  <div class="section-heading">
    <p class="eyebrow">Featured Record</p>
    <h2>Groundhog | Synthetic Network Traffic Generator</h2>
    <p>The strongest public story right now is not a generic CRUD app. It is a testing utility built around realistic network validation needs.</p>
  </div>

  <div class="step-list">
    <article class="step-card">
      <div class="step-card__meta">
        <span>Step 01</span>
        <span class="status-pill status-pill--pass">Pass</span>
      </div>
      <h3>Verify the project is anchored in a real testing problem.</h3>
      <p>Groundhog was built to provide on-demand synthetic traffic generation for validation scenarios where realistic traffic patterns are required before release or troubleshooting.</p>
    </article>

    <article class="step-card">
      <div class="step-card__meta">
        <span>Step 02</span>
        <span class="status-pill status-pill--pass">Pass</span>
      </div>
      <h3>Confirm the architecture reflects system-thinking, not just UI polish.</h3>
      <p>The project combined AWS infrastructure, RabbitMQ, and Python automation flows to queue, trigger, and manage traffic-generation tasks across multiple scenarios.</p>
    </article>

    <article class="step-card">
      <div class="step-card__meta">
        <span>Step 03</span>
        <span class="status-pill status-pill--pass">Pass</span>
      </div>
      <h3>Verify the validation strategy mirrors practical QA use.</h3>
      <p>The design targeted load balancer and inline-path scenarios, which made the tool useful for repeatable test setup rather than a one-off hackathon demo.</p>
    </article>

    <article class="step-card">
      <div class="step-card__meta">
        <span>Step 04</span>
        <span class="status-pill status-pill--pass">Pass</span>
      </div>
      <h3>Confirm there is a visible outcome worth mentioning.</h3>
      <p>The project placed third among more than twenty teams in an internal company competition, giving it both technical and comparative signal.</p>
    </article>
  </div>
</section>

<section class="suite-section">
  <div class="section-heading">
    <p class="eyebrow">Implementation Snapshot</p>
    <h2>Core system notes</h2>
  </div>

  <div class="tag-grid">
    <section class="tag-cluster">
      <h3>Problem framing</h3>
      <div class="tag-list">
        <span class="tag">Scenario setup friction</span>
        <span class="tag">Synthetic traffic demand</span>
        <span class="tag">Network path validation</span>
      </div>
    </section>

    <section class="tag-cluster">
      <h3>System components</h3>
      <div class="tag-list">
        <span class="tag">AWS</span>
        <span class="tag">RabbitMQ</span>
        <span class="tag">Python</span>
        <span class="tag">Automation workflows</span>
      </div>
    </section>

    <section class="tag-cluster">
      <h3>Validation targets</h3>
      <div class="tag-list">
        <span class="tag">Load balancer paths</span>
        <span class="tag">Inline traffic simulation</span>
        <span class="tag">Repeatable scenario execution</span>
      </div>
    </section>

    <section class="tag-cluster">
      <h3>Outcome</h3>
      <div class="tag-list">
        <span class="tag">Faster setup</span>
        <span class="tag">Scenario flexibility</span>
        <span class="tag">Hackathon recognition</span>
      </div>
    </section>
  </div>
</section>

<section class="suite-section">
  <div class="section-heading">
    <p class="eyebrow">Queued Follow-up</p>
    <h2>Additional public case studies to add</h2>
  </div>

  <div class="step-list">
    <article class="step-card">
      <div class="step-card__meta">
        <span>Queue 01</span>
        <span class="status-pill status-pill--queued">Queued</span>
      </div>
      <h3>Internal QA web tools</h3>
      <p>Public-safe breakdowns of the traffic generator, X-ray report generator, and system health monitor would add more evidence of tooling ownership.</p>
    </article>

    <article class="step-card">
      <div class="step-card__meta">
        <span>Queue 02</span>
        <span class="status-pill status-pill--queued">Queued</span>
      </div>
      <h3>Automation refactor work</h3>
      <p>A case study about reducing redundancy across a large test suite would show maintainability thinking and test architecture discipline.</p>
    </article>
  </div>
</section>
