---
layout: default
title: Privacy Policy
description: Privacy policy for the Mietsenkung app. Swiss nDSG-compliant, GDPR-aware, local-first.
lang: en
permalink: /privacy-en.html
---

<div class="lang-switch">
  <a href="privacy-de.html">DE</a>
  <a class="active">EN</a>
</div>

# Privacy Policy — Mietsenkung

**Date:** 2026-04-24
**Effective from:** Launch of the app on the Apple App Store / Google Play Store
**Applies to:** Mietsenkung iOS + Android app (Bundle ID `com.mietsenkung.mietsenkung`)

---

## 1. Data controller

The person responsible for data processing in this app is:

**Manuel Weingartner**
Private individual, no commercial register entry.
E-mail: manuel.weingartner@gmx.ch
Postal address available on request via e-mail.

This privacy policy is based on the revised Swiss Federal Act on Data Protection (nDSG, in force since 01.09.2023). For users resident in the EEA, the relevant provisions of the EU General Data Protection Regulation (GDPR) apply in addition.

---

## 2. Overview — local-first

Mietsenkung is deliberately built "local-first". Your lease data, your address, the address of your landlord and your signature stay exclusively on your device in a local SQLite database. There is no user account, no cloud sync, no server-side database at our end.

Data is transferred to third parties in only two situations:

1. When you send a letter from the app (in that case the letter content goes to Pingen).
2. When the app fetches reference interest rate data or receives a push notification (an anonymous channel via Firebase).

If you uninstall the app, all lease data is gone. There is no backup trace on our side.

---

## 3. What data is processed

### 3.1 Locally on your device

- **Tenant data:** name, address, optional co-tenants
- **Landlord data:** name, address, optional e-mail
- **Lease data:** net rent, start of tenancy, date of last adjustment, reference interest rate at the time of adjustment, termination dates
- **Letter history:** generated letters (PDF), Pingen tracking IDs, dispatch date
- **Signature:** finger-drawn PNG image, captured once per tenant, stored as BLOB in sqflite
- **Premium status:** cached RevenueCat entitlement flag
- **App settings:** language, theme, push preferences

### 3.2 Technical data (anonymous)

- **FCM token:** an anonymous string that Google's push system issues per app installation so we can send you rate alerts. No personal identifier.
- **App Check token:** short-lived attestation token that confirms device integrity to Firebase. No personal identifier.
- **RevenueCat app user ID:** anonymous UUID used to map your subscription. No personal identifier, no e-mail.
- **Crash reports:** if the app crashes, stack trace, device type and OS version are sent to Sentry. PII is actively stripped before transmission (see section 4.3).

### 3.3 Data we **do not** collect

- No analytics (no Google Analytics, no Firebase Analytics, no Mixpanel).
- No cross-device tracking.
- No advertising IDs (IDFA / GAID are not read).
- No location data.
- No contacts, no calendar, no camera access. The app does not request these permissions.
- No photos except the signature you draw inside the app yourself.

---

## 4. Where your data goes

We work with a small number of carefully selected data processors. Each is listed individually.

### 4.1 Firebase (Google LLC / Google Ireland Ltd)

- **Purpose:** push notifications ("rate alert"), anti-abuse protection (App Check), backend endpoints for reference rate data, letter dispatch proxy to Pingen.
- **What is transferred:** FCM token and App Check token. When Cloud Functions are called: anonymous API calls with no personal identifier. Letter data only passes through the function proxy when you actively trigger a dispatch (see 4.4).
- **Legal basis:** legitimate interest in operating and securing the app (Art. 31 para. 2 nDSG). For EEA users additionally Art. 6 para. 1 lit. f GDPR.
- **Server location:** europe-west6 (Zurich) for Cloud Functions. FCM is operated globally by Google.
- **Retention:** the FCM token exists as long as the app is installed. Cloud Functions logs: 30-day rotation.
- **Provider privacy policy:** [https://firebase.google.com/support/privacy](https://firebase.google.com/support/privacy)

### 4.2 RevenueCat (RevenueCat Inc., USA)

- **Purpose:** subscription management (CHF 19.90 per year premium, CHF 7.90 registered-letter consumable).
- **What is transferred:** anonymous app user ID, purchase transaction receipts that RevenueCat receives from Apple / Google. No credit card numbers, no payment data. Payment runs exclusively through the App Store or Google Play.
- **Legal basis:** contract performance (Art. 31 para. 1 lit. a nDSG, Art. 6 para. 1 lit. b GDPR).
- **Server location:** USA. Data transfer based on EU Standard Contractual Clauses.
- **Retention:** as long as your subscription is active, plus accounting retention periods.
- **Provider privacy policy:** [https://www.revenuecat.com/privacy](https://www.revenuecat.com/privacy)

### 4.3 Sentry (Functional Software Inc., USA)

- **Purpose:** error monitoring so that crashes can be fixed.
- **What is transferred:** stack traces, device type, OS version, breadcrumbs (in-app events around the moment of the error).
- **Active PII scrubbing:** `ui.input` and `ui.click` breadcrumbs are dropped server-side so no form input ends up in Sentry. `user` and `request` contexts are scrubbed. Offline noise (`SocketException` during host lookup) is dropped.
- **Legal basis:** legitimate interest in a stable app (Art. 31 para. 2 nDSG).
- **Server location:** USA.
- **Retention:** 90-day rotation.
- **Provider privacy policy:** [https://sentry.io/privacy/](https://sentry.io/privacy/)

### 4.4 Pingen (Pingen AG, Industriestrasse 27, 8304 Wallisellen, Switzerland)

- **Purpose:** physical printing and delivery of letters you send from the app.
- **What is transferred:** sender name and address, recipient name and address, full letter content as PDF including embedded signature, channel (A-Post or registered), an idempotency UUID.
- **Legal basis:** contract performance (Art. 31 para. 1 lit. a nDSG). Dispatch happens only when you actively trigger it.
- **Server location:** Switzerland.
- **Retention:** Pingen retains dispatch evidence for 90 days, then deletes it according to their privacy policy.
- **Data processing agreement:** signed and countersigned on 2026-04-21.
- **Provider privacy policy:** [https://www.pingen.com/de/datenschutz](https://www.pingen.com/de/datenschutz)

### 4.5 Apple App Store and Google Play

- **Purpose:** app distribution, payment processing for subscriptions and in-app purchases, optional device-level crash reports if you have enabled them in your OS settings.
- **What is transferred:** everything you provide at purchase time and whatever Apple or Google already captures through your account. We have no influence over this.
- **Apple privacy policy:** [https://www.apple.com/legal/privacy/](https://www.apple.com/legal/privacy/)
- **Google privacy policy:** [https://policies.google.com/privacy](https://policies.google.com/privacy)

---

## 5. Cookies and tracking

The app is a native mobile app and sets **no cookies**. There is no advertising, no trackers, no analytics SDK. No cross-app tracking, no fingerprinting, no Identifier for Advertisers.

---

## 6. Children and minors

Mietsenkung is aimed at adults who have entered into a valid lease agreement. The app is not intended for children under 16. We do not knowingly collect data from anyone under 16.

---

## 7. Your rights

Under nDSG (and GDPR where applicable) you have the following rights:

- **Access** (Art. 25 nDSG): you can ask us what data we process about you. Because we store nothing about you on our servers, the answer is usually: none. The app itself shows you all local data at any time.
- **Rectification** (Art. 32 nDSG): you can correct inaccurate data directly in the app.
- **Erasure** (Art. 32 nDSG): you can delete individual records in the app. If you uninstall the app, all local data is wiped automatically. No copy remains on our side.
- **Data portability** (Art. 28 nDSG): you can download generated letters as PDF and reuse them. Further structured exports are provided on request via e-mail.
- **Objection and restriction:** you can object to processing by Sentry and RevenueCat by discontinuing use of the app. A granular per-provider opt-out is not implemented in v1.0.
- **Right to lodge a complaint:** with the competent data protection authority. In Switzerland: Federal Data Protection and Information Commissioner (FDPIC), [https://www.edoeb.admin.ch](https://www.edoeb.admin.ch).

Please send requests to manuel.weingartner@gmx.ch. We respond within 30 days.

---

## 8. Data security

We take appropriate technical measures to protect your data:

- **Transport encryption:** all connections to Firebase, RevenueCat, Sentry and Pingen use HTTPS with TLS 1.2 or higher.
- **App integrity protection:** Firebase App Check ensures that only the official app can access our backend endpoints.
- **PII scrubbing in Sentry:** form input and click events are not captured server-side.
- **Signed data processing agreement** with Pingen per Art. 9 nDSG.
- **Data minimisation:** we only collect data needed for the respective purpose.
- **Local database:** sqflite on device, protected by the iOS and Android sandbox model.

---

## 9. Changes to this policy

We may adapt this privacy policy when app features, third parties or legal requirements change. The current version is available in the app menu under "About the app > Privacy" and in the app store listing. For material changes we notify you in advance via an in-app banner with 30 days lead time.

---

## 10. Contact

For all data protection inquiries:

**Manuel Weingartner**
E-mail: manuel.weingartner@gmx.ch

Postal address on request. We usually respond within 30 days.
