---
title: Privacy Policy
---

# Privacy Policy — BitArcade: GBA Emulator

**Effective date:** 10 November 2026
**App:** BitArcade: GBA Emulator (Android, package `com.txclabs.gba`)
**Developer:** TXC Labs ("we", "us")

This policy explains what information BitArcade handles, where it is kept, and the choices you have.
In short: **BitArcade has no accounts and no analytics. The free version shows ads from Google AdMob,
which uses your device's advertising ID. BitArcade Premium removes all ads. Your games, saves and
settings stay on your device.** If you buy BitArcade Premium, the purchase is handled by Google Play.

## 1. Information we collect

We do not collect personal information ourselves. We do not run servers that receive data from the app,
and the app contains no analytics or crash-reporting SDKs. The free version contains the Google Mobile
Ads SDK, described below.

**BitArcade Premium (optional subscription).** Purchases are made through Google Play Billing. Google Play
handles the payment; we never receive your name, email address or payment details. The app only receives
the purchase status from Google Play on your device (which Premium product, whether it is active, and a
purchase token it uses to confirm the purchase) so it can unlock Premium. Google's
[Privacy Policy](https://policies.google.com/privacy) applies to the payment itself.

**Advertising (Google AdMob).** The free version of the app shows ads served by Google AdMob, using the
Google Mobile Ads SDK. The ads are:

- a banner above the bottom tab bar;
- native ad cards on Home and on the language screen;
- a full-screen ad that sometimes appears when you leave a game or close the Premium screen (at most
  about once a minute);
- an app open ad that sometimes appears when you return to the app;
- optional rewarded ads that you can choose to watch to unlock up to 2 extra save slots permanently.

To show ads, measure them and prevent fraud, the SDK collects and shares with Google your device's
advertising ID (the SDK adds the Android `AD_ID` permission), your IP address, device and app
information, and how you interact with ads. The SDK also declares Android's Privacy Sandbox ad permissions
(`ACCESS_ADSERVICES_AD_ID`, `ACCESS_ADSERVICES_ATTRIBUTION` and `ACCESS_ADSERVICES_TOPICS`), so on devices
that support it Google may use Android's ad APIs (such as Topics and attribution) for ads. Where you have
consented, Google may use this to show personalised ads. We do not receive this data. Learn more:

- [Google Privacy Policy](https://policies.google.com/privacy)
- [How Google uses information from sites or apps that use its services](https://policies.google.com/technologies/partner-sites)
- [AdMob partners list](https://support.google.com/admob/answer/9012903)

**App configuration (Google Firebase Remote Config).** The app uses Google Firebase Remote Config to download a
small configuration from Google's Firebase servers: whether ads are on and which ad units to use. To do this,
Firebase uses a Firebase installation ID (a random identifier for this app install, not the advertising ID),
your IP address, and basic app and device information (app version, platform, language). It contains no personal
information that you type into the app. Learn more: [Firebase privacy information](https://firebase.google.com/support/privacy)

**Consent.** In the European Economic Area, the UK, Switzerland and some US states, Google's User
Messaging Platform (UMP) consent form is shown before ads load.

**Your choices**

- Change your ad consent choice any time in Settings, "Ads privacy settings". This row only appears
  where consent is required.
- Reset or delete your advertising ID in Android settings (Settings, Privacy or Google, Ads).
- Manage Android's ad privacy settings (such as Topics and ad measurement) in Android settings (Privacy, Ads or Ad privacy).
- Buy BitArcade Premium, which turns all ads off.

## 2. Information stored only on your device

To work, the app keeps the following in its private storage on your phone. We cannot see or access it.

| What | Why |
|---|---|
| Your game library: game title, game code read from the ROM header, the location of the file you picked, when you added and last played it | To show and open your games |
| Sample games that come with the app, copied out of the app the first time you play them | So you can play them |
| Games you download from the in-app game list, and each game's cover image saved next to it | So you can play them and Home can show them offline |
| Battery saves (`.sav`), save states and the automatic save made when you leave a game | So your progress is kept |
| Settings: language, sound volume, auto save, frame skip, FPS display, console colors | To remember your preferences |
| Your ad consent choice, and how many extra save slots you unlocked with rewarded ads | To respect your choice and keep the slots you earned |
| Whether Premium is active (a yes/no flag, checked again with Google Play when the app starts) | To unlock Premium features such as extra save slots offline |

When you add a game from your device, you choose the file with Android's system file picker. The app
can read only the files you pick, and only to load them as games. It does not scan or upload your other
files.

## 3. Internet use

The app uses the internet only in these cases:

- **Downloading games.** When you open "Download games", the app loads the list of free/homebrew games
  (a JSON file) and each game's cover image from the app's site on GitHub Pages
  (tangxuanchien.github.io). The game files you choose come from each game's author (their GitHub release
  or repository). Downloads are checked against a checksum and saved in the app's private storage.
- **Links you tap.** Rate us, Privacy Policy, Terms of Use and the source-code links on the Open source
  licenses page open in your browser or the Google Play Store app. The "More free games on the web" card in
  Download games opens free homebrew sites (Homebrew Hub and itch.io) in your browser. We do not control
  those sites, and their own privacy policies apply.
- **Google Play.** To show Premium prices and confirm purchases, the app talks to the Google Play app on
  your device, which contacts Google's servers. Manage subscription opens Google Play.
- **Ads.** In the free version, the app sends ad requests to Google's ad servers and receives ads from them.
- **Ad settings.** The app checks Firebase Remote Config (Google) for the ad settings.
- **Share and feedback.** Share app opens Android's share sheet with a link to the app. Send feedback opens
  your email app addressed to us; we receive only what you choose to send.

These requests go directly to those hosts. Like any web request, they receive your IP address and basic
technical information. We do not receive this. Those hosts' own privacy policies apply, for example the
[GitHub Privacy Statement](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement).

Playing games, saving and loading do not need the internet.

## 4. Android backup

If you have Android Backup turned on, Android may include the app's settings (including the Premium flag and the
save slots you unlocked with ads), the game library list and battery saves in your device backup (for example to your Google account), so they can be restored on a
new phone. This is handled by Android and your backup provider, not by us. You can turn backup off in
your device settings.

## 5. Sharing

We do not collect or sell personal information ourselves. The Google AdMob SDK in the free version shares
the data described in section 1 with Google and its ad partners, and Google Firebase Remote Config receives the
Firebase-related data described in section 1.

## 6. Keeping and deleting data

- Deleting a downloaded game (Delete in Download games, or removing it from Home) deletes its file and
  cover image. Your saves stay on your device.
- Turning off Auto save stops new automatic saves.
- Clearing the app's storage in Android settings, or uninstalling the app, deletes everything the app
  stored on your device.

## 7. Children

The app is not directed at children under 13, and it does not knowingly collect information from
anyone, including children. Ads are not intended for children.

## 8. Security

Your data stays in the app's private storage, which other apps cannot read. Downloads use HTTPS.

## 9. Changes to this policy

If we change this policy, we will update this page and its effective date. Material changes will also be
noted in the app's release notes.

## 10. Contact

Questions about this policy: **tangxuanchien511@gmail.com**
