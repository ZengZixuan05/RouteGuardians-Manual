---
title: RouteGuardians Manual
description: TransitOps Judge Walkthrough
layout: default
---

<section class="hero">
  <div class="hero-grid">
    <div>
      <div class="eyebrow">Operations manual</div>
      <h1>TransitOps Judge Walkthrough</h1>
      <p class="lead">
        Use this guide when testing the prototype. It is written as a click-by-click
        walkthrough for the operations officer flow only.
      </p>
      <div class="tag-row" style="margin-top: 22px;">
        <span class="tag">Incident review</span>
        <span class="tag">Route comparison</span>
        <span class="tag">Dispatch approval</span>
      </div>
      <div class="hero-actions">
        <a class="button" href="{{ '/android-app/' | relative_url }}">Open Android app guide <span aria-hidden="true">→</span></a>
        <span class="action-note">Guest and administrator credentials included</span>
      </div>
    </div>

    <aside class="card quickfacts">
      <div class="quickfact">
        <small>Test account</small>
        <strong>officer@officer.com<br />password: 12345678</strong>
      </div>
      <div class="quickfact">
        <small>Admin account</small>
        <strong>admin@officer.com<br />password: 12345678</strong>
      </div>
      <div class="quickfact">
        <small>Sample incident</small>
        <strong>Bras Basah Road blockage near the National Museum of Singapore</strong>
      </div>
    </aside>
  </div>
</section>

<section class="section">
  <h2>What The Prototype Shows</h2>
  <p>TransitOps simulates an operations response workflow.</p>
  <ol class="timeline">
    <li class="step">
      <strong>Review the incident</strong>
      <p>The officer opens the active incident and checks the live context.</p>
    </li>
    <li class="step">
      <strong>Compare diversion options</strong>
      <p>The officer looks at route choices and checks delay, feasibility, and impact.</p>
    </li>
    <li class="step">
      <strong>Approve and dispatch</strong>
      <p>The officer confirms the route and sends notifications to the relevant teams.</p>
    </li>
  </ol>
</section>

<section class="section grid-2">
  <div>
    <h2>Recommended Test Path</h2>
    <p>
      This manual covers only the officer workflow. The sample incident is already
      available in the prototype, so you can start from the officer dashboard.
    </p>
    <div class="callout">
      <strong>Good to know</strong>
      <span class="muted">The default scenario is designed to be simple to reproduce during judging or demos.</span>
    </div>
  </div>

  <div>
    <h2>Test Scenario</h2>
    <ul>
      <li>Road blockage on Bras Basah Road near the National Museum of Singapore</li>
      <li>Bus service 14</li>
      <li>High severity</li>
      <li>41 passengers onboard</li>
    </ul>
  </div>
</section>

<section class="section">
  <h2>Walkthrough</h2>
  <div class="timeline">
    <div class="step">
      <strong>1. Open the app</strong>
      <p>You should see a sign in page for Operations Officer. Sign in with either of these accounts below.</p>
    </div>
    <div class="step">
      <strong>2. Overview of Incident Feed</strong>
      <p>The command centre is showing live incident context. You can switch between active and historical incidents if available.</p>
    </div>
    <div class="step">
      <strong>3. Select Incident</strong>
      <p>You see the incident summary, plus location, service, severity, and live map context.</p>
    </div>
    <div class="step">
      <strong>4. Review Incident</strong>
      <p>Go to <code>Review</code>. More details will be shown. If the incident report was written in another language, translate it into English.</p>
    </div>
    <div class="step">
      <strong>5. Decision Settings</strong>
      <p>Go to <code>Decision Settings</code>.</p>
    </div>
    <div class="step">
      <strong>6. Compare routes</strong>
      <p>Go to <code>AI Route Comparison</code>. One or more route options should appear, and you can compare delay and feasibility. You can also create a custom route or edit the AI-generated route.</p>
    </div>
    <div class="step">
      <strong>7. Review Directions</strong>
      <p>This gives a final overview of the confirmed route.</p>
    </div>
    <div class="step">
      <strong>8. Check affected buses</strong>
      <p>Go to <code>Check Affected Buses</code>. The system scans for services near the incident and shows affected buses that can be notified.</p>
    </div>
    <div class="step">
      <strong>9. Approve the diversion</strong>
      <p>Go to <code>Proceed to Approval</code>. The incident summary and selected diversion are shown. You can approve or reject the route.</p>
    </div>
    <div class="step">
      <strong>10. Dispatch notifications</strong>
      <p>The bus captain will be notified about the reroute. Passengers will be notified via Telegram, and the incident is marked as dispatched.</p>
    </div>
  </div>
</section>

<section class="section">
  <h2>Optional Screens</h2>
  <ul>
    <li><code>Historical Reports</code></li>
    <li><code>User Management</code> if the officer is an admin. Admin can add users.</li>
  </ul>
</section>
