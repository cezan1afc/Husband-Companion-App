# Partner Support Dashboard - Android App Source

This ZIP file contains the complete source code and configuration files to build your **Partner Support Dashboard** into an Android APK using Capacitor or PWA tools (like Bubblewrap).

## Quick Instructions to Build the APK using Capacitor:

1. **Extract this ZIP file** on your computer.
2. Ensure you have **Node.js** and **Android Studio** installed.
3. Open a terminal inside the extracted folder and run:
   ```bash
   npm install
   npx cap init
   npx cap add android
   npx cap open android
   ```
4. Once Android Studio opens, click **Build > Build Bundle(s) / APK(s) > Build APK(s)** to generate your installable `.apk` file!

## Included Files:
- `www/index.html`: The complete, fully responsive single-file web application containing the Partner Support Dashboard, Firebase integration, cycle tracker, monthly calendar, refreshable messages, phase-specific meal ideas, and custom activity counters (Tea, Cigarettes, Water, Other).
- `capacitor.config.json`: Capacitor project configuration.
- `package.json`: Dependencies for building the native wrapper.
