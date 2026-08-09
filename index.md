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
        <a class="button button-secondary" href="#admin-workflow">Jump to admin workflow</a>
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
    <a class="role-link" href="#admin-workflow">
      <span class="role-link-copy">
        <strong>Admin</strong>
        <span>Add or remove officers and admins</span>
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
    <a class="button button-secondary" href="#admin-workflow">Admin workflow ↓</a>
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
        <h3>Select Incident</h3>
        <p>Select an incident from the list displayed at the bottom-left of the dashboard. For this demonstration, we will use the SVC 93 incident at Lor Ah Soo.</p>
      </div>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 3</span>
        <h3>Review Incident</h3>
        <p>Click “Review” to examine the incident details. Photos submitted by bus captains may also be available, providing operators with a clearer understanding of the situation.</p>
      </div>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 4</span>
        <h3>Decision Settings</h3>
        <p>Configure the notification settings to alert affected passengers and the next bus captain approaching the incident area.</p>
      </div>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 5</span>
        <h3>AI route comparison</h3>
        <p>Review the AI-generated diversion route and make adjustments where necessary. Operators can modify the proposed route or add custom waypoints to better suit operational requirements.</p>
      </div>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 6</span>
        <h3>Review Directions</h3>
        <p>Review the proposed directions and confirm that the diversion route is suitable before proceeding.</p>
      </div>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 7</span>
        <h3>Check Affected Bus</h3>
        <p>Review the bus services affected by the disruption and notify the relevant bus captains of the approved diversion.</p>
      </div>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 8</span>
        <h3>Approval</h3>
        <p>Review the diversion summary and approve the confirmed route. Once approved, the system will automatically send the relevant notifications through the designated Telegram channel: <code>https://t.me/busreroute_huawei_hackathon</code>.</p>
      </div>
    </article>
  </div>
</section>

<section class="section" id="admin-workflow" aria-labelledby="admin-title">
  <div class="section-heading">
    <div>
      <span class="workflow-kicker">Admin</span>
      <h2 id="admin-title">Admin workflow</h2>
      <p>Use the admin account to manage access for officers and admins, including creating new users and removing existing ones when needed.</p>
    </div>
    <a class="button button-secondary" href="#officer-workflow">Back to officer workflow ↑</a>
  </div>

  <div class="workflow-list">
    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 1</span>
        <h3>Sign in as admin</h3>
        <p>Open TransitOps and sign in with <code>admin@officer.com</code> and password <code>12345678</code>. The admin dashboard opens to the access management area.</p>
      </div>
      <figure class="screenshot-slot screenshot-image">
        <img src="{{ '/assets/admin1.png' | relative_url }}" alt="Admin sign in screen" />
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 2</span>
        <h3>Add a user</h3>
        <p>Open the user management panel and choose whether to add an admin or an officer. Enter the user details, assign the correct role, and confirm the new account.</p>
      </div>
      <figure class="screenshot-slot screenshot-image">
        <img src="{{ '/assets/admin2.png' | relative_url }}" alt="Admin user management screen" />
        <img src="{{ '/assets/admin3.png' | relative_url }}" alt="Admin user creation screen" />
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 3</span>
        <h3>Remove a user</h3>
        <p>Select the existing admin or officer account you want to remove, review the account details, and confirm the deletion or deactivation action.</p>
      </div>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 4</span>
        <h3>Verify access changes</h3>
        <p>Check that the user list reflects the updated roles and that the removed account no longer has access. Once confirmed, sign out if you are done managing users.</p>
      </div>
    </article>
  </div>
</section>
