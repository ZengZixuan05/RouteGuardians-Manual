---
title: RouteGuardians Manual
description: TransitOps Judge Walkthrough
layout: default
header_subtitle: TransitOps Operations Officer Walkthrough
guide_label: Operations workflow
---

<section class="hero">
  <div class="hero-grid">
    <div>
      <div class="eyebrow">Operations manual</div>
      <h1>TransitOps Judge Walkthrough</h1>
      <p class="lead">
        Follow the Operations Officer workflow to review an incident, compare diversion
        options, approve the route, and dispatch notifications. Follow the Admin workflow to add or remove admin, operations officer.
      </p>
      <div class="tag-row" style="margin-top: 22px;">
        <span class="tag">Incident review</span>
        <span class="tag">Route comparison</span>
        <span class="tag">Dispatch approval</span>
      </div>
      <div class="hero-actions">
        <a class="button" href="#officer-workflow">Start officer workflow <span aria-hidden="true">↓</span></a>
        <a class="button button-secondary" href="#driver-workflow">Jump to driver placeholder</a>
      </div>
    </div>

    <aside class="card quickfacts" aria-label="Operations demo credentials">
      <div class="quickfact">
        <small>Test account</small>
        <div class="credential-lines">
          <div class="credential-line">
            <span>Email</span>
            <code>officer@officer.com</code>
          </div>
          <div class="credential-line">
            <span>Password</span>
            <code>12345678</code>
          </div>
        </div>
      </div>
      <div class="quickfact">
        <small>Admin account</small>
        <div class="credential-lines">
          <div class="credential-line">
            <span>Email</span>
            <code>admin@officer.com</code>
          </div>
          <div class="credential-line">
            <span>Password</span>
            <code>12345678</code>
          </div>
        </div>
      </div>
      <div class="quickfact">
        <small>Sample incident</small>
        <strong>SVC 93 accident at Lor Ah Soo (Upp Paya Lebar Rd)</strong>
      </div>
    </aside>
  </div>
</section>

<section class="section" aria-labelledby="choose-workflow">
  <h2 id="choose-workflow">Choose a workflow</h2>
  <p>Open the TransitOps web guide, then choose the section you want to follow.</p>
  <div class="role-links">
    <a class="role-link" href="#officer-workflow">
      <span class="role-link-copy">
        <strong>Operations Officer</strong>
        <span>Review incidents, compare routes, and approve a diversion.</span>
      </span>
      <b aria-hidden="true">→</b>
    </a>
    <a class="role-link" href="#driver-workflow">
      <span class="role-link-copy">
        <strong>Officer Admin</strong>
        <span>Add and remove Officer and Admin</span>
      </span>
      <b aria-hidden="true">→</b>
    </a>
  </div>
  <div class="callout">
    <strong>Demo note</strong>
    <span class="muted">The officer workflow uses the SVC 93 accident as the sample incident.</span>
  </div>
</section>

<section class="section" id="officer-workflow" aria-labelledby="officer-title">
  <div class="section-heading">
    <div>
      <span class="workflow-kicker">Operations officer</span>
      <h2 id="officer-title">Officer workflow</h2>
      <p>Use the operations officer account to review the incident feed, examine the SVC 93 accident, and complete the diversion approval flow.</p>
    </div>
    <a class="button button-secondary" href="#driver-workflow">Driver placeholder ↓</a>
  </div>

  <div class="workflow-list">
    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 1</span>
        <h3>Open the app and sign in</h3>
        <p>Launch TransitOps and sign in with <code>officer@officer.com</code> and password <code>12345678</code>. The app opens to the incident feed.</p>
      </div>
      <figure class="screenshot-slot screenshot-image">
        <img src="{{ '/assets/ss1.png' | relative_url }}" alt="Sample incident screenshot showing the SVC 93 accident at Lor Ah Soo" />
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 2</span>
        <h3>Review the incident feed</h3>
        <p>Select an incident from the list displayed at the bottom-left of the dashboard. For this demonstration, we will use the SVC 93 incident at Lor Ah Soo.</p>
      </div>
      <figure class="screenshot-slot">
        <img src="{{ '/assets/ss1.png' | relative_url }}" alt="Sample incident screenshot showing the SVC 93 accident at Lor Ah Soo" />
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 3</span>
        <h3>Select the incident</h3>
        <p>Click “Review” to examine the incident details. Photos submitted by bus captains may also be available, providing operators with a clearer understanding of the situation.</p>
      </div>
      <figure class="screenshot-slot">
        <figcaption>
          <span class="phone-mark" aria-hidden="true"></span>
          <strong>Screenshot: Incident summary</strong>
          <span>Show the incident summary after tapping the live card.</span>
        </figcaption>
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 4</span>
        <h3>Review the incident details</h3>
        <p>Configure the notification settings to alert affected passengers and the next bus captain approaching the incident area.</p>
      </div>
      <figure class="screenshot-slot">
        <figcaption>
          <span class="phone-mark" aria-hidden="true"></span>
          <strong>Screenshot: Review screen</strong>
          <span>Show the review screen before route decisions are made.</span>
        </figcaption>
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 5</span>
        <h3>Open decision settings</h3>
        <p>Review the AI-generated diversion route and make adjustments where necessary. Operators can modify the proposed route or add custom waypoints to better suit operational requirements.</p>
      </div>
      <figure class="screenshot-slot">
        <figcaption>
          <span class="phone-mark" aria-hidden="true"></span>
          <strong>Screenshot: Decision settings</strong>
          <span>Show the control page used before comparing routes.</span>
        </figcaption>
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 6</span>
        <h3>Compare route options</h3>
        <p>Review the proposed directions and confirm that the diversion route is suitable before proceeding.</p>
      </div>
      <figure class="screenshot-slot">
        <figcaption>
          <span class="phone-mark" aria-hidden="true"></span>
          <strong>Screenshot: Route comparison</strong>
          <span>Show the route options and any AI-generated route cards.</span>
        </figcaption>
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 7</span>
        <h3>Review the final directions</h3>
        <p>Review the bus services affected by the disruption and notify the relevant bus captains of the approved diversion.</p>
      </div>
      <figure class="screenshot-slot">
        <figcaption>
          <span class="phone-mark" aria-hidden="true"></span>
          <strong>Screenshot: Final directions</strong>
          <span>Show the confirmed route before checking bus impact.</span>
        </figcaption>
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 8</span>
        <h3>Check affected buses</h3>
        <p>Review the diversion summary and approve the confirmed route. Once approved, the system will automatically send the relevant notifications through the designated Telegram channel: <code>https://t.me/busreroute_huawei_hackathon</code>.</p>
      </div>
      <figure class="screenshot-slot">
        <figcaption>
          <span class="phone-mark" aria-hidden="true"></span>
          <strong>Screenshot: Affected buses</strong>
          <span>Show the affected-service list before approval.</span>
        </figcaption>
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 9</span>
        <h3>Approve the diversion</h3>
        <p>Review the diversion summary and approve the confirmed route.</p>
      </div>
      <figure class="screenshot-slot">
        <figcaption>
          <span class="phone-mark" aria-hidden="true"></span>
          <strong>Screenshot: Approval screen</strong>
          <span>Show the final approval page before dispatch.</span>
        </figcaption>
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 10</span>
        <h3>Dispatch notifications</h3>
        <p>Once approved, the system will automatically send the relevant notifications through the designated Telegram channel.</p>
      </div>
      <figure class="screenshot-slot">
        <figcaption>
          <span class="phone-mark" aria-hidden="true"></span>
          <strong>Screenshot: Dispatched status</strong>
          <span>Show the incident after dispatch notifications are sent.</span>
        </figcaption>
      </figure>
    </article>
  </div>
</section>

<section class="section" id="driver-workflow" aria-labelledby="driver-title">
  <div class="section-heading">
    <div>
      <span class="workflow-kicker">Bus driver</span>
      <h2 id="driver-title">Driver workflow placeholder</h2>
      <p>This section is a placeholder for now. We can replace it with the real Bus Driver manual later.</p>
    </div>
    <a class="button button-secondary" href="#officer-workflow">Back to officer workflow ↑</a>
  </div>

  <div class="workflow-list">
    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 1</span>
        <h3>Open the driver view</h3>
        <p>Placeholder content for the Bus Driver manual.</p>
      </div>
      <figure class="screenshot-slot">
        <figcaption>
          <span class="phone-mark" aria-hidden="true"></span>
          <strong>Screenshot placeholder</strong>
          <span>Replace this with the driver sign-in or home screen later.</span>
        </figcaption>
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 2</span>
        <h3>Receive the diversion notice</h3>
        <p>Placeholder content for the Bus Driver manual.</p>
      </div>
      <figure class="screenshot-slot">
        <figcaption>
          <span class="phone-mark" aria-hidden="true"></span>
          <strong>Screenshot placeholder</strong>
          <span>Replace this with the route alert or notification view later.</span>
        </figcaption>
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 3</span>
        <h3>Confirm the updated route</h3>
        <p>Placeholder content for the Bus Driver manual.</p>
      </div>
      <figure class="screenshot-slot">
        <figcaption>
          <span class="phone-mark" aria-hidden="true"></span>
          <strong>Screenshot placeholder</strong>
          <span>Replace this with the confirmed route screen later.</span>
        </figcaption>
      </figure>
    </article>
  </div>
</section>
