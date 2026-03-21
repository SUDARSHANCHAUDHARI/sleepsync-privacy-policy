# SleepSync — Privacy Policy

**Effective Date:** 2026-03-21
**Last Updated:** 2026-03-21
**Version:** 1.0.0

Published by **Sudarshan Tech Labs** | https://sudarshantechlabs.com | sudarshantechlabs@gmail.com

---

SleepSync is a sleep tracking and improvement app for Android. It tracks your sleep sessions, plays ambient audio to help you fall asleep, detects movement during sleep using the device's activity recognition sensor, and optionally provides AI-powered sleep insights via Google Gemini. All sleep data is stored locally on your device.

---

## Data Collection

### Data Stored Locally on Your Device

| Data | Purpose | Storage |
|---|---|---|
| Sleep sessions (start time, end time, duration, quality rating) | Core sleep tracking | Room database (encrypted) |
| Movement and activity data during sleep | Sleep quality analysis | Room database (encrypted) |
| Sleep schedule and alarm settings | Personalisation | DataStore on your device |
| App preferences | Personalisation | DataStore on your device |

### Activity Recognition

SleepSync uses Android's Activity Recognition API to detect movement during sleep. Movement data is processed on-device and stored locally. It is not transmitted to Sudarshan Tech Labs or any external server.

### Google Gemini API (user-initiated only)

When you request AI sleep insights, anonymised sleep pattern data (sleep durations and quality ratings, no personal notes) is sent to the Gemini API. Sudarshan Tech Labs does not retain this data.

---

## How We Use Your Data

| Purpose | Data Used |
|---|---|
| Record and display sleep sessions | Local sleep data |
| Play ambient sounds to aid sleep | Device audio (MediaPlayer foreground service) |
| Detect movement during sleep | Activity Recognition sensor |
| Send sleep schedule reminders and alarms | Local WorkManager exact alarm |
| Generate AI sleep insights (on request) | Sleep data sent to Gemini API |
| Display sleep trend charts | Local sleep history |

---

## Background Services

SleepSync uses two foreground services during active sleep tracking:

- **Sleep Tracking Service** (`FOREGROUND_SERVICE_DATA_SYNC`) — Records movement and sleep session data in the background
- **Audio Service** (`FOREGROUND_SERVICE_MEDIA_PLAYBACK`) — Plays ambient sounds to aid sleep

Both services are visible via a persistent notification and can be stopped at any time.

---

## Data Storage and Security

- **Sleep data:** Stored in an encrypted Room database (security-crypto)
- **No cloud storage:** Sudarshan Tech Labs operates no backend server
- **Android sandbox:** Additional protection from Android's application isolation

## Data Retention

| Data | Retention |
|---|---|
| All local sleep data | Until you delete it or uninstall the App |

---

## Data Sharing

We do not sell your data. The only external transmission is anonymised sleep data sent to the Gemini API when you explicitly request insights.

---

## Permissions Explained

| Permission | Why It Is Needed |
|---|---|
| `INTERNET` | Call the Gemini API when you request sleep insights |
| `ACCESS_NETWORK_STATE` | Check connectivity before Gemini API call |
| `WAKE_LOCK` | Keep the device active during sleep tracking |
| `FOREGROUND_SERVICE` | Run sleep tracking and audio services in the background |
| `FOREGROUND_SERVICE_MEDIA_PLAYBACK` | Required service type for background ambient audio |
| `FOREGROUND_SERVICE_DATA_SYNC` | Required service type for background sleep tracking |
| `POST_NOTIFICATIONS` | Send sleep schedule reminders and alarm notifications |
| `VIBRATE` | Haptic feedback for alarms |
| `SCHEDULE_EXACT_ALARM` | Schedule precise sleep and wake alarms |
| `USE_EXACT_ALARM` | Use exact alarms on Android 13+ |
| `RECEIVE_BOOT_COMPLETED` | Reschedule alarms after device restart |
| `ACTIVITY_RECOGNITION` | Detect movement during sleep sessions |

---

## Your Rights and Controls

- **Delete individual sleep sessions:** Use the delete function in the App
- **Stop background services:** Dismiss the persistent notification
- **Delete all data:** Uninstall or go to Android Settings > Apps > SleepSync > Storage > Clear Data

---

## Children's Privacy

SleepSync is not directed at children under 13. We do not knowingly collect personal information from children.

---

## Changes to This Policy

We may update this Privacy Policy from time to time. We will notify you of significant changes via:

- In-app notification
- Updated policy date on this page

Continued use of SleepSync after changes become effective constitutes your acceptance of the updated policy.

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
| Sleep session data | Local only (encrypted) | No | App functionality |
| Movement data | Local only (encrypted) | No | Sleep quality tracking |
| Sleep data (Gemini) | On request | Google (Gemini) | AI insights |

---

---

**This privacy policy complies with:**
- Google Play Store requirements
- GDPR (General Data Protection Regulation)
- CCPA (California Consumer Privacy Act)

**Last reviewed:** 2026-03-21
