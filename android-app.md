---
title: Android App Guide
description: TransitOps Android app credentials and step-by-step Bus Captain and Administrator workflows
layout: default
permalink: /android-app/
header_subtitle: TransitOps Android App Walkthrough
guide_label: Start here - Android app
---

<section class="hero">
  <div class="hero-grid">
    <div>
      <div class="eyebrow">Start here - Android app manual</div>
      <h1>TransitOps Android App Guide</h1>
      <p class="lead">
        Begin with the Bus Captain workflow. The captain must submit an incident in
        this app before the Operations Officer can review and route it on the web dashboard.
        Use the Administrator workflow separately to manage Bus Captain accounts.
      </p>
      <div class="tag-row" style="margin-top: 22px;">
        <span class="tag">Incident reporting</span>
        <span class="tag">Report status</span>
        <span class="tag">Captain management</span>
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

<section class="section" aria-labelledby="journey-title">
  <span class="workflow-kicker">Recommended test order</span>
  <h2 id="journey-title">One incident across the app and dashboard</h2>
  <p>Use the same sample report from start to finish. The Android app is the first step in the operational workflow.</p>
  <ol class="journey-list">
    <li class="journey-step">
      <span class="journey-number" aria-hidden="true">1</span>
      <div>
        <strong>Report in the Android app</strong>
        <p>The Bus Captain signs in as Guest, adds the two sample images, checks the details, and submits the incident.</p>
      </div>
    </li>
    <li class="journey-step">
      <span class="journey-number" aria-hidden="true">2</span>
      <div>
        <strong>Review on the web dashboard</strong>
        <p>The Operations Officer opens the submitted incident, compares routes, approves a diversion, and dispatches it.</p>
      </div>
    </li>
    <li class="journey-step">
      <span class="journey-number" aria-hidden="true">3</span>
      <div>
        <strong>Return to the Android app</strong>
        <p>The Bus Captain refreshes the report, reads the officer response, and opens the approved route.</p>
      </div>
    </li>
  </ol>
</section>

<section class="section" id="install-app" aria-labelledby="install-title">
  <div class="section-heading">
    <div>
      <span class="workflow-kicker">Start here</span>
      <h2 id="install-title">Download and install TransitOps</h2>
      <p>Install the supplied prototype directly on an Android or Huawei phone before starting either workflow.</p>
    </div>
  </div>

  <div class="download-panel">
    <div>
      <span class="file-badge">Android APK · 21.2 MB</span>
      <h3>TransitOps Prototype</h3>
      <p>This tested prototype supports Android 8.0 or newer. The “unknown app” prompt is expected because the APK comes from this project website rather than an app store.</p>
      <div class="download-actions">
        <a class="button" href="{{ '/assets/downloads/TransitOps-Prototype.apk' | relative_url }}" download="TransitOps-Prototype.apk">Download TransitOps APK <span aria-hidden="true">↓</span></a>
        <span class="action-note">Filename: <code>TransitOps-Prototype.apk</code></span>
      </div>
    </div>
    <dl class="file-details">
      <dt>Version</dt>
      <dd>1.0 prototype</dd>
      <dt>Package</dt>
      <dd><code>sg.transitops.buscaptain</code></dd>
      <dt>Minimum</dt>
      <dd>Android 8.0</dd>
      <dt>SHA-256</dt>
      <dd><code>740188B23B1559CE6C39855B262A34A0BD70A0AE859F5B889F4547426B2AB221</code></dd>
    </dl>
  </div>

  <ol class="timeline install-steps">
    <li class="step">
      <strong>Download the APK</strong>
      <p>Open this page on the Android or Huawei phone and tap <strong>Download TransitOps APK</strong>. If the browser asks whether to download the file, confirm the download.</p>
    </li>
    <li class="step">
      <strong>Open the downloaded file</strong>
      <p>Tap the completed-download notification. If it is no longer visible, open the browser’s <strong>Downloads</strong> list or open <strong>Files</strong> / <strong>File Manager</strong> → <strong>Downloads</strong>, then tap <code>TransitOps-Prototype.apk</code>.</p>
    </li>
    <li class="step">
      <strong>Temporarily allow installation from this source</strong>
      <p>If the phone says the browser or file manager is not allowed to install unknown apps, tap <strong>Settings</strong> and enable only the app that opened the APK.</p>
      <ul class="settings-paths">
        <li><strong>Standard Android:</strong> Settings → Apps → Special app access → Install unknown apps → select the browser or Files → Allow from this source.</li>
        <li><strong>Huawei / EMUI:</strong> Settings → Security → More settings → Install apps from external sources → select the browser or Files → Allow app installs.</li>
      </ul>
      <p>If the menus look different, search Settings for <strong>Install unknown apps</strong>, <strong>external sources</strong>, or <strong>in-app installations</strong>.</p>
    </li>
    <li class="step">
      <strong>Return to the installer</strong>
      <p>Go back to the APK installer and tap <strong>Install</strong>. Keep the phone’s security scanning enabled. If Google Play Protect offers to scan the app, let it complete the scan.</p>
    </li>
    <li class="step">
      <strong>Open TransitOps</strong>
      <p>When installation finishes, tap <strong>Open</strong>. Choose English, Simplified Chinese, Malay, or Tamil if the language screen appears, then use one of the demo accounts shown at the top of this page.</p>
    </li>
    <li class="step">
      <strong>Turn the temporary permission back off</strong>
      <p>Return to the same <strong>Install unknown apps</strong> or <strong>Install apps from external sources</strong> setting and disable permission for the browser or file manager.</p>
    </li>
  </ol>

  <div class="callout security-note">
    <strong>Stop if the phone identifies the file as harmful</strong>
    <span class="muted">Do not disable Play Protect or device security. If the phone reports that the APK is dangerous, harmful, corrupt, or blocked by an organisation policy, stop and contact the project owner. A normal “unknown source” permission prompt is different from a harmful-app warning.</span>
  </div>
</section>

<section class="section" id="sample-test-case" aria-labelledby="sample-title">
  <div class="section-heading">
    <div>
      <span class="workflow-kicker">Sample test case</span>
      <h2 id="sample-title">Save these two report images</h2>
      <p>Download both images to the phone before testing. Use the bus image as the <strong>Bus photo</strong> and the accident image as the <strong>Incident photo</strong>.</p>
    </div>
  </div>

  <div class="sample-grid">
    <article class="sample-card">
      <a class="sample-media" href="{{ '/assets/sample-test-case/double-decker-bus.jpg' | relative_url }}" download="TransitOps-sample-bus.jpg" aria-label="Download the sample double-decker bus photo">
        <img src="{{ '/assets/sample-test-case/double-decker-bus.jpg' | relative_url }}" width="1448" height="1086" loading="lazy" alt="SBS Transit double-decker bus service 93 on the road" />
      </a>
      <div class="sample-card-body">
        <h3>1. Bus photo</h3>
        <p>Use this image for the vehicle photograph. It shows bus service 93, plate <code>SBS7530C</code>, and a double-decker bus.</p>
        <div class="sample-actions">
          <a class="button button-secondary" href="{{ '/assets/sample-test-case/double-decker-bus.jpg' | relative_url }}" download="TransitOps-sample-bus.jpg">Save bus photo <span aria-hidden="true">↓</span></a>
        </div>
      </div>
    </article>

    <article class="sample-card">
      <a class="sample-media" href="{{ '/assets/sample-test-case/car-accident.jpg' | relative_url }}" download="TransitOps-sample-incident.jpg" aria-label="Download the sample traffic accident photo">
        <img src="{{ '/assets/sample-test-case/car-accident.jpg' | relative_url }}" width="596" height="335" loading="lazy" alt="Traffic accident obstructing the road near Lor Ah Soo" />
      </a>
      <div class="sample-card-body">
        <h3>2. Incident photo</h3>
        <p>Use this image for the incident evidence. It shows a traffic accident and road obstruction near Lor Ah Soo.</p>
        <div class="sample-actions">
          <a class="button button-secondary" href="{{ '/assets/sample-test-case/car-accident.jpg' | relative_url }}" download="TransitOps-sample-incident.jpg">Save incident photo <span aria-hidden="true">↓</span></a>
        </div>
      </div>
    </article>
  </div>

  <div class="callout sample-note" id="sample-expected-values">
    <strong>Expected AI output and manual-entry values</strong>
    <p>After you tap <strong>Analyze Photos and Continue</strong>, TransitOps should autofill the report with the values below. Do not type them again when the AI output already matches.</p>
    <ul>
      <li>Bus service: <code>93</code>; vehicle plate: <code>SBS7530C</code>; bus type: <strong>Double decker</strong></li>
      <li>Direction of travel: <strong>Direction 1</strong> — select this manually because direction is not autofilled</li>
      <li>Incident type: <strong>Traffic accident</strong>; severity: <strong>High</strong></li>
      <li>Closest location: <strong>Lor Ah Soo / Upper Paya Lebar Road</strong></li>
      <li>Passenger count: <code>41</code>; rain: <strong>Not raining</strong>; wheelchair passenger onboard: <strong>No</strong></li>
      <li>Description: <strong>Traffic accident obstructing the road near Lor Ah Soo. Diversion may be required.</strong></li>
    </ul>
    <span class="muted">Use this list to verify the AI output, or as the complete reference if you choose <strong>Enter Details Manually</strong>. Correct only values that differ. If tapping a save button opens the image instead, press and hold the image and choose <strong>Download image</strong> or <strong>Save image</strong>.</span>
  </div>
</section>

<section class="section" aria-labelledby="choose-workflow">
  <h2 id="choose-workflow">Android app roles</h2>
  <p>Start with Guest / Bus Captain to create the incident. Use Administrator only when you need to add, review, or remove Bus Captain accounts.</p>
  <div class="role-links">
    <a class="role-link" href="#guest-workflow">
      <span class="role-link-copy">
        <strong>Guest / Bus Captain</strong>
        <span>Create an incident report and follow its progress.</span>
      </span>
      <b aria-hidden="true">&rarr;</b>
    </a>
    <a class="role-link" href="#admin-workflow">
      <span class="role-link-copy">
        <strong>Administrator</strong>
        <span>Add, review, and remove Bus Captain accounts.</span>
      </span>
      <b aria-hidden="true">&rarr;</b>
    </a>
  </div>
</section>

<section class="section" id="guest-workflow" aria-labelledby="guest-title">
  <div class="section-heading">
    <div>
      <span class="workflow-kicker">Guest account</span>
      <h2 id="guest-title">Bus Captain workflow</h2>
      <p>Use the guest account to create a complete incident report, submit it to the command centre, and check for an approved diversion.</p>
    </div>
    <a class="workflow-jump" href="#admin-workflow">Go to admin workflow &darr;</a>
  </div>

  <div class="workflow-list">
    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 1</span>
        <h3>Sign in as the Bus Captain</h3>
        <p>Open TransitOps and enter <code>guest@guest.com</code> with password <code>guest1234</code>. Tap <strong>Sign In</strong>. The app opens the <strong>My Incidents</strong> screen.</p>
      </div>
      <figure class="screenshot-slot screenshot-image">
        <img
          src="{{ '/assets/android/guest-login.jpg' | relative_url }}"
          alt="TransitOps guest sign-in screen showing the demo credentials"
          loading="lazy"
        />
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 2</span>
        <h3>Start a new incident report</h3>
        <p>On <strong>My Incidents</strong>, tap <strong>+ Add Report</strong>. On the Report Incident screen, select the incident type that best matches the disruption.</p>
      </div>
      <figure class="screenshot-slot screenshot-image">
        <img
          src="{{ '/assets/android/incident-report.jpg' | relative_url }}"
          alt="TransitOps guest workflow step"
          loading="lazy"
        />
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 3</span>
        <h3>Add the sample photos and let AI fill the report</h3>
        <p>For AI-assisted reporting, attach one clear <strong>Bus photo</strong> and one <strong>Incident photo</strong> using Camera, Photo Library, or Files. The bus photo should show the service number, licence plate, and deck type. For the prepared demo, use the two files from the <a href="#sample-test-case">sample test case</a> above.</p>
        <p>Tap <strong>Analyze Photos and Continue</strong>. TransitOps should autofill the report details from the two images; only the direction of travel still needs to be selected. If photos or analysis are unavailable, tap <strong>Enter Details Manually</strong> instead.</p>
      </div>
      <figure class="screenshot-slot screenshot-image">
        <img
          src="{{ '/assets/android/autofill-report.jpg' | relative_url }}"
          alt="TransitOps guest submission of photos for autofill"
          loading="lazy"
        />
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 4</span>
        <h3>Select Direction 1 and verify the autofill</h3>
        <p><strong>Required for this demo:</strong> set <strong>Direction of travel</strong> to <strong>Direction 1</strong>. This is the only report value that photo analysis does not autofill.</p>
        <p>Compare the remaining AI-filled fields with the <a href="#sample-expected-values">expected output above</a>. Do not re-enter values that already match; correct only any differences. If you chose manual entry, complete the form using that same reference.</p>
      </div>
      <figure class="screenshot-slot screenshot-image">
        <img
          src="{{ '/assets/android/select-direction.jpg' | relative_url }}"
          alt="TransitOps guest select which direction bus is going from"
          loading="lazy"
        />
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 5</span>
        <h3>Review the submission summary</h3>
        <p>Tap <strong>Review Summary</strong>. Check the photographs, bus information, <strong>Direction 1</strong>, operating conditions, location, severity, passenger count, and incident description. Use <strong>Back to edit details</strong> if anything needs to change.</p>
      </div>
      <figure class="screenshot-slot screenshot-image">
        <img
          src="{{ '/assets/android/review-summary.jpg' | relative_url }}"
          alt="TransitOps guest review summary"
          loading="lazy"
        />
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 6</span>
        <h3>Submit the incident</h3>
        <p>When every detail is correct, tap <strong>Submit Incident</strong>. Wait for the app to return to <strong>My Incidents</strong> and confirm that the new report appears in the list.</p>
      </div>
      <figure class="screenshot-slot screenshot-image">
        <img
          src="{{ '/assets/android/submit-incident.jpg' | relative_url }}"
          alt="Transitops guest submit incidents page"
          loading="lazy"
        />
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 7</span>
        <h3>Track the command-centre response</h3>
        <p>After submitting, continue with the <a class="text-link" href="{{ '/web-dashboard/' | relative_url }}">Operations Officer dashboard workflow</a> so the incident can be reviewed and dispatched. Then return to the report to see its status, submitted photographs, and officer-message history. Pull to refresh or tap <strong>Check Now</strong> to request the latest decision and route information.</p>
      </div>
      <figure class="screenshot-slot screenshot-image">
        <img
          src="{{ '/assets/android/track-response.jpg' | relative_url }}"
          alt="TransitOps guest track status of response"
          loading="lazy"
        />
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 8</span>
        <h3>Open an approved diversion route</h3>
        <p>After the operations officer approves a diversion, tap <strong>Go to Route</strong>. Use <strong>Overview</strong> to frame the complete route, or <strong>Follow Me</strong> when device location is available.</p>
        <p>If the route is rejected, the report returns to a reviewing state and <strong>Go to Route</strong> is no longer shown.</p>
      </div>
      <figure class="screenshot-slot screenshot-image">
        <img
          src="{{ '/assets/android/open-approvedroute.jpg' | relative_url }}"
          alt="TransitOps guest open already approved route"
          loading="lazy"
        />
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
    <a class="workflow-jump" href="#guest-workflow">Return to guest workflow &uarr;</a>
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
      <figure class="screenshot-slot screenshot-image">
        <img
          src="{{ '/assets/android/admin-login.jpg' | relative_url }}"
          alt="TransitOps admin login view"
          width="462"
          height="1026"
          loading="lazy"
        />
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 2</span>
        <h3>Review configured Bus Captains</h3>
        <p>Scroll to <strong>Configured Bus Captains</strong>. Each row shows the captain’s full name, auto-generated employee ID, email address, and Active or Disabled status. Tap a row to open the complete account details.</p>
      </div>
      <figure class="screenshot-slot screenshot-image">
        <img
          src="{{ '/assets/android/review-bus-captain.jpg' | relative_url }}"
          alt="TransitOps admin review existing bus captains"
          width="468"
          height="1028"
          loading="lazy"
        />
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 3</span>
        <h3>Add a Bus Captain</h3>
        <p>In <strong>Add Bus Captain</strong>, enter the new captain’s <strong>Email</strong> and <strong>Full name</strong>. Leave <strong>Active</strong> switched on for an account that should be usable, then tap <strong>Create Bus Captain</strong>.</p>
        <p>The app creates an employee ID in the format <code>BC-XXXX</code> and sends a password-setup email. The form clears after successful creation.</p>
      </div>
      <figure class="screenshot-slot screenshot-image">
        <img
          src="{{ '/assets/android/add-bus-captain.jpg' | relative_url }}"
          alt="TransitOps admin add new bus captains"
          width="464"
          height="1032"
          loading="lazy"
        />
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 4</span>
        <h3>Confirm the new account</h3>
        <p>Find the new captain under <strong>Configured Bus Captains</strong>. Confirm the correct name, email, employee ID, and status. Tap the row if you need to review the full account details.</p>
      </div>
      <figure class="screenshot-slot screenshot-image">
        <img
          src="{{ '/assets/android/confirm-account.jpg' | relative_url }}"
          alt="TransitOps admin confirm created account"
          width="464"
          height="1028"
          loading="lazy"
        />
      </figure>
    </article>

    <article class="workflow-step">
      <div class="workflow-copy">
        <span class="step-label">Step 5</span>
        <h3>Remove a Bus Captain</h3>
        <p>Tap the trash icon on the captain’s row, or open the captain and tap <strong>Delete Bus Captain</strong>. In the confirmation dialog, check that you selected the correct person, then tap <strong>Delete</strong>.</p>
      </div>
      <figure class="screenshot-slot screenshot-image">
        <img
          src="{{ '/assets/android/delete-bus-captain.jpg' | relative_url }}"
          alt="TransitOps admin delete bus captains"
          width="467"
          height="1032"
          loading="lazy"
        />
      </figure>
    </article>
  </div>
</section>

<section class="section end-nav">
  <div>
    <h2>Continue testing</h2>
    <p style="margin: 0;">Return to the web-dashboard guide for the operations officer workflow.</p>
  </div>
  <a class="button" href="{{ '/web-dashboard/' | relative_url }}">Open web dashboard guide <span aria-hidden="true">&rarr;</span></a>
</section>
