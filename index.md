# Outpost Privacy Policy

**Last updated:** August 10, 2026

This is the privacy policy for Outpost — an app for iOS and Android that helps you find sports backer bars and submit community ratings — and for the Outpost app on Reddit (together, "the app"). Outpost is operated by the team behind the app ("we", "us").

Most of this policy applies to all three. Where behaviour differs by platform, the section says so explicitly.

## How to delete your data

To request deletion of your data, **email us at outpostforfans@gmail.com** with the subject "Delete my data".

**What to include.** Because Outpost uses anonymous accounts by default, we usually cannot identify you from an email address alone. To locate your data we may ask you to confirm details only you would know — specific bars or teams you rated, or roughly when you submitted — or to sign in with the Apple ID linked to your account (iOS) or tell us your Reddit username (Reddit app).

**What gets deleted.** Your account identifier and the ratings, nominations, plans, check-ins, reports, and feedback tied to it.

**What is kept.** Bars themselves stay in the shared directory — a bar describes a public business, not you — and community ratings that already contributed to a bar's aggregate score cannot be individually separated back out. Tell us if you would like a bar you submitted attributed to no one, and we will detach it from your account.

**How long it takes.** We respond within 14 days and complete verified requests within 30 days.

**Deleting the app does not delete your data.** See "Your choices and rights" below for the full detail, including how this differs between iOS and Android.

## Information we collect

**Anonymous account identifier.** When you open Outpost, we create an anonymous account using Firebase Authentication. This generates a random identifier ("user ID") that is not connected to your name, email, phone number, or any other personal information. The user ID is used to prevent duplicate reviews, attribute bar nominations, and associate your contributed data within the app. **This behaves differently on iOS and Android.** On iOS the user ID is stored in the iOS Keychain, which survives app deletion, so **reinstalling on the same device restores your previous ID** and your contributed data remains linked to you. On Android the ID lives in the app's private storage, which Android erases when the app is uninstalled, so **reinstalling produces a NEW anonymous ID** — your previous contributions stay in the app for everyone else but are no longer connected to you, and we cannot reconnect them.

**Account information (Sign in with Apple — iOS only).** There is no equivalent sign-in on Android yet; the Android app is anonymous-only, so an Android account cannot be carried to another device. Signing in is optional — Outpost works fully without an account. If you choose to Sign in with Apple, we link your existing anonymous account to your Apple ID so your contributions stay tied to you. Apple shares your name with us the first time you sign in, and we use it as your display name (if you provide no name, we use a default, "Outpost Fan"). Apple may also share an email address, which can be a private relay address that forwards to your inbox without revealing it; we do not use your email inside the app, but it is retained by our authentication provider (Firebase) as part of your sign-in record. In our own database we store only your display name and the date your account was created — not your email, Apple ID, or other personal details.

**If you use Outpost through Reddit.** The Outpost app on Reddit is a separate way to reach the same bar directory. It does not use the anonymous account described above. Instead, Reddit — which has already signed you in — tells us your Reddit username, and we receive the actions you take: the team and city you look up, the bars you rate, and the details of any bar you submit (its name and street address). We never see or handle your Reddit password.

We keep your Reddit username in two forms, for two different reasons:

- **As a one-way hash** (SHA-256 with a secret we hold on our servers). This hashed value is what your ratings are recorded against, and it is what lets us enforce one rating per bar per Reddit account. It cannot be turned back into your username.
- **As plaintext, in an access-restricted internal store** that only our administrators can read. This exists for one purpose — investigating suspected manipulation of community ratings, for example when a subreddit moderator or Reddit reports it. It is never displayed in the app, never attached to a rating that anyone can see, and never shared.

Bar names and addresses are business information, not personal information. Your use of Reddit itself is governed by Reddit's own privacy policy, not this one.

**Location data.** With your permission, Outpost accesses your current location to show bars near you and to surface relevant suggestions. Location data is used in-memory only — we do not store your location on our servers or share it with anyone. You can deny or revoke location access at any time — iOS Settings → Privacy & Security → Location Services → Outpost, or Android Settings → Apps → Outpost → Permissions → Location — in which case Outpost will use a default location.

**Reviews and nominations.** When you rate a bar or nominate a new bar, that information is stored in our database (Google Firestore). Reviews include yes/no/skip answers to questions about a bar's qualities (such as fight songs, sound, crowd, decor, and food) and a verdict question asking whether you would watch a game from your team there again. Nominations include the bar's name, address, and approximate location. To place a nominated bar on the map, we send its address (and no personal information) to geocoding services that turn an address into map coordinates: the US Census Bureau geocoder is tried first, and OpenStreetMap / Nominatim is used as a fallback — including for addresses outside the US, where the Census geocoder has no coverage. Reviews and nominations are public to all Outpost users in aggregated form. Bars submitted through the Reddit app are geocoded the same way, on our servers rather than on your device.

**Game plans, RSVPs, and check-ins.** When you RSVP to watch a game at a bar ("I'm going"), Outpost saves a game plan — the bar, the game, and your anonymous user ID — in our database (Google Firestore), so we can show you your plan and, if you opt in, remind you before kickoff. The number of people who have RSVP'd to a particular bar for a particular game is **public to all Outpost users as an aggregate count** ("X going"); **who specifically RSVP'd is private and is never shown to other users.** Likewise, when you check in at a bar during a live game ("I'm here now"), we store a check-in record with your anonymous user ID, and other users see only the **aggregate count** of how many people are there ("X here now") — never who. You can remove an RSVP or a check-in at any time within the app.

**Calendar access.** If the "Add games to calendar" setting is on, Outpost adds the games you RSVP to your device calendar so you don't miss kickoff. The first time it syncs, your device asks your permission for calendar access. For each RSVP we write one event — the matchup, the start time, and the bar's name and address — and we store that event's identifier alongside your game plan (in our database) so we can update the event if you switch bars or remove it if you cancel your RSVP. Outpost only adds, updates, and removes these game events; it does not read or collect your other calendar entries. **On Android the app requests calendar READ permission as well as write** — Android requires it to find which calendar to write into and to update an event it previously created. It is used only for that: Outpost reads the LIST of calendars on the device to pick a destination, and never queries the contents of your events. You can turn the setting off at any time in Outpost, or revoke calendar access in iOS Settings → Privacy & Security → Calendars → Outpost, or Android Settings → Apps → Outpost → Permissions → Calendar.

**Bar ownership claims.** If you use the "Own this bar?" feature to claim or request to manage a bar listing, we collect the name, email address, phone number, and any notes you provide, so we can contact you about your claim. This information is stored in our database and used only to follow up on the claim.

**Reports.** If you report a bar (for example, flagging inappropriate content), we store the report along with your anonymous user ID and the reason you select. We use this only to review reports and prevent abuse. Reports are not public.

**Feedback and feature requests.** If you submit a feature request or other feedback through the app, we store the text of your submission alongside your anonymous user ID. We use this only to improve Outpost.

**Favorited teams.** Your favorited teams (which sports teams you follow) are stored only on your device using standard iOS storage. They never leave your device and we never see them.

**Favorited bars (future).** A future version of Outpost may allow you to mark individual bars as favorites for each team. If added, we will update this policy to clarify whether those favorites are stored locally or on our servers.

**Schedule and live game data.** Outpost fetches upcoming game schedules, live game status, and final scores for your favorited teams' leagues from TheSportsDB (a sports data API). This data is cached on your device for offline access and to reduce network usage. We do not send any personal information to TheSportsDB — only league and season identifiers (e.g., "NHL", "2025-2026").

**Notifications.** With your permission, Outpost sends you notifications about your favorited teams' games, including game start reminders, schedule changes (such as a game being moved or cancelled), a heads-up when there's a backer bar near you before a game, and live score updates shown on your lock screen while a game is in progress. Reminder and schedule notifications are scheduled and delivered on your device. Live score updates are delivered as push notifications through the Apple Push Notification service and Firebase Cloud Messaging; to deliver them, we process your device's push token and the game you are following so we can send the right scores. The feature is opt-in; you can enable or disable notifications at any time within Outpost, or in iOS Settings → Notifications → Outpost / Android Settings → Apps → Outpost → Notifications.

**Advertising data.** Outpost displays advertisements provided by Google AdMob. AdMob may collect your device's advertising identifier, your approximate location for ad relevance, and information about your interactions with ads (such as taps and impressions) for ad performance measurement. How this is controlled differs by platform:

- **iOS.** The identifier is Apple's IDFA. The first time the app launches you are prompted to allow or deny tracking through Apple's App Tracking Transparency (ATT) framework, and you can change the answer later in iOS Settings → Privacy & Security → Tracking.
- **Android.** The identifier is the Google Advertising ID. There is no ATT prompt. If you are in the EEA or UK, a Google **User Messaging Platform (UMP)** consent form appears before personalised ads are shown, and you can reopen your choices from Outpost's settings. You can also delete or reset the Advertising ID in Android Settings → Privacy → Ads.

For more information, see Google's privacy policy: https://policies.google.com/privacy

**Crash and diagnostic data.** If the app crashes, Outpost uses Firebase Crashlytics (a Google service) to record a stack trace, your device model, OS version, app version, free memory and storage at the moment of the crash, and a Crashlytics-installation identifier. This information is uploaded to our crash-reporting console the next time you launch Outpost so we can diagnose and fix bugs. Crash reports do not include your name, email, location, anonymous Outpost user ID, photos, or anything you've typed into the app. For Google's privacy practices around Crashlytics, see https://firebase.google.com/support/privacy.

**Home-screen widget (iOS and Android).** If you add the Outpost widget, the app writes a small snapshot to a shared on-device store so the widget can draw without doing any lookup of its own. The snapshot holds only what the widget displays: your next game's teams, the kickoff time, and the name of the bar you've RSVP'd to, if any. It stays on your device, and the widget makes no network requests and reads nothing from our database.

**On-device data and offline cache.** Outpost stores recently viewed bars and other app preferences on your device using standard iOS storage. The app also keeps a local cache of database content it has already loaded — bars, ratings, and your own plans — so it works offline and uses less network. This cache lives on your device, is managed by the Firebase SDK, and is removed when you delete the app. This data never leaves your device.

## Information we do not collect

Outpost does NOT collect:

- Photos, videos, or audio
- Your contacts or health data (and we do not read your existing calendar entries — see "Calendar access" above)
- Your browsing or search history outside the app
- A stored history of your location (location is used in-memory only)
- Third-party analytics beyond AdMob (advertising) and Firebase Crashlytics (crash diagnostics)

From the Reddit app specifically, we do NOT collect:

- Your Reddit posts, comments, votes, saved items, or browsing history
- Which subreddits you belong to or visit
- Your Reddit email address or any account credentials
- Device identifiers, advertising identifiers, or location data

We receive only the username Reddit provides and the actions you deliberately take in the Outpost app. The Reddit app shows no ads and requests no device permissions.

We never ask for your name, email, or phone number except when you choose to Sign in with Apple or submit a bar ownership claim, as described above; on Reddit, we receive the username you already use publicly there. We do not sell or rent your personal information.

## How we use information

We use the data above only to:

- Display bars and their community ratings to you
- Save your reviews, nominations, and feedback to operate the app
- Find bars near your current location and place nominated bars on the map
- Maintain your account and display name if you sign in
- Follow up on bar ownership claims you submit
- Send notifications you've opted into
- Add games you RSVP to your device calendar, if you enable it
- Display advertisements relevant to your usage of the app
- Review and respond to abuse reports
- Diagnose and fix crashes
- On Reddit: show you bars for the team and city you asked about; record your rating and make sure each Reddit account rates a given bar once; add a bar you submit to the shared directory; apply daily submission limits that protect the free public mapping services we depend on; and investigate abuse, such as coordinated vote manipulation, when it is reported to us

We do not use Reddit data for advertising or profiling, and we do not combine your Reddit activity with any Outpost iOS account. We do not sell or rent personal user data. We share data with our service providers as described above to operate the app.

## Service providers

Outpost uses the following third-party services:

- **Google Firebase** (Authentication, Firestore Database, Cloud Functions, Cloud Messaging, and Crashlytics) — provides app infrastructure, account sign-in, the database, push notifications, and crash diagnostics. Privacy policy: https://policies.google.com/privacy
- **Apple — Sign in with Apple (iOS only)** — provides optional account sign-in. Apple shares your name and, optionally, an email or private relay email. Privacy policy: https://www.apple.com/legal/privacy/
- **Google AdMob** — provides advertising. On Android, Google's User Messaging Platform (UMP) also handles EEA/UK consent. Privacy policy: https://policies.google.com/privacy
- **TheSportsDB** — provides sports schedule and live game data. No personal information is sent; only league and season identifiers are queried. See https://www.thesportsdb.com for their terms.
- **US Census Bureau Geocoder** — converts a nominated bar's US address into map coordinates. Only the bar's address is sent; no personal information. See https://geocoding.geo.census.gov
- **OpenStreetMap / Nominatim** — converts a nominated bar's address into map coordinates when the Census geocoder cannot, including addresses outside the US. Only the bar's address is sent; no personal information. Privacy policy: https://osmfoundation.org/wiki/Privacy_Policy
- **Reddit** — hosts the Outpost app on Reddit and signs you in there. Reddit provides us your username; we do not provide Reddit any information about you. Your use of Reddit is governed by Reddit's own privacy policy: https://www.reddit.com/policies/privacy-policy

These providers receive only the data described above, and only as needed to operate their portions of the app.

## Your choices and rights

**Ad tracking.** On iOS, opt out of personalised advertising via iOS Settings → Privacy & Security → Tracking. On Android, delete or reset your Advertising ID via Android Settings → Privacy → Ads; if you are in the EEA or UK you can also reopen the consent form from Outpost's settings. Either way this does not stop ads from showing — it only makes them less personalised.

**Location.** Revoke location access at any time via iOS Settings → Privacy & Security → Location Services → Outpost, or Android Settings → Apps → Outpost → Permissions → Location. The app will fall back to a default location.

**Notifications.** Revoke notification permission at any time via iOS Settings → Notifications → Outpost, or Android Settings → Apps → Outpost → Notifications. You can also disable notifications from Outpost's own settings screen.

**Calendar.** Stop adding games to your calendar at any time with the "Add games to calendar" toggle in Outpost's settings, or revoke calendar access via iOS Settings → Privacy & Security → Calendars → Outpost, or Android Settings → Apps → Outpost → Permissions → Calendar.

**Reddit app.** You can stop using the Outpost app on Reddit at any time. To have your Reddit data removed — the stored username and the ratings tied to it — email us with your Reddit username using the address below. Bars you submitted will normally stay in the directory, because they describe a public business rather than you; tell us if you would like your submission attributed to no one and we will detach it.

**Your account (iOS).** Signing in with Apple is optional. You can manage or revoke Sign in with Apple access for Outpost at any time via iOS Settings → (your name) → Sign in with Apple. The Android app has no sign-in; it is anonymous-only.

**Access, correction, and deletion.** By default Outpost uses anonymous authentication, so we have no way to identify you outside the app. If you have signed in with Apple, your contributions are linked to your account. To request access to, correction of, or deletion of your data:

1. Email us at outpostforfans@gmail.com
2. To verify the data is yours, we may ask you to confirm details only the original submitter would know (e.g., specific bars or teams you've reviewed, or approximate dates of submissions), or to sign in with the Apple ID associated with your account.
3. We will respond within 14 days and complete verified requests within 30 days.

**Important note on uninstalling.** Deleting the Outpost app from your device does **not** automatically delete your contributed data from our database, on either platform. What differs is whether the app can still recognise you afterwards:

- **iOS.** Your anonymous user ID is preserved in the iOS Keychain and is restored if you reinstall on the same device, and any Apple sign-in stays linked to your account. Your contributions remain yours across reinstalls.
- **Android.** Android erases the app's private storage on uninstall, so a reinstall creates a NEW anonymous ID. Your earlier contributions stay in the shared directory but are no longer connected to you, and we have no way to reconnect them.

To delete contributed data, contact us using the email above — see "How to delete your data" at the top of this policy.

**California residents** have additional rights under the California Consumer Privacy Act (CCPA) and California Privacy Rights Act (CPRA), including the right to know what categories of personal information we have collected, the right to delete it, the right to correct inaccurate information, and the right to opt out of the sale or sharing of personal information. We do not sell or share personal information. To exercise these rights, contact us at the email above.

**EU and UK residents.** If you are in the European Union or United Kingdom, you have rights under the General Data Protection Regulation (GDPR) or UK GDPR, including the rights to access, rectification, erasure, restriction of processing, and data portability. The lawful basis for our processing is your consent (which you provide by using the app and, for notifications, location, and Sign in with Apple, via the system permission prompts, which now also include calendar access) and our legitimate interest in operating the service. To exercise these rights, contact us at the email above.

## Children's privacy

Outpost is not intended for users under 13. We do not knowingly collect data from children. If you believe a child has used the app, contact us and we will delete the associated data.

## Changes to this policy

We may update this policy from time to time. The "Last updated" date at the top reflects the latest version. Material changes will be highlighted in app updates.

## Contact

Questions or concerns? Email: outpostforfans@gmail.com
