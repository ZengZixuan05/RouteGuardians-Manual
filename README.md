# RouteGuardians Manual

RouteGuardians Manual contains the complete TransitOps demonstration flow. A Bus Captain creates the prepared Service 45 incident in either the Android app or iOS web app, an Operations Officer reviews it on the web dashboard, and the captain returns to the same mobile workflow to receive the approved route.

## Guides

- [Open the published manual](https://zengzixuan05.github.io/RouteGuardians-Manual/) (starts with the Android/iOS workflow chooser)
- [Open the published web-dashboard guide](https://zengzixuan05.github.io/RouteGuardians-Manual/web-dashboard/)
- [Open the published iOS web-app guide](https://zengzixuan05.github.io/RouteGuardians-Manual/ios-web-app/)
- [View the Android guide source](./android-app.md)
- [View the web-dashboard guide source](./web-dashboard.md)
- [View the iOS web-app guide source](./ios-web-app.md)

## iOS web app note

Publishing a native iOS build through TestFlight or the App Store requires paid Apple Developer Program access. The project therefore includes a browser-based TransitOps Web version that simulates the iOS Bus Captain experience while using the same backend workflow and prepared Service 45 test case.

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

## Sample Service 45 incident test case

Save both images to the test device before starting either Bus Captain workflow:

- [Download the sample Service 45 double-decker bus photo](./assets/sample-test-case/bus-service-45.png?raw=1)
- [Download the sample traffic-accident photo](./assets/sample-test-case/car-accident.jpg?raw=1)

Use `bus-service-45.png` as the **Bus photo** and `car-accident.jpg` as the **Incident photo**. For the route-specific field, select **Direction 1 towards Yio Chu Kang**. Both mobile guides provide the remaining matching values to verify before submitting the report.

## Demo credentials

| Role | Email | Password |
|---|---|---|
| Guest / Bus Captain | `guest@guest.com` | `guest1234` |
| Administrator | `admin@admin.com` | `admin` |
