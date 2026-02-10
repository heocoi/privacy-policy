# Privacy Policy

**Sotto** is a Safari content blocker for iOS and iPadOS. The app does not collect, store, or transmit any personal data to us.

## Data Collection

- Sotto does **not** collect any personal information
- Sotto does **not** include analytics, tracking, or telemetry of any kind
- Sotto does **not** require an account or registration
- Sotto's App Store privacy label is **"Data Not Collected"**

## How Content Blocking Works

Sotto uses Apple's [Safari Content Blocker API](https://developer.apple.com/documentation/safariservices/creating-a-content-blocker) — a fully declarative system. Filter rules are compiled into bytecode by Safari at install time. Sotto **cannot** see, intercept, or log your browsing activity. It has no access to the websites you visit, the pages you view, or any network requests made by Safari.

## Filter Lists

Sotto downloads open-source filter lists to keep its blocking rules up to date:

- **EasyList** — ad blocking rules
- **EasyPrivacy** — tracker blocking rules
- **EasyList Cookie** — cookie notice rules
- **Fanboy's Annoyances** — social widgets and annoyances
- **AdGuard Mobile Ads** — mobile-specific ad rules
- **NoCoin** — cryptocurrency miner blocking

These lists are fetched directly from their public repositories over HTTPS. Sotto does not proxy, modify, or log any of this traffic. Each list's content is converted into Safari-compatible JSON rules and stored locally on your device.

## Local Data

All app data remains on your device:

- **Category preferences** (which blocking categories are enabled) are stored in `UserDefaults` via an App Group shared between the app, its Safari extensions, and the home screen widget
- **Whitelist domains** you configure are stored in the same shared `UserDefaults`
- **Filter list files** (converted JSON rules) are stored in the app's shared container
- No data is transmitted to any server other than fetching the filter lists described above

## Safari Extensions

Sotto includes three Safari Content Blocker extensions (Ads, Privacy, Annoyances). These extensions:

- Run entirely within Safari's sandboxed content blocker system
- Have **no access** to page content, browsing history, or user data
- Cannot execute JavaScript or modify web pages beyond declarative blocking rules
- Communicate with the main app only through the shared App Group container

## Widget

The home screen widget displays your protection status (active rule count and enabled categories). It reads this information from `UserDefaults` on your device. No network requests are made by the widget.

## Background Updates

Sotto may periodically update filter lists in the background using iOS Background Tasks. These updates only download publicly available filter list files over HTTPS and store the results locally.

## Contact

If you have any questions, contact us at [contact@anhphong.dev](mailto:contact@anhphong.dev).

*Last updated: February 2026*
