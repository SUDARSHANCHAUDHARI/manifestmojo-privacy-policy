# ManifestMojo Privacy Policy

**Effective Date:** May 17, 2026
_Last updated: November 9, 2026_
**Version:** 1.2.0

ManifestMojo ("we," "our," or "us") is an Android app. ManifestMojo is a manifestation and journaling app for Android with local goals, intentions, daily posts, media, reminders, and optional AI assistance. This Privacy Policy explains what information the app collects, how it is used, and the choices you have. By installing or using ManifestMojo you agree to the practices described below.

## Information We Collect

### Location Data
- ManifestMojo does not collect location data.

### Account Information
- No account is required to use ManifestMojo.

### Device Information
- Journal entries, intentions, goals, daily posts, affirmations, activity logs, preferences, reminder settings, and the Gemini API key you provide are stored on your device.
- **Your journal and goals are held in an encrypted database.** The app uses SQLCipher, and the key is generated per installation and wrapped by a key held in the Android Keystore. If that key cannot be unwrapped the app shows an error rather than falling back to an unencrypted database.

## How We Use Your Information

### Location Sharing
- ManifestMojo does not use your location.

### Account Management
- Manage manifestation goals, journal entries, reminders, and daily content locally.
- Use optional AI features only when you request them.

### Service Improvement
- Improve local manifestation and journaling workflows.
- We do not sell, rent, or monetize your journal content.

## Storage and Retention

### Data Storage
- Personal content and preferences are stored on your device, in an encrypted Room database and in DataStore.
- **The AI feature does not send your journal, goals or any text you wrote.** When you ask for a daily post or an affirmation, the app sends Google Gemini a request containing only the category you picked — wealth, health, love, success, gratitude or general — and the day of the week. Nothing you typed is included. Earlier versions of this policy said "the selected prompt/content may be sent", which claimed more than the app does.

### Data Retention
- Local content remains until you delete it, clear app data, or uninstall the app.

### Data Security
- On your device, your journal and goals sit in a SQLCipher-encrypted database inside the app's private storage, protected by Android's application sandbox as well as that encryption.
- In transit, the one network call the app makes — to the Google Gemini API, only when you ask for an affirmation and only if you have supplied a key — is over HTTPS.
- **No Sudarshan Tech Labs server exists**, so there is no third place holding your data.
- ManifestMojo is an Android app only; there is no web or browser version of it, and it uses no Firebase and no GitHub service.
- You should protect your device with a screen lock, since that is what stands between someone holding your phone and your journal.

## Data Sharing

### Sharing With Other People
- **ManifestMojo has no sharing, pairing or collaboration features.** It is a single-user app; there is nobody to share your journal with.

### Third Parties
- **Google Gemini** receives a category name and the day of the week when you request an affirmation or a daily post. It receives none of your journal, goals or notes.
- The request cannot happen at all unless you have pasted your own Gemini API key into Settings. The key is stored on your device. With no key, the app makes no network request. Because the call uses your own key, Google processes it under your own Google AI account and terms rather than ours.
- No journal content is sent to Sudarshan Tech Labs servers, because no such server exists.

We do **not** share your data with:
- Data brokers
- Unrelated advertising networks, unless advertising is explicitly listed above for this app
- Third parties unrelated to the app features described in this policy

## Permissions Used

### Required Permissions

* **INTERNET**: Used only for the optional Gemini request described above.
* **POST_NOTIFICATIONS, RECEIVE_BOOT_COMPLETED, SCHEDULE_EXACT_ALARM, VIBRATE**: Used for reminders.

**Removed:** earlier versions of this policy listed `CAMERA`, `READ_MEDIA_IMAGES`, `READ_EXTERNAL_STORAGE` and `WRITE_EXTERNAL_STORAGE` as being "used for media capture/import/export features". **The app has no camera or photo feature.** Those four permissions were declared in the manifest without any code using them, and they have been removed from the app.

### Permissions added by Android libraries

The app declares the five above. The finished build carries three more, declared by WorkManager — which runs your scheduled reminders and affirmation generation — rather than by the app's own code. They appear in the permission list you see on the Play Store:

* **WAKE_LOCK**: lets scheduled work run while the phone is idle.
* **FOREGROUND_SERVICE**: how WorkManager runs that work.
* **ACCESS_NETWORK_STATE**: lets a library check whether a network exists before attempting to send; it grants no ability to use one.

Verified against the merged manifest of the release build rather than the app's own manifest file.

### Optional Permissions

* The AI affirmations and the reminders are optional features you control. The AI feature additionally requires you to supply your own API key.

## Your Rights and Controls

### Location Sharing Control
- No location sharing exists in ManifestMojo.

### Account Management
- No account is required.

### Data Access
- You can view, edit, export, or delete local journal and manifestation data in the app.

### GDPR Rights (EU Users)
If you are in the European Union, you have additional rights:
- **Right to Access**: Request a copy of your personal data
- **Right to Rectification**: Correct inaccurate data
- **Right to Erasure**: Request deletion of your data
- **Right to Restrict Processing**: Limit how we use your data
- **Right to Data Portability**: Receive your data in a portable format
- **Right to Object**: Object to certain types of processing

To exercise these rights, contact us using the methods in the Contact Us section.

### Permissions
- You can revoke Android permissions in Android Settings -> Apps -> ManifestMojo -> Permissions.
- Revoking required permissions may prevent related features from functioning.

## Children's Privacy

- Our app is **not intended for children under 13**.
- We do not knowingly collect data from children under 13.
- If you are a parent or guardian and believe your child has provided personal information, please contact us to request deletion.
- Parents and guardians should supervise children's use of apps that store personal content.

## Security

- Local data is protected by Android's application sandbox, and your journal and goals additionally by SQLCipher encryption.
- Network communication uses HTTPS/TLS where applicable.
- Third-party services named in this policy provide their own security controls and privacy policies.
- You are responsible for protecting your device, which for this app means a screen lock, and the Gemini API key you paste in.
- We do not sell your personal data.

## Changes to This Policy

We may update this Privacy Policy to reflect new features, legal requirements, or changes in our practices. Significant changes will be:
- Noted in the app release notes or repository when applicable
- Reflected with a new "Last updated" date
- Communicated in the app or project page if the change is significant

The "Last updated" date at the top of this policy indicates when revisions occurred. Continued use of the app after changes constitutes acceptance of the updated policy.

## Contact Us

If you have questions about this Privacy Policy, wish to request data deletion, or have privacy concerns:

* **GitHub Repository:** https://github.com/SUDARSHANCHAUDHARI/manifestmojo-privacy-policy
* **Email:** sunny.sudarshan@gmail.com
* **Main App Repository:** https://github.com/SUDARSHANCHAUDHARI/ManifestMojo

We will respond as quickly as possible, typically within 48 hours.

## Data Deletion

### How to Delete Your Account:
This app does not require an account. You can delete local app data using the options below:

#### Option 1: In-App Deletion
1. Open ManifestMojo
2. Delete individual entries, reminders, history, or settings where the app provides controls
3. Or clear the app's data from Android Settings
4. Uninstalling the app also removes local app-private data

#### Option 2: Email Deletion Request
Send an email to: **support@sudarshantechlabs.com** or **sunny.sudarshan@gmail.com**
- Subject: "Data Deletion Request - ManifestMojo"
- Include: The email/account identifier used in the app, if any
- We will process deletion requests as quickly as possible, typically within 48 hours for acknowledgement

#### Option 3: Web Deletion
1. Visit the privacy policy website for contact and support information
2. Uninstalling the app removes its local data, including the encrypted database
3. For Android apps, clear storage from Android Settings if you want a full local reset

### What Gets Deleted:
- Local app data stored by the app
- Local preferences and reminder/history records
- Cached data controlled by the app
- Exported/shared files only if you delete them from where you saved them

### Data Retention After Deletion:
- **Immediate:** clearing app data removes local app-private data from your device
- **Uninstall:** removes app-private local data from Android apps
- **Exports/shared files:** remain wherever you saved or sent them until you delete them

To request deletion of your data:

1. Open ManifestMojo, if installed
2. Delete local content or clear app/site data where applicable
3. Contact support via email: sunny.sudarshan@gmail.com
4. Request account/data deletion and include enough detail for us to identify the app and any account, if one exists
5. We will confirm what data can be deleted and complete the request according to the retention terms above

## Third-Party Services

One, and only if you choose to use it:

- **Google Gemini API**, for the optional affirmation and daily-post generation, using an API key you supply yourself

**The app uses no Firebase**, no analytics, no crash reporting, no advertising SDK and no backend of ours.

Please review the relevant third-party terms:

- [Google Privacy Policy](https://policies.google.com/privacy)
- [Gemini API Additional Terms of Service](https://ai.google.dev/gemini-api/terms)
- [Google Play Terms](https://play.google.com/about/play-terms/)

## About ManifestMojo

ManifestMojo is built with privacy in mind. The app is built with:
- Kotlin and Jetpack Compose
- A SQLCipher-encrypted Room database for your journal, goals and affirmations
- Optional Google Gemini AI features, using a key you supply
- Android reminders

There is no "media support": the app has no camera or photo feature. Your journal stays on your device, and the only thing that ever leaves it is a category name and a day of the week, when you ask for an affirmation.

---

**Last Updated:** November 9, 2026

---

## Recent Updates (Version 1.2.0 - November 9, 2026)

- **Said what the AI feature actually sends, which is far less than this policy claimed.** The old wording was "the selected prompt/content may be sent to Google Gemini" and "Gemini may receive selected text". The request contains only the category you picked and the day of the week. **None of your journal, goals or notes is sent.** A policy that overstates what leaves your device is still a wrong policy.
- **Said the AI feature needs your own API key.** The app has no key built in; with no key in Settings it makes no network request at all, and because the call uses your key, Google processes it under your own account and terms.
- **Disclosed that your journal and goals are in an encrypted database.** SQLCipher, with a per-installation key wrapped by the Android Keystore, and no unencrypted fallback. This had never been mentioned, which is odd given it is the strongest protection the app has.
- **Removed the camera and photo permissions, which described features that do not exist.** `CAMERA`, `READ_MEDIA_IMAGES`, `READ_EXTERNAL_STORAGE` and `WRITE_EXTERNAL_STORAGE` were listed as "used for media capture/import/export features"; no code in the app used any of them. They have now been removed from the app itself too.
- **Listed the three permissions WorkManager merges in** — `WAKE_LOCK`, `FOREGROUND_SERVICE` and `ACCESS_NETWORK_STATE` — and noted that the last lets a library check for a network without being able to use one.
- **Removed the scaffold text** shared with sibling policies: a "Family Groups" heading for a single-user app, and references to a browser, a browser profile, browser site settings, Firebase and GitHub accounts. ManifestMojo is an Android app with no web version and uses neither Firebase nor any GitHub service.

## Recent Updates (Version 1.1.0 - May 17, 2026)

- **Aligned policy with the shared privacy-policy structure.**
- **Clarified local journal/manifestation data, optional AI, reminders, and media permissions.**
