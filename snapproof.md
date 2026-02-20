# Privacy Policy

**SnapProof** is a GPS timestamp camera app for iOS. It stamps verifiable time, date, and location data directly onto your photos. The app processes everything on-device and does not collect, store, or transmit your photos or personal data to external servers.

## Data Collection

- SnapProof does **not** collect any personal information
- SnapProof does **not** upload your photos or location data to any server
- SnapProof does **not** require an account or registration
- SnapProof does **not** use analytics or tracking SDKs
- SnapProof's App Store privacy label is **"Data Not Collected"**

## How Photo Stamping Works

SnapProof uses your device's camera to capture photos and stamps them with the current time, date, GPS coordinates, and street address using on-device processing (Core Graphics). The stamped photo is saved locally to your device. No photos, thumbnails, or image data are ever sent off your device.

## Camera Access

SnapProof requires camera access to capture photos. The camera is used exclusively for:

- Capturing photos through the in-app viewfinder
- Applying real-time stamp preview overlay

SnapProof does not record video or access the camera in the background.

## Location Access

SnapProof requests "When In Use" location access to embed GPS data into your photo stamps. Location data is used exclusively for:

- Stamping GPS coordinates (latitude, longitude, altitude) onto captured photos
- Reverse geocoding your coordinates into a street address using Apple's built-in [CLGeocoder](https://developer.apple.com/documentation/corelocation/clgeocoder) service
- Displaying GPS accuracy on the camera screen

Location data is processed entirely on-device and embedded directly into your photos. SnapProof does not store location history or transmit your location to any server. The reverse geocoding request is handled by Apple's service under Apple's own privacy policy.

## Photo Library Access

SnapProof requests write-only access to your Photo Library (Add Photos Only). This is used exclusively for:

- Saving stamped photos to your Camera Roll when enabled in settings

SnapProof cannot read, browse, or access existing photos in your library.

## Local Data

All app data remains on your device:

- **Stamped photos** are stored in the app's local sandbox and optionally saved to your Camera Roll
- **Photo metadata** (capture date, GPS coordinates, template used) is stored in a local Core Data database on your device
- **User preferences** (stamp template, position, camera settings) are stored in `UserDefaults` on your device
- **Subscription status** is managed by Apple's App Store and RevenueCat SDK (see below)

## Subscriptions

SnapProof offers optional in-app purchases managed through Apple's App Store and [RevenueCat](https://www.revenuecat.com). RevenueCat:

- Processes subscription transactions through Apple's secure payment system
- Does **not** have access to your payment details (handled entirely by Apple)
- Uses an anonymous app user ID to manage entitlements
- Does **not** collect personal information beyond what is necessary for subscription management

You can learn more about RevenueCat's privacy practices at [revenuecat.com/privacy](https://revenuecat.com/privacy).

## Third-Party Services

| Service | Purpose | Data Shared |
|---------|---------|-------------|
| RevenueCat | Subscription management | Anonymous user ID |

No other third-party SDKs or services are used. Camera capture (AVFoundation), location (Core Location), and reverse geocoding (CLGeocoder) are all Apple system frameworks that run entirely on-device.

## Children's Privacy

SnapProof does not knowingly collect any information from children under the age of 13.

## Changes to This Policy

We may update this Privacy Policy from time to time. Changes will be posted on this page with an updated revision date.

## Contact

If you have any questions, contact us at [contact@anhphong.dev](mailto:contact@anhphong.dev).

*Last updated: February 2026*
