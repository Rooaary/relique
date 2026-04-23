# Privacy Policy for Relique

**Effective date:** April 22, 2026

Relique is a mobile app that helps you identify and catalog antiques using AI. This policy explains what data the app collects, how it is used, and who has access to it.

**Developer:** Rory Watson
**Contact:** RAWorks2000@gmail.com

---

## The short version

- Your collection data stays on your device.
- Photos sent for AI identification are not stored on any server.
- There are no user accounts, no logins, and no email collection.
- Ads are shown to free-tier users and involve standard ad tracking.
- Subscription purchases are handled by RevenueCat through Google Play.

---

## What data the app collects

### Photos you submit for identification

When you use the identification feature, the photo you take is sent to Google's Gemini model via Google Cloud Vertex AI for analysis. Google processes the image to return identification results. The photo is **not stored** on our servers or any server we control. Google's handling of that data is governed by [Google's Privacy Policy](https://policies.google.com/privacy).

### Device integrity attestation

To protect the service from abuse and fraudulent usage, Relique uses Firebase App Check with the Google Play Integrity API. When you make an identification request, your device generates a short-lived attestation token (not a personal identifier) that is verified by Google and Relique's backend. This is the standard Android anti-abuse mechanism; it does not transmit any personal data. See [Google's Play Integrity API documentation](https://developer.android.com/google/play/integrity/verdicts) for details.

### Your collection

All items, photos, notes, and other collection data you create in Relique are stored **locally on your device** using SQLite. This data never leaves your phone unless you choose to share it yourself.

### Camera and storage permissions

The app requests camera access so you can take photos of items for identification. Storage access is used to save photos to your local collection. These permissions are only used for app functionality — nothing is uploaded or shared without your action.

### Advertising data (free-tier users)

If you use the free version of Relique, Google AdMob displays ads within the app. AdMob may collect device identifiers, ad interaction data, and other standard advertising information as described in [Google's Advertising Privacy Policy](https://policies.google.com/technologies/ads).

### Subscription and purchase data

Subscriptions are managed through RevenueCat, which processes purchase information through Google Play. RevenueCat receives transaction data (purchase tokens, subscription status) but does not receive your name, email, or any personal contact information from us. See [RevenueCat's Privacy Policy](https://www.revenuecat.com/privacy/) for details.

## What the app does NOT collect

- Email addresses
- Names or personal information
- Location data
- Contacts
- Usage analytics beyond basic crash reporting (Firebase Crashlytics)
- Account credentials (there are no accounts)

## Third-party services

| Service | Purpose | Data involved |
|---------|---------|---------------|
| Google Cloud Vertex AI (Gemini) | AI-powered antique identification | Photos submitted for analysis |
| Firebase App Check + Play Integrity API | Device attestation to prevent abuse | Short-lived non-personal attestation tokens |
| Google AdMob | Advertising (free tier) | Device identifiers, ad interaction data |
| RevenueCat | Subscription management | Google Play purchase tokens and subscription status |
| Firebase Crashlytics | Crash reporting | Device info, crash logs (no personal identifiers) |

Each of these services has its own privacy policy governing how they handle data.

## Data storage and security

Your collection data is stored locally on your device. We do not operate servers that store your personal data. If you uninstall the app, your local data is deleted.

## Children's privacy

Relique is not directed at children under 13. We do not knowingly collect data from children.

## Changes to this policy

If this policy changes, the updated version will be posted at [https://rooaary.github.io/relique/privacy-policy](https://rooaary.github.io/relique/privacy-policy) with a new effective date.

## Contact

If you have questions about this policy, reach out at **RAWorks2000@gmail.com**.
