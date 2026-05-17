---
layout: default
title: Datenschutzerklärung
description: Datenschutzerklärung für die App Mietsenkung. nDSG-konform, DSGVO-aware, local-first.
lang: de-CH
permalink: /privacy-de.html
---

<div class="lang-switch">
  <span class="active" aria-current="page">DE</span>
  <a href="privacy-fr.html">FR</a>
  <a href="privacy-it.html">IT</a>
  <a href="privacy-en.html">EN</a>
</div>

# Datenschutzerklärung Mietsenkung

- **Stand:** 2026-05-10
- **In Kraft ab:** Launch der App im Apple App Store / Google Play Store
- **Gilt für:** Mietsenkung iOS + Android App (Bundle ID `com.mietsenkung.mietsenkung`)

---

## 1. Verantwortliche Person

Verantwortlich für die Datenbearbeitung in dieser App ist:

**Manuel Weingartner**
Privatperson, kein Handelsregister-Eintrag.
E-Mail: kontakt@mietsenkung-app.ch
Postadresse auf Anfrage per E-Mail.

Diese Datenschutzerklärung richtet sich nach dem revidierten Schweizer Datenschutzgesetz (nDSG, in Kraft seit 01.09.2023). Für Nutzer&ast;innen mit Wohnsitz im EWR gelten ergänzend die einschlägigen Bestimmungen der EU-Datenschutz-Grundverordnung (DSGVO).

---

## 2. Überblick: Local-first

Mietsenkung ist bewusst "local-first" gebaut. Deine Mietvertragsdaten, deine Adresse, die Adresse deiner Vermieter&ast;in und deine Signatur bleiben ausschliesslich auf deinem Gerät in einer lokalen SQLite-Datenbank gespeichert. Es gibt kein Benutzer&ast;innen-Konto, keine Cloud-Synchronisierung, keine serverseitige Datenbank bei uns.

Daten werden nur in zwei Situationen an Dritte übertragen:

1. Wenn du einen Brief aus der App versendest (dann geht der Brief-Inhalt an Pingen).
2. Wenn die App Referenzzinssatz-Daten lädt oder eine Push-Benachrichtigung empfängt (dann läuft ein anonymer Kanal über Firebase).

Löschst du die App, sind alle Mietvertragsdaten weg. Es gibt keine Backup-Spur bei uns.

---

## 3. Welche Daten verarbeitet werden

### 3.1 Lokal auf deinem Gerät

- **Mieter&ast;in-Daten:** Name, Anschrift, optional weitere Co-Mieter&ast;innen
- **Vermieter&ast;in-Daten:** Name, Anschrift, optional E-Mail
- **Mietvertrag:** Netto-Mietzins, Startdatum des Mietverhältnisses, Datum der letzten Anpassung, Referenzzinssatz bei der Anpassung, Kündigungstermine
- **Brief-Historie:** generierte Briefe (PDF), Pingen-Tracking-IDs, Versanddatum
- **Signatur:** Finger-gezeichnetes PNG-Bild, pro Mieter&ast;in einmal erfasst, als BLOB in sqflite
- **Premium-Status:** gecachter RevenueCat-Entitlement-Flag
- **App-Einstellungen:** Sprache, Theme, Push-Präferenzen

### 3.2 Technische Daten (anonym)

- **FCM-Token:** eine anonyme Zeichenkette, die Googles Push-System pro App-Installation vergibt, damit wir dir Zins-Alarme schicken können. Kein Personenbezug.
- **App-Check-Token:** kurzlebiges Attestation-Token, das Integrität deines Geräts gegenüber Firebase bestätigt. Kein Personenbezug.
- **RevenueCat-App-User-ID:** anonyme UUID zur Zuordnung deines Abos. Kein Personenbezug, keine E-Mail.
- **Crash-Reports:** falls die App abstürzt, werden Stack-Trace, Gerätetyp und OS-Version an Sentry gesendet. PII wird vor Versand aktiv entfernt (siehe Ziff. 4.3).
- **Anonyme Nutzungs-Statistiken (opt-out):** Standardmässig aktiviert, jederzeit in den Einstellungen unter Datenschutz abschaltbar. Es werden ausschliesslich aggregierte Tages-Zähler in Firestore geführt (z.B. "Anzahl Anspruchs-Prüfungen heute", "Anzahl versendete Briefe heute", "Summe der akzeptierten CHF-Reduktionen heute" in 10er-Schritten gebuckelt). Es gibt **kein** User-ID-Feld, **kein** Device-ID-Feld, **kein** Event mit personenbezogenen Daten. Eine Re-Identifikation einzelner Personen aus diesen Zählern ist nicht möglich. Rechtsgrundlage: berechtigtes Interesse an Produkt-Erfolgsmessung (Art. 31 Abs. 2 nDSG, Art. 6 Abs. 1 lit. f DSGVO).

### 3.3 Daten, die wir **nicht** sammeln

- Keine personenbezogenen Analytics (kein Google Analytics, kein Firebase Analytics, kein Mixpanel). Die unter 3.2 erwähnten aggregierten Tages-Zähler enthalten keine Personen-Identifier.
- Kein Cross-Device-Tracking.
- Keine Werbe-IDs (IDFA / GAID werden nicht gelesen).
- Keine Standortdaten.
- Keine Kontakte, keine Kalender, keine Kamera. Zugriff wird nicht angefragt.
- Keine Fotos ausser der Signatur, die du selbst in der App zeichnest.

---

## 4. Wohin deine Daten gehen

Wir arbeiten mit wenigen, sorgfältig ausgewählten Auftragsverarbeitern zusammen. Jeder ist hier einzeln aufgeführt.

### 4.1 Firebase (Google LLC / Google Ireland Ltd)

- **Zweck:** Push-Benachrichtigungen ("Zins-Alarm"), Missbrauchsschutz (App Check), Backend-Endpoints für Referenzzinsdaten und als Pingen-Versand-Proxy.
- **Was übertragen wird:** FCM-Token und App-Check-Token. Bei Aufruf von Cloud Functions: anonyme API-Calls ohne Personenbezug. Briefdaten laufen via Function-Proxy nur im Versandfall durch (siehe 4.4).
- **Rechtsgrundlage:** berechtigtes Interesse an Betrieb und Sicherheit der App (Art. 31 Abs. 2 nDSG). Für EWR-Nutzer&ast;innen zusätzlich Art. 6 Abs. 1 lit. f DSGVO.
- **Serverstandort:** europe-west6 (Zürich) für Cloud Functions. FCM ist global durch Google betrieben.
- **Aufbewahrung:** FCM-Token existiert, solange die App installiert ist. Cloud-Functions-Logs: 30 Tage rotierend.
- **Datenschutz des Anbieters:** [https://firebase.google.com/support/privacy](https://firebase.google.com/support/privacy)

### 4.2 RevenueCat (RevenueCat Inc., USA)

- **Zweck:** Abo-Verwaltung (CHF 19.90/Jahr Premium, CHF 7.90 Einschreiben-Consumable).
- **Was übertragen wird:** anonyme App-User-ID, Kauf-Transaktionsbestätigungen, die RevenueCat von Apple / Google erhält. Keine Kreditkartennummern, keine Zahlungsdaten. Bezahlung läuft ausschliesslich über den App Store beziehungsweise Google Play.
- **Rechtsgrundlage:** Vertragserfüllung (Art. 31 Abs. 1 lit. a nDSG, Art. 6 Abs. 1 lit. b DSGVO).
- **Serverstandort:** USA. Datenübermittlung gestützt auf EU-Standardvertragsklauseln.
- **Aufbewahrung:** solange dein Abo aktiv ist, plus buchhalterische Aufbewahrungsfristen.
- **Datenschutz des Anbieters:** [https://www.revenuecat.com/privacy](https://www.revenuecat.com/privacy)

### 4.3 Sentry (Functional Software Inc., USA)

- **Zweck:** Fehler-Monitoring, damit Abstürze behoben werden können.
- **Was übertragen wird:** Stack-Traces, Gerätetyp, OS-Version, Breadcrumbs (App-interne Events im Moment des Fehlers).
- **PII-Scrubbing aktiv:** `ui.input`- und `ui.click`-Breadcrumbs werden serverseitig nicht aufgezeichnet, damit keine Formulareingaben in Sentry landen. `user`- und `request`-Kontexte werden gescrubbt. Offline-Noise (`SocketException` bei Host-Lookup) wird gedroppt.
- **Rechtsgrundlage:** berechtigtes Interesse an einer stabilen App (Art. 31 Abs. 2 nDSG).
- **Serverstandort:** USA.
- **Aufbewahrung:** 90 Tage rotierend.
- **Datenschutz des Anbieters:** [https://sentry.io/privacy/](https://sentry.io/privacy/)

### 4.4 Pingen (Pingen AG, Industriestrasse 27, 8304 Wallisellen, Schweiz)

- **Zweck:** physischer Druck und Zustellung von Briefen, die du aus der App verschickst.
- **Was übertragen wird:** Absender-Name und -Adresse, Empfänger-Name und -Adresse, vollständiger Brief-Inhalt als PDF inklusive eingebetteter Signatur, Kanal (Standardbrief oder Einschreiben), eine Idempotency-UUID.
- **Rechtsgrundlage:** Vertragserfüllung (Art. 31 Abs. 1 lit. a nDSG). Der Versand erfolgt nur auf aktive Auslösung durch dich.
- **Serverstandort:** Schweiz.
- **Aufbewahrung:** Pingen bewahrt Versand-Nachweise für 90 Tage auf. Danach Löschung gemäss Pingen-Datenschutzerklärung.
- **Auftragsverarbeitungsvertrag:** mit Pingen abgeschlossen und gegenbestätigt am 2026-04-21.
- **Datenschutz des Anbieters:** [https://www.pingen.com/de/datenschutz](https://www.pingen.com/de/datenschutz)

### 4.5 Apple App Store und Google Play

- **Zweck:** Distribution der App, Zahlungsabwicklung für Abos und In-App-Käufe, optionale Device-Level-Crash-Reports wenn du es in den OS-Einstellungen aktiviert hast.
- **Was übertragen wird:** alles, was du beim Kauf angibst und was Apple beziehungsweise Google ohnehin über deinen Account erfasst. Wir haben darauf keinen Einfluss.
- **Datenschutz von Apple:** [https://www.apple.com/legal/privacy/](https://www.apple.com/legal/privacy/)
- **Datenschutz von Google:** [https://policies.google.com/privacy](https://policies.google.com/privacy)

---

## 5. Cookies und Tracking

Die App ist eine native Mobile-App und setzt **keine Cookies**. Es gibt keine Werbung, keine Tracker, keine Analytics-SDKs. Kein Cross-App-Tracking, kein Fingerprinting, keine Identifier for Advertisers.

### 5.1 Webseite mietsenkung-app.ch

Diese Webseite ist statisch und wird über GitHub Pages ausgeliefert. Sie setzt **keine Cookies**, nutzt **kein Tracking**, lädt keine Drittanbieter-Skripte und speichert keine personenbezogenen Daten. Es läuft kein serverseitiges Analytics.

---

## 6. Kinder und Jugendliche

Mietsenkung richtet sich an Erwachsene, die einen gültigen Mietvertrag abgeschlossen haben. Die App ist nicht für Kinder unter 16 Jahren bestimmt. Wir erheben wissentlich keine Daten von Personen unter 16.

---

## 7. Deine Rechte

Nach nDSG (und DSGVO, falls anwendbar) stehen dir folgende Rechte zu:

- **Auskunft** (Art. 25 nDSG): Du kannst von uns erfragen, welche Daten wir über dich verarbeiten. Weil wir serverseitig nichts über dich speichern, ist die Antwort in der Regel: gar nichts. Die App selbst zeigt dir jederzeit alle lokalen Daten an.
- **Berichtigung** (Art. 32 nDSG): falsche Daten kannst du direkt in der App korrigieren.
- **Löschung** (Art. 32 nDSG): du kannst einzelne Einträge in der App löschen. Deinstallierst du die App, werden automatisch alle lokalen Daten entfernt. Es bleibt keine Kopie bei uns.
- **Datenportabilität** (Art. 28 nDSG): du kannst generierte Briefe als PDF herunterladen und weiterverwenden. Weitere strukturierte Exporte liefern wir auf Anfrage per E-Mail.
- **Widerspruch und Einschränkung:** du kannst gegen die Verarbeitung durch Sentry und RevenueCat widersprechen, indem du die App nicht mehr nutzt. Ein granulares Opt-out pro Drittanbieter ist in v1.0 nicht implementiert.
- **Beschwerderecht:** bei der zuständigen Datenschutzaufsichtsbehörde. In der Schweiz: Eidgenössischer Datenschutz- und Öffentlichkeitsbeauftragter (EDÖB), [https://www.edoeb.admin.ch](https://www.edoeb.admin.ch).

Anfragen richtest du bitte an kontakt@mietsenkung-app.ch. Wir antworten innerhalb von 48 Stunden.

---

## 8. Datensicherheit

Wir treffen angemessene technische Massnahmen, um deine Daten zu schützen:

- **Transportverschlüsselung:** alle Verbindungen zu Firebase, RevenueCat, Sentry und Pingen laufen über HTTPS mit TLS 1.2 oder höher.
- **App-Integritätsschutz:** Firebase App Check stellt sicher, dass nur die offizielle App auf unsere Backend-Endpoints zugreifen kann.
- **PII-Scrubbing in Sentry:** Formulareingaben und Klicks werden serverseitig nicht aufgezeichnet.
- **Signierter Auftragsverarbeitungsvertrag** mit Pingen gemäss Art. 9 nDSG.
- **Minimalprinzip:** wir erheben nur Daten, die für den jeweiligen Zweck nötig sind.
- **Lokale Datenbank:** sqflite auf dem Gerät, geschützt durch das Sandbox-Modell von iOS und Android.

---

## 9. Änderungen dieser Erklärung

Wir dürfen diese Datenschutzerklärung anpassen, wenn sich Funktionen der App, Drittanbieter oder gesetzliche Anforderungen ändern. Die jeweils aktuelle Version findest du im App-Menü unter "Über die App → Datenschutz" sowie im App-Store-Listing. Bei wesentlichen Änderungen informieren wir dich vor Inkrafttreten über ein In-App-Banner mit 30 Tagen Vorlauf.

---

## 10. Kontakt

Für alle Datenschutzanfragen:

**Manuel Weingartner**
E-Mail: kontakt@mietsenkung-app.ch

Postadresse auf Anfrage. Antwort in der Regel innerhalb 48 Stunden.
