# batterylevel

A new Flutter application.

## Getting Started

Calling platform-specific iOS and Android code using platform channels

The following code demonstrates how to call a platform-specific API to retrieve and display the current battery level. It uses the Android BatteryManager API, and the iOS device.batteryLevel API, via a single platform message, getBatteryLevel().

The example adds the platform-specific code inside the main app itself. If you want to reuse the platform-specific code for multiple apps, the project creation step is slightly different (see developing packages), but the platform channel code is still written in the same way.

Documentation: https://flutter.dev/docs/development/platform-integration/platform-channels?tab=ios-channel-objective-c-tab


