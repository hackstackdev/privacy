# Privacy Policy

**HackStack**
*Last updated: May 10, 2026*

## Overview

HackStack is a free-to-play mobile game developed by an independent developer. Your privacy matters, and this policy explains what data is and isn't collected.

## Data We Collect

**We don't collect any personal data.** HackStack does not require an account, login, email address, or any personal information to play. All gameplay data (progress, settings, preferences) is stored locally on your device and is never transmitted to our servers.

**Anonymous crash diagnostics.** When the app crashes, anonymous diagnostic data is collected via Firebase Crashlytics to help fix the bug. This is limited to: the crash stack trace, your device model, iOS version, and the HackStack app version. No personal data, no account identifiers, no gameplay data, and no advertising identifiers are included. You can disable this entirely in Settings → System → Send Crash Reports. See the Firebase Crashlytics section below for details.

## Third-Party Services

HackStack uses the following third-party services:

### Google AdMob (Advertising)

HackStack displays advertisements provided by Google AdMob. Google may collect and use data to serve personalised ads, including device identifiers, usage data, and approximate location. You can control ad personalisation through your device settings or when prompted by the consent dialog on first launch.

**App Tracking Transparency.** On first launch (after the GDPR/CCPA consent dialog completes), HackStack presents Apple's standard "Allow [App] to track your activity" dialog. This is required by Apple before any tracking-enabled SDK can read your IDFA (Identifier for Advertisers). Granting permission allows AdMob to deliver personalised ads; denying permission means ads will still be shown, but they will not be personalised. This choice can be revisited at any time via iOS Settings > Privacy & Security > Tracking.

For details on how Google handles your data, see:
- [Google's Privacy Policy](https://policies.google.com/privacy)
- [How Google Uses Information from Sites or Apps That Use Our Services](https://policies.google.com/technologies/partner-sites)

You can opt out of personalised advertising via your iOS device settings under Settings > Privacy & Security > Tracking.

### Firebase Crashlytics (Crash Reporting)

HackStack uses Firebase Crashlytics, a service provided by Google, to collect anonymous diagnostic data when the app crashes. The data captured is strictly limited to:

* The crash stack trace (which line of code crashed)
* Your device model (e.g. iPhone 15 Pro)
* Your iOS version
* The HackStack app version

We do not collect, log, or attach any custom data, user identifiers, gameplay state, or advertising identifiers to crash reports. This is a hard rule in our app architecture, not a configuration setting.

Crashlytics data is processed by Google as a data processor on our behalf, retained for up to 90 days under Google's standard policy, and used solely to diagnose and fix bugs in HackStack.

You can opt out at any time in **Settings → System → Send Crash Reports** in the app. Opting out takes effect immediately and prevents any further crash data from being sent.

For details on how Google handles Crashlytics data, see [Firebase's Privacy and Security page](https://firebase.google.com/support/privacy).

## Children's Privacy

HackStack does not knowingly collect data from children under 13. Since the app collects no personal data, there is no age-gated data collection.

## Data Storage

All game progress is stored locally on your device using standard iOS storage mechanisms. Uninstalling the app will delete all local game data. We have no access to your saved game data.

**iCloud sync (optional).** HackStack offers an optional iCloud Key-Value sync feature, controlled via Settings > System > iCloud Sync. When enabled, your game progress is synchronised across your iOS devices via Apple's iCloud Key-Value Store under your own Apple ID. This data is held in your iCloud account, not on our servers — we have no access to it. You can disable iCloud sync at any time. The "Wipe Cloud Save" option in Settings clears the iCloud-synchronised copy. Uninstalling the app does not automatically delete iCloud-synchronised data; use the wipe option in Settings or the iOS Settings > [Your Name] > iCloud > Manage Storage flow.

## Your Rights

Under UK GDPR and other applicable data protection laws, you have the right to access, correct, or delete your personal data. Since HackStack does not collect personal data, there is no data for us to provide, correct, or delete. For data collected by Google AdMob and Firebase Crashlytics, please refer to Google's privacy policy linked above and Firebase's Privacy and Security page linked in the Crashlytics section.

## Changes to This Policy

We may update this privacy policy from time to time. Any changes will be reflected on this page with an updated revision date.

## Contact

If you have questions about this privacy policy, please contact us at:

**Email:** hackstack.dev@gmail.com

---

*This privacy policy applies to the HackStack iOS application.*
