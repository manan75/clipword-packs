---
title: Clipword privacy policy
permalink: /privacy
---

# Clipword privacy policy

Last updated: 26 October 2026

Clipword is an Android app for saving words you meet in other apps, together with the sentence they came from, and reviewing them as flashcards. It is made by [Developer name] ("we"). Questions or requests: **manankapkar000@gmail.com**.

## The short version

- Your words, sentences, notes and review history are saved **only on your phone**. There is no Clipword account.
- When **AI explanations** are on, the word you save and its sentence are sent to our server and to OpenAI to write the explanation. We don't keep that text. You can switch AI off in Settings.
- **Usage statistics** (counts like "a card was saved", never the words) and **crash reports** help us fix and improve the app. You can switch usage statistics off in Settings.
- No ads, no advertising ID, and we never sell data.

## 1. What stays on your phone

Everything you create in Clipword stays on your phone: the words you save, their sentences, meanings, notes and sources, your review history, your settings, and the dictionaries you download. We can't see it.

- **Android backup.** If backup is turned on in your phone's settings, Android may include Clipword's data in your phone's backup to your Google account, as it does for other apps. Downloaded dictionaries are left out. Google's terms apply to that backup.
- **Files you export.** An Anki export or a Clipword backup file is saved where you choose. What happens to it after that is up to you.
- **Deleting.** Deleting a card removes it and its review history. Uninstalling Clipword removes all of its data from your phone.

## 2. What you send to Clipword

Clipword only receives text you choose to send it: text you select and send with **Save to Clipword**, text you share to it, or text you type or paste into it.

**The clipboard.** When you open Clipword, it checks whether the clipboard holds text, without reading it, so it can offer a "Paste copied text" card. It reads the text only when you tap that card. Clipword never watches the clipboard in the background.

## 3. AI explanations (optional)

AI explanations are on by default. Switch them off any time in **Settings → AI explanations**. Cards saved while it's off are not sent.

When it is on and you save a word, Clipword sends this to our server:

- the word you saved and the sentence you saved it with,
- the language, and
- what the offline dictionary found (base form and word type).

Our server runs on Google Cloud (Cloud Functions for Firebase, in the United States). It forwards the request to **OpenAI** to write the explanation, then returns the result to your phone, where it is saved with your card.

- **Our server doesn't store the word or sentence**, and they never appear in our logs.
- **OpenAI** doesn't use data sent through its API to train its models. It may keep requests and responses for up to 30 days to monitor for abuse, as described in [OpenAI's API data controls](https://developers.openai.com/api/docs/guides/your-data).
- Please don't save sentences that contain private information about you or other people, such as passwords, addresses or health details, while AI explanations are on.

To keep the service fair and protected from abuse, the app also uses:

- **Firebase Anonymous Authentication.** This gives your copy of the app a random ID. It has no name, email or phone number. Google may process your IP address during sign-in for security.
- **Firebase App Check with Google Play Integrity.** This checks that requests come from the genuine Clipword app on a real device.
- **A daily request counter** for each random ID. Each count is deleted automatically after about two days.
- **Request logs.** For each request the server logs whether it worked, a one-way hash of the random ID, the language, the AI model, token counts, an estimated cost and how long it took. These logs are kept for 30 days.

## 4. Usage statistics (optional)

Clipword uses **Google Analytics for Firebase** to count how the app is used. This is on by default. Switch it off any time in **Settings → Your data → Share usage statistics**.

**What is counted:**

- app opens, sessions and screens viewed;
- these Clipword events:
  - finishing the welcome steps (language, and whether a starter deck was added);
  - saving a card (language, how it was captured, whether the dictionary found it, whether AI was on);
  - a review session (language, cards reviewed, cards due when you started, whether you finished);
  - exporting or restoring (type and number of cards);
  - viewing or choosing a plan on the Clipword Plus page (where it was opened from, the price shown, the plan).

**Along with each event, Google Analytics receives:**

- a random app-instance ID;
- app version, device model, Android version and language;
- an approximate region (country or city) derived from your IP address.

**What is never sent:** the text of your cards (no words, sentences, meanings or notes).

**How it's limited:**

- Advertising ID collection is switched off, and ad personalization and ad data signals are denied.
- Usage data is not used for advertising.
- It is kept for 14 months.

## 5. Crash reports

When Clipword crashes, **Firebase Crashlytics** sends a crash report. A report contains:

- the technical error (stack trace) and the app's state at the time;
- device model and Android version;
- a random installation ID.

Crash reports don't contain your cards. We use them only to find and fix bugs, and Crashlytics keeps them for 90 days. Crash reports can't currently be switched off in the app.

## 6. Dictionary downloads

Dictionaries are downloaded from GitHub (github.com). As with any website, GitHub receives your IP address when a file is downloaded; [GitHub's privacy statement](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement) applies. Clipword checks for newer versions about once a month on Wi-Fi.

## 7. Pronunciation and reminders

- **Pronunciation** uses your phone's own text-to-speech engine. Clipword doesn't send audio or text anywhere for this; your text-to-speech engine's own terms apply.
- **Daily reminders** are worked out on your phone. They are off unless you switch them on.

## 8. Clipword Plus

The Clipword Plus page shows planned features and prices. Plus is not on sale. Choosing a plan charges nothing and collects no payment details. It is only counted as described in section 4.

## 9. Who processes data for us

We don't sell or rent data, show ads, or share data with data brokers. These services process data for us:

| Service | What it does for Clipword |
|---|---|
| Google (Firebase and Google Cloud) | Server, anonymous sign-in, App Check, usage statistics, crash reports |
| OpenAI | Writing AI explanations |
| GitHub | Hosting dictionary downloads |

These services may process data in the United States and other countries.

## 10. Your choices and rights

- **Switch things off.** AI explanations and usage statistics each have a switch in Settings.
- **Keep or remove your words.** Export your words (Settings → Your data), delete cards, or uninstall the app to remove everything on your phone.
- **Ask us.** Email us to ask about, or ask us to delete, data held on our side. Clipword has no accounts, so we can't look you up by name or email. The data on our side is tied only to random IDs and expires on the schedules above.
- **Legal basis.** Where laws such as the EU GDPR or India's Digital Personal Data Protection Act apply, we rely on:
  - your consent for AI explanations and usage statistics (each can be switched off), and
  - our legitimate interest in keeping the app working and secure (crash reports and abuse protection).

  You may also complain to your local data protection authority.

## 11. Children

Clipword is not directed at children under 13, and we don't knowingly collect data from them.

## 12. Security

- Data sent by Clipword travels over encrypted connections (HTTPS).
- Downloaded dictionaries are checked against published checksums before use.

## 13. Changes

If this policy changes, we'll update this page and the date at the top. If a change affects what leaves your phone, we'll also say so in the app's release notes.
