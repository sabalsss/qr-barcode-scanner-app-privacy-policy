# Privacy Policy — QR Code Scan

**Effective Date:** January 2025

This Privacy Policy describes how the QR Code Scan app ("the App") handles your information. We designed the App to scan QR codes and barcodes on your device with privacy in mind.

## Summary
- **Minimal data collection**: We collect only essential data for app functionality and user feedback.
- **On-device processing**: Camera frames used for scanning stay on your device and are not uploaded.
- **Transparent data handling**: All data collection is clearly disclosed and optional where possible.

## Information We Collect

### Email Addresses
- **When collected**: Only when you voluntarily send feedback through the app
- **Purpose**: To respond to your feedback and improve the app
- **Sharing**: Email addresses are shared with email service providers (Gmail, etc.) to enable feedback functionality
- **Retention**: We do not store email addresses on our servers
- **Optional**: You can use the app without ever providing an email address

### App Interaction Data
- **When collected**: Automatically during app usage for core functionality
- **Purpose**: Required for barcode scanning functionality through Google ML Kit
- **Sharing**: Shared with Google for analytics purposes to improve ML services
- **Processing**: Data is processed ephemerally (in memory only)
- **Required**: This data collection is necessary for the app's core scanning feature

### Camera Input (On-Device Only)
- **Processing**: Camera frames are processed locally and are not stored or transmitted
- **Purpose**: Solely to detect and decode QR codes and barcodes in real time
- **Retention**: Frames are discarded immediately after processing

### Scan Results
- **Storage**: Scan history is stored locally on your device only
- **Sharing**: Results are only shared when you choose to act on them (open URLs, share content, etc.)

## Permissions We Use and Why

- `android.permission.CAMERA`: Enables scanning QR codes and barcodes with the device camera.
- `android.permission.VIBRATE`: Provides optional haptic feedback after a successful scan.
- `android.permission.ACCESS_NETWORK_STATE` and `android.permission.INTERNET`: Allows the App to open links you choose, fetch website titles, and check connectivity when needed for user-initiated actions.
- `android.permission.ACCESS_WIFI_STATE` and `android.permission.CHANGE_WIFI_STATE`: Lets the App read Wi-Fi status and help you connect to Wi-Fi networks from QR codes.
- `android.permission.ACCESS_FINE_LOCATION` and `android.permission.ACCESS_COARSE_LOCATION`: Used for location-based QR code functionality (maps, directions).

## Data Sharing

### Third-Party Services
- **Email Service Providers**: When you send feedback, your email address is shared with email service providers (Gmail, Outlook, etc.)
- **Google ML Kit**: App interaction data is shared with Google for analytics and service improvement
- **Website Servers**: When fetching website titles, URLs are transmitted to the respective website servers

### What We Don't Share
- We do not sell, rent, or share your personal data with advertisers
- We do not share scan history or camera data
- We do not share data with analytics or advertising SDKs

## Data Retention

- **Email addresses**: Not stored on our servers; only used for feedback responses
- **App interaction data**: Processed ephemerally and not retained
- **Camera frames**: Processed in memory and discarded immediately
- **Scan history**: Stored locally on your device until you clear it
- **Website titles**: Cached temporarily for display purposes

## Data Security

- All data transmission is encrypted in transit (HTTPS, TLS)
- Camera processing happens entirely on-device
- We take reasonable measures to protect any data we handle
- No method is 100% secure, but we minimize data collection and transmission

## Your Rights and Choices

- **Email collection**: Completely optional - you can use the app without providing your email
- **App interaction data**: Required for core functionality, but processed ephemerally
- **Scan history**: You can clear this data anytime through the app settings
- **Data deletion**: Uninstalling the app removes all local data

## Third-Party Libraries

The app uses the following libraries that may collect data:
- **Google ML Kit**: For barcode scanning functionality
- **ZXing**: For barcode processing (no data collection)
- **CameraX**: For camera functionality (no data collection)
- **Room Database**: For local data storage (no data collection)

## Changes to This Policy

We may update this Privacy Policy to reflect improvements or legal requirements. Updates will be posted in this file and/or on the App's store listing with a new effective date. Continued use of the app after changes constitutes acceptance of the updated policy.

## Contact Us

If you have questions about this Privacy Policy or the App, contact us at: **sabaldev670@gmail.com**

---

*This privacy policy complies with Google Play Console data safety requirements and accurately reflects our data collection practices.*
