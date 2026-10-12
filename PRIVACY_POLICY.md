# Privacy Policy for CueCam

**Effective Date:** October 11, 2026  
**Last Updated:** October 11, 2026

## Overview

**CueCam — Teleprompter & Video Studio** ("CueCam", "we", "us", or "our") is designed with a strict, uncompromising **privacy-first, offline-first philosophy**. 

CueCam is **100% free**, operates **completely offline**, contains **zero advertisements**, includes **zero tracking or analytics SDKs**, requires **no user accounts**, and has **zero external cloud servers or databases**.

---

## 1. Zero Data Collection & Zero Network Transmissions

- **No Network Requests:** CueCam does not declare or use the `android.permission.INTERNET` permission. The application is completely incapable of transmitting data over the internet or contacting any remote server.
- **No Analytics / Telemetry:** We do not include Firebase Analytics, Mixpanel, AppsFlyer, Sentry, or any third-party telemetry tools.
- **No Advertisements:** CueCam contains zero ad SDKs (no Google AdMob, Unity Ads, etc.).
- **No User Accounts:** You do not need to register, provide an email address, login, or provide any personal details to use CueCam.

---

## 2. On-Device Data Storage

All data created or modified within CueCam stays strictly on your physical device:
- **Scripts & Speaker Notes:** Stored locally in a secure on-device SQLite database.
- **User Settings & Preferences:** Stored locally in Android shared preferences (such as your chosen scroll speed, font size, WPM pacing, and camera orientation).
- **Video Recordings:** Recorded video takes and audio tracks are saved solely to your device's internal storage or your device's local photo gallery (MediaStore) upon your explicit export.
- **Script Absolution:** Your teleprompter script and UI overlays are rendered strictly in memory on-screen for the speaker and are **never** encoded, burned, or stamped into the exported MP4 video files.

---

## 3. Device Permissions & How They Are Used

CueCam requests only the minimum device permissions essential to perform core on-device teleprompter and video recording functions:

1. **Camera (`android.permission.CAMERA`):**
   - **Purpose:** Allows the app to render a live on-screen camera preview and record vertical video takes while the prompter text scrolls.
   - **Scope:** Used exclusively when the user opens the Recording Studio and taps record. Never operates in the background.

2. **Microphone (`android.permission.RECORD_AUDIO`):**
   - **Purpose:** Synchronizes high-fidelity audio with your video recording.
   - **Scope:** Used strictly during active recording sessions. Never listens or records in the background.

3. **Keep Screen Awake (`android.permission.WAKE_LOCK`):**
   - **Purpose:** Prevents your device screen from dimming or sleeping while you are actively reading a script in rehearsal or recording a take.

4. **Media Storage (`READ_MEDIA_VIDEO` / Storage permissions):**
   - **Purpose:** Enables saving your completed video takes to your device's gallery or sharing them via the Android system share sheet.

---

## 4. Third-Party Sharing

We do not sell, rent, trade, share, or disclose any user data to third parties under any circumstances, because we never collect or possess your data in the first place.

---

## 5. Data Retention & Deletion

Because all data resides strictly on your physical device:
- You have 100% control over deleting individual scripts, speaker notes, and video takes within the app at any time.
- Uninstalling CueCam or clearing app data in your Android system settings immediately and permanently deletes all local scripts and application data.

---

## 6. Children's Privacy

CueCam does not collect any personal information from any user, including children under the age of 13.

---

## 7. Changes to This Privacy Policy

If we make any updates to this Privacy Policy, the revised policy will be posted with an updated "Last Updated" date.

---

## 8. Contact Us

If you have any questions or feedback regarding this Privacy Policy or CueCam, you can reach us at:
- **Project Repository:** CueCam Open Teleprompter
- **Email:** support@cuecam.app
