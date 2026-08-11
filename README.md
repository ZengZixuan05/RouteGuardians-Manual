# RouteGuardians Manual

RouteGuardians Manual contains the complete TransitOps demonstration flow: a Bus Captain creates an incident in the Android app, an Operations Officer reviews it on the web dashboard, and the captain receives the approved route in the app.

## Guides

- [Open the published manual](https://zengzixuan05.github.io/RouteGuardians-Manual/) (starts with the Android app)
- [Open the published web-dashboard guide](https://zengzixuan05.github.io/RouteGuardians-Manual/web-dashboard/)
- [Open the published iOS web-app guide](https://zengzixuan05.github.io/RouteGuardians-Manual/ios-web-app/)
- [View the Android guide source](./android-app.md)
- [View the web-dashboard guide source](./web-dashboard.md)
- [View the iOS web-app guide source](./ios-web-app.md)

## iOS web app note

Publishing a native iOS build through TestFlight or the App Store requires paid Apple Developer Program access. For judging, the project includes a browser-based TransitOps Web version that simulates the iOS Bus Captain experience while using the same backend workflow.

## Android prototype download

[Download TransitOps-Prototype.apk](./assets/downloads/TransitOps-Prototype.apk?raw=1)

| Item | Value |
|---|---|
| App | TransitOps Prototype 1.0 |
| Package | `sg.transitops.buscaptain` |
| Minimum version | Android 8.0 |
| File size | 22,243,648 bytes (21.2 MiB) |
| SHA-256 | `740188B23B1559CE6C39855B262A34A0BD70A0AE859F5B889F4547426B2AB221` |

This is a debug-signed competition prototype, not a production Play Store or AppGallery release. Follow the complete download, security, and installation instructions in the [Android app guide](https://zengzixuan05.github.io/RouteGuardians-Manual/android-app/#install-app).

## Sample incident test case

Save both images to the test phone before starting the Bus Captain workflow:

- [Download the sample double-decker bus photo](./assets/sample-test-case/double-decker-bus.jpg?raw=1)
- [Download the sample traffic-accident photo](./assets/sample-test-case/car-accident.jpg?raw=1)

Use `double-decker-bus.jpg` as the **Bus photo** and `car-accident.jpg` as the **Incident photo**. The Android guide provides the matching test values to enter before submitting the report.

## Demo credentials

| Role | Email | Password |
|---|---|---|
| Guest / Bus Captain | `guest@guest.com` | `guest1234` |
| Administrator | `admin@admin.com` | `admin` |
