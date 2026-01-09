# Privacy Policy

**HotspotPeek** is designed with privacy in mind. The app does not collect, store, or transmit any personal data to us or any third-party services.

## Data Collection

- No personal information collected by the app
- No usage analytics or tracking
- No accounts or registration required
- No data transmitted to external servers

## Permissions

HotspotPeek requires the following permissions to function:

### Location Permission (Required)

HotspotPeek requests location permission **only** to identify which WiFi network (SSID) you are connected to. This is a macOS Sonoma+ system requirement for accessing WiFi network names.

**Important:** Your actual physical location is never accessed, tracked, stored, or transmitted. The location permission is used exclusively to read the WiFi network name from your Mac's system configuration.

### Network Permission (Required)

HotspotPeek requires network access (`com.apple.security.network.client`) to:
- Detect when you connect to a hotspot (using NWPathMonitor)
- Monitor network interface statistics to calculate data usage
- Track download and upload bytes on active connections

This monitoring happens entirely on your device. No data is sent to us or any external service.

### Notification Permission (Optional)

HotspotPeek can send local notifications to alert you when:
- Your data usage reaches a configured threshold (50%, 75%, 90%)
- A new hotspot is detected

These notifications are processed entirely on your device and are not transmitted anywhere. You can disable notifications at any time in System Settings.

## Local Data Storage

All data is stored locally on your Mac using UserDefaults and never leaves your device:

- **Hotspot Profiles** - Name, SSID, data limits, reset cycles, alert settings
- **Usage Data** - Total bytes used per profile, last reset date, last used date
- **Session History** - Connection times and data usage per session
- **App Settings** - Unknown hotspot behavior, menu bar display preferences, launch at login

## What We Don't Do

- We do not collect or store your location data
- We do not track which networks you connect to
- We do not monitor the content of your network traffic
- We do not use analytics or crash reporting services
- We do not share any data with third parties
- We do not have access to any of your data

## App Sandbox

HotspotPeek runs in the macOS App Sandbox with these entitlements:

- `com.apple.security.app-sandbox` - Ensures the app is sandboxed
- `com.apple.security.network.client` - Allows network monitoring
- `com.apple.security.personal-information.location` - Allows reading WiFi SSID

These are the minimum permissions required for the app to function.

## Data Security

All data stored locally on your Mac is protected by macOS security features including:
- App Sandbox restrictions
- File system permissions
- UserDefaults encryption (when FileVault is enabled)

## Contact

Questions about privacy? Contact [me](mailto:contact@anhphong.dev).

*Last updated: January 2026*
