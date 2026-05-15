---
layout: default
title: Politique de confidentialité
description: Politique de confidentialité de l'application Baisse-loyer. Conforme à la nLPD, compatible RGPD, local-first.
lang: fr-CH
permalink: /privacy-fr.html
---

<div class="lang-switch">
  <a href="privacy-de.html">DE</a>
  <span class="active" aria-current="page">FR</span>
  <a href="privacy-it.html">IT</a>
  <a href="privacy-en.html">EN</a>
</div>

# Politique de confidentialité — Baisse-loyer

- **État:** 2026-05-10
- **En vigueur depuis:** lancement de l'application sur l'Apple App Store / Google Play Store
- **S'applique à:** Baisse-loyer iOS + Android (Bundle ID `com.mietsenkung.mietsenkung`)

---

## 1. Personne responsable

Responsable du traitement des données dans cette application:

**Manuel Weingartner**
Personne privée, sans inscription au registre du commerce.
E-mail: kontakt@mietsenkung-app.ch
Adresse postale sur demande par e-mail.

La présente politique de confidentialité se fonde sur la loi fédérale révisée sur la protection des données (nLPD, en vigueur depuis le 01.09.2023). Pour les utilisateur·rice·s domicilié·e·s dans l'EEE, les dispositions applicables du règlement général de l'UE sur la protection des données (RGPD) s'appliquent en complément.

---

## 2. Aperçu: local-first

Baisse-loyer est volontairement conçue selon le principe « local-first ». Tes données de bail, ton adresse, l'adresse de ta·ton bailleur·euse et ta signature restent exclusivement sur ton appareil, dans une base SQLite locale. Il n'y a aucun compte utilisateur·rice, aucune synchronisation cloud, aucune base de données serveur de notre côté.

Des données ne sont transmises à des tiers que dans deux situations:

1. Lorsque tu envoies une lettre depuis l'application (le contenu de la lettre est alors transmis à Pingen).
2. Lorsque l'application charge des données sur le taux d'intérêt de référence ou reçoit une notification push (un canal anonyme passe alors par Firebase).

Si tu désinstalles l'application, toutes les données de bail disparaissent. Il ne reste aucune trace de sauvegarde chez nous.

---

## 3. Quelles données sont traitées

### 3.1 Localement sur ton appareil

- **Données du·de la locataire:** nom, adresse, optionnellement co-locataires
- **Données du·de la bailleur·euse:** nom, adresse, e-mail facultatif
- **Bail:** loyer net, date de début du bail, date du dernier ajustement, taux d'intérêt de référence lors de l'ajustement, dates de résiliation
- **Historique des lettres:** lettres générées (PDF), identifiants de suivi Pingen, date d'envoi
- **Signature:** image PNG dessinée au doigt, saisie une fois par locataire, stockée comme BLOB dans sqflite
- **Statut Premium:** indicateur d'abonnement RevenueCat mis en cache
- **Préférences de l'application:** langue, thème, préférences de notifications

### 3.2 Données techniques (anonymes)

- **Jeton FCM:** chaîne anonyme attribuée par le système de notifications de Google par installation, afin que nous puissions t'envoyer des alertes de taux. Aucune référence à une personne.
- **Jeton App Check:** jeton d'attestation de courte durée qui certifie l'intégrité de ton appareil auprès de Firebase. Aucune référence à une personne.
- **Identifiant utilisateur RevenueCat:** UUID anonyme pour rattacher ton abonnement. Aucune référence personnelle, aucune adresse e-mail.
- **Rapports de crash:** en cas de plantage, la trace de pile, le type d'appareil et la version de l'OS sont envoyés à Sentry. Les données personnelles sont activement supprimées avant l'envoi (voir 4.3).

### 3.3 Données que nous **ne** collectons **pas**

- Pas d'analytics (ni Google Analytics, ni Firebase Analytics, ni Mixpanel).
- Pas de suivi cross-device.
- Pas d'identifiants publicitaires (IDFA / GAID ne sont pas lus).
- Pas de données de localisation.
- Pas de contacts, pas de calendriers, pas d'accès à la caméra. Aucun accès n'est demandé.
- Aucune photo, à l'exception de la signature que tu dessines toi-même dans l'application.

---

## 4. Où vont tes données

Nous travaillons avec un nombre restreint de sous-traitants soigneusement sélectionnés. Chacun est listé individuellement ici.

### 4.1 Firebase (Google LLC / Google Ireland Ltd)

- **But:** notifications push (« alerte de taux »), protection contre les abus (App Check), points de terminaison backend pour les données de référence et proxy d'envoi Pingen.
- **Ce qui est transmis:** jeton FCM et jeton App Check. Lors d'appels aux Cloud Functions: appels API anonymes sans référence personnelle. Les données de lettre transitent par le proxy de fonction uniquement lors d'un envoi (voir 4.4).
- **Base légale:** intérêt légitime à exploiter et sécuriser l'application (art. 31 al. 2 nLPD). Pour les utilisateur·rice·s de l'EEE en complément art. 6 al. 1 let. f RGPD.
- **Localisation des serveurs:** europe-west6 (Zurich) pour les Cloud Functions. FCM est exploité globalement par Google.
- **Conservation:** le jeton FCM existe tant que l'application est installée. Logs des Cloud Functions: 30 jours par rotation.
- **Politique du fournisseur:** [https://firebase.google.com/support/privacy](https://firebase.google.com/support/privacy)

### 4.2 RevenueCat (RevenueCat Inc., USA)

- **But:** gestion des achats (consommables CHF 9.90–29.90 par lettre, CHF 7.90 envoi recommandé).
- **Ce qui est transmis:** identifiant utilisateur anonyme, confirmations de transaction d'achat reçues par RevenueCat depuis Apple / Google. Aucun numéro de carte de crédit, aucune donnée de paiement. Le paiement passe exclusivement par l'App Store ou Google Play.
- **Base légale:** exécution du contrat (art. 31 al. 1 let. a nLPD, art. 6 al. 1 let. b RGPD).
- **Localisation des serveurs:** USA. Transfert basé sur les clauses contractuelles types de l'UE.
- **Conservation:** tant que ton achat est actif, plus les délais de conservation comptables.
- **Politique du fournisseur:** [https://www.revenuecat.com/privacy](https://www.revenuecat.com/privacy)

### 4.3 Sentry (Functional Software Inc., USA)

- **But:** monitoring d'erreurs, afin de pouvoir corriger les plantages.
- **Ce qui est transmis:** traces de pile, type d'appareil, version d'OS, breadcrumbs (événements internes au moment de l'erreur).
- **PII-scrubbing actif:** les breadcrumbs `ui.input` et `ui.click` ne sont pas enregistrés côté serveur, afin qu'aucune saisie de formulaire n'arrive dans Sentry. Les contextes `user` et `request` sont nettoyés. Le bruit hors ligne (`SocketException` lors de la résolution d'hôte) est filtré.
- **Base légale:** intérêt légitime à une application stable (art. 31 al. 2 nLPD).
- **Localisation des serveurs:** USA.
- **Conservation:** 90 jours par rotation.
- **Politique du fournisseur:** [https://sentry.io/privacy/](https://sentry.io/privacy/)

### 4.4 Pingen (Pingen AG, Industriestrasse 27, 8304 Wallisellen, Suisse)

- **But:** impression et acheminement physiques des lettres que tu envoies depuis l'application.
- **Ce qui est transmis:** nom et adresse de l'expéditeur·rice, nom et adresse du·de la destinataire, contenu complet de la lettre en PDF y compris la signature intégrée, canal (lettre standard ou recommandé), un UUID d'idempotence.
- **Base légale:** exécution du contrat (art. 31 al. 1 let. a nLPD). L'envoi a lieu uniquement sur ton déclenchement actif.
- **Localisation des serveurs:** Suisse.
- **Conservation:** Pingen conserve les preuves d'envoi pendant 90 jours. Suppression ensuite conformément à la politique de Pingen.
- **Contrat de sous-traitance:** conclu et contresigné avec Pingen le 2026-04-21.
- **Politique du fournisseur:** [https://www.pingen.com/de/datenschutz](https://www.pingen.com/de/datenschutz)

### 4.5 Apple App Store et Google Play

- **But:** distribution de l'application, traitement des paiements pour abonnements et achats intégrés, rapports de plantage optionnels au niveau de l'appareil si tu les as activés dans les réglages OS.
- **Ce qui est transmis:** tout ce que tu indiques lors de l'achat et ce qu'Apple ou Google enregistre déjà sur ton compte. Nous n'avons aucune influence à ce sujet.
- **Politique d'Apple:** [https://www.apple.com/legal/privacy/](https://www.apple.com/legal/privacy/)
- **Politique de Google:** [https://policies.google.com/privacy](https://policies.google.com/privacy)

---

## 5. Cookies et suivi

L'application est une application mobile native et ne pose **aucun cookie**. Pas de publicité, pas de traceurs, pas de SDK d'analytics. Pas de tracking cross-app, pas de fingerprinting, pas d'identifiants publicitaires.

### 5.1 Site web mietsenkung-app.ch

Ce site web est statique, hébergé sur GitHub Pages. Il **ne pose aucun cookie**, **n'utilise aucun tracking**, ne charge aucun script tiers et ne stocke pas de données personnelles. Aucune analytique côté serveur n'est exploitée.

---

## 6. Enfants et adolescents

Baisse-loyer s'adresse à des adultes ayant conclu un bail valide. L'application n'est pas destinée aux enfants de moins de 16 ans. Nous ne collectons sciemment aucune donnée de personnes de moins de 16 ans.

---

## 7. Tes droits

En vertu de la nLPD (et du RGPD si applicable), tu disposes des droits suivants:

- **Accès** (art. 25 nLPD): tu peux nous demander quelles données nous traitons à ton sujet. Comme nous ne stockons rien à ton sujet côté serveur, la réponse est en général: rien. L'application elle-même t'affiche à tout moment toutes les données locales.
- **Rectification** (art. 32 nLPD): tu peux corriger directement des données incorrectes dans l'application.
- **Effacement** (art. 32 nLPD): tu peux supprimer des entrées individuelles dans l'application. En désinstallant l'application, toutes les données locales sont automatiquement supprimées. Aucune copie ne subsiste chez nous.
- **Portabilité des données** (art. 28 nLPD): tu peux télécharger les lettres générées en PDF et les réutiliser. D'autres exports structurés sont fournis sur demande par e-mail.
- **Opposition et limitation:** tu peux t'opposer au traitement par Sentry et RevenueCat en cessant d'utiliser l'application. Un opt-out granulaire par fournisseur tiers n'est pas implémenté en v1.0.
- **Droit de plainte:** auprès de l'autorité de contrôle compétente. En Suisse: Préposé fédéral à la protection des données et à la transparence (PFPDT), [https://www.edoeb.admin.ch](https://www.edoeb.admin.ch).

Adresse tes demandes à kontakt@mietsenkung-app.ch. Nous répondons dans un délai de 30 jours.

---

## 8. Sécurité des données

Nous prenons des mesures techniques appropriées pour protéger tes données:

- **Chiffrement de transport:** toutes les connexions vers Firebase, RevenueCat, Sentry et Pingen passent par HTTPS avec TLS 1.2 ou supérieur.
- **Protection de l'intégrité de l'app:** Firebase App Check garantit que seule l'application officielle accède à nos points de terminaison backend.
- **PII-scrubbing dans Sentry:** saisies de formulaire et clics ne sont pas enregistrés côté serveur.
- **Contrat de sous-traitance signé** avec Pingen conformément à l'art. 9 nLPD.
- **Principe de minimisation:** nous ne collectons que les données nécessaires à la finalité concernée.
- **Base de données locale:** sqflite sur l'appareil, protégée par le modèle de sandbox d'iOS et d'Android.

---

## 9. Modifications de cette déclaration

Nous pouvons adapter cette politique de confidentialité si les fonctionnalités de l'application, les fournisseurs tiers ou les exigences légales évoluent. La version en vigueur est disponible dans le menu de l'application sous « À propos → Confidentialité » ainsi que dans la fiche de l'App Store. En cas de modifications substantielles, nous t'informons avant l'entrée en vigueur via une bannière in-app avec un préavis de 30 jours.

---

## 10. Contact

Pour toutes les demandes liées à la confidentialité:

**Manuel Weingartner**
E-mail: kontakt@mietsenkung-app.ch

Adresse postale sur demande. Nous répondons en règle générale dans un délai de 30 jours.
