# Privacy Policy

**Lento** is a long exposure camera app for iOS. It captures professional-grade long exposure photos using computational frame stacking powered by Metal GPU shaders. The app processes everything on-device and does not collect, store, or transmit your photos or personal data to external servers.

## Data Collection

- Lento does **not** collect any personal information
- Lento does **not** upload your photos or image data to any server
- Lento does **not** require an account or registration
- Lento does **not** use analytics or tracking SDKs
- Lento's App Store privacy label is **"Data Not Collected"**

## How Long Exposure Capture Works

Lento uses your device's camera to capture video frames and blends them in real time using Metal compute shaders to produce long exposure effects (light trails, smooth water, crowd removal, star trails). All image processing happens entirely on your device using the GPU. The final photo is saved locally to your device. No photos, frames, or image data are ever sent off your device.

## Camera Access

Lento requires camera access to capture long exposure photos. The camera is used exclusively for:

- Capturing video frames through the in-app viewfinder
- Displaying real-time blended preview during capture

Lento does not access the camera in the background (except during active Astro Suite captures with screen dimmed, which requires explicit user initiation).

## Location Access

Lento requests optional "When In Use" location access to embed GPS coordinates into photo metadata. Location data is used exclusively for:

- Embedding GPS coordinates into EXIF metadata of captured photos (opt-in, off by default)

Location data is processed entirely on-device. Lento does not store location history or transmit your location to any server. You can disable GPS metadata at any time in Settings.

## Photo Library Access

Lento requests write-only access to your Photo Library (Add Photos Only). This is used exclusively for:

- Saving captured long exposure photos to your Camera Roll

Lento cannot read, browse, or access existing photos in your library.

## Local Data

All app data remains on your device:

- **Captured photos** are saved to your Camera Roll and/or shared via the standard iOS share sheet
- **User preferences** (output format, grid overlay, capture settings) are stored in `UserDefaults` on your device
- **Purchase status** is managed entirely by Apple's App Store and StoreKit framework on-device

## In-App Purchases

Lento offers an optional one-time Pro upgrade managed entirely through Apple's App Store using StoreKit 2. All purchase transactions are processed by Apple. Lento does not have access to your payment details.

## Third-Party Services

Lento does **not** use any third-party SDKs or services. Camera capture (AVFoundation), GPU processing (Metal), image output (ImageIO), and in-app purchases (StoreKit) are all Apple system frameworks that run entirely on-device.

## Children's Privacy

Lento does not knowingly collect any information from children under the age of 13.

## Changes to This Policy

We may update this Privacy Policy from time to time. Changes will be posted on this page with an updated revision date.

## Contact

If you have any questions, contact us at [contact@anhphong.dev](mailto:contact@anhphong.dev).

*Last updated: February 2026*
