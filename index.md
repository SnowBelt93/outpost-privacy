# Outpost Privacy Policy

**Last updated:** June 22, 2026

This is the privacy policy for Outpost ("the app"), an iOS app for finding sports backer bars and submitting community ratings. Outpost is operated by the team behind the app ("we", "us").

## Information we collect

**Anonymous account identifier.** When you open Outpost, we create an anonymous account using Firebase Authentication. This generates a random identifier ("user ID") that is not connected to your name, email, phone number, or any other personal information. The user ID is used to prevent duplicate reviews, attribute bar nominations, and associate your contributed data within the app. The user ID is stored securely on your device using iOS Keychain and **persists across app reinstalls on the same device**. This means deleting and reinstalling Outpost does not generate a new user ID — your contributed data remains linked to you.

**Account information (Sign in with Apple).** Signing in is optional — Outpost works fully without an account. If you choose to Sign in with Apple, we link your existing anonymous account to your Apple ID so your contributions stay tied to you. Apple shares your name with us the first time you sign in, and we use it as your display name (if you provide no name, we use a default, "Outpost Fan"). Apple may also share an email address, which can be a private relay address that forwards to your inbox without revealing it; we do not use your email inside the app, but it is retained by our authentication provider (Firebase) as part of your sign-in record. In our own database we store only your display name and the date your account was created — not your email, Apple ID, or other personal details.

**Location data.** With your permission, Outpost accesses your current location to show bars near you and to surface relevant suggestions. Location data is used in-memory only — we do not store your location on our servers or share it with anyone. You can deny location access in iOS Settings, in which case Outpost will use a default location.

**Reviews and nominations.** When you rate a bar or nominate a new bar, that information is stored in our database (Google Firestore). Reviews include yes/no/skip answers to questions about a bar's qualities (such as fight songs, sound, crowd, decor, and food) and a verdict question asking whether you would watch a game from your team there again. Nominations include the bar's name, address, and approximate location. To place a nominated bar on the map, we send its address (and no personal information) to geocoding services that turn an address into map coordinates: the US Census Bureau geocoder for US addresses, and OpenStreetMap / Nominatim for addresses outside the US. Reviews and nominations are public to all Outpost users in aggregated form.

**Bar ownership claims.** If you use the "Own this bar?" feature to claim or request to manage a bar listing, we collect the name, email address, phone number, and any notes you provide, so we can contact you about your claim. This information is stored in our database and used only to follow up on the claim.

**Reports.** If you report a bar (for example, flagging inappropriate content), we store the report along with your anonymous user ID and the reason you select. We use this only to review reports and prevent abuse. Reports are not public.

**Feedback and feature requests.** If you submit a feature request or other feedback through the app, we store the text of your submission alongside your anonymous user ID. We use this only to improve Outpost.

**Favorited teams.** Your favorited teams (which sports teams you follow) are stored only on your device using standard iOS storage. They never leave your device and we never see them.

**Favorited bars (future).** A future version of Outpost may allow you to mark individual bars as favorites for each team. If added, we will update this policy to clarify whether those favorites are stored locally or on our servers.

**Schedule and live game data.** Outpost fetches upcoming game schedules, live game status, and final scores for your favorited teams' leagues from TheSportsDB (a sports data API). This data is cached on your device for offline access and to reduce network usage. We do not send any personal information to TheSportsDB — only league and season identifiers (e.g., "NHL", "2025-2026").

**Notifications.** With your permission, Outpost sends you notifications about your favorited teams' games, including game start reminders, schedule changes (such as a game being moved or cancelled), a heads-up when there's a backer bar near you before a game, and live score updates shown on your lock screen while a game is in progress. Reminder and schedule notifications are scheduled and delivered on your device. Live score updates are delivered as push notifications through the Apple Push Notification service and Firebase Cloud Messaging; to deliver them, we process your device's push token and the game you are following so we can send the right scores. The feature is opt-in; you can enable or disable notifications at any time in iOS Settings or within Outpost.

**Advertising data.** Outpost displays advertisements provided by Google AdMob. AdMob may collect your device's Advertising Identifier (IDFA), your approximate location for ad relevance, and information about your interactions with ads (such as taps and impressions) for ad performance measurement. You can limit ad tracking by enabling "Limit Ad Tracking" in iOS Settings → Privacy & Security → Tracking. The first time the app launches, you will be prompted to allow or deny tracking via Apple's App Tracking Transparency (ATT) framework. For more information, see Google's privacy policy: https://policies.google.com/privacy

**Crash and diagnostic data.** If the app crashes, Outpost uses Firebase Crashlytics (a Google service) to record a stack trace, your device model, OS version, app version, free memory and storage at the moment of the crash, and a Crashlytics-installation identifier. This information is uploaded to our crash-reporting console the next time you launch Outpost so we can diagnose and fix bugs. Crash reports do not include your name, email, location, anonymous Outpost user ID, photos, or anything you've typed into the app. For Google's privacy practices around Crashlytics, see https://firebase.google.com/support/privacy.

**On-device data.** Outpost stores recently viewed bars and other app preferences on your device using standard iOS storage. This data never leaves your device.

## Information we do not collect

Outpost does NOT collect:

- Photos, videos, or audio
- Your contacts, calendar, or health data
- Your browsing or search history outside the app
- A stored history of your location (location is used in-memory only)
- Third-party analytics beyond AdMob (advertising) and Firebase Crashlytics (crash diagnostics)

We never ask for your name, email, or phone number except when you choose to Sign in with Apple or submit a bar ownership claim, as described above. We do not sell or rent your personal information.

## How we use information

We use the data above only to:

- Display bars and their community ratings to you
- Save your reviews, nominations, and feedback to operate the app
- Find bars near your current location and place nominated bars on the map
- Maintain your account and display name if you sign in
- Follow up on bar ownership claims you submit
- Send notifications you've opted into
- Display advertisements relevant to your usage of the app
- Review and respond to abuse reports
- Diagnose and fix crashes

We do not sell or rent personal user data. We share data with our service providers as described above to operate the app.

## Service providers

Outpost uses the following third-party services:

- **Google Firebase** (Authentication, Firestore Database, Cloud Functions, Cloud Messaging, and Crashlytics) — provides app infrastructure, account sign-in, the database, push notifications, and crash diagnostics. Privacy policy: https://policies.google.com/privacy
- **Apple — Sign in with Apple** — provides optional account sign-in. Apple shares your name and, optionally, an email or private relay email. Privacy policy: https://www.apple.com/legal/privacy/
- **Google AdMob** — provides advertising. Privacy policy: https://policies.google.com/privacy
- **TheSportsDB** — provides sports schedule and live game data. No personal information is sent; only league and season identifiers are queried. See https://www.thesportsdb.com for their terms.
- **US Census Bureau Geocoder** — converts a nominated bar's US address into map coordinates. Only the bar's address is sent; no personal information. See https://geocoding.geo.census.gov
- **OpenStreetMap / Nominatim** — converts a nominated bar's non-US address into map coordinates. Only the bar's address is sent; no personal information. Privacy policy: https://osmfoundation.org/wiki/Privacy_Policy

These providers receive only the data described above, and only as needed to operate their portions of the app.

## Your choices and rights

**Ad tracking.** You can opt out of personalized advertising at any time via iOS Settings → Privacy & Security → Tracking. Doing so will not stop ads from showing — it will only make them less personalized.

**Location.** You can revoke location access at any time via iOS Settings → Privacy & Security → Location Services → Outpost. The app will fall back to a default location.

**Notifications.** You can revoke notification permission at any time via iOS Settings → Notifications → Outpost. You can also disable notifications from Outpost's own settings screen.

**Your account.** Signing in with Apple is optional. You can manage or revoke Sign in with Apple access for Outpost at any time via iOS Settings → (your name) → Sign in with Apple.

**Access, correction, and deletion.** By default Outpost uses anonymous authentication, so we have no way to identify you outside the app. If you have signed in with Apple, your contributions are linked to your account. To request access to, correction of, or deletion of your data:

1. Email us at outpostforfans@gmail.com
2. To verify the data is yours, we may ask you to confirm details only the original submitter would know (e.g., specific bars or teams you've reviewed, or approximate dates of submissions), or to sign in with the Apple ID associated with your account.
3. We will respond within 14 days and complete verified requests within 30 days.

**Important note on uninstalling.** Deleting the Outpost app from your device does **not** automatically delete your contributed data from our database. Your anonymous user ID is preserved in iOS Keychain and will be restored if you reinstall Outpost on the same device, and any Apple sign-in stays linked to your account. This preserves your contributions across reinstalls and prevents duplicate submissions. To delete contributed data, please contact us using the email above.

**California residents** have additional rights under the California Consumer Privacy Act (CCPA) and California Privacy Rights Act (CPRA), including the right to know what categories of personal information we have collected, the right to delete it, the right to correct inaccurate information, and the right to opt out of the sale or sharing of personal information. We do not sell or share personal information. To exercise these rights, contact us at the email above.

**EU and UK residents.** If you are in the European Union or United Kingdom, you have rights under the General Data Protection Regulation (GDPR) or UK GDPR, including the rights to access, rectification, erasure, restriction of processing, and data portability. The lawful basis for our processing is your consent (which you provide by using the app and, for notifications, location, and Sign in with Apple, via the system permission prompts) and our legitimate interest in operating the service. To exercise these rights, contact us at the email above.

## Children's privacy

Outpost is not intended for users under 13. We do not knowingly collect data from children. If you believe a child has used the app, contact us and we will delete the associated data.

## Changes to this policy

We may update this policy from time to time. The "Last updated" date at the top reflects the latest version. Material changes will be highlighted in app updates.

## Contact

Questions or concerns? Email: outpostforfans@gmail.com
