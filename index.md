---
layout: default
title: Privacy Policy
---

# Vouch - Privacy Policy

Last updated: 13 August 2026

Vouch is an Android app that turns the payment alerts your phone already receives into a record of your own spending.
This policy explains what Vouch does with your information, in plain words.

The short version: **Vouch has no server, no account, and no way of its own to send anything anywhere.**
What it reads and what it stores stays on your phone.

Vouch is made by Wang Rui, an individual developer in Singapore.
For any question about privacy, or to ask about anything in this policy, write to vouch.app.sg@gmail.com.

## What Vouch reads

Vouch uses Android's **notification access** permission.
You grant it yourself, in Android's settings, and you can take it away at any time.

Notification access is all or nothing.
Android has no way for an app to ask only for your bank's notifications.
So for as long as the permission is granted, Vouch is handed **every notification your phone shows, from every app** - your bank, but also your messages, your email, your deliveries.

Vouch turns alerts into transactions only for a fixed list of banking and wallet apps.
That list is shown inside the app and in the Google Play listing, and every other notification is ignored for that purpose.

Vouch also reads two things you hand it deliberately:

- **Statement files you share into it** - PDF or CSV statements you have downloaded from your bank yourself.
- **Text you share into it** from another app, when you choose to.

Vouch has no access to your contacts, your photos, your location, your call history, or the files on your phone.
It cannot open your messaging apps or read your conversations - it is handed the notifications those apps post, in the same way it is handed every other notification, and nothing more.

## What Vouch stores, and where

Everything Vouch stores lives in a database inside Vouch's own private storage on your phone.
Android keeps that storage isolated from other apps, and it sits behind your device's screen lock and encryption.
Vouch adds no encryption of its own, and it stores nothing anywhere but your phone.

Vouch stores:

- **A copy of each notification it is handed** - the app it came from, its title and its text. This includes notifications from apps that have nothing to do with money, because Vouch keeps the copy first and works out what it was afterwards.
- **The transactions it works out** - amount, date, merchant, category, and which of your accounts each belongs to.
- **The accounts, categories and merchant corrections you set up.**

**Vouch deletes none of this on its own.** There is no expiry and no automatic clean-up. What Vouch has stored stays until you delete it or uninstall the app.

Vouch's data is excluded from Android's automatic cloud backup, so no copy of it is sent to your Google Drive.

## How your transaction text is understood

The work of reading an alert and pulling out the amount, the merchant and the date is done by a language model that runs **on your phone**, inside Vouch.
Your transaction text is never sent anywhere to be processed.

The model itself is downloaded once, on first launch, and Google Play delivers it in the same way it delivers the app.

## When information leaves your phone

Only when you send it, and only to where you send it.
Vouch transmits nothing on its own: there is no sync, no upload, no scheduled send, and nothing happens in the background.

There are three ways to get information out, and you start all three:

- **Backup.** You save a file holding everything Vouch has, to a location you choose. The file is plain readable text and is not encrypted, so look after it as you would a bank statement.
- **Share your transactions.** A file of your confirmed transactions, sent wherever you point it.
- **Diagnostic messages**, described below.

Payment alerts sometimes name other people - someone who paid you, for instance.
That text sits on your phone like everything else, so it is worth reading anything through before you pass it on.

## Helping fix a problem

Vouch is being tested by a small group of people, and when something comes out wrong the only way I can look into it is if you show me.

You can send a diagnostic message from inside the app.
It opens your own messaging app with the text already written, so you see exactly what you are about to send and can edit or delete any part of it first.
Card and account numbers, balances, email addresses, phone numbers and postcodes are masked before you ever see it.
Names cannot be masked reliably by any automatic rule, so the message is yours to read before it goes.

Nothing is sent automatically, and nothing is sent that you did not send yourself.
What you send me, I keep only for as long as it takes to look into the problem, and then delete.

## Crash reports

If Vouch crashes, Google Play may pass me a crash report: the technical details of what failed, along with your device model and Android version.
These come from Google, only from devices whose owners have turned on sharing usage and diagnostics data with Google, and they do not contain your transactions or your notification text.
Google's own privacy policy governs how Google handles them.

## What Vouch never does

- No account, no sign-in, no password.
- No connection to your bank. Nothing is linked, and there are no credentials to hand over.
- No advertising, no analytics, no tracking, and no third-party component that collects anything.
- Your information is never sold, rented, shared or transferred to anyone. There is no one to share it with, and no way to do it.

## Your choices

- **Turn notification access off** at any time, in Android's settings. Vouch is handed nothing from that moment on. What it has already stored stays until you delete it.
- **Edit or reject any transaction** Vouch has produced.
- **Delete** accounts, categories and learned merchant corrections.
- **Delete the stored alerts, or everything**, from Settings.
- **Uninstall Vouch.** That removes the app and everything it stored, permanently and completely.

Because Vouch holds nothing about you anywhere but on your own phone, there is nothing for me to look up, correct or delete on your behalf.
Every one of these is yours to do directly, in the app.

## Children

Vouch is not directed at children, and is not intended for anyone under 18.

## Singapore

Singapore's Personal Data Protection Act gives you rights over personal data an organisation holds about you.
Vouch keeps yours on your phone, so for the spending record itself the answer to "what do you hold about me" is nothing.
There is nothing for me to look up, correct, hand over or lose.
That record is yours, and the app is where you read, correct and delete it.

There are two exceptions, both small, and you control both:

- **If you are one of the testers, I have your email address**, because that is how Google Play gives someone access to a test. It is used for that and nothing else.
- **If you send me a diagnostic message, I have what you chose to send**, until the problem has been looked into. Then I delete it.

Questions about either of those, about anything else in this policy, or about data protection generally, go to vouch.app.sg@gmail.com.
That address is also Vouch's data protection contact under the PDPA.

## Changes to this policy

The date at the top of this page says when it last changed.
The current version always lives at https://ruiwang94.github.io/vouch-privacy/.
The copy inside the app is the version that shipped with the build you have installed.

## Contact

Wang Rui, Singapore
vouch.app.sg@gmail.com
