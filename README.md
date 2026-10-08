# Privacy Policy for NeverSnooze

**Effective Date:** September 19, 2026  
**Last Updated:** October 2026  

Thank you for choosing **NeverSnooze** ("we", "our", or "us"). We are committed to protecting your privacy and ensuring your personal information is kept completely secure.

This Privacy Policy explains how our mobile application handles user information.

---

## 1. Information We Handle On-Device

1. **Alarm & Routine Configuration**: Alarm hours, minutes, repeat days, and chosen challenge types (Step, Math, Memory, Shake) are stored in a local SQLite database.
2. **Body Metrics (Optional)**: User height and weight entered during onboarding are used solely for on-device calorie and stride distance mathematical estimation.
3. **Hardware Sensor Data**:
   - **Step Sensor & Accelerometer**: Accessed only during active alarm ringing to detect physical movement for alarm dismissal. Sensor readings are processed in real time and are not recorded as raw telemetry.
4. **Audio & Media**:
   - Built-in sound synthesizers run locally without network streaming.

---

## 2. Cloud & Community Features (Google Firebase)

NeverSnooze includes optional "Community" features (Friends, Squads, and Leaderboards). If you choose to use these features, we use **Google Firebase** to securely process and store necessary data:

1. **Account & Authentication Data**: 
   - We use Firebase Authentication (including Google Sign-In) to securely manage your account. 
   - We store a unique User ID and your chosen Display Name. We do NOT store your email address in our public database.
2. **Community Data**:
   - Your current "Wake Streak", XP, and Squad memberships are synced to Google Cloud Firestore so you can participate in community leaderboards.
3. **Third-Party Data Sharing**: 
   - We do NOT sell your data to advertising networks or data brokers. Your account data is processed securely by Google Firebase in accordance with their privacy policy.

---

## 3. Google Health Connect

NeverSnooze optionally syncs your completed morning steps to Google Health Connect.
- **Strict Data Minimization**: We only request `WRITE_STEPS` permission. We **do not request `READ_STEPS`**.
- We **do not transmit your health information to our servers** or any third-party advertising networks. Health data is synced solely via the official Android Health Connect APIs on your device.
- **Health Connect Compliance**: Our use of information received from Health Connect adheres strictly to the [Health Connect Permissions Policy](https://support.google.com/googleplay/android-developer/answer/14299863), including the Limited Use requirements.

---

## 4. Permissions Requested

- `android.permission.USE_EXACT_ALARM`: Essential to ensure your alarm triggers at the exact minute.
- `android.permission.POST_NOTIFICATIONS`: Used to display active mission status.
- `android.permission.ACTIVITY_RECOGNITION`: Used to track physical steps for wake-up missions.
- `android.permission.FOREGROUND_SERVICE` & `FOREGROUND_SERVICE_MEDIA_PLAYBACK`: Used to sustain reliable audio playback when the alarm rings with the screen locked.

---

## 5. Data Retention & Deletion

You have the right to request the complete deletion of your account and data at any time.

- **In-App Deletion (Recommended & Instant):** Go to **Settings > Delete Account & Wipe Data**. This will instantly delete your local configurations and securely erase your Google Firebase Authentication account.
- **Web Deletion Request:** You may also request account deletion without installing the app by emailing us at ishanbohra1414@gmail.com with the subject "Account Deletion Request".

---

## 6. Contact Us

If you have any questions, suggestions, or concerns regarding this Privacy Policy, please contact us at:  
**Support Email:** ishanbohra1414@gmail.com
