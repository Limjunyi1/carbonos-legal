---
title: CarbonOS Privacy Policy
permalink: /privacy/
---
# CarbonOS Privacy Policy

*Effective 29 October 2026 · [Bahasa Malaysia](../privacy-ms/) · [Terms of Use](../terms/)*

CarbonOS keeps your log on your phone. Our servers hold your account, your plan and how much of your allowance you have used, plus a copy of your log only if you turn on Backup. We never sell your data, show ads or track you across other apps.

## Who we are

CarbonOS is made by Lim Jun Yi, an independent developer in Malaysia ("we" in this policy), who is responsible for your personal data in CarbonOS. Contact: carbonos.support@gmail.com. Where the law requires a data protection officer, that is Lim Jun Yi, at the same email.

## What stays on your phone

What you log is stored on your device, in the app's database and in a folder of Markdown files you own (your "vault"):

- Meals and drinks, their nutrition, your notes and corrections
- Meal photos (before and after)
- Workouts and weigh-ins
- Your profile for targets (sex, birth year, height, weight, activity, goal) and your targets
- Your conversation with Carbon, meal plans and weekly reviews
- How many share cards you have used this month, and the captions you posted lately (so the next one is different)
- Steps and active energy read from Apple Health or Health Connect, if you connect it (shown, never saved)
- Small choices and flags: your units, whether haptics (vibration) are on, Ramadan mode, which welcome and milestone messages you have seen, your reminder choices, your weekly experiment, and meals you filled in as estimates after a gap (estimates are marked and never counted in your stats)

Unless you turn on Backup, we cannot see, back up or recover this data. Your phone's own backup (iCloud or Google) may include the app's database, under that provider's terms; it never includes Apple Health or Health Connect data, because CarbonOS does not save it.

## What reaches our servers

| What | Why | Legal basis | Kept |
| --- | --- | --- | --- |
| Email address and password (stored hashed), or, if you use Sign in with Apple, your Apple account identifier and the email Apple gives us (which may be a private relay address) | Signing in, and emailing you a numeric code if you reset your password | Contract | Until you delete your account |
| Your plan (Free or Pro) and renewal date | Unlocking Pro | Contract | Until you delete your account |
| How many scans, messages and captions you used each day and week, and how many requests you made in the last hour or day | Fair-use limits | Contract | Until you delete your account (the short-term counters are cleared after about 3 days) |
| A one-way scrambled (hashed) form of your network address, saved the first time an account uses Carbon's AI, and whether the email address is a throwaway one (the email itself is not kept for this) | Stopping mass sign-ups and misuse of the free tier | Legitimate interests | The scrambled value is cleared after 30 days; it cannot be turned back into your address |
| A copy of your log (only if you turn on Backup; no photos, no health-app data) | Restoring on a new phone | Your consent | Until you turn Backup off or delete your account |
| The request for a share card's caption: counts and short names, never what you typed (see "Share cards" below) | Writing the caption, and a daily limit | Your consent | Not saved; only a short-lived count in memory for the daily limit |
| The app's version number and a random one-off request ID (not linked to you or your device; a retry of the same message reuses it) with each request | Asking very old versions to update, and telling a retry from a second message | Legitimate interests | Not saved by us beyond the operational logs below |
| Operational logs: time, IP address, which feature, response time and sizes; never what you said | Security and keeping the service running | Legitimate interests | Up to 30 days |

## When you ask Carbon

Carbon's answers are made by an AI model. The app asks your permission before it sends anything to the AI, and you can withdraw it any time in Settings → Privacy. Logging by hand and barcode logging work without it.

A request to Carbon contains what you typed or your meal photos, plus the context needed to answer: that day's meals, workouts and weigh-in, recent daily totals, your targets, foods you log often, and the day's recent chat. It goes to our server and to our AI provider, which generates the answer.

- A photo scan also carries two weak hints to help tell look-alike foods apart: your phone's region setting (a two-letter country code such as MY, from its language and region settings) and the names of the foods you log most. They are sent only with a scan and used only for that scan.
- Our server does not save requests or answers. It does check them: see "Safety checks" below.
- Photos are shrunk on your phone to a JPEG of at most 1024 pixels before they leave it. Our server accepts only JPEG, PNG or WebP photos up to 4 MB and 4096 pixels on a side, and does not keep them.
- Our AI provider is BytePlus ModelArk, which acts as our data processor. [Its data-processing terms](https://docs.byteplus.com/en/docs/ModelArk/BytePlus_ModelArk_Data_Processing) say it handles customer data only on our instructions and does not use it for its own model training without our authorization, which we have not given. How long it handles a request while answering is set by those terms. Those terms also let BytePlus keep, for content-safety purposes, requests that its safety filters flag, for a limited period it sets.
- Apple Health and Health Connect data, your email, your vault files and photos you did not scan are never sent to the AI.

What you log can reveal health information. We treat it as sensitive and send it to the AI only with your explicit permission.

## Safety checks

Some messages, for example about self-harm, eating disorders, extreme dieting, a medical emergency, or a person saying they are under 18, are recognised on our server by simple pattern checks before any AI is used. They get a fixed, kind reply and nothing is sent to the AI provider. In Malaysia that reply names 999 and Befrienders KL (03-7627 2929); elsewhere it points to your local emergency number or a crisis line. Carbon's AI replies are also checked automatically, and a reply that gives advice we never give (such as starvation diets, purging, laxatives, detoxes, steroids or skipping meals to lose weight) is removed instead of shown. These are automated checks without human review. They can miss things, and Carbon is not a doctor.

## Backup (optional, off by default)

Backup is off until you turn it on in Settings, and it belongs to the account that turned it on: another account on the same phone never has its data copied to yours. When on, a copy of your meals, chat messages, workouts, weigh-ins, saved barcode foods, targets, body details (sex, birth year, height, weight, activity, goal), units and the small choices listed above is stored in your CarbonOS account. Never copied: photos, anything from Apple Health or Health Connect, your AI permission, and your phone's permissions. It is not end-to-end encrypted (see "How we protect it"). A backup is limited to about 8 MB: if yours is bigger, the oldest chat messages are left out first, and the app tells you how many. Turning Backup off deletes the copy on our servers. Signing out or deleting your account also switches it off on that phone. Restoring replaces the log on your phone with the backup.

## Share cards

You can turn your week, a day, a lift, a streak or other summaries into a picture to post or send. The picture is drawn on your phone from your own log and handed to your phone's share sheet. CarbonOS does not upload it or keep a copy: it goes only where you choose to send it, and from then on that app or person handles it under their own terms. A card can show things from your log, such as food and exercise names, counts, times of day and streaks. It never shows your weight, a body image, calories against a target, or your photos. Check a card before you post it: anyone you share it with can see everything on it.

A card starts with a caption written into the app. Only if you tap "Write a new caption", and you have allowed the AI, the app sends our server a short summary of the card: a title, the weekday, counts (for example days logged, meals, workouts, sets, a streak), up to a few food, exercise and muscle names, and the captions you were shown recently so a new one is different. Not your photos, your messages, your weight, your calories or any health-app data. It is handled like a request to Carbon: our server does not save it, our AI provider (BytePlus ModelArk) writes the caption on our instructions, and we limit how many captions you can ask for each day. If you have not allowed the AI, or you are offline, captions come from lines written into the app and nothing is sent.

## Barcode lookups

When you scan a barcode, the app sends only the barcode number, directly from your phone, to [Open Food Facts](https://world.openfoodfacts.org), an open food database run by a French non-profit. It sees the number and your phone's IP address, as any website would, and nothing about your account. Nutrition data is © Open Food Facts contributors, under the Open Database Licence.

## Apple Health and Health Connect

If you connect them, CarbonOS reads only your steps and active energy, to show how much you moved each day. This data stays on your phone. It is never saved by CarbonOS, sent to our servers or the AI, included in backups, used for advertising or marketing, or shared with anyone. Disconnect any time in Settings, and remove access in the Health app or Health Connect.

## Reminders

Reminders are worked out and scheduled by your phone from your own log, so no push server or device token is involved and nothing about them is sent to us. They can mention a food you often log, your streak, the day of the week, or (in your first days, or if you have been away) a short tip or a gentle nudge. Away for a while, you get at most three nudges and then none until you return. They never show your weight or calorie numbers, and a reply you type into a reminder stays on your phone until you send it. Turn each kind off in Settings → Reminders, or all of them in your phone's settings.

## Who processes it

These companies handle data for us, under terms that limit them to providing CarbonOS:

| Company | What it handles | Where |
| --- | --- | --- |
| Supabase | Your account, plan, usage counts, backup, sign-in and Sign in with Apple identifiers, and sign-in emails | Singapore |
| BytePlus ModelArk | Each request to Carbon while it is answered | BytePlus data centres, including Malaysia and Indonesia |
| Fly.io | Our server, which passes requests through | Singapore |
| RevenueCat | Subscription status, linked to your account id | United States |
| Apple and Google | Payment for Pro, and Sign in with Apple, under their own privacy policies | Their own |

If we change AI provider, we update this table first, and ask your permission again if what is sent changes.

Your data may be processed outside Malaysia. We transfer it only to countries with laws substantially similar to Malaysia's Personal Data Protection Act or under contracts that protect it to the same standard, and for users in the EU or UK under the European Commission's Standard Contractual Clauses.

## How we protect it

- Everything travels encrypted (HTTPS). Your sign-in token is kept in the iPhone Keychain or Android Keystore.
- Your backup is encrypted at rest and protected by access rules so that other users cannot read it. It is not end-to-end encrypted, so we could technically access it; we do not, except to keep the service running or where the law requires.
- Access to our servers is limited to what running the service needs.
- If a breach is likely to cause significant harm, we notify the Personal Data Protection Commissioner within 72 hours and you without undue delay.

## Your choices and rights

- **Access and copy:** Settings → Export my log gives you everything on your phone as plain files. Email us for what our servers hold, in a portable format.
- **Correction:** edit anything in the app, or ask us to correct account data.
- **Delete your account:** Settings → Delete account immediately removes your account, plan, usage counts and backup from our servers; operational logs expire within 30 days. After that we also try, on a best-effort basis, to revoke the Sign in with Apple tokens we hold for you (the app asks Apple for a fresh one-time code for this and does not store it) and to delete your RevenueCat subscriber record. If either cannot be reached at that moment, email us and we will finish it by hand. What is on your phone stays until you delete the app. Deleting your account does not cancel a Pro subscription: cancel it in your App Store or Google Play settings.
- **Withdraw consent:** turn off Carbon's AI, Backup (this deletes the copy), Health access or Reminders in Settings. This does not affect what was processed before.
- **Complain:** to the [Personal Data Protection Commissioner of Malaysia](https://www.pdp.gov.my) or the data protection authority where you live.

We answer requests within 21 days. Email carbonos.support@gmail.com.

## Adults, health and safety

CarbonOS is for adults aged 18 and over; we do not knowingly collect data from anyone younger, and delete it if we learn of it. If you tell Carbon in a message that you are under 18, it will not give weight, calorie or diet guidance. Personal targets are only set for adults: the app asks for your birth year and sets no targets if it could mean under 18. CarbonOS is a tracking and coaching tool, not medical advice: calorie, nutrient and burn figures are estimates, especially from photos. Talk to a doctor or dietitian before changing your diet if you are pregnant, have a medical condition, or have a history of disordered eating. The app never sets a weight-loss target for anyone underweight, keeps calories above a safe floor, and caps loss at 1% of body weight a week.

## Changes

We will tell you in the app before a material change takes effect. The date at the top shows the current version.
