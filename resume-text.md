---
layout: page
title: Printable Resume
permalink: /resume-text/
ticket_id: QA-RES-PRINT
ticket_type: Recruiter Handoff
status: Pass
priority: High
component: One-Page Resume
owner: Tuan Wang
review_target: ATS copy, recruiter handoff, and browser print
summary: Compact resume version optimized for printing, copying, and quick recruiter review.
objective: Provide a plain, structured resume route that keeps the portfolio theme but remains easy to print or hand off.
checks:
  - Verify target role and contact information appear first.
  - Confirm experience bullets include measurable outcomes.
  - Confirm skills are grouped by screening category.
evidence:
  - One-page web resume route exists.
  - Print CSS removes navigation and visual chrome.
---
<section class="resume-document">
  <section>
    <h2>Tuan Wang</h2>
    <p>SDET | Python Automation | Network Systems Validation | QA Tooling</p>
    <p>San Jose, CA | <a href="mailto:tuanwang1@gmail.com">tuanwang1@gmail.com</a> | <a href="https://github.com/tuanwang1">github.com/tuanwang1</a></p>
  </section>

  <section>
    <h2>Summary</h2>
    <p>SDET with experience building Python automation, validating network systems, refactoring large automated test suites, and shipping internal QA tools that reduce manual validation overhead.</p>
  </section>

  <section>
    <h2>Experience</h2>
    <h3>cPacket Networks Inc. | Software Development Engineer in Test | Sept 2022 - Jan 2025</h3>
    <ul>
      <li>Built 100+ Python automation scripts to improve validation coverage, repeatability, and release confidence.</li>
      <li>Refactored 600+ automated test cases using shared inheritance patterns to reduce duplicated logic and improve maintainability.</li>
      <li>Built internal QA web tools with Flask, SQLite, Gunicorn, JavaScript, and Ajax for traffic generation, reporting, and system health monitoring.</li>
      <li>Validated packet capture appliances, network brokers, APIs, migration workflows, monitoring behavior, and PCAP-based scenarios.</li>
    </ul>

    <h3>Computer Science Teaching Assistant | Aug 2019 - May 2022</h3>
    <ul>
      <li>Supported labs in operating systems, architecture, security, networking, and algorithms.</li>
      <li>Explained technical concepts, debugged student work, and adapted support for hybrid teaching models.</li>
    </ul>
  </section>

  <section>
    <h2>Project Evidence</h2>
    <h3>Groundhog | Synthetic Network Traffic Generator</h3>
    <ul>
      <li>Built AWS-backed traffic generation workflows using RabbitMQ and Python automation.</li>
      <li>Supported realistic validation scenarios for load balancers and inline traffic paths.</li>
      <li>Placed 3rd out of 20+ teams in an internal company competition.</li>
    </ul>
  </section>

  <section>
    <h2>Skills</h2>
    <p><strong>Automation:</strong> Python, Selenium, pandas, NumPy, Bash, test refactoring, scenario design</p>
    <p><strong>Networking:</strong> Ethernet, IXIA, tcpreplay, Wireshark, packet capture, PCAP workflows, CCNA</p>
    <p><strong>Tooling:</strong> Flask, SQLite, Gunicorn, JavaScript, jQuery, Ajax, RabbitMQ</p>
    <p><strong>Infra:</strong> AWS, Azure, Docker, Terraform, GitHub Actions, Jenkins</p>
  </section>

  <section>
    <h2>Education</h2>
    <p>Santa Clara University | M.S. Computer Science | Sept 2025 - Spring 2027</p>
    <p>Colgate University | B.A. Computer Science | Aug 2018 - May 2022</p>
  </section>
</section>
