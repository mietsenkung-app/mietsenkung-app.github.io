---
layout: default
title: Informativa sulla privacy
description: Informativa sulla privacy dell'app Ribassoaffitto. Conforme alla nLPD, compatibile GDPR, local-first.
lang: it-CH
permalink: /privacy-it.html
---

<div class="lang-switch">
  <a href="privacy-de.html">DE</a>
  <a href="privacy-fr.html">FR</a>
  <span class="active" aria-current="page">IT</span>
  <a href="privacy-en.html">EN</a>
</div>

# Informativa sulla privacy — Ribassoaffitto

- **Aggiornamento:** 2026-05-10
- **In vigore dal:** lancio dell'app sull'Apple App Store / Google Play Store
- **Si applica a:** Ribassoaffitto iOS + Android (Bundle ID `com.mietsenkung.mietsenkung`)

---

## 1. Persona responsabile

Responsabile del trattamento dei dati in questa app:

**Manuel Weingartner**
Persona privata, nessuna iscrizione al registro di commercio.
E-mail: kontakt@mietsenkung-app.ch
Indirizzo postale su richiesta via e-mail.

La presente informativa si fonda sulla legge federale svizzera riveduta sulla protezione dei dati (nLPD, in vigore dal 01.09.2023). Per gli utenti domiciliati nello SEE, si applicano in aggiunta le pertinenti disposizioni del Regolamento generale UE sulla protezione dei dati (GDPR).

---

## 2. Panoramica: local-first

Ribassoaffitto è progettata deliberatamente secondo il principio « local-first ». I tuoi dati di locazione, il tuo indirizzo, l'indirizzo del/della tuo/a locatore/locatrice e la tua firma rimangono esclusivamente sul tuo dispositivo, in un database SQLite locale. Non c'è nessun account utente, nessuna sincronizzazione cloud, nessun database lato server da parte nostra.

I dati vengono trasmessi a terzi solo in due situazioni:

1. Quando invii una lettera dall'app (il contenuto della lettera viene inviato a Pingen).
2. Quando l'app carica i dati sul tasso d'interesse di riferimento o riceve una notifica push (un canale anonimo passa via Firebase).

Se disinstalli l'app, tutti i dati di locazione spariscono. Non resta alcuna copia di backup da noi.

---

## 3. Quali dati vengono trattati

### 3.1 Localmente sul tuo dispositivo

- **Dati del/della locatario/a:** nome, indirizzo, opzionalmente co-locatari/e
- **Dati del/della locatore/locatrice:** nome, indirizzo, e-mail facoltativa
- **Contratto di locazione:** affitto netto, data d'inizio della locazione, data dell'ultimo adeguamento, tasso d'interesse di riferimento al momento dell'adeguamento, scadenze di disdetta
- **Storico lettere:** lettere generate (PDF), ID di tracciamento Pingen, data di spedizione
- **Firma:** immagine PNG disegnata col dito, salvata una volta per locatario/a, come BLOB in sqflite
- **Stato Premium:** flag di abbonamento RevenueCat in cache
- **Preferenze app:** lingua, tema, preferenze di notifica

### 3.2 Dati tecnici (anonimi)

- **Token FCM:** stringa anonima assegnata dal sistema di notifiche push di Google per installazione, affinché possiamo inviarti gli avvisi sul tasso. Nessun riferimento a una persona.
- **Token App Check:** token di attestazione di breve durata che certifica l'integrità del tuo dispositivo verso Firebase. Nessun riferimento a una persona.
- **ID utente RevenueCat:** UUID anonimo per associare il tuo abbonamento. Nessun riferimento personale, nessuna e-mail.
- **Rapporti di crash:** in caso di crash, lo stack-trace, il tipo di dispositivo e la versione del sistema operativo vengono inviati a Sentry. I dati personali vengono attivamente rimossi prima dell'invio (vedi 4.3).
- **Statistiche di utilizzo anonime (opt-out):** Attive di default, disattivabili in qualsiasi momento nelle Impostazioni, sezione Privacy. Vengono conservati solo contatori giornalieri aggregati in Firestore (ad esempio "numero di verifiche del diritto oggi", "numero di lettere inviate oggi", "somma delle riduzioni di affitto accettate oggi, arrotondate in fasce da 10 CHF"). **Nessun** identificativo utente, **nessun** identificativo del dispositivo, **nessun** evento con dati personali. Non è possibile re-identificare singole persone da questi contatori. Base giuridica: interesse legittimo a misurare il successo del prodotto (art. 31 cpv. 2 nLPD, art. 6 par. 1 lett. f GDPR).

### 3.3 Dati che **non** raccogliamo

- Nessun analytics nominativo (né Google Analytics, né Firebase Analytics, né Mixpanel). I contatori giornalieri aggregati menzionati al 3.2 non contengono alcun identificativo personale.
- Nessun tracking cross-device.
- Nessun ID pubblicitario (IDFA / GAID non vengono letti).
- Nessun dato di posizione.
- Nessun contatto, nessun calendario, nessun accesso alla fotocamera. Non viene richiesto alcun accesso.
- Nessuna foto, eccetto la firma che disegni tu stesso/a nell'app.

---

## 4. Dove vanno i tuoi dati

Lavoriamo con un numero ridotto di responsabili del trattamento accuratamente selezionati. Ognuno è elencato qui singolarmente.

### 4.1 Firebase (Google LLC / Google Ireland Ltd)

- **Scopo:** notifiche push (« avviso sul tasso »), protezione contro abusi (App Check), endpoint backend per i dati di riferimento e proxy d'invio Pingen.
- **Cosa viene trasmesso:** token FCM e token App Check. Per le chiamate alle Cloud Functions: chiamate API anonime senza riferimento personale. I dati delle lettere passano dal proxy della funzione solo in caso di invio (vedi 4.4).
- **Base giuridica:** interesse legittimo all'esercizio e alla sicurezza dell'app (art. 31 cpv. 2 nLPD). Per gli utenti dello SEE, in aggiunta art. 6 par. 1 lett. f GDPR.
- **Sede dei server:** europe-west6 (Zurigo) per le Cloud Functions. FCM è gestito globalmente da Google.
- **Conservazione:** il token FCM esiste finché l'app è installata. Log delle Cloud Functions: 30 giorni a rotazione.
- **Privacy del fornitore:** [https://firebase.google.com/support/privacy](https://firebase.google.com/support/privacy)

### 4.2 RevenueCat (RevenueCat Inc., USA)

- **Scopo:** gestione degli acquisti (consumabili CHF 9.90–29.90 per lettera, CHF 7.90 raccomandata).
- **Cosa viene trasmesso:** ID utente anonimo, conferme di transazione d'acquisto che RevenueCat riceve da Apple / Google. Nessun numero di carta di credito, nessun dato di pagamento. Il pagamento avviene esclusivamente tramite App Store o Google Play.
- **Base giuridica:** esecuzione del contratto (art. 31 cpv. 1 lett. a nLPD, art. 6 par. 1 lett. b GDPR).
- **Sede dei server:** USA. Trasferimento basato sulle clausole contrattuali tipo dell'UE.
- **Conservazione:** finché il tuo acquisto è attivo, più i termini di conservazione contabili.
- **Privacy del fornitore:** [https://www.revenuecat.com/privacy](https://www.revenuecat.com/privacy)

### 4.3 Sentry (Functional Software Inc., USA)

- **Scopo:** monitoraggio degli errori, per poter correggere i crash.
- **Cosa viene trasmesso:** stack-trace, tipo di dispositivo, versione OS, breadcrumbs (eventi interni all'app al momento dell'errore).
- **PII-scrubbing attivo:** i breadcrumbs `ui.input` e `ui.click` non vengono registrati lato server, in modo che nessun dato di un campo modulo finisca in Sentry. I contesti `user` e `request` vengono ripuliti. Il rumore offline (`SocketException` durante la risoluzione host) viene scartato.
- **Base giuridica:** interesse legittimo a un'app stabile (art. 31 cpv. 2 nLPD).
- **Sede dei server:** USA.
- **Conservazione:** 90 giorni a rotazione.
- **Privacy del fornitore:** [https://sentry.io/privacy/](https://sentry.io/privacy/)

### 4.4 Pingen (Pingen AG, Industriestrasse 27, 8304 Wallisellen, Svizzera)

- **Scopo:** stampa e recapito fisico delle lettere che invii dall'app.
- **Cosa viene trasmesso:** nome e indirizzo del/della mittente, nome e indirizzo del/della destinatario/a, contenuto completo della lettera in PDF inclusa la firma incorporata, canale (lettera standard o raccomandata), un UUID di idempotenza.
- **Base giuridica:** esecuzione del contratto (art. 31 cpv. 1 lett. a nLPD). L'invio avviene solo dopo un'attivazione attiva da parte tua.
- **Sede dei server:** Svizzera.
- **Conservazione:** Pingen conserva le prove di invio per 90 giorni. In seguito cancellazione conformemente all'informativa privacy di Pingen.
- **Contratto di responsabile del trattamento:** concluso e controfirmato con Pingen il 2026-04-21.
- **Privacy del fornitore:** [https://www.pingen.com/de/datenschutz](https://www.pingen.com/de/datenschutz)

### 4.5 Apple App Store e Google Play

- **Scopo:** distribuzione dell'app, elaborazione dei pagamenti per abbonamenti e acquisti in-app, rapporti di crash a livello di dispositivo facoltativi se attivati nelle impostazioni del sistema.
- **Cosa viene trasmesso:** tutto ciò che indichi all'acquisto e ciò che Apple o Google registra comunque sul tuo account. Non abbiamo alcun controllo su questo.
- **Privacy di Apple:** [https://www.apple.com/legal/privacy/](https://www.apple.com/legal/privacy/)
- **Privacy di Google:** [https://policies.google.com/privacy](https://policies.google.com/privacy)

---

## 5. Cookie e tracking

L'app è un'app mobile nativa e **non imposta cookie**. Nessuna pubblicità, nessun tracker, nessun SDK di analytics. Nessun tracking cross-app, nessun fingerprinting, nessun identificatore pubblicitario.

### 5.1 Sito web mietsenkung-app.ch

Questo sito web è statico, ospitato su GitHub Pages. **Non imposta alcun cookie**, **non utilizza alcun tracking**, non carica script di terze parti e non memorizza dati personali. Non viene utilizzata alcuna analytics lato server.

---

## 6. Bambini e adolescenti

Ribassoaffitto si rivolge a persone adulte che hanno stipulato un contratto di locazione valido. L'app non è destinata a bambini sotto i 16 anni. Non raccogliamo consapevolmente dati di persone sotto i 16 anni.

---

## 7. I tuoi diritti

In virtù della nLPD (e del GDPR, se applicabile), ti spettano i seguenti diritti:

- **Accesso** (art. 25 nLPD): puoi chiederci quali dati trattiamo su di te. Poiché lato server non memorizziamo nulla su di te, la risposta è di norma: nulla. L'app stessa ti mostra in qualsiasi momento tutti i dati locali.
- **Rettifica** (art. 32 nLPD): puoi correggere direttamente nell'app i dati errati.
- **Cancellazione** (art. 32 nLPD): puoi cancellare singole voci nell'app. Disinstallando l'app, tutti i dati locali vengono automaticamente rimossi. Nessuna copia rimane da noi.
- **Portabilità dei dati** (art. 28 nLPD): puoi scaricare le lettere generate in PDF e riutilizzarle. Ulteriori esportazioni strutturate forniamo su richiesta via e-mail.
- **Opposizione e limitazione:** puoi opporti al trattamento da parte di Sentry e RevenueCat smettendo di utilizzare l'app. Un opt-out granulare per fornitore non è implementato nella v1.0.
- **Diritto di reclamo:** presso l'autorità di vigilanza competente. In Svizzera: Incaricato federale della protezione dei dati e della trasparenza (IFPDT), [https://www.edoeb.admin.ch](https://www.edoeb.admin.ch).

Indirizza le tue richieste a kontakt@mietsenkung-app.ch. Rispondiamo entro 30 giorni.

---

## 8. Sicurezza dei dati

Adottiamo misure tecniche adeguate per proteggere i tuoi dati:

- **Cifratura del trasporto:** tutte le connessioni verso Firebase, RevenueCat, Sentry e Pingen avvengono via HTTPS con TLS 1.2 o superiore.
- **Protezione dell'integrità dell'app:** Firebase App Check garantisce che solo l'app ufficiale acceda ai nostri endpoint backend.
- **PII-scrubbing in Sentry:** input di moduli e click non vengono registrati lato server.
- **Contratto di responsabile del trattamento firmato** con Pingen ai sensi dell'art. 9 nLPD.
- **Principio di minimizzazione:** raccogliamo solo i dati necessari alla rispettiva finalità.
- **Database locale:** sqflite sul dispositivo, protetto dal modello sandbox di iOS e Android.

---

## 9. Modifiche di questa informativa

Possiamo adeguare la presente informativa privacy se le funzionalità dell'app, i fornitori terzi o i requisiti legali cambiano. La versione corrente è disponibile nel menu dell'app sotto « Informazioni → Privacy » e nella scheda dell'App Store. In caso di modifiche sostanziali ti informiamo prima dell'entrata in vigore tramite un banner in-app con 30 giorni di preavviso.

---

## 10. Contatto

Per tutte le richieste sulla privacy:

**Manuel Weingartner**
E-mail: kontakt@mietsenkung-app.ch

Indirizzo postale su richiesta. Rispondiamo di norma entro 30 giorni.
