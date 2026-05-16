# SleepSync Privacy Policy

**Effective Date:** March 21, 2026
_Last updated: March 21, 2026_
**Version:** 1.0.0

SleepSync ("we," "our," or "us") is a sleep tracking and improvement app for Android. This Privacy Policy explains how the app handles your data.

## Information We Collect

### Data Stored Locally
- Sleep session records (start time, end time, duration, movement data) stored on your device using Room database.
- Ambient audio settings and sleep preferences stored locally.
- No account or sign-in is required.

### Device Sensors
- **Activity Recognition**: The app detects movement during sleep using your device's activity recognition sensor. This data is processed and stored locally only.

### AI Sleep Insights (Optional)
- If you request AI-powered sleep insights, a summary of your recent sleep data (durations and patterns, no audio) is sent to **Google Gemini API**.
- Audio is never sent to any server.
- See [Google's Privacy Policy](https://policies.google.com/privacy) for Gemini data practices.

## How We Use Your Information

- Record and display your sleep sessions and trends.
- Play ambient audio to aid sleep onset.
- Generate AI sleep insights when you explicitly request them.

We do not sell, rent, or share your data with third parties.

## Storage and Retention

- All sleep data is stored exclusively on your device.
- Data is retained until you delete sessions or uninstall the app.
- No SudarshanTechLabs server stores your sleep data.

## Data Security

- Local data is protected by Android's built-in storage encryption.
- Data sent to Gemini is transmitted over HTTPS/TLS.

## Permissions Used

- **ACTIVITY_RECOGNITION**: Required to detect movement during sleep sessions.
- **POST_NOTIFICATIONS** (Android 13+): Required to send bedtime reminders and sleep session alerts.
- **FOREGROUND_SERVICE**: Required to keep the sleep tracking session running reliably overnight.
- **INTERNET**: Required only when you request AI sleep insights via Gemini.

## Your Rights and Controls

- Delete any sleep session at any time within the app.
- Disable AI insights by simply not using that feature — no data is ever sent automatically.
- Revoke Activity Recognition permission in Android Settings → Apps → SleepSync → Permissions.

## Children's Privacy

SleepSync is not intended for children under 13. We do not knowingly collect data from children under 13.

## Changes to This Policy

We may update this policy to reflect new features or legal requirements. Continued use after changes constitutes acceptance.

## Contact Us

- **GitHub:** https://github.com/SUDARSHANCHAUDHARI/sleepsync-privacy-policy
- **Email:** sunny.sudarshan@gmail.com

We respond within 48 hours.

## Data Deletion

Uninstall the app to permanently remove all locally stored sleep data.

---

**Last Updated:** March 21, 2026
