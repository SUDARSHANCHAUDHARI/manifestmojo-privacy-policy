# ManifestMojo Privacy Policy 📱🔒

<div align="center">

**Official Privacy Policy Repository for ManifestMojo Android Application**

[![Privacy](https://img.shields.io/badge/Privacy-First-green.svg)](./PRIVACY_POLICY.md)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-success.svg)](https://github.com/SUDARSHANCHAUDHARI/ManifestMojo)

*Your privacy is our priority. All your personal data stays on your device.*

</div>

---

## 📋 About This Repository

This repository hosts the official privacy policy for the **ManifestMojo** Android application. It is maintained for:

- **Public Access**: Easy access to our privacy policy
- **Google Play Store**: Required privacy policy link for app listing
- **Transparency**: Clear communication about how we handle your data
- **Compliance**: Meeting privacy regulations (GDPR, CCPA, etc.)

---

## 🎯 About ManifestMojo

**ManifestMojo** is a beautiful native Android app designed for manifestation, motivation, and personal growth. The app helps you:

- ✨ **Daily AI-Generated Posts**: Get personalized manifestation content powered by Google Gemini AI
- 💫 **Personal Affirmations**: Create and manage your own affirmations with text-to-speech support
- 📔 **Gratitude Journal**: Write daily journal entries with mood tracking
- 🔥 **Streak Tracking**: Track your consistency and maintain daily streaks
- 🔔 **Smart Notifications**: Customizable reminders for daily practice

**Learn more**: [Main ManifestMojo Repository](https://github.com/SUDARSHANCHAUDHARI/ManifestMojo)

---

## 🔒 Privacy-First Design

ManifestMojo is built with **privacy as a core principle**. We believe your personal thoughts, journal entries, and affirmations should remain private and secure.

### Core Privacy Principles

1. **Local-First Storage**: All your personal data is stored locally on your device
2. **No Cloud Storage**: We don't store your data on any remote servers
3. **No User Accounts**: No account creation required - reducing data exposure
4. **Minimal Data Collection**: We only collect what's necessary for app functionality
5. **Transparent Practices**: Clear communication about what data we access and why

---

## 📊 What Data We Collect

### Personal Content (Stored Locally Only)

- **Journal Entries**: Your daily journal entries, including:
  - Entry content (text you write)
  - Mood information (happy, neutral, sad, anxious, angry)
  - Date and timestamp
- **Affirmations**: Custom affirmations you create, including:
  - Affirmation text
  - Category (Wealth, Health, Love, Success, Gratitude, General)
  - Creation date and play count
- **Daily Posts**: AI-generated daily manifestation posts that you save or favorite
- **Activity Logs**: Your app usage data for streak tracking

### App Preferences (Stored Locally Only)

- Theme settings (Light, Dark, System Default)
- Notification preferences (times, frequency)
- API key (if you provide your own Google Gemini API key)
- Onboarding completion status

### What We DON'T Collect

- ❌ Personal identification information (name, email, phone)
- ❌ Location data
- ❌ Contact information
- ❌ Payment information
- ❌ Biometric data
- ❌ Device identifiers for tracking

---

## 💾 Data Storage & Security

### Local Storage

**All your personal data is stored locally on your device using:**

- **Room Database**: Encrypted local database for journal entries, affirmations, and daily posts
- **DataStore**: Secure local storage for app preferences
- **No Cloud Sync**: Your data never leaves your device

### Security Measures

- ✅ **Encryption**: All local data is encrypted using Android's built-in encryption
- ✅ **No Network Transmission**: Journal entries and affirmations are never sent over the network
- ✅ **Secure API Keys**: API keys stored securely using DataStore
- ✅ **Regular Updates**: Security patches and updates applied regularly

### Data Retention

- **Journal Entries**: Retained until you delete them manually
- **Affirmations**: Retained until you delete them manually
- **Daily Posts**: Cached locally for offline access
- **Activity Logs**: Retained for streak calculation
- **Uninstall**: All data is deleted when you uninstall the app

---

## 🌐 Third-Party Services

### Google Gemini API

- **Purpose**: Generate personalized daily manifestation posts
- **Data Sent**: Only your selected category (e.g., "wealth", "health")
- **Data NOT Sent**: 
  - ❌ Your journal entries
  - ❌ Your affirmations
  - ❌ Personal information
  - ❌ Device identifiers
- **Privacy Policy**: [Google Privacy Policy](https://policies.google.com/privacy)

### Google Play Services (Optional)

- **Purpose**: Analytics and crash reporting (if enabled)
- **Data Collected**: Aggregated, anonymized usage statistics
- **No Personal Data**: No personally identifiable information is collected

---

## 🔐 Permissions Explained

### Required Permissions

| Permission | Purpose | Why Needed |
|------------|---------|------------|
| **INTERNET** | Connect to Google Gemini API | Generate daily posts (optional - app works offline for saved content) |
| **POST_NOTIFICATIONS** | Send push notifications | Daily reminders based on your preferences |
| **RECEIVE_BOOT_COMPLETED** | Restore notifications after restart | Ensure notifications work after device restart |
| **SCHEDULE_EXACT_ALARM** | Precise notification scheduling | Accurate reminder timing |
| **VIBRATE** | Haptic feedback | Better user experience |

### Privacy Controls

- ✅ **Offline Mode**: App works without internet connection
- ✅ **Notification Control**: Enable/disable notifications anytime
- ✅ **API Key Control**: Use your own Gemini API key or default (if available)
- ✅ **Data Export**: Export your journal entries anytime
- ✅ **Data Deletion**: Delete individual entries or all data

---

## 👤 Your Rights

### Data Control

- **View Your Data**: Access all your journal entries, affirmations, and posts in the app
- **Edit Your Data**: Modify or delete entries and affirmations anytime
- **Export Your Data**: Export journal entries to text files (Settings → Export)
- **Delete Your Data**: Clear individual entries or all data (Settings → Clear All Data)
- **Uninstall**: Uninstalling removes all local data

### GDPR Rights (EU Users)

If you're in the European Union, you have additional rights:

- ✅ **Right to Access**: View all your personal data
- ✅ **Right to Rectification**: Edit inaccurate data
- ✅ **Right to Erasure**: Delete your data at any time
- ✅ **Right to Data Portability**: Export your data in a portable format
- ✅ **Right to Object**: Disable analytics (if implemented)

**How to Exercise**: Use the app's built-in features or contact us directly.

---

## 📱 App Information

- **Package Name**: `com.sudarshantechlabs.manifestmojo`
- **Version**: 1.0.0
- **Min SDK**: 24 (Android 7.0)
- **Target SDK**: 36 (Android 16)
- **Platform**: Android only
- **Language**: Kotlin
- **Architecture**: MVVM with Jetpack Compose

---

## 📄 Privacy Policy

The complete, detailed privacy policy is available in [PRIVACY_POLICY.md](./PRIVACY_POLICY.md).

**Key Sections:**
- Information We Collect
- How We Use Your Information
- Data Storage & Retention
- Data Sharing
- Your Rights and Controls
- Children's Privacy
- Permissions Explained
- Security Measures
- GDPR Rights
- Contact Information

---

## 🚨 Important Privacy Highlights

### ✅ What We Do

- Store all data locally on your device
- Use encryption for local storage
- Only send category selection to Gemini API (not your content)
- Allow you to export or delete your data anytime
- Work offline for most features
- Respect your privacy choices

### ❌ What We DON'T Do

- Store your data in the cloud
- Share your data with third parties
- Sell your data
- Track you across apps or websites
- Require user accounts
- Collect location data
- Access your contacts or photos

---

## 📞 Contact & Support

### Privacy-Related Questions

If you have questions about:
- How we handle your data
- Your privacy rights
- Data deletion requests
- GDPR compliance
- Security concerns

**Contact Us:**
- **Email**: sudarshantechlabs@gmail.com
- **Developer Email**: sunny.sudarshan@gmail.com
- **Website**: https://sudarshantechlabs.com
- **GitHub Issues**: [ManifestMojo Repository](https://github.com/SUDARSHANCHAUDHARI/ManifestMojo/issues)

### Response Time

We aim to respond to privacy-related inquiries within **48 hours**.

---

## 🔄 Policy Updates

We may update this privacy policy from time to time to reflect:
- Changes in app features
- Legal requirements
- Best practices
- User feedback

**How We Notify You:**
- In-app notifications for significant changes
- App update release notes
- Updated "Last updated" date in the policy

**Last Updated**: January 2025

---

## 📚 Additional Resources

- **[Main App Repository](https://github.com/SUDARSHANCHAUDHARI/ManifestMojo)**: Source code and documentation
- **[Google Privacy Policy](https://policies.google.com/privacy)**: Third-party service privacy
- **[GDPR Information](https://gdpr.eu/)**: European privacy regulations
- **[CCPA Information](https://oag.ca.gov/privacy/ccpa)**: California privacy regulations

---

## 🏢 About Sudarshan Tech Labs

**ManifestMojo** is developed and published by **Sudarshan Tech Labs**.

- **Company**: Sudarshan Tech Labs
- **Website**: https://sudarshantechlabs.com
- **Email**: sudarshantechlabs@gmail.com
- **Developer**: Sudarshan Kishor Chaudhari
- **Developer Email**: sunny.sudarshan@gmail.com

---

## 📜 License

This privacy policy repository is licensed under the **MIT License**.

See [LICENSE](./LICENSE) file for details.

---

## ⭐ Quick Privacy Summary

<div align="center">

### 🔒 Your Data Stays Local

**All your personal content (journal entries, affirmations) is stored on your device and never sent to any server.**

| Feature | Privacy Status |
|---------|---------------|
| Journal Entries | ✅ 100% Local |
| Affirmations | ✅ 100% Local |
| Daily Posts | ✅ Cached Locally |
| App Preferences | ✅ Stored Locally |
| Analytics | ⚠️ Optional (Anonymized) |

</div>

---

<div align="center">

**Made with ❤️ by Sudarshan Tech Labs**

*Privacy is not a feature - it's a fundamental right.*

[View Full Privacy Policy](./PRIVACY_POLICY.md) | [Main App Repository](https://github.com/SUDARSHANCHAUDHARI/ManifestMojo)

</div>
