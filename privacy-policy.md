# Privacy Policy — Blend Loop

**Effective date:** 2026-10-22
**Developer:** AmoryDev
**Contact:** amory.dev@gmail.com

## Summary
Blend Loop is a puzzle game with online leaderboards and a weekly race. To run them, the game creates an anonymous account for your device; it never asks for your email, phone number, contacts or precise location. The game shows ads from Google AdMob: videos you choose to watch for a reward, and ads between levels (buying Remove Ads turns those off). Google (Firebase) runs our servers and our analytics. Where the law requires it (the EEA, the UK and Switzerland), analytics only runs, and ads are only personalised, with your consent. If you buy something in the game, Google Play takes the payment; we keep a record of the purchase to deliver it, restore it and handle refunds. You can delete your online data in the game at any time: Settings → Privacy → Delete my online data.

## What we collect and why

### Anonymous account (every install, from the first launch)
- **What:** a random account id created by Firebase Authentication. Google receives your device's IP address and the app's user agent when the account is created and each time the game checks in.
- **Why:** to keep your leaderboard profile and race entries yours, and to check the time with Google's servers so that timers (lives, daily rewards) cannot be skipped by changing the device clock.
- **Legal basis:** providing the game's online features to you.
- **Kept:** until you delete it in the game.

### Leaderboard profile (only once you choose a name)
- **What:** the nickname you choose, your avatar, your country (from your device's region setting, not from GPS) and the highest level you reached.
- **Who sees it:** other players, on the Country and World leaderboards.
- **Why and legal basis:** showing you and others on the leaderboards, which you ask for by choosing a name.
- **Kept:** until you delete it in the game.

### Weekly race
- **What:** your score for the week and your race group of five. Your nickname, avatar and score are shown to the four other players in your group.
- **Kept:** deleted automatically 30 days after the week ends, or earlier when you delete your online data.

### In-app purchases (only if you buy something)
- **What:** Google Play handles the payment; we never see your card or bank details. When you buy, the game sends the purchase's token and product to our server, which checks it with Google Play and records: the product, Google's order number, the country or region of the purchase, the dates of the purchase and of our check, whether it was a test purchase, its status (valid, refunded or cancelled), a one-way hash of the purchase token (not the token itself) and your anonymous account id. On your device, the game keeps the products you own and any purchase still being confirmed in its save, and logs an analytics event with the product, price and currency (under the analytics rules below).
- **Purchase library:** Unity In-App Purchasing (Unity Technologies) runs in the game to talk to Google Play. It also sends technical events about each purchase (the product, Google's purchase receipt, device and app information) to Unity, under Unity's privacy policy: https://unity.com/legal/privacy-policy.
- **Why and legal basis:** giving you what you bought exactly once, restoring Remove Ads and the starter pack on a new install, handling refunds and preventing fraud (performing our contract with you; our legitimate interest in preventing fraud).
- **Kept:** 13 months after the purchase or our last check of it, then deleted automatically. Google keeps its own record of your purchases under Google's privacy policy.

### Ads (Google AdMob)
- **What we show:** rewarded videos you choose to watch (for example to double a level's coins or get a life) and, from level 20, full-screen ads between levels (after every second win or after giving up a level, never two within a minute). Remove Ads turns the ads between levels off; rewarded videos stay available. Ads are limited to content rated for general audiences (G).
- **What Google receives:** your device's IP address (from which it derives an approximate location), the advertising ID and app set ID of your device, information about the ads you see and tap and the videos you finish, diagnostics about the ads library (performance and errors), and device and app information (model, OS version, app version). The Google Mobile Ads plugin for Unity also reports its own errors to Google, with the error trace, the app's package and version and the device model.
- **When:** the ads library only starts once the consent step allows it. In the EEA, the UK and Switzerland, Google personalises ads only with your consent in the consent form (change it any time: Settings → Privacy → Open options); without it you see non-personalised ads. Elsewhere Google may personalise ads; you can reset or delete your advertising ID, or opt out of ad personalisation, in your device's settings (Settings → Google → Ads, or Settings → Privacy → Ads).
- **Why and legal basis:** paying for the free game (your consent where it is required; otherwise our legitimate interest in funding the game). Google uses this data for advertising, analytics and fraud prevention, as its own controller for personalised ads.
- **Kept:** by Google, under Google's privacy policy: https://policies.google.com/privacy and https://policies.google.com/technologies/partner-sites. We do not receive your advertising ID.

### Analytics (Google Analytics for Firebase)
- **What:** game events (levels started, won or lost, boosters used, tutorial steps, your consent answer), device and app information (model, OS version, app version, language), an app instance id, your anonymous account id (so that one support code finds all your data when you ask us to delete it), and an approximate location (country or region) that Google derives from your IP address. Analytics never collects the advertising ID and Google's advertising features in Analytics are off; Google Analytics may record each ad shown and its earnings, without any advertising ID; no names or free text are sent.
- **When:** in the EEA, the UK and Switzerland only after you agree in the consent form (change your choice any time: Settings → Privacy → Open options). Elsewhere analytics runs from the first launch.
- **Why and legal basis:** understanding which levels are too hard or too easy, to improve the game (your consent where it is required; otherwise our legitimate interest in improving the game).
- **Kept:** for the retention period set in Google Analytics (14 months). A copy of the events goes to our Google BigQuery project, where each daily table is deleted after 14 months.

### Crash reports (Firebase Crashlytics)
- **What:** when the game crashes: the crash trace, the app's state at the time, device information (model, OS version, free memory), a crash installation id, and the level being played.
- **When:** from the first launch.
- **Why and legal basis:** finding and fixing crashes (our legitimate interest in a working game).
- **Kept:** 90 days by Google.

### Game settings (Firebase Remote Config)
- **What:** each launch the game downloads our current settings (reward amounts, belt timing). Google receives a Firebase installation id, your country, language and time zone, the OS and app versions.
- **Why and legal basis:** delivering the game's settings (providing the game).

### App integrity (Firebase App Check)
- **What:** a token from Google Play Integrity that shows requests come from our unmodified app.
- **Why and legal basis:** protecting our servers and the leaderboards from abuse (our legitimate interest).

### Stored only on your device
- Your progress (levels, coins, lives, album, settings), the products you own and your consent choice. If Android device backup is on, Google may include them in your backup. Uninstalling the game removes them from the device, but not your online data: delete that first in the game.

## Who processes your data
Google is our service provider for all of the above (Firebase, Google Analytics, Google Cloud, Google Play) and shows the ads (Google AdMob). Unity Technologies provides the purchase library and receives its purchase events. Our game data (leaderboard profiles, race entries) is stored in Google Cloud's Singapore region; Google may process data in other countries under its own safeguards. We do not sell your data. The only data used for advertising is what Google AdMob receives as described under Ads.

## Deleting your data
- **In the game:** Settings → Privacy → **Delete my online data**. This deletes your leaderboard profile, your race entries and your anonymous account at once, and resets this install's Firebase and analytics ids. Within 30 days we ask Google to delete your analytics data (Google removes it from reports within 72 hours and deletes it within about two months) and we delete it from BigQuery. Crash reports expire after 90 days. What Google AdMob received is held by Google under its own policy; reset or delete your advertising ID in your device's settings to stop it being linked to you. Purchase records stay until they expire (13 months) but without your account id, order number or country, so a purchase cannot be used twice and refunds still match; Remove Ads and the starter pack can still be restored with the same Google account. Your progress on the device stays.
- **By email:** if you cannot use the game, email amory.dev@gmail.com from any address with the **support code** shown in Settings → Privacy (tap it to copy the full code). We delete the same data within 30 days, as above. We cannot find your data by your nickname alone, because nicknames are not unique.
- More: https://amorydev.github.io/blendloop-legal/delete-data

## Your rights
Depending on where you live, you can ask to access, correct or delete your data, object to its use or withdraw your consent (Settings → Privacy → Open options, where offered). Withdrawing consent does not affect what was done before. You can also complain to your data protection authority.

## Children
The game's content is suitable for all ages, but it is not directed to children; our target audience is adults. Ads are limited to content rated for general audiences. We do not knowingly collect personal information from children.

## Security
All data travels encrypted (HTTPS). The game cannot read or write our database directly; only our server functions can, each acting for the signed-in player only.

## Changes to this policy
We will post changes on this page and update the effective date above.

## Contact
Questions about this policy or your data: amory.dev@gmail.com.
