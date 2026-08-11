---
title: Web Dashboard Guide
description: TransitOps Operations Officer incident review, diversion approval, and administration workflows
layout: default
permalink: /web-dashboard/
header_subtitle: TransitOps Operations Officer Walkthrough
guide_label: Step 2 - Operations Officer
---

<section class="hero">
  <div class="hero-grid">
    <div>
      <div class="eyebrow">Step 2 - Operations Officer</div>
      <h1>TransitOps Operations Officer Guide</h1>
      <p class="lead">
        Continue here after a Bus Captain has submitted an incident through either Step 1 mobile app.
        Follow the Operations Officer workflow to review the report, compare diversion options,
        approve the route, and dispatch notifications. Use the Admin workflow separately to manage dashboard users.
      </p>
      <p class="dashboard-access">
        <strong>Live web dashboard:</strong>
        <a
          class="text-link"
          href="https://huawei-hackathon26.vercel.app"
          target="_blank"
          rel="noopener noreferrer"
        >huawei-hackathon26.vercel.app <span aria-hidden="true">&nearr;</span></a>
      </p>
      <div class="tag-row" style="margin-top: 22px;">
        <span class="tag">Incident review</span>
        <span class="tag">Route comparison</span>
        <span class="tag">Dispatch approval</span>
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

<section class="section" aria-labelledby="prerequisite-title">
  <span class="workflow-kicker">Before you begin</span>
  <h2 id="prerequisite-title">Create the incident in a Step 1 mobile app first</h2>
  <p>The dashboard is the second part of the demonstration. Sign in as Guest / Bus Captain in either the Android app or the iOS web app, submit the prepared SVC 93 incident, and then locate that report in the active incident feed.</p>
  <div class="callout">
    <strong>Need to create the report?</strong>
    <span class="muted"><a class="text-link" href="{{ '/android-app/' | relative_url }}#guest-workflow">Open the Android Bus Captain workflow</a> or <a class="text-link" href="{{ '/ios-web-app/' | relative_url }}#captain-workflow">open the iOS web app captain workflow</a>, submit the report, and then return to this page.</span>
  </div>
</section>

<section class="section" aria-labelledby="choose-workflow">
  <h2 id="choose-workflow">Web dashboard roles</h2>
  <p>Use Operations Officer for incident review and routing. Use Admin only when you need to add or remove dashboard users.</p>
  <div class="role-links">
    <a class="role-link" href="#officer-workflow">
      <span class="role-link-copy">
        <strong>Operations Officer</strong>
        <span>Review incidents, compare routes, and approve a diversion.</span>
      </span>
      <b aria-hidden="true">&rarr;</b>
    </a>
    <a class="role-link" href="#admin-workflow">
      <span class="role-link-copy">
        <strong>Admin</strong>
        <span>Add or remove officers and administrators.</span>
      </span>
      <b aria-hidden="true">&rarr;</b>
    </a>
  </div>
  <div class="callout">
    <strong>Demo note</strong>
    <span class="muted">The officer workflow uses the SVC 93 accident submitted from either Step 1 mobile app.</span>
  </div>
</section>

<section class="section" id="officer-workflow" aria-labelledby="officer-title">
  <div class="section-heading">
    <div>
      <span class="workflow-kicker">Operations officer</span>
      <h2 id="officer-title">Officer workflow</h2>
      <p>Use the Operations Officer account to review the incident feed, examine the submitted SVC 93 accident, and complete the diversion approval flow.</p>
    </div>
    <a class="workflow-jump" href="#admin-workflow">Go to admin workflow &darr;</a>
  </div>

  <div class="workflow-list">
    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 1</span>
        <h3>Open the web dashboard and sign in</h3>
        <p>Open TransitOps in the browser and sign in with <code>officer@officer.com</code> and password <code>12345678</code>. The dashboard opens to the incident feed.</p>
      </div>
      <figure class="screenshot-slot screenshot-image">
        <img src="{{ '/assets/ss1.png' | relative_url }}" alt="Sample incident screenshot showing the SVC 93 accident at Lor Ah Soo" />
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 2</span>
        <h3>Select the submitted incident</h3>
        <p>Select an incident from the list at the bottom-left of the dashboard. For this demonstration, choose the SVC 93 incident at Lor Ah Soo that was submitted through Android or the iOS web app.</p>
      </div>
      <figure class="screenshot-slot screenshot-image">
        <img src="{{ '/assets/ss2.png' | relative_url }}" alt="Operations Officer dashboard showing the submitted incident selected from the feed" loading="lazy" />
      </figure>
    </article>

    <article class="workflow-step workflow-step-stack">
      <div class="workflow-copy">
        <span class="step-label">Step 3</span>
        <h3>Review the incident</h3>
        <p>Click <strong>Review</strong> to examine the incident details. Review the photos submitted by the Bus Captain and confirm that they match the reported situation.</p>
      </div>
      <figure class="screenshot-slot screenshot-image screenshot-stack">
        <img src="{{ '/assets/ss3.png' | relative_url }}" alt="Operations Officer review screen showing incident details and route information" loading="lazy" />
        <img src="{{ '/assets/ss4.png' | relative_url }}" alt="Operations Officer review screen showing the second supporting screenshot for the incident review" loading="lazy" />
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 4</span>
        <h3>Configure decision settings</h3>
        <p>Configure the notification settings for affected passengers and the next Bus Captain approaching the incident area.</p>
      </div>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 5</span>
        <h3>Compare AI routes</h3>
        <p>Review the AI-generated diversion route and make adjustments where necessary. You can modify the proposed route or add custom waypoints to better suit operational requirements.</p>
      </div>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 6</span>
        <h3>Review directions</h3>
        <p>Review the proposed directions and confirm that the diversion route is suitable before proceeding.</p>
      </div>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 7</span>
        <h3>Check affected buses</h3>
        <p>Review the bus services affected by the disruption and notify the relevant Bus Captains of the approved diversion.</p>
      </div>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 8</span>
        <h3>Approve and dispatch</h3>
        <p>Review the diversion summary and approve the confirmed route. The system notifies the Bus Captain and sends passenger notifications through the designated Telegram channel: <code>https://t.me/busreroute_huawei_hackathon</code>.</p>
      </div>
    </article>
  </div>
</section>

<section class="section" id="admin-workflow" aria-labelledby="admin-title">
  <div class="section-heading">
    <div>
      <span class="workflow-kicker">Admin</span>
      <h2 id="admin-title">Admin workflow</h2>
      <p>Use the dashboard Admin account to manage access for officers and administrators, including creating new users and removing existing ones.</p>
    </div>
    <a class="workflow-jump" href="#officer-workflow">Return to officer workflow &uarr;</a>
  </div>

  <div class="workflow-list">
    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 1</span>
        <h3>Sign in as Admin</h3>
        <p>Open TransitOps in the browser and sign in with <code>admin@officer.com</code> and password <code>12345678</code>. The dashboard opens to the access-management area.</p>
      </div>
      <figure class="screenshot-slot screenshot-image">
        <img src="{{ '/assets/admin1.png' | relative_url }}" alt="Admin sign-in screen" />
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 2</span>
        <h3>Add a user</h3>
        <p>Open the user-management panel and choose whether to add an administrator or an officer. Enter the user details, assign the correct role, and confirm the new account.</p>
      </div>
      <figure class="screenshot-slot screenshot-image">
        <img src="{{ '/assets/admin2.png' | relative_url }}" alt="Admin user-management screen" />
        <img src="{{ '/assets/admin3.png' | relative_url }}" alt="Admin user-creation screen" />
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 3</span>
        <h3>Remove a user</h3>
        <p>Select the existing administrator or officer account you want to remove, review the account details, and confirm the deletion or deactivation action.</p>
      </div>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 4</span>
        <h3>Verify access changes</h3>
        <p>Check that the user list reflects the updated roles and that the removed account no longer has access. Sign out when you are finished managing users.</p>
      </div>
    </article>
  </div>
</section>

<section class="section end-nav">
  <div>
    <h2>Continue testing</h2>
    <p style="margin: 0;">After the Operations Officer approves and dispatches the route, return to the Step 1 mobile app used by the Bus Captain.</p>
  </div>
  <div class="hero-actions" style="margin-top: 0;">
    <a class="button" href="{{ '/android-app/' | relative_url }}#track-response">Return to Android Step 7 <span aria-hidden="true">&rarr;</span></a>
    <a class="button button-secondary" href="{{ '/ios-web-app/' | relative_url }}#captain-workflow">Return to iOS Step 1 guide</a>
  </div>
</section>
