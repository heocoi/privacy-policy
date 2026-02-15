# Privacy Policy

**Snapsift** is a photo duplicate finder app for iOS. It uses on-device AI to detect similar and duplicate photos in your library. The app does not collect, store, or transmit any personal data or photos to external servers.

## Data Collection

- Snapsift does **not** collect any personal information
- Snapsift does **not** upload your photos or any image data to any server
- Snapsift does **not** require an account or registration
- Snapsift's App Store privacy label is **"Data Not Collected"**

## How Photo Analysis Works

Snapsift uses Apple's [Vision framework](https://developer.apple.com/documentation/vision) to generate feature vectors from your photos entirely on-device. These vectors are used to compute similarity scores between photos and identify duplicates. Snapsift **cannot** and does **not** send your photos, thumbnails, or any visual data off your device.

## Photo Library Access

Snapsift requires access to your Photo Library to scan for duplicates and similar photos. This access is used exclusively for:

- Reading photo metadata (date, size, resolution)
- Generating on-device feature vectors for similarity comparison
- Displaying thumbnails within the app
- Deleting photos you explicitly select for removal (via the system Photos deletion prompt)

Snapsift never modifies or deletes photos without your explicit confirmation through Apple's standard photo deletion dialog.

## Local Data

All app data remains on your device:

- **Feature vector cache** (numerical representations of photos for fast re-scanning) is stored in a local SQLite database on your device
- **Scan results** (group information, similarity scores) are stored locally and never transmitted
- **Subscription status** is managed by Apple's App Store and RevenueCat SDK (see below)
- **User preferences** (onboarding state, delete counts) are stored in `UserDefaults` on your device

## Analytics

Snapsift uses [TelemetryDeck](https://telemetrydeck.com) for privacy-respecting analytics. TelemetryDeck:

- Does **not** collect personally identifiable information
- Does **not** use cookies or fingerprinting
- Does **not** track users across apps
- Only collects anonymous, aggregated usage signals (e.g., "scan completed", "app launched")
- Is fully GDPR compliant

You can learn more about TelemetryDeck's privacy practices at [telemetrydeck.com/privacy](https://telemetrydeck.com/privacy).

## Subscriptions

Snapsift offers optional in-app subscriptions managed through Apple's App Store and [RevenueCat](https://www.revenuecat.com). RevenueCat:

- Processes subscription transactions through Apple's secure payment system
- Does **not** have access to your payment details (handled entirely by Apple)
- Uses an anonymous app user ID to manage entitlements
- Does **not** collect personal information beyond what is necessary for subscription management

You can learn more about RevenueCat's privacy practices at [revenuecat.com/privacy](https://www.revenuecat.com/privacy).

## Third-Party Services

| Service | Purpose | Data Shared |
|---------|---------|-------------|
| Apple Vision Framework | On-device photo analysis | None (fully on-device) |
| TelemetryDeck | Anonymous usage analytics | Anonymous signals only |
| RevenueCat | Subscription management | Anonymous user ID |

No other third-party SDKs or services are used.

## Children's Privacy

Snapsift does not knowingly collect any information from children under the age of 13.

## Changes to This Policy

We may update this Privacy Policy from time to time. Changes will be posted on this page with an updated revision date.

## Contact

If you have any questions, contact us at [contact@anhphong.dev](mailto:contact@anhphong.dev).

*Last updated: February 2026*
