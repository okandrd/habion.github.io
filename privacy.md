# Habion — Privacy Policy

_Effective date: May 20, 2026_
_Last updated: May 20, 2026_

Habion ("the app", "we", "us") is a habit tracking app built by **Ininia** (the "developer"). This Privacy Policy explains what data the app handles and how.

Habion is designed to be **local-first**. The app does not require an account, sign-up, or cloud sync. The habits, completions and settings you create stay on your device.

---

## 1. What we collect

### 1.1 Stored on your device only

- Habit definitions (title, color, icon, schedule, optional reminder time)
- Completion history (date and time of each check-in)
- App preferences (language, time format, notification toggle, week start)

This data lives in encrypted local storage (MMKV) on your phone. **It is never transmitted to our servers** because we don't operate any. Uninstalling the app deletes all of this data permanently.

### 1.2 Diagnostics (release builds only)

When the app crashes or hits an unexpected error in a release build, we receive an anonymous diagnostic report via [Sentry](https://sentry.io). These reports may include:

- The crash stack trace and a short log of in-app events leading up to the crash
- Device model, OS version, app version
- An anonymous install identifier (random UUID generated on first launch)
- IP address (used briefly by Sentry for coarse geolocation, then discarded per [Sentry's data retention policy](https://docs.sentry.io/security-legal-pii/security/ip-address-retention/))

We use these reports **only** to find and fix bugs. We do not link them to your identity (we don't have one).

Diagnostic reporting is **disabled in development builds**. It is only active in App Store / Play Store releases.

Sentry's privacy policy: <https://sentry.io/privacy/>

### 1.3 What we do NOT collect

- No email, name, phone number, address, age, or other personal details
- No location data
- No contacts, photos, calendar, microphone, or camera access
- No advertising identifiers (IDFA / GAID)
- No third-party analytics or tracking SDKs
- No social-network connections
- No biometric data
- No keystroke or screen recording

---

## 2. Notifications

Habion schedules **local notifications** for habit reminders and daily motivation nudges. Notifications are generated on your device by iOS / Android — we do not operate a push-notification server.

You control notifications via your system Settings, or inside Habion under **Settings → Notifications**.

---

## 3. Permissions

| Permission | Why it's needed |
| --- | --- |
| Notifications | To deliver local habit reminders and motivation nudges |

We do not request location, camera, microphone, contacts, photos, or any other sensitive permission.

---

## 4. Third-party services

| Service | Purpose | Data shared |
| --- | --- | --- |
| [Sentry](https://sentry.io) | Crash diagnostics (release builds only) | Anonymous crash reports, device info, app version |
| [Expo](https://expo.dev) | App build / runtime framework | None at app runtime |
| [Apple](https://www.apple.com/legal/privacy/) / [Google](https://policies.google.com/privacy) | OS-level notification scheduling and app distribution | Standard platform telemetry handled by Apple / Google directly |

We are **not partnered with any advertising network**. We do **not sell, rent, or trade** your data with anyone.

---

## 5. Children's privacy

Habion is suitable for ages 4+. We do not knowingly collect personal information from anyone, including children. If you are under 13 (or the equivalent minimum age in your region), please use the app only with a parent or guardian's permission.

---

## 6. Your rights

Because all your habit data lives on your device:

- **Delete a single habit** — open the habit's detail page → tap "Delete habit". The habit and its full history are permanently removed.
- **Delete everything** — uninstall the app. All local data is removed automatically.
- **Delete diagnostic data** — email us at the address below and we'll scrub any anonymous install ID associated with your request from Sentry within 30 days.

Residents of the EU / UK (GDPR), California (CCPA / CPRA) and other regions with similar regulations can contact us at the address below to exercise their data-protection rights (access, deletion, portability, objection). Because we do not maintain user accounts, most requests are satisfied by uninstalling the app or by the diagnostic-deletion process above.

---

## 7. Data retention

| Data | Where | Retention |
| --- | --- | --- |
| Habits, completions, preferences | Your device | Until you delete them or uninstall the app |
| Crash diagnostics | Sentry | Up to 90 days, per Sentry retention policy |

---

## 8. Security

Local data on your device is protected by the operating system's standard sandbox and by MMKV's built-in encryption. Diagnostic data in transit to Sentry is encrypted using TLS.

No system is 100% secure. We do our best to follow industry-standard practices but cannot guarantee absolute security.

---

## 9. Changes to this policy

If we materially change how we handle data, we will update the "Last updated" date at the top of this page and announce the change in the app's release notes. Continued use of the app after a change constitutes acceptance of the revised policy.

---

## 10. Contact

Questions, deletion requests, or feedback:

📧 **support@habion.app**

> **Developers: replace the email above with a real, monitored address before submitting to the App Store / Play Store.** Apple and Google reviewers will reach out via this address.
