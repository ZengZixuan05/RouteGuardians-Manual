---
title: Android App Guide
description: TransitOps Android app credentials and step-by-step Bus Captain and Administrator workflows
layout: default
permalink: /android-app/
header_subtitle: TransitOps Android App Walkthrough
guide_label: Guest & admin workflows
---

<section class="hero">
  <div class="hero-grid">
    <div>
      <div class="eyebrow">Android app manual</div>
      <h1>TransitOps Android App Guide</h1>
      <p class="lead">
        Follow the Bus Captain workflow to report and track a road incident, or use
        the Administrator workflow to add and remove Bus Captain accounts.
      </p>
      <div class="tag-row" style="margin-top: 22px;">
        <span class="tag">Incident reporting</span>
        <span class="tag">Report status</span>
        <span class="tag">Captain management</span>
      </div>
      <div class="hero-actions">
        <a class="button" href="#guest-workflow">Start guest workflow <span aria-hidden="true">↓</span></a>
        <a class="button button-secondary" href="#admin-workflow">Jump to admin workflow</a>
      </div>
    </div>

    <aside class="card quickfacts" aria-label="Android app demo credentials">
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

<section class="section" aria-labelledby="choose-workflow">
  <h2 id="choose-workflow">Choose a workflow</h2>
  <p>Open the installed TransitOps app, then select the role you want to test.</p>
  <div class="role-links">
    <a class="role-link" href="#guest-workflow">
      <span class="role-link-copy">
        <strong>Guest / Bus Captain</strong>
        <span>Create an incident report and follow its progress.</span>
      </span>
      <b aria-hidden="true">→</b>
    </a>
    <a class="role-link" href="#admin-workflow">
      <span class="role-link-copy">
        <strong>Administrator</strong>
        <span>Add, review, and remove Bus Captain accounts.</span>
      </span>
      <b aria-hidden="true">→</b>
    </a>
  </div>
  <div class="callout">
    <strong>First launch</strong>
    <span class="muted">Choose a language if prompted. Camera, photos, location, and microphone permissions are requested only when the related feature is used.</span>
  </div>
</section>

<section class="section" id="guest-workflow" aria-labelledby="guest-title">
  <div class="section-heading">
    <div>
      <span class="workflow-kicker">Guest account</span>
      <h2 id="guest-title">Bus Captain workflow</h2>
      <p>Use the guest account to create a complete incident report, submit it to the command centre, and check for an approved diversion.</p>
    </div>
    <a class="button button-secondary" href="#admin-workflow">Admin workflow ↓</a>
  </div>

  <div class="workflow-list">
    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 1</span>
        <h3>Sign in as the Bus Captain</h3>
        <p>Open TransitOps and enter <code>guest@guest.com</code> with password <code>guest1234</code>. Tap <strong>Sign In</strong>. The app opens the <strong>My Incidents</strong> screen.</p>
      </div>
      <figure class="screenshot-slot">
        <figcaption>
          <span class="phone-mark" aria-hidden="true"></span>
          <strong>Screenshot: Guest sign in</strong>
          <span>Show the completed email field and the Sign In button.</span>
        </figcaption>
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 2</span>
        <h3>Start a new incident report</h3>
        <p>On <strong>My Incidents</strong>, tap <strong>+ Add Report</strong>. On the Report Incident screen, select the incident type that best matches the disruption.</p>
      </div>
      <figure class="screenshot-slot">
        <figcaption>
          <span class="phone-mark" aria-hidden="true"></span>
          <strong>Screenshot: My Incidents</strong>
          <span>Show the + Add Report action and an example report list.</span>
        </figcaption>
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 3</span>
        <h3>Add evidence or enter details manually</h3>
        <p>For AI-assisted reporting, attach one clear <strong>Bus photo</strong> and one <strong>Incident photo</strong> using Camera, Photo Library, or Files. The bus photo should show the service number, licence plate, and deck type.</p>
        <p>Tap <strong>Analyze Photos and Continue</strong>. If photos or analysis are unavailable, tap <strong>Enter Details Manually</strong> instead.</p>
      </div>
      <figure class="screenshot-slot">
        <figcaption>
          <span class="phone-mark" aria-hidden="true"></span>
          <strong>Screenshot: Upload photos</strong>
          <span>Show both photo upload areas and the manual-entry option.</span>
        </figcaption>
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 4</span>
        <h3>Check and complete the report details</h3>
        <p>Review every AI-filled value and correct anything that is wrong. If you chose manual entry, complete the same fields yourself:</p>
        <ul>
          <li>Bus service, direction of travel, vehicle plate, and bus deck type</li>
          <li>Rain condition and whether a wheelchair passenger is onboard</li>
          <li>Closest stop or location before the obstruction</li>
          <li>Optional obstruction area on the map</li>
          <li>Incident type, severity, details, and passenger count</li>
        </ul>
      </div>
      <figure class="screenshot-slot">
        <figcaption>
          <span class="phone-mark" aria-hidden="true"></span>
          <strong>Screenshot: Edit details</strong>
          <span>Show the completed bus and incident fields before review.</span>
        </figcaption>
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 5</span>
        <h3>Review the submission summary</h3>
        <p>Tap <strong>Review Summary</strong>. Check the photographs, bus information, operating conditions, location, severity, passenger count, and incident description. Use <strong>Back to edit details</strong> if anything needs to change.</p>
      </div>
      <figure class="screenshot-slot">
        <figcaption>
          <span class="phone-mark" aria-hidden="true"></span>
          <strong>Screenshot: Review Summary</strong>
          <span>Show the summary with the two report photographs.</span>
        </figcaption>
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 6</span>
        <h3>Submit the incident</h3>
        <p>When every detail is correct, tap <strong>Submit Incident</strong>. Wait for the app to return to <strong>My Incidents</strong> and confirm that the new report appears in the list.</p>
      </div>
      <figure class="screenshot-slot">
        <figcaption>
          <span class="phone-mark" aria-hidden="true"></span>
          <strong>Screenshot: Submitted report</strong>
          <span>Show the new report and its current status in My Incidents.</span>
        </figcaption>
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 7</span>
        <h3>Track the command-centre response</h3>
        <p>Open the report to see its status, submitted photographs, and officer-message history. Pull to refresh or tap <strong>Check Now</strong> to request the latest decision and route information.</p>
      </div>
      <figure class="screenshot-slot">
        <figcaption>
          <span class="phone-mark" aria-hidden="true"></span>
          <strong>Screenshot: Incident Details</strong>
          <span>Show status, officer messages, and the Check Now action.</span>
        </figcaption>
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 8</span>
        <h3>Open an approved diversion route</h3>
        <p>After the operations officer approves a diversion, tap <strong>Go to Route</strong>. Use <strong>Overview</strong> to frame the complete route, or <strong>Follow Me</strong> when device location is available.</p>
        <p>If the route is rejected, the report returns to a reviewing state and <strong>Go to Route</strong> is no longer shown.</p>
      </div>
      <figure class="screenshot-slot">
        <figcaption>
          <span class="phone-mark" aria-hidden="true"></span>
          <strong>Screenshot: Approved route</strong>
          <span>Show Go to Route, the diversion map, or the guidance controls.</span>
        </figcaption>
      </figure>
    </article>
  </div>
</section>

<section class="section" id="admin-workflow" aria-labelledby="admin-title">
  <div class="section-heading">
    <div>
      <span class="workflow-kicker">Administrator account</span>
      <h2 id="admin-title">Admin workflow</h2>
      <p>Use the Administrator account to review configured Bus Captains, create an account, or remove an account that is no longer needed.</p>
    </div>
    <a class="button button-secondary" href="#guest-workflow">Guest workflow ↑</a>
  </div>

  <div class="callout" style="margin: 0 0 18px;">
    <strong>Use disposable data for deletion tests</strong>
    <span class="muted">Only remove a demonstration account that is safe to delete. Do not delete an account another tester still needs.</span>
  </div>

  <div class="workflow-list">
    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 1</span>
        <h3>Sign in as the Administrator</h3>
        <p>Sign out of the guest account if necessary. Enter <code>admin@admin.com</code> with password <code>admin</code>, then tap <strong>Sign In</strong>. The app opens the <strong>Admin Portal</strong>.</p>
        <p>The Administrator account manages users only; incident reporting is disabled for this role.</p>
      </div>
      <figure class="screenshot-slot">
        <figcaption>
          <span class="phone-mark" aria-hidden="true"></span>
          <strong>Screenshot: Admin sign in</strong>
          <span>Show the admin credentials entered on the sign-in screen.</span>
        </figcaption>
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 2</span>
        <h3>Review configured Bus Captains</h3>
        <p>Scroll to <strong>Configured Bus Captains</strong>. Each row shows the captain’s full name, auto-generated employee ID, email address, and Active or Disabled status. Tap a row to open the complete account details.</p>
      </div>
      <figure class="screenshot-slot">
        <figcaption>
          <span class="phone-mark" aria-hidden="true"></span>
          <strong>Screenshot: Captain list</strong>
          <span>Show configured captains and their account statuses.</span>
        </figcaption>
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 3</span>
        <h3>Add a Bus Captain</h3>
        <p>In <strong>Add Bus Captain</strong>, enter the new captain’s <strong>Email</strong> and <strong>Full name</strong>. Leave <strong>Active</strong> switched on for an account that should be usable, then tap <strong>Create Bus Captain</strong>.</p>
        <p>The app creates an employee ID in the format <code>BC-XXXX</code> and sends a password-setup email. The form clears after successful creation.</p>
      </div>
      <figure class="screenshot-slot">
        <figcaption>
          <span class="phone-mark" aria-hidden="true"></span>
          <strong>Screenshot: Add Bus Captain</strong>
          <span>Show the completed email, full-name, and Active fields.</span>
        </figcaption>
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 4</span>
        <h3>Confirm the new account</h3>
        <p>Find the new captain under <strong>Configured Bus Captains</strong>. Confirm the correct name, email, employee ID, and status. Tap the row if you need to review the full account details.</p>
      </div>
      <figure class="screenshot-slot">
        <figcaption>
          <span class="phone-mark" aria-hidden="true"></span>
          <strong>Screenshot: New captain</strong>
          <span>Show the newly created captain in the configured list.</span>
        </figcaption>
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 5</span>
        <h3>Remove a Bus Captain</h3>
        <p>Tap the trash icon on the captain’s row, or open the captain and tap <strong>Delete Bus Captain</strong>. In the confirmation dialog, check that you selected the correct person, then tap <strong>Delete</strong>.</p>
      </div>
      <figure class="screenshot-slot">
        <figcaption>
          <span class="phone-mark" aria-hidden="true"></span>
          <strong>Screenshot: Delete confirmation</strong>
          <span>Show the selected captain and the Delete Bus Captain dialog.</span>
        </figcaption>
      </figure>
    </article>
  </div>
</section>

<section class="section end-nav">
  <div>
    <h2>Continue testing</h2>
    <p style="margin: 0;">Return to the web-dashboard guide for the operations officer workflow.</p>
  </div>
  <a class="button" href="{{ '/' | relative_url }}">Open web dashboard guide <span aria-hidden="true">→</span></a>
</section>
