---
title: RouteGuardians Manual
description: TransitOps Judge Walkthrough
---

# TransitOps Judge Walkthrough

Use this guide when testing the prototype. It is written as a click-by-click
walkthrough for the operations officer flow only.

## What The Prototype Shows

TransitOps simulates an operations response workflow:

1. The officer reviews an active incident.
2. The officer compares diversion options.
3. The officer approves a route and sends dispatch notifications.

## Recommended Test Path

This manual covers only the officer workflow. The sample incident is already
available in the prototype, so you can start from the officer dashboard.

## Test Scenario

The built-in sample incident is:

- Road blockage on Bras Basah Road near the National Museum of Singapore
- Bus service 14
- High severity
- 41 passengers onboard

This is the default scenario used by the prototype.

## Walkthrough

### 1. Open the app
You should see a sign in page for Operations Officer.

Sign in with either of these accounts below

For Admin Panel:
email: admin@officer.com
password: 12345678

For Officer:
email: officer@officer.com
password: 12345678

### 2. Overview of Incident Feed
- The command centre is showing live incident context.
- You can switch between active and historical incidents if available.

### 3. Select Incident
- You see the incident summary.
- You see location, service, severity, and live map context.

### 4. Review Incident

Go to `Review`.

More details will be shown. If incident report was written in other languages, you can translate it into English.

### 5. Decision Settings

Go to `Decision Settings`.

### 6. Compare routes

Go to `AI Route Comparison`.

Expected result:

- One or more route options are shown.
- Route differences such as delay or feasibility can be compared.

At this page, you can also click on `Create Custom Route` to create a custom route from scratch.

There is also an option to edit the AI generated route.

### 7. Review Directions

Gives a final overview of the confirmed route.

### 8. Check affected buses

Go to `Check Affected Buses`

- The system scans for services near the incident.
- A list of affected services appears.
- Bus drivers of selected services can be notified.

### 9. Approve the diversion

Go to `Proceed to Approval`.

- The incident summary and selected diversion are shown.
- You can approve or reject the route.

If you approve:

- The route status changes to approved.

### 10. Dispatch notifications

- The bus captain will be notified about the reroute.
- Passenger will be notified via a Telegram Channel. (Tentative since we dont have access to the official SBS app)
- The incident is marked as dispatched.

## Optional Screens

If time allows, also check:

- `Historical Reports`
- `User Management` if the officer is an admin. Admin can add users.
