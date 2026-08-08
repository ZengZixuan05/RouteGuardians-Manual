---
title: RouteGuardians Manual
description: TransitOps Judge Walkthrough
layout: default
---

<h1>TransitOps Judge Walkthrough</h1>
<p class="subtitle">
  Use the tabs below to switch between the Operations Officer manual and the Bus Driver manual.
</p>

<div class="tabs" role="tablist" aria-label="Manual sections">
  <button
    class="tab-button"
    id="tab-officer"
    role="tab"
    type="button"
    aria-selected="true"
    aria-controls="panel-officer"
    data-tab="officer"
  >
    Operations Officer
  </button>
  <button
    class="tab-button"
    id="tab-driver"
    role="tab"
    type="button"
    aria-selected="false"
    aria-controls="panel-driver"
    data-tab="driver"
  >
    Bus Driver
  </button>
</div>

<section class="tab-panel is-active" id="panel-officer" role="tabpanel" aria-labelledby="tab-officer">
  <section class="section">
    <h2>Procedure</h2>
    <ol class="procedure">
      <li>
        <span class="step-title">Open the app</span>
        You should see a sign-in page for Operations Officer. Below are the demo account details:
          <strong>Accounts</strong><br />
            Admin: <code>email: admin@officer.com</code> / <code>password: 12345678</code><br>
            Officer: <code>email: officer@officer.com</code> / <code>password: 12345678</code>
      </li>
      <li>
        <span class="step-title">Review the incident feed</span>
        Check the SVC 93 accident card and confirm the live context shown on screen.
        <div class="note">
          <strong>Sample incident</strong><br />
          SVC 93 accident<br />
          Lor Ah Soo (Upp Paya Lebar Rd)<br />
          Medium severity<br />
          41 passengers onboard<br />
          Awaiting assessment<br />
          Pending status
        </div>
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
</section>

<section class="tab-panel" id="panel-driver" role="tabpanel" aria-labelledby="tab-driver" hidden>
  <section class="section">
    <h2>Bus Driver Manual</h2>
    <p>This section is a placeholder for now. We can fill this in with the bus driver workflow next.</p>
  </section>

  <section class="section">
    <h2>Proposed Flow</h2>
    <ol class="procedure">
      <li>
        <span class="step-title">Open the driver view</span>
        Placeholder content.
      </li>
      <li>
        <span class="step-title">Receive the diversion notice</span>
        Placeholder content.
      </li>
      <li>
        <span class="step-title">Confirm the updated route</span>
        Placeholder content.
      </li>
      <li>
        <span class="step-title">Proceed with the trip</span>
        Placeholder content.
      </li>
    </ol>
    <div class="warning">
      <strong>Placeholder</strong><br />
      The driver manual is not finalized yet, so the steps above are just a draft.
    </div>
  </section>
</section>

<script>
  (function () {
    const tabs = Array.from(document.querySelectorAll('.tab-button'));
    const panels = {
      officer: document.getElementById('panel-officer'),
      driver: document.getElementById('panel-driver'),
    };

    function activate(name) {
      tabs.forEach((tab) => {
        const active = tab.dataset.tab === name;
        tab.setAttribute('aria-selected', String(active));
      });

      Object.entries(panels).forEach(([key, panel]) => {
        const active = key === name;
        panel.classList.toggle('is-active', active);
        panel.hidden = !active;
      });
    }

    tabs.forEach((tab) => {
      tab.addEventListener('click', () => activate(tab.dataset.tab));
    });
  })();
</script>
