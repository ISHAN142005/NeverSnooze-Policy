# Privacy Policy for NeverSnooze

**Effective Date:** September 19, 2026  
**Last Updated:** September 19, 2026  

Thank you for choosing **NeverSnooze** ("we", "our", or "us"). We are committed to protecting your privacy and ensuring your personal information is kept completely secure.

This Privacy Policy explains how our mobile application handles user information.

---

## 1. Summary: 100% Offline-First & Private

- **NeverSnooze is built on an offline-first architecture.**
- All user data—including alarm times, wake missions, step tracking history, REM sleep calculations, body metrics (height and weight), and audio preferences—**is stored strictly on your local device**.
- We **do not** collect, store, sell, or transmit your personal biometric data or alarm history to external servers.

---

## 2. Information We Handle On-Device

1. **Alarm & Routine Configuration**: Alarm hours, minutes, repeat days, and chosen challenge types (Step, Math, Memory, Shake) stored in local SQLite database.
2. **Body Metrics (Optional)**: User height and weight entered during onboarding are used solely for on-device calorie and stride distance mathematical estimation ($0.04 \times \text{weight} \times \text{steps}$).
3. **Hardware Sensor Data**:
   - **Step Sensor & Accelerometer**: Accessed only during active alarm ringing to detect physical movement for alarm dismissal. Sensor readings are processed in real time and are not recorded as raw telemetry.
4. **Audio & Media**:
   - Built-in sound synthesizers run locally without network streaming.
   - If you select a custom audio track from your device, only the local Android `content://` URI is referenced.

---

## 3. Third-Party Services & Data Sharing

- **Zero Third-Party Data Sharing**: We do not share any user data with advertising networks, third-party analytics providers, or data brokers.
- **Google Play Services**: If you optionally interact with Google Play Services (e.g., standard Play Store licensing, app updates), Google may process standard device diagnostics according to [Google's Privacy Policy](https://policies.google.com/privacy).

---

## 4. Permissions Requested

- `android.permission.USE_EXACT_ALARM`: Essential to ensure your alarm triggers at the exact minute even when the device is in deep Doze mode.
- `android.permission.POST_NOTIFICATIONS`: Used to display active mission status and optional bedtime reminders.
- `android.permission.ACTIVITY_RECOGNITION`: Used to track physical steps when completing step-based wake-up missions.
- `android.permission.RECEIVE_BOOT_COMPLETED`: Used to automatically reschedule your active alarms if your device restarts or updates.
- `android.permission.FOREGROUND_SERVICE` & `FOREGROUND_SERVICE_MEDIA_PLAYBACK`: Used to sustain reliable audio playback when the alarm rings with the screen locked.

---

## 5. Data Retention & Deletion

- Because all data is stored exclusively in your device's internal app sandbox, you have full control over your data.
- You can erase all data at any time by clearing application data in **Android Settings > Apps > NeverSnooze > Storage > Clear Data**, or by uninstalling the application.

---

## 6. Children's Privacy

NeverSnooze does not knowingly collect any personal information from children under the age of 13.

---

## 7. Contact Us

If you have any questions, suggestions, or concerns regarding this Privacy Policy, please contact us at:  
**Support Email:** support@neversnooze.app
