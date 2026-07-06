# FaceTheTrade — Privacy Policy

**Effective date: July 6, 2026**

FaceTheTrade ("the App") is developed by Cup of Coffee Software ("we," "us"). The App is a behavioral journaling tool for traders that records short videos of you during trades, transcribes what you say, and provides AI-generated coaching feedback after the trade is over.

We designed FaceTheTrade around one principle: **your recordings never leave your phone.** This policy explains exactly what stays on your device, what doesn't, and why.

## The short version

- We operate **no servers** and have **no account system**. We cannot see your videos, hear your audio, read your transcripts, or identify you.
- Your video and audio recordings are captured, processed, and stored **entirely on your device**, and recordings are automatically deleted after 7 days.
- To generate coaching reports, the **text transcript** of what you said and **aggregate heart-rate statistics** (averages and peaks only) are sent to our AI provider. Nothing else is ever transmitted.
- We do not collect analytics, show ads, use trackers, or sell any data — because we never possess any of your data in the first place.

## What the App processes on your device only

The following never leaves your phone (or your watch):

- **Video and audio recordings** of your trading sessions. Captured with your permission, stored in the App's private storage, automatically deleted after 7 days. Transcription happens on-device using Apple's speech frameworks.
- **Raw heart-rate data** from your Apple Watch (with your HealthKit permission), used to place markers on your session timeline. Raw sensor readings are stored only on your device.
- **Your name, your coach's name, transcripts, grades, notes, and patterns** — stored locally in the App's database.
- **Face ID / passcode** (if you enable App Lock) — handled entirely by Apple's LocalAuthentication system; we never see biometric data.

If you delete a trade, its data is removed from your device. If you delete the App, everything is removed.

## What is transmitted, and to whom

**AI coaching reports (optional feature).** When a coaching report is generated, the App sends the following to Google's Gemini API over an encrypted connection:

- the plain-text transcript of your spoken commentary,
- your prompt answers and your named patterns, and
- aggregate heart-rate statistics for the session (low / average / peak beats per minute — never raw sensor data, and never your health records).

We use a **paid commercial API plan whose terms prohibit the provider from using your data to train their models.** The data is sent solely to generate your report. We attach no name, email, or identifier to these requests. Google's handling of API data is described in their [Gemini API terms](https://ai.google.dev/gemini-api/terms).

**Purchases.** Subscriptions are processed entirely by Apple through the App Store. We receive no payment details and cannot identify purchasers.

That is the complete list. The App makes no other network connections.

## HealthKit

With your permission, the App reads heart rate and heart-rate variability from Apple Watch during a recording, and uses a workout session on the Watch solely to keep the heart-rate sensor active while you trade (no workout is saved to your Health history). HealthKit data is used only for the features described above. We do not use HealthKit data for advertising or marketing, and we never sell it or share it with data brokers — sharing is limited to the aggregate statistics described in the AI section, and only when you use the AI coaching feature.

## What we don't do

- No analytics or crash-reporting SDKs
- No advertising, ad identifiers, or tracking of any kind
- No selling, renting, or sharing of personal information
- No accounts, and therefore no profiles of you

## Children

FaceTheTrade is a financial-behavior tool intended for adults and is not directed at children under 17.

## Your choices and rights

Because your data lives only on your device, you are in direct control: revoke camera, microphone, speech, or Health permissions at any time in iOS Settings; skip the AI features to keep everything 100% on-device; delete individual trades or the whole App to erase data. If privacy law in your region (GDPR, CCPA, etc.) grants you rights to access or delete personal data, those rights are satisfied by the same controls — we hold nothing about you on any server.

## Changes to this policy

If we change how the App handles data, we will update this page and the effective date, and material changes will be re-presented in the App for acknowledgment.

## Contact

Questions about this policy: **mandalorecapital@gmail.com**
