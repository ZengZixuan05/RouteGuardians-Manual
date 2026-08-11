---
title: iOS Web App Guide
description: TransitOps iOS-style web app workflow, installation notes, and captain/admin navigation
layout: default
permalink: /ios-web-app/
header_subtitle: TransitOps iOS Web App Walkthrough
guide_label: Step 1 - iOS web app
---

<section class="hero">
  <div class="hero-grid">
    <div>
      <div class="eyebrow">Step 1 - iOS web app</div>
      <h1>TransitOps iOS Web App Guide</h1>
      <p class="lead">
        TransitOps Web is the iPhone-friendly Step 1 version of the Bus Captain iOS experience.
        Publishing a native iOS build through TestFlight or the App Store requires paid
        Apple Developer Program access, so this project provides a browser-based version
        that judges can open immediately on iPhone, iPad, desktop, or Android.
      </p>
      <p class="dashboard-access">
        <strong>Live web app:</strong>
        <a
          class="text-link"
          href="https://huawei-webapp.vercel.app/"
          target="_blank"
          rel="noopener noreferrer"
        >huawei-webapp.vercel.app <span aria-hidden="true">&nearr;</span></a>
      </p>
      <div class="tag-row" style="margin-top: 22px;">
        <span class="tag">iOS-style workflow</span>
        <span class="tag">Same Supabase backend</span>
        <span class="tag">Add to Home Screen</span>
      </div>
    </div>

    <aside class="card quickfacts" aria-label="iOS web app demo credentials">
      <div class="quickfact">
        <small>Guest / Bus Captain</small>
        <div class="credential-lines">
          <div class="credential-line">
            <span>Email</span>
            <code>guest@guest.com</code>
          </div>
          <div class="credential-line">
            <span>Password</span>
            <code>guest1234</code>
          </div>
        </div>
      </div>
      <div class="quickfact">
        <small>Administrator</small>
        <div class="credential-lines">
          <div class="credential-line">
            <span>Email</span>
            <code>admin@admin.com</code>
          </div>
          <div class="credential-line">
            <span>Password</span>
            <code>admin</code>
          </div>
        </div>
      </div>
    </aside>
  </div>
</section>

<section class="section" aria-labelledby="why-web-title">
  <span class="workflow-kicker">Why this exists</span>
  <h2 id="why-web-title">A web version replaces native iOS publishing</h2>
  <p>
    The original target was a native iOS Bus Captain app. For judging and public
    demonstration, distributing that native app would require paid Apple Developer
    Program access and the extra TestFlight or App Store publishing flow. To avoid
    making judges install through a gated iOS channel, TransitOps Web recreates the
    iOS captain and admin workflows in the browser.
  </p>
  <div class="callout">
    <strong>What remains the same</strong>
    <span class="muted">The web app uses the same Supabase authentication users, UUID profile linkage, database tables, Storage bucket, role routing, incident lifecycle, and captain/admin permissions as the native app workflow.</span>
  </div>
</section>

<section class="section" aria-labelledby="app-setup-title">
  <div class="section-heading">
    <div>
      <span class="workflow-kicker">Before you begin</span>
      <h2 id="app-setup-title">Open the iOS-style web app</h2>
      <p>Use the deployed HTTPS link supplied with the project. The web app can run as a normal browser tab, or it can be added to the device home screen for a more app-like launch.</p>
    </div>
  </div>

  <ol class="timeline install-steps">
    <li class="step">
      <strong>Open the deployed web address</strong>
      <p>Launch the TransitOps Web URL in Safari on iPhone/iPad, or in a current version of Chrome, Edge, or Safari on another device.</p>
    </li>
    <li class="step">
      <strong>Allow required permissions when prompted</strong>
      <p>Camera, precise location, and microphone permissions are needed only for photo capture, live route following, and voice dictation. Manual entry remains available if a permission is unavailable.</p>
    </li>
    <li class="step">
      <strong>Install it like an app if needed</strong>
      <p>On iPhone or iPad Safari, use <strong>Share</strong> then <strong>Add to Home Screen</strong>. On supported desktop or Android browsers, use the browser install option when offered.</p>
    </li>
    <li class="step">
      <strong>Use configured TransitOps accounts</strong>
      <p>For this test, sign in as Guest / Bus Captain with <code>guest@guest.com</code> and password <code>guest1234</code>, or as Administrator with <code>admin@admin.com</code> and password <code>admin</code>. A valid Supabase login must also have the matching active TransitOps profile.</p>
    </li>
  </ol>
</section>

<section class="section" aria-labelledby="choose-workflow">
  <h2 id="choose-workflow">iOS web app roles</h2>
  <p>Use Bus Captain to create and track incident reports. Use Administrator only to configure Bus Captain access.</p>
  <div class="role-links">
    <a class="role-link" href="#captain-workflow">
      <span class="role-link-copy">
        <strong>Bus Captain</strong>
        <span>Submit incidents, receive officer updates, and follow approved routes.</span>
      </span>
      <b aria-hidden="true">&rarr;</b>
    </a>
    <a class="role-link" href="#admin-workflow">
      <span class="role-link-copy">
        <strong>Administrator</strong>
        <span>Add, review, and remove configured Bus Captains.</span>
      </span>
      <b aria-hidden="true">&rarr;</b>
    </a>
  </div>
  <div class="callout">
    <strong>Screenshot note</strong>
    <span class="muted">The steps below match the manual-tab style and leave space for the screenshots you plan to add afterwards.</span>
  </div>
</section>

<section class="section" id="captain-workflow" aria-labelledby="captain-title">
  <div class="section-heading">
    <div>
      <span class="workflow-kicker">Bus Captain</span>
      <h2 id="captain-title">Captain workflow</h2>
      <p>Use the captain account to create a report, verify AI-assisted details, monitor officer messages, and open the approved diversion route.</p>
    </div>
    <a class="workflow-jump" href="#admin-workflow">Go to admin workflow &darr;</a>
  </div>

  <div class="workflow-list">
    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 1</span>
        <h3>Launch, choose language, and sign in</h3>
        <p>Open the web app. On the first visit, choose English, Chinese, Malay, or Tamil. Sign in with <code>guest@guest.com</code> and password <code>guest1234</code>; TransitOps opens <strong>My Incidents</strong> after it confirms the linked Bus Captain profile is active.</p>
      </div>
      <figure class="screenshot-slot screenshot-image">
        <img src="{{ '/assets/ios/captain/Step 1.png' | relative_url }}" alt="TransitOps iOS web app Step 1 showing the language selection and sign in screen" loading="lazy" />
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 2</span>
        <h3>Review My Incidents</h3>
        <p>The incident list shows reports from newest to oldest with the incident type, location, bus service, reported time, and current status. Select a row to open its details, or use <strong>+ Add Report</strong> to begin a new report.</p>
      </div>
      <figure class="screenshot-slot screenshot-image">
        <img src="{{ '/assets/ios/captain/Step 2.png' | relative_url }}" alt="TransitOps iOS web app Step 2 showing the My Incidents list" loading="lazy" />
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 3</span>
        <h3>Create the incident report</h3>
        <p>Choose the incident type, attach one Bus photo and one Incident photo, then tap <strong>Analyze Photos and Continue</strong>. The browser version supports live camera capture, photo-library selection, JPG/PNG file upload, and full-screen previews.</p>
        <p>If photos cannot be used, choose <strong>Enter Details Manually</strong> to create the same operational report without photo upload or AI analysis.</p>
      </div>
      <figure class="screenshot-slot screenshot-image">
        <img src="{{ '/assets/ios/captain/Step 3.png' | relative_url }}" alt="TransitOps iOS web app Step 3 showing incident creation with photo upload and analysis" loading="lazy" />
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 4</span>
        <h3>Check and edit the report details</h3>
        <p>Verify the service number, direction of travel, vehicle plate, rain condition, bus deck type, closest stop or location, severity, passenger count, and description. The web app also supports current location, Singapore place search, LTA bus-stop search, optional obstruction-area drawing, and browser speech-to-text dictation.</p>
      </div>
      <figure class="screenshot-slot screenshot-image">
        <img src="{{ '/assets/ios/captain/Step 4.png' | relative_url }}" alt="TransitOps iOS web app Step 4 showing report details and edits" loading="lazy" />
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 5</span>
        <h3>Review and submit</h3>
        <p>Open <strong>Review Summary</strong>, check every item and attached photo, then submit once. TransitOps uploads photos to the existing <code>incident-photos</code> bucket, creates the report with <strong>Pending</strong> status, and returns to <strong>My Incidents</strong>.</p>
      </div>
      <figure class="screenshot-slot screenshot-image">
        <img src="{{ '/assets/ios/captain/Step 5.png' | relative_url }}" alt="TransitOps iOS web app Step 5 showing the review and submit summary" loading="lazy" />
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 6</span>
        <h3>Track officer updates</h3>
        <p>Open the submitted report to view its status, photos, officer messages, and approved diversion action. Pending reports can be edited or deleted; reports under review can be checked manually with <strong>Check Now</strong> while the page also polls for updates.</p>
      </div>
      <figure class="screenshot-slot screenshot-image">
        <img src="{{ '/assets/ios/captain/Step 6.png' | relative_url }}" alt="TransitOps iOS web app Step 6 showing incident tracking and officer updates" loading="lazy" />
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 7</span>
        <h3>Open the approved diversion</h3>
        <p>When the report becomes <strong>Route Ready</strong>, tap <strong>Go to Route</strong>. Review the diversion summary, start live guidance, and use Overview, Follow Me, Previous Step, and Next Step controls as needed.</p>
      </div>
      <figure class="screenshot-slot screenshot-image">
        <img src="{{ '/assets/ios/captain/Step 7.png' | relative_url }}" alt="TransitOps iOS web app Step 7 showing the approved diversion route" loading="lazy" />
      </figure>
    </article>

    <article class="workflow-step workflow-step-stack">
      <div class="workflow-copy">
        <span class="step-label">Step 8</span>
        <h3>Resolve and review route history</h3>
        <p>After the diversion or shift is complete, select <strong>End shift and resolve</strong>. The report moves to <strong>Resolved</strong>; if a route exists, the captain can reopen the report later and select <strong>View Route Taken</strong>.</p>
      </div>
      <figure class="screenshot-slot screenshot-image screenshot-stack">
        <img src="{{ '/assets/ios/captain/Step 8.png' | relative_url }}" alt="TransitOps iOS web app Step 8 showing resolved report history" loading="lazy" />
      </figure>
    </article>
  </div>
</section>

<section class="section" id="admin-workflow" aria-labelledby="admin-title">
  <div class="section-heading">
    <div>
      <span class="workflow-kicker">Administrator</span>
      <h2 id="admin-title">Admin workflow</h2>
      <p>Use the Administrator portal to add, inspect, and remove Bus Captain accounts. Administrators cannot create incident reports.</p>
    </div>
    <a class="workflow-jump" href="#captain-workflow">Return to captain workflow &uarr;</a>
  </div>

  <div class="workflow-list">
    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 1</span>
        <h3>Sign in as Administrator</h3>
        <p>Sign in with <code>admin@admin.com</code> and password <code>admin</code>. TransitOps routes this role to <strong>Admin Portal</strong> instead of <strong>My Incidents</strong>.</p>
      </div>
      <figure class="screenshot-slot screenshot-image">
        <img src="{{ '/assets/ios/admin/Step 1.png' | relative_url }}" alt="TransitOps iOS web app admin Step 1 showing administrator sign in" loading="lazy" />
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 2</span>
        <h3>Add a Bus Captain</h3>
        <p>Enter the captain email and full name, keep <strong>Active</strong> enabled for immediate access, and select <strong>Create Bus Captain</strong>. TransitOps creates the employee ID and sends the password setup or reset email.</p>
      </div>
      <figure class="screenshot-slot screenshot-image">
        <img src="{{ '/assets/ios/admin/Step 2.png' | relative_url }}" alt="TransitOps iOS web app admin Step 2 showing add bus captain" loading="lazy" />
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 3</span>
        <h3>Review or delete a captain</h3>
        <p>Select a captain row to view full name, email, employee ID, and active status. Use <strong>Delete Bus Captain</strong> only when access should be removed from the configured profile lists.</p>
      </div>
      <figure class="screenshot-slot screenshot-image">
        <img src="{{ '/assets/ios/admin/Step 3.png' | relative_url }}" alt="TransitOps iOS web app admin Step 3 showing captain review and delete flow" loading="lazy" />
      </figure>
    </article>
  </div>
</section>

<section class="section" aria-labelledby="parity-title">
  <span class="workflow-kicker">How it works</span>
  <h2 id="parity-title">Browser implementation notes</h2>
  <p>The web app is designed as a parity layer over the native iOS workflow, with browser-safe replacements where native APIs are unavailable.</p>
  <div class="grid-2">
    <div class="callout" style="margin-top: 0;">
      <strong>Backend parity</strong>
      <span class="muted">It expects the same <code>profiles</code>, <code>captain_profiles</code>, <code>incidents</code>, <code>incident_messages</code>, <code>diversion_routes</code>, and public <code>incident-photos</code> bucket used by the existing TransitOps backend.</span>
    </div>
    <div class="callout" style="margin-top: 0;">
      <strong>Web-specific substitutions</strong>
      <span class="muted">Maps use OpenStreetMap and Leaflet, while camera, location, microphone, and install behavior follow the browser and operating system permissions.</span>
    </div>
  </div>
</section>

<section class="section end-nav">
  <div>
    <h2>Continue to Step 2</h2>
    <p style="margin: 0;">After submitting an incident from the iOS web app, open the Operations Officer dashboard to review and dispatch the route.</p>
  </div>
  <a class="button" href="{{ '/web-dashboard/' | relative_url }}">Open Operations Officer guide <span aria-hidden="true">&rarr;</span></a>
</section>
