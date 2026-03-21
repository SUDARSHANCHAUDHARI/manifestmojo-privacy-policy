# ManifestMojo — Privacy Policy

**Effective Date:** 2026-03-21
**Last Updated:** 2026-03-21
**Version:** 1.0.0

Published by **Sudarshan Tech Labs** | https://sudarshantechlabs.com | sudarshantechlabs@gmail.com

---

ManifestMojo is a manifestation and goal-setting app for Android. It allows you to write affirmations, capture vision board images, record audio affirmations, and optionally generate AI-powered insights via Google Gemini. All personal data is stored locally on your device in an encrypted database.

---

## Data Collection

### Data Stored Locally on Your Device

| Data | Purpose | Storage |
|---|---|---|
| Goals and affirmations (text, date, category) | Core app functionality | Room database (SQLCipher encrypted) |
| Vision board images (from camera or gallery) | Visual manifestation | App private storage |
| Audio affirmation recordings | Audio manifestation | App private storage |
| App preferences and reminders | Personalisation | DataStore on your device |
| PDF exports | Data export | App private storage |

All data is encrypted using SQLCipher and stored exclusively on your device.

### Data Sent to Third-Party Services

**Google Gemini API (user-initiated only):**
When you request AI insights, the text content of your affirmations or goals is sent to the Gemini API. Sudarshan Tech Labs does not receive or store this data.

---

## How We Use Your Data

| Purpose | Data Used |
|---|---|
| Display and manage your goals and affirmations | Local encrypted data |
| Play back audio affirmations | Local audio files |
| Generate AI insights (on request) | Affirmation text sent to Gemini API |
| Send daily affirmation reminders | Local WorkManager schedules |
| Export content to PDF | Local data (iText7, on-device) |

---

## Data Storage and Security

- **Database:** AES-256 encrypted via SQLCipher
- **Photos and audio:** Stored in the App's private directory
- **No cloud storage:** Sudarshan Tech Labs operates no backend server
- **Android sandbox:** Additional protection from Android's application isolation

## Data Retention

| Data | Retention |
|---|---|
| All local app data | Until you delete it or uninstall the App |

---

## Data Sharing

We do not sell or share your data. The only external transmission is affirmation text sent to the Gemini API when you explicitly request AI insights.

---

## Permissions Explained

| Permission | Why It Is Needed |
|---|---|
| `RECORD_AUDIO` | Record audio affirmations |
| `CAMERA` | Capture vision board images |
| `READ_MEDIA_IMAGES` (Android 13+) | Select images from gallery on Android 13+ |
| `READ_EXTERNAL_STORAGE` (Android 12 and below) | Select images from gallery on older Android |
| `WRITE_EXTERNAL_STORAGE` (Android 9 and below) | Save files on Android 9 and below |
| `INTERNET` | Call the Gemini API when you request AI insights |
| `POST_NOTIFICATIONS` | Send daily affirmation reminder notifications |
| `RECEIVE_BOOT_COMPLETED` | Reschedule reminders after device restart |
| `SCHEDULE_EXACT_ALARM` | Schedule precise daily reminder alarms |
| `VIBRATE` | Haptic feedback for reminders |

---

## Your Rights and Controls

- **Delete individual entries:** Use the delete function within the App
- **Delete all data:** Uninstall or go to Android Settings > Apps > ManifestMojo > Storage > Clear Data
- **Disable reminders:** Turn off in App Settings

---

## Children's Privacy

ManifestMojo is not directed at children under 13. We do not knowingly collect personal information from children.

---

## Changes to This Policy

We may update this Privacy Policy from time to time. We will notify you of significant changes via:

- In-app notification
- Updated policy date on this page

Continued use of ManifestMojo after changes become effective constitutes your acceptance of the updated policy.

---

## Contact Us

For privacy questions, data access requests, or account deletion:

- **Email:** sudarshantechlabs@gmail.com
- **Developer:** sunny.sudarshan@gmail.com
- **Website:** https://sudarshantechlabs.com
- **Response Time:** Within 48 hours

---

## GDPR Rights (EU Users)

If you are in the European Economic Area, you have the right to:

- **Access** — Request a copy of your personal data
- **Rectification** — Correct inaccurate data
- **Erasure** — Request deletion of your data
- **Restrict Processing** — Limit how we use your data
- **Data Portability** — Receive your data in a portable format
- **Object** — Object to certain types of processing

To exercise these rights, contact us at the details above.

---

## Play Store Data Safety Summary

| Data type | Collected | Shared | Purpose |
|---|---|---|---|
| Goals and affirmations | Local only (encrypted) | No | App functionality |
| Audio recordings | Local only | No | App functionality |
| Vision board images | Local only | No | App functionality |
| Affirmation text (Gemini) | On request | Google (Gemini) | AI insights |

---

---

**This privacy policy complies with:**
- Google Play Store requirements
- GDPR (General Data Protection Regulation)
- CCPA (California Consumer Privacy Act)

**Last reviewed:** 2026-03-21
