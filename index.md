---
title: RouteGuardians Manual
description: TransitOps Judge Walkthrough
layout: default
---

<h1>TransitOps Judge Walkthrough</h1>
<p class="subtitle">
  Use this guide when testing the prototype. It is written as a simple step-by-step
  instruction manual for the operations officer flow only.
</p>

<div class="manual-meta">
  <span class="meta">Version: Judge walkthrough</span>
  <span class="meta">Audience: Operations officer</span>
  <span class="meta">Format: Step by step</span>
</div>

<section class="section">
  <h2>Before You Start</h2>
  <ul>
    <li>Open the app and sign in as the operations officer.</li>
    <li>Use the sample incident already included in the prototype.</li>
    <li>Follow the steps below in order.</li>
  </ul>
  <div class="note">
    <strong>Accounts</strong><br />
    Admin: <code>admin@officer.com</code> / <code>12345678</code><br />
    Officer: <code>officer@officer.com</code> / <code>12345678</code>
  </div>
</section>

<section class="section">
  <h2>Sample Incident</h2>
  <ul>
    <li>Road blockage on Bras Basah Road near the National Museum of Singapore</li>
    <li>Bus service 14</li>
    <li>High severity</li>
    <li>41 passengers onboard</li>
  </ul>
</section>

<section class="section">
  <h2>Procedure</h2>
  <ol class="procedure">
    <li>
      <span class="step-title">Open the app</span>
      You should see a sign-in page for Operations Officer.
    </li>
    <li>
      <span class="step-title">Review the incident feed</span>
      Check the active incident and confirm the live context shown on screen.
    </li>
    <li>
      <span class="step-title">Select the incident</span>
      Open the incident summary and review location, service, severity, and map context.
    </li>
    <li>
      <span class="step-title">Review the incident</span>
      Go to <code>Review</code>. If the incident report is in another language, translate it into English.
    </li>
    <li>
      <span class="step-title">Open decision settings</span>
      Go to <code>Decision Settings</code>.
    </li>
    <li>
      <span class="step-title">Compare routes</span>
      Go to <code>AI Route Comparison</code> and compare the route options shown.
    </li>
    <li>
      <span class="step-title">Review directions</span>
      Check the final overview of the confirmed route.
    </li>
    <li>
      <span class="step-title">Check affected buses</span>
      Go to <code>Check Affected Buses</code> and review the services flagged by the system.
    </li>
    <li>
      <span class="step-title">Approve the diversion</span>
      Go to <code>Proceed to Approval</code> and approve or reject the route.
    </li>
    <li>
      <span class="step-title">Dispatch notifications</span>
      The bus captain is notified about the reroute, passengers are notified, and the incident is marked as dispatched.
    </li>
  </ol>
</section>

<section class="section">
  <h2>Optional Screens</h2>
  <ul>
    <li><code>Historical Reports</code></li>
    <li><code>User Management</code> if the officer is an admin</li>
  </ul>
  <div class="warning">
    <strong>Note</strong><br />
    Passenger notifications are shown in the prototype as a Telegram flow.
  </div>
</section>
