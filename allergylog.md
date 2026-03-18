# Privacy Policy

**AllergyLog** is a food allergy tracker for iOS. It helps families track allergen introductions, log reactions, and manage allergy profiles. All data stays on your device.

## Data Collection

- AllergyLog does **not** collect any personal information
- AllergyLog does **not** upload your data to any server
- AllergyLog does **not** require an account or registration
- AllergyLog's App Store privacy label is **"Data Not Collected"**

## Health Data

AllergyLog records allergy-related information you enter, including:

- Family member profiles (names, roles)
- Allergen introduction logs (food, date, quantity, preparation method)
- Reaction entries (severity, symptoms, notes)
- Photos you attach to reaction entries

All health data is stored locally on your device using Apple's SwiftData framework. AllergyLog **never** transmits health data off your device.

## Camera and Photo Library Access

AllergyLog may request access to your camera and photo library to attach photos to reaction entries. This access is used exclusively for:

- Taking photos of allergic reactions
- Selecting existing photos from your library
- Displaying attached photos within the app

Photos are stored locally alongside your reaction data. They are never uploaded or shared.

## Local Data

All app data remains on your device:

- **Family profiles and allergy records** are stored in a local SwiftData database
- **Reaction photos** are stored locally on your device
- **Notification preferences** (introduction reminders) are stored in `UserDefaults`
- **Subscription status** is managed by Apple's App Store and RevenueCat SDK (see below)

## Subscriptions

AllergyLog offers optional in-app purchases managed through Apple's App Store and [RevenueCat](https://www.revenuecat.com). RevenueCat:

- Processes transactions through Apple's secure payment system
- Does **not** have access to your payment details (handled entirely by Apple)
- Uses an anonymous app user ID to manage entitlements
- Does **not** collect personal information beyond what is necessary for subscription management

You can learn more about RevenueCat's privacy practices at [revenuecat.com/privacy](https://www.revenuecat.com/privacy).

## Third-Party Services

| Service | Purpose | Data Shared |
|---------|---------|-------------|
| RevenueCat | Subscription management | Anonymous user ID |

No other third-party SDKs or services are used.

## Data Export

AllergyLog allows you to export your data as PDF reports or CSV files. These exports are generated on-device and shared only through the system share sheet at your discretion.

## Children's Privacy

AllergyLog does not knowingly collect any information from children under the age of 13. While the app can track allergen introductions for babies and children, all data is entered and managed by the parent or guardian.

## Changes to This Policy

We may update this Privacy Policy from time to time. Changes will be posted on this page with an updated revision date.

## Contact

If you have any questions, contact us at [contact@anhphong.dev](mailto:contact@anhphong.dev).

*Last updated: March 2026*
