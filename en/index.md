# Privacy Policy

**Last Updated: September 18, 2026**

This Privacy Policy explains how the developer (“we”, “us”, or “our”) handles information in Oh!MyMeds (the “App”).

---

## 1. Medication and Intake Data

The App does not require user registration or an account.

- **Stored on your device**: Personal data you enter, including registered medications or supplements, intake schedules and history, inventory information, and notes, is generally stored on your device.
- **No continuous cloud sync**: The App does not continuously synchronize this personal data to our cloud.
- **Excluded from analytics and diagnostic custom fields**: The App is designed not to send medication names, free-form notes, symptom notes, or raw search terms as custom Firebase Analytics or Crashlytics fields.

## 2. Device Transfer

Only when you explicitly start Device Transfer from Settings, the App encrypts your medication and intake data on your device and sends the encrypted data to a temporary transfer service.

- Transfer content sent to and stored by the service is encrypted with a key derived locally from the recovery code. Our normal server processing does not receive medication names, intake history, notes, or symptoms in plaintext.
- Encrypted transfer data remains available for at most **72 hours**. After a successful restore or when you revoke the transfer, we make it unavailable and delete it as soon as practicable. If a temporary communication or cleanup failure occurs, the 72-hour expiry remains the final retention safeguard.
- The recovery code is required to decrypt the data on the new device. We do not store the recovery code and cannot recover or reissue a lost code.
- We use Firebase App Check and rate limits to protect the transfer service from abuse. Network information may be processed for abuse prevention; operational transfer metadata stores a one-way derived identifier rather than the raw IP address.
- Device Transfer is an explicit, temporary handoff. It is not account-based backup or continuous cloud synchronization.

## 3. Medication Search and Suggestions

When you use medication search or suggestions for a supported country, the search term you enter may be sent to a country-specific public or third-party medication information service, or to a search proxy operated by us, to return suggestions.

The App does not add your intake history, inventory information, notes, or symptom notes to those search requests. Data handling by an external service is subject to that provider’s terms and privacy policy.

## 4. Usage Analytics

The App uses **Google Firebase Analytics** to understand feature usage and improve quality. Information sent may include the app version, language or locale, feature interactions, bucketed counts, and technical app or device information.

Our custom Analytics events are designed not to include medication names, free-form notes, symptom notes, raw search terms, recovery codes, transfer capabilities, or transfer payloads. We do not use Analytics for advertising or user tracking.

## 5. Crash and Error Diagnostics

The App uses **Google Firebase Crashlytics** to investigate crashes and serious errors and improve stability. Crashlytics may collect technical information such as crash stack traces and app, OS, and device information.

Non-fatal diagnostic information added by the App is restricted to predefined operation names, stages, error classifications, and numeric codes. The App is designed not to send the original error message, file path, URL, medication name, note, search term, recovery code, transfer capability, or transfer payload as those custom diagnostic fields. We also do not set a custom Crashlytics user ID.

You can disable Crashlytics collection from **Share crash diagnostics** in Settings. A change may take full effect after the next app launch. Disabling collection does not retroactively delete information that was already transmitted before the change.

## 6. Advertising and Tracking

The App currently does not display ads and does not use Google AdMob. We do not perform advertising tracking through App Tracking Transparency (ATT).

## 7. Third-Party Services and Cloud Infrastructure

The App uses Firebase and Google Cloud services. Encrypted Device Transfer data and minimal operational metadata are temporarily processed and stored on Google Cloud infrastructure managed by us.

- [Google Privacy Policy](https://policies.google.com/privacy)
- [Firebase Privacy and Security](https://firebase.google.com/support/privacy)
- [Google Cloud Privacy Notice](https://cloud.google.com/terms/cloud-privacy-notice)

## 8. Changes to This Policy

We may update this policy when the App’s features or third-party services change. We will provide appropriate notice for material changes where required.

## 9. Contact Us

If you have questions about this Privacy Policy, contact us at:

- **Email**: k.lifetime.app+ohkusuri-support@gmail.com

---
*The Japanese version of this Privacy Policy is the reference version.*
