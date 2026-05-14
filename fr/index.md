---
layout: default
title: "Baisse-loyer. Récupère ce qui te revient."
description: Application suisse pour locataires. En 2 minutes elle vérifie si tu as droit à une baisse de loyer pour ton appartement et envoie la demande à ton·a bailleur·esse en un tap. Dès CHF 9.90.
lang: fr-CH
lang_short: fr
permalink: /fr/
---

<section class="hero">
  <div class="hero__bg-trend" aria-hidden="true">
    <!-- Historique réel du taux de référence OFL 2008–2025 (source: bwo.admin.ch).
         3.50% (sept 2008) jusqu'à 1.25% (aujourd'hui), avec hausse 2023 vers 1.75%
         et baisse 2025 retour à 1.25%. -->
    <svg viewBox="0 0 800 300" preserveAspectRatio="none">
      <defs>
        <linearGradient id="heroTrendGrad" x1="0" y1="0" x2="0" y2="1">
          <stop offset="0%" stop-color="#059669" stop-opacity="0.05"/>
          <stop offset="100%" stop-color="#059669" stop-opacity="0"/>
        </linearGradient>
      </defs>
      <path d="M 0 60 L 33 80 L 44 100 L 101 120 L 146 140 L 169 160 L 226 180 L 305 200 L 395 220 L 519 240 L 667 220 L 689 200 L 745 220 L 800 240 L 800 300 L 0 300 Z" fill="url(#heroTrendGrad)"/>
      <path data-trend-line d="M 0 60 L 33 80 L 44 100 L 101 120 L 146 140 L 169 160 L 226 180 L 305 200 L 395 220 L 519 240 L 667 220 L 689 200 L 745 220 L 800 240" fill="none" stroke="#059669" stroke-width="1.4" stroke-linecap="round" stroke-linejoin="round" opacity="0.22" stroke-dasharray="1500" stroke-dashoffset="1500">
        <animate attributeName="stroke-dashoffset" from="1500" to="0" dur="7s" fill="freeze"/>
      </path>
      <g fill="#059669" opacity="0.35">
        <circle data-trend-dot cx="0"   cy="60"  r="2.5"><animate attributeName="opacity" values="0;0.35;0.35" dur="7s" fill="freeze"/></circle>
        <circle data-trend-dot cx="44"  cy="100" r="2"><animate attributeName="opacity" values="0;0;0.35;0.35" dur="7s" fill="freeze"/></circle>
        <circle data-trend-dot cx="146" cy="140" r="2"><animate attributeName="opacity" values="0;0;0;0.35;0.35" dur="7s" fill="freeze"/></circle>
        <circle data-trend-dot cx="305" cy="200" r="2"><animate attributeName="opacity" values="0;0;0;0;0.35;0.35" dur="7s" fill="freeze"/></circle>
        <circle data-trend-dot cx="519" cy="240" r="2.5"><animate attributeName="opacity" values="0;0;0;0;0;0.35;0.35" dur="7s" fill="freeze"/></circle>
        <circle data-trend-dot cx="689" cy="200" r="2.5"><animate attributeName="opacity" values="0;0;0;0;0;0;0.35;0.35" dur="7s" fill="freeze"/></circle>
        <circle data-trend-dot cx="800" cy="240" r="2.8" fill="#047857"><animate attributeName="opacity" values="0;0;0;0;0;0;0;0.55;0.55" dur="7s" fill="freeze"/></circle>
      </g>
    </svg>
  </div>
  <div class="hero__inner">
    <div class="hero__copy" data-reveal>
      <a class="hero__brandmark" href="#download" aria-label="Télécharger l'application Baisse-loyer">
        <img src="{{ '/assets/app_icon.svg' | relative_url }}" alt="" class="hero__brandmark__icon" width="56" height="56">
        <span class="hero__brandmark__word">Baisse-loyer</span>
      </a>
      <span class="eyebrow">Baisse de loyer pour ton appartement, en 2 minutes</span>
      <h1 class="hero__title">Récupère<br>ce qui te <em>revient</em>.</h1>
      <p class="hero__sub">Tu paies peut-être un loyer trop élevé depuis des années. <strong>Baisse-loyer</strong> calcule ta prétention selon le droit fédéral et envoie la lettre par La Poste. Si ton·a bailleur·esse reste silencieux·se ou refuse, l'app t'accompagne jusqu'à l'autorité de conciliation.</p>

      <div class="hero__cta">
        <a class="store-button" href="#" data-coming-soon aria-label="Télécharger Baisse-loyer sur l'App Store">
          <svg class="store-button__icon" viewBox="0 0 384 512" fill="currentColor" aria-hidden="true"><path d="M318.7 268.7c-.2-36.7 16.4-64.4 50-84.8-18.8-26.9-47.2-41.7-84.7-44.6-35.5-2.8-74.3 20.7-88.5 20.7-15 0-49.4-19.7-76.4-19.7C63.3 141.2 4 184.8 4 273.5q0 39.3 14.4 81.2c12.8 36.7 59 126.7 107.2 125.2 25.2-.6 43-17.9 75.8-17.9 31.8 0 48.3 17.9 76.4 17.9 48.6-.7 90.4-82.5 102.6-119.3-65.2-30.7-61.7-90-61.7-91.9zm-56.6-164.2c27.3-32.4 24.8-61.9 24-72.5-24.1 1.4-52 16.4-67.9 34.9-17.5 19.8-27.8 44.3-25.6 71.9 26.1 2 49.9-11.4 69.5-34.3z"/></svg>
          <span class="store-button__text">
            <span class="store-button__small">Télécharger sur l'</span>
            <span class="store-button__big">App&nbsp;Store</span>
          </span>
        </a>
        <a class="store-button" href="#" data-coming-soon aria-label="Obtenir Baisse-loyer sur Google Play">
          <svg class="store-button__icon" viewBox="0 0 512 512" aria-hidden="true">
            <path fill="#34d399" d="M325.3 234.3 104.6 13l280.8 161.2-60.1 60.1z"/>
            <path fill="#fbbf24" d="M104.6 499 325.3 277.7l60.1 60.1L104.6 499z"/>
            <path fill="#60a5fa" d="m480.6 256.5-95.2 60.1-66.3-60.1 66.3-60.1 95.2 60.1z"/>
            <path fill="#f87171" d="m104.6 499 1.3-489.7 219.4 222 0 .3 0 .3z"/>
          </svg>
          <span class="store-button__text">
            <span class="store-button__small">Disponible sur</span>
            <span class="store-button__big">Google&nbsp;Play</span>
          </span>
        </a>
      </div>

      <p class="hero__pricing"><span class="hero__pricing-bit"><strong>Vérification du droit + alerte taux gratuites</strong></span><span class="dot" aria-hidden="true">·</span><span class="hero__pricing-bit">Lettre dès <strong>CHF&nbsp;9.90</strong></span><span class="dot" aria-hidden="true">·</span><span class="hero__pricing-bit">Courrier A inclus</span><span class="dot" aria-hidden="true">·</span><span class="hero__pricing-bit">Sans abonnement</span></p>

      <div class="qr-install" aria-label="QR codes pour installer l'app">
        <p class="qr-install__hint">Sur un ordinateur ? Scanne avec ton smartphone&nbsp;:</p>
        <div class="qr-install__row">
          <span class="qr-card">
            <img src="{{ '/assets/qr-app-store.svg' | relative_url }}" alt="QR code App Store" width="84" height="84">
            <span class="qr-card__label">App&nbsp;Store</span>
          </span>
          <span class="qr-card">
            <img src="{{ '/assets/qr-google-play.svg' | relative_url }}" alt="QR code Google Play" width="84" height="84">
            <span class="qr-card__label">Google&nbsp;Play</span>
          </span>
        </div>
      </div>

      <div class="hero__trust">
        <span class="trust-pill">
          <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/></svg>
          Conforme nLPD
        </span>
        <span class="trust-pill">
          <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="3" y="11" width="18" height="11" rx="2"/><path d="M7 11V7a5 5 0 0 1 10 0v4"/></svg>
          Tes données restent sur ton appareil
        </span>
        <span class="trust-pill">
          <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M3 12h18M12 3v18"/></svg>
          Swiss made
        </span>
      </div>
    </div>

    <div class="hero__visual" data-reveal>
      <div class="phone" role="img" aria-label="Écran d'exemple de Baisse-loyer : droit actuel CHF 73 par mois, un tap pour créer la lettre.">
        <div class="phone__notch"></div>
        <div class="phone__screen">
          <div class="phone__statusbar">
            <span>13:12</span>
            <span aria-hidden="true">●●●●● 5G</span>
          </div>
          <div class="phone__appbar">
            <span class="phone__appbar-leading" aria-hidden="true">
              <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"/><path d="M9.09 9a3 3 0 0 1 5.83 1c0 2-3 3-3 3"/><line x1="12" y1="17" x2="12.01" y2="17"/></svg>
            </span>
            <span class="phone__appbar-title">Baisse-loyer</span>
            <span class="phone__appbar-action" aria-hidden="true">
              <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="3"/><path d="M19.4 15a1.65 1.65 0 0 0 .33 1.82l.06.06a2 2 0 0 1-2.83 2.83l-.06-.06a1.65 1.65 0 0 0-1.82-.33 1.65 1.65 0 0 0-1 1.51V21a2 2 0 0 1-4 0v-.09a1.65 1.65 0 0 0-1-1.51 1.65 1.65 0 0 0-1.82.33l-.06.06a2 2 0 0 1-2.83-2.83l.06-.06a1.65 1.65 0 0 0 .33-1.82 1.65 1.65 0 0 0-1.51-1H3a2 2 0 0 1 0-4h.09a1.65 1.65 0 0 0 1.51-1 1.65 1.65 0 0 0-.33-1.82l-.06-.06a2 2 0 0 1 2.83-2.83l.06.06a1.65 1.65 0 0 0 1.82.33h0a1.65 1.65 0 0 0 1-1.51V3a2 2 0 0 1 4 0v.09a1.65 1.65 0 0 0 1 1.51h0a1.65 1.65 0 0 0 1.82-.33l.06-.06a2 2 0 0 1 2.83 2.83l-.06.06a1.65 1.65 0 0 0-.33 1.82v0a1.65 1.65 0 0 0 1.51 1H21a2 2 0 0 1 0 4h-.09a1.65 1.65 0 0 0-1.51 1z"/></svg>
            </span>
          </div>
          <div class="phone__body">
            <div class="phone__card">
              <p class="phone__claim-label">Ton droit</p>
              <div class="phone__claim-row">
                <span class="phone__claim-value">CHF&nbsp;73</span>
                <span class="phone__claim-unit">par mois</span>
              </div>
              <p class="phone__claim-sub">CHF&nbsp;876 par an · dès le 1er&nbsp;juin</p>
              <a class="phone__cta" href="#download">Créer la lettre →</a>
              <p class="phone__recalc">Recalculer</p>
            </div>
            <div class="phone__card">
              <p class="phone__history-title">
                <svg width="11" height="11" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M3 3v18h18"/><polyline points="7 14 11 10 15 14 21 8"/></svg>
                Historique du loyer
              </p>
              <div class="phone__history-row">
                <span>Actuel</span>
                <strong>CHF 1'920</strong>
              </div>
              <div class="phone__history-row">
                <span>Nouveau (dès 1er juin)</span>
                <strong class="is-new">CHF 1'847</strong>
              </div>
              <div class="phone__history-row">
                <span>Taux de référence</span>
                <strong>1.25&nbsp;%</strong>
              </div>
            </div>
          </div>
          <div class="phone__tabbar" aria-hidden="true">
            <span class="phone__tab phone__tab--active">
              <span class="phone__tab-icon-wrap">
                <svg viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2.5l9.5 8.2v10.3a1 1 0 0 1-1 1h-5.5v-7h-6v7H4.5a1 1 0 0 1-1-1V10.7L12 2.5z"/></svg>
              </span>
              <span>Accueil</span>
            </span>
            <span class="phone__tab">
              <span class="phone__tab-icon-wrap">
                <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M22 19a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h5l2 3h9a2 2 0 0 1 2 2z"/></svg>
              </span>
              <span>Données</span>
            </span>
            <span class="phone__tab">
              <span class="phone__tab-icon-wrap">
                <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="3" y="5" width="18" height="14" rx="2"/><path d="M3 7l9 6 9-6"/></svg>
              </span>
              <span>Lettres</span>
            </span>
            <span class="phone__tab">
              <span class="phone__tab-icon-wrap">
                <svg viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><circle cx="5" cy="12" r="1.7"/><circle cx="12" cy="12" r="1.7"/><circle cx="19" cy="12" r="1.7"/></svg>
              </span>
              <span>Plus</span>
            </span>
          </div>
          <div class="phone__home"></div>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="trust-strip">
  <div class="trust-strip__inner">
    <span class="trust-strip__label">Données et droit issus de sources officielles&nbsp;suisses</span>
    <div class="trust-strip__sources">
      <span>Office fédéral du logement</span>
      <span>Office fédéral de la statistique</span>
      <span>Droit du bail (CO + OBLF)</span>
      <span>Calculateur ZH</span>
    </div>
  </div>
</section>

<section class="section steps" id="how">
  <div class="section__inner">
    <span class="eyebrow" data-reveal>Déroulement</span>
    <h2 class="section-title" data-reveal>Trois étapes de la prétention à la lettre prête à envoyer.</h2>
    <p class="section-lead" data-reveal>Tu saisis ton loyer actuel et la date de la dernière adaptation. L'app calcule la prétention, génère la demande de baisse avec ta signature et la confie à La Poste suisse. Si ton·a bailleur·esse ne répond pas ou refuse, l'app gère aussi la suite.</p>

    <div class="steps__grid">
      <article class="step" data-reveal>
        <span class="step__num">01</span>
        <span class="step__icon">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="3" y="3" width="18" height="18" rx="3"/><path d="M9 9h6M9 13h6M9 17h4"/></svg>
        </span>
        <h3>Vérifier ton droit</h3>
        <p>Tu saisis ton loyer et la date de la dernière adaptation. L'app calcule selon le droit fédéral (art.&nbsp;270a&nbsp;CO + OBLF&nbsp;art.&nbsp;13) avec renchérissement et hausses de coûts. Parité 1:1 avec le calculateur des tribunaux zurichois.</p>
        <span class="step__time">≈ 2&nbsp;min · gratuit</span>
      </article>

      <article class="step" data-reveal>
        <span class="step__num">02</span>
        <span class="step__icon">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="2" y="5" width="20" height="14" rx="2"/><path d="M2 7l10 7 10-7"/></svg>
        </span>
        <h3>Un tap sur Envoyer</h3>
        <p>L'app génère ta demande de baisse avec ta signature au doigt, la transmet chiffrée à notre partenaire postal suisse, qui l'envoie en courrier A ou recommandé. Tu reçois une notification de confirmation.</p>
        <span class="step__time">≈ 3&nbsp;sec · dès CHF&nbsp;9.90</span>
      </article>

      <article class="step" data-reveal>
        <span class="step__num">03</span>
        <span class="step__icon">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M18 8a6 6 0 0 0-12 0c0 7-3 9-3 9h18s-3-2-3-9"/><path d="M13.73 21a2 2 0 0 1-3.46 0"/></svg>
        </span>
        <h3>Rappels automatiques et lettres de suivi</h3>
        <p>Si ton·a bailleur·esse ne répond pas, l'app te rappelle après 30 et 60 jours. Selon la réponse, elle te propose la lettre adaptée : une lettre de rappel en cas de silence, une demande de justification et de pièces en cas de refus, ou une demande de conciliation comme dernière étape.</p>
        <span class="step__time">automatique</span>
      </article>
    </div>
  </div>
</section>

<section class="stats">
  <div class="stats__inner">
    <span class="eyebrow" data-reveal>Pourquoi cette appli</span>
    <h2 class="stats__title" data-reveal>Les locataires en Suisse perdent des millions chaque année.</h2>
    <p class="stats__lead" data-reveal>Seule une fraction des personnes en droit réclame effectivement. La charge dissuade : calculer la prétention, rédiger la lettre, planifier les rappels, relancer en cas de silence ou refus. Baisse-loyer prend ces étapes en main, de la première vérification jusqu'à l'autorité de conciliation.</p>

    <div class="stats__grid">
      <div class="stat" data-reveal>
        <p class="stat__num"><span class="stat__num--accent">9&nbsp;sur&nbsp;10</span></p>
        <p class="stat__label">locataires ne demandent rien</p>
        <p class="stat__desc">Seuls 12 % font activement valoir une baisse, alors qu'environ la moitié y aurait droit. Source : étude ZKB&nbsp;2026.</p>
      </div>
      <div class="stat" data-reveal>
        <p class="stat__num">CHF&nbsp;73</p>
        <p class="stat__label">économie mensuelle moyenne</p>
        <p class="stat__desc">Pour un 2.5 pièces typique à CHF&nbsp;1'920. La lettre est rentabilisée la première semaine.</p>
      </div>
      <div class="stat" data-reveal>
        <p class="stat__num">2&nbsp;min</p>
        <p class="stat__label">de l'ouverture à la lettre prête</p>
        <p class="stat__desc">Tu saisis ton loyer et la date d'adaptation, l'app prend tout le reste en charge, jusqu'à la notification que la lettre est partie.</p>
      </div>
    </div>
  </div>
</section>

<section class="section">
  <div class="section__inner">
    <span class="eyebrow" data-reveal>Ce qui rend Baisse-loyer différent</span>
    <h2 class="section-title" data-reveal>Privée. Précise. En un tap.</h2>
    <p class="section-lead" data-reveal>Ce qui distingue Baisse-loyer d'un modèle Word.</p>

    <div class="bento">
      <article class="bento__card bento__a bento__card--accent" data-reveal>
        <span class="bento__icon">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M13 2L3 14h9l-1 8 10-12h-9l1-8z"/></svg>
        </span>
        <h3>Calcul à la précision des tribunaux</h3>
        <p>Baisse-loyer utilise les données fédérales officielles (taux de référence OFL, IPC OFS) et reproduit le calculateur de loyer des tribunaux zurichois au centime près. Y compris renchérissement, hausses de coûts et test d'admissibilité.</p>
      </article>

      <article class="bento__card bento__b" data-reveal>
        <span class="bento__icon">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="3" y="11" width="18" height="11" rx="2"/><path d="M7 11V7a5 5 0 0 1 10 0v4"/></svg>
        </span>
        <h3>Vie privée d'abord</h3>
        <p>Tes données restent chiffrées sur ton appareil. Pas de compte, pas de base de données cloud. Seul le PDF final est transmis chiffré à notre partenaire postal suisse.</p>
      </article>

      <article class="bento__card bento__c" data-reveal>
        <span class="bento__icon">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><circle cx="12" cy="12" r="10"/><path d="M12 6v6l4 2"/></svg>
        </span>
        <h3>Alerte taux gratuite</h3>
        <p>Notification dès que le taux de référence baisse. Pas d'inscription, pas d'abonnement. Tu peux utiliser l'appli uniquement comme système d'alerte précoce, c'est tout à fait OK.</p>
      </article>

      <article class="bento__card bento__d" data-reveal>
        <span class="bento__icon">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M9 12l2 2 4-4"/><path d="M21 12c0 5-4 9-9 9s-9-4-9-9 4-9 9-9c2 0 4 1 5 2"/></svg>
        </span>
        <h3>Accompagnement par dossier</h3>
        <p>Pour chaque appartement, l'app gère un dossier propre : prétention actuelle, toutes les lettres envoyées, statut selon la réaction de ton·a bailleur·esse (accepté, partiel, refusé). Rappels à 30 et 60 jours, suggestions concrètes pour l'étape suivante. Les dossiers clos passent à l'archive, un nouveau commence à tout moment.</p>
      </article>

      <article class="bento__card bento__e" data-reveal>
        <span class="bento__icon">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M3 3h18v18H3z"/><path d="M10 8h4M10 12h4M10 16h4M8 8v8M16 8v8"/></svg>
        </span>
        <h3>De la demande à la conciliation</h3>
        <p>Quatre types de lettres dans l'app : demande de baisse, lettre de rappel, demande de justification et de pièces, demande de conciliation. Chaque lettre de suivi est préparée dans le contexte du dossier, avec les copies des lettres précédentes en annexe. Pour la lettre de conciliation, tu téléverses le bail directement depuis l'app, par photo, fichier ou scanner de documents intégré.</p>
      </article>

      <article class="bento__card" data-reveal>
        <span class="bento__icon">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"/><circle cx="9" cy="7" r="4"/><path d="M23 21v-2a4 4 0 0 0-3-3.87"/><path d="M16 3.13a4 4 0 0 1 0 7.75"/></svg>
        </span>
        <h3>Adapté à ta situation</h3>
        <p>Tu vis seul·e, en couple ou en coloc ? Chaque locataire signe sur l'appareil, la lettre est formulée automatiquement dans la bonne forme. Si une régie gère ton appartement, l'app trouve l'adresse via le registre suisse du commerce. Pour un·e bailleur·esse privé·e, tu saisis simplement le nom.</p>
      </article>

      <article class="bento__card" data-reveal>
        <span class="bento__icon">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><circle cx="12" cy="12" r="10"/><path d="M2 12h20M12 2a15 15 0 0 1 0 20M12 2a15 15 0 0 0 0 20"/></svg>
        </span>
        <h3>Quatre langues</h3>
        <p>App et lettres en allemand, français, italien et anglais. Tu choisis la langue, l'app calcule, La Poste suisse livre.</p>
      </article>
    </div>
  </div>
</section>

<section class="section pricing" id="price">
  <div class="section__inner">
    <span class="eyebrow" data-reveal>Prix</span>
    <h2 class="section-title" data-reveal>Sans abonnement. Moins d'1/3 de ta première économie mensuelle.</h2>
    <p class="section-lead" data-reveal>La vérification du droit est gratuite. Tu paies uniquement quand tu envoies la lettre, et même là, qu'une seule fois par lettre.</p>

    <div class="pricing__grid">
      <article class="price-card" data-reveal>
        <p class="price-card__name">Gratuit</p>
        <p class="price-card__price">CHF&nbsp;0</p>
        <p class="price-card__price-sub">utilisation illimitée</p>
        <ul class="price-card__list">
          <li><svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><polyline points="20 6 9 17 4 12"/></svg>Vérification du droit en 2 minutes</li>
          <li><svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><polyline points="20 6 9 17 4 12"/></svg>Alerte si le taux de référence baisse</li>
          <li><svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><polyline points="20 6 9 17 4 12"/></svg>Historique du loyer + compteur d'économies</li>
          <li><svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><polyline points="20 6 9 17 4 12"/></svg>Données chiffrées localement, pas de compte</li>
        </ul>
        <div class="price-card__addons">
          <strong>Parfait pour découvrir.</strong> Si tu n'as pas droit à une baisse de loyer, tu n'as rien à payer.
        </div>
      </article>

      <article class="price-card price-card--featured" data-reveal>
        <span class="price-card__tag">Populaire</span>
        <p class="price-card__name">Envoi de la lettre</p>
        <p class="price-card__price">CHF&nbsp;9.90<span style="font-size: 0.4em; color: var(--ink-soft); font-weight: 500;">&nbsp;à 29.90</span></p>
        <p class="price-card__price-sub">une fois par lettre · courrier A inclus</p>
        <ul class="price-card__list">
          <li><svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><polyline points="20 6 9 17 4 12"/></svg>Demande de baisse en PDF juridiquement&nbsp;solide</li>
          <li><svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><polyline points="20 6 9 17 4 12"/></svg>Impression + envoi par notre partenaire postal suisse</li>
          <li><svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><polyline points="20 6 9 17 4 12"/></svg>Ta signature au doigt, capturée dans le wizard</li>
          <li><svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><polyline points="20 6 9 17 4 12"/></svg>Rappels automatiques + lettres de suivi disponibles</li>
        </ul>
        <div class="price-card__addons">
          <strong>Options (à la carte) :</strong>
          <div class="price-card__addons-grid">
            <div class="price-card__addons-row"><span>Recommandé avec suivi</span><strong>+ CHF 7.90</strong></div>
            <div class="price-card__addons-row"><span>Suivi rappel / demande de pièces (via Pingen)</span><strong>CHF 6.90</strong></div>
            <div class="price-card__addons-row"><span>Demande de conciliation en recommandé avec photo du bail et lettres précédentes en annexe (ou téléchargement Word)</span><strong>CHF 6.90 + 7.90</strong></div>
          </div>
        </div>
      </article>
    </div>

    <p class="pricing-note">Le prix de la lettre suit ton économie mensuelle, environ un tiers.</p>
    <p class="pricing-note">Petite baisse, petit prix. Grosse baisse, un peu plus, mais jamais au-dessus de CHF&nbsp;29.90.</p>
    <p class="pricing-note">CHF&nbsp;9.90 / 14.90 / 19.90 / 24.90 / 27.90 / 29.90, selon ton économie.</p>
  </div>
</section>

<section class="section" id="faq">
  <div class="section__inner">
    <span class="eyebrow" data-reveal>Questions fréquentes</span>
    <h2 class="section-title" data-reveal>Ce que tu veux savoir avant de te lancer.</h2>

    <div class="faq__list" data-reveal>
      <details>
        <summary>Est-ce que j'ai vraiment droit à une baisse ?</summary>
        <div class="faq__answer">
          <p>Si ta dernière adaptation de loyer reposait sur un taux de référence plus élevé qu'aujourd'hui, alors oui, très probablement. Baisse-loyer le calcule automatiquement selon l'art.&nbsp;270a&nbsp;CO et l'OBLF art.&nbsp;13. Tu n'as qu'à saisir ton loyer actuel et la date de la dernière adaptation.</p>
          <p>La vérification est gratuite. Si ta prétention est nulle, tu n'as rien à payer, le calcul reste gratuit.</p>
        </div>
      </details>

      <details>
        <summary>Combien coûte vraiment l'app ?</summary>
        <div class="faq__answer">
          <p>L'app est gratuite. La vérification du droit et l'alerte taux le restent. Tu paies uniquement l'envoi de la lettre : CHF&nbsp;9.90 à 29.90 selon ton économie mensuelle. Inclus : génération de la lettre, impression et distribution courrier A par notre partenaire postal suisse.</p>
          <p>Optionnel : recommandé avec suivi (+ CHF&nbsp;7.90). Lettres de suivi à CHF&nbsp;6.90 chacune, la <strong>lettre de rappel</strong> et la <strong>demande de justification et de pièces</strong> partent automatiquement via Pingen. La <strong>demande de conciliation</strong> part aussi depuis l'app, en recommandé (+ CHF&nbsp;7.90) avec ta photo du bail et toutes les lettres précédentes en annexe. Préfères-tu passer toi-même à La Poste ? Tu peux aussi la télécharger en <strong>fichier Word</strong>.</p>
        </div>
      </details>

      <details>
        <summary>Baisse-loyer est-elle une appli officielle de l'État ?</summary>
        <div class="faq__answer">
          <p>Non. Baisse-loyer est une application indépendante, sans lien avec la Confédération, un canton, une autorité ou un tribunal. Toutes les données et bases légales utilisées proviennent de sources officielles suisses. Voir le bloc Sources plus bas.</p>
          <p>Baisse-loyer ne remplace pas un conseil juridique. Pour des questions juridiques, contacte une association cantonale de défense des locataires ou un·e avocat·e.</p>
        </div>
      </details>

      <details>
        <summary>Que deviennent mes données ?</summary>
        <div class="faq__answer">
          <p>Tes données de loyer et de bail restent chiffrées sur ton appareil. Nous ne gérons aucune base de données cloud et tu n'as pas besoin de compte. Seul le PDF final de ta lettre est transmis chiffré à notre partenaire postal suisse pour impression et distribution.</p>
          <p>Détails dans la <a href="{{ '/privacy-de.html' | relative_url }}">politique de confidentialité</a>.</p>
        </div>
      </details>

      <details>
        <summary>Quelle est la précision du calcul ?</summary>
        <div class="faq__answer">
          <p>Au centime près face au calculateur des tribunaux zurichois. Nous utilisons les sources officielles (taux de référence OFL, IPC OFS) et reproduisons la formule de l'OBLF art.&nbsp;13, y compris renchérissement, hausses de coûts et test d'admissibilité.</p>
          <p>Quand les données fédérales sont mises à jour en amont, l'app les reprend automatiquement et recalcule au prochain ouverture.</p>
        </div>
      </details>

      <details>
        <summary>Que faire si mon·a bailleur·esse ne répond pas ?</summary>
        <div class="faq__answer">
          <p>Baisse-loyer te rappelle automatiquement après <strong>30 et 60 jours</strong>. À chaque rappel tu peux déclencher la lettre de suivi adaptée d'un seul tap, selon le statut : <strong>lettre de rappel</strong>, <strong>demande de justification et de pièces</strong> ou <strong>demande de conciliation</strong>. Chaque lettre de suivi coûte CHF&nbsp;6.90. La lettre de rappel et la demande de justification partent via Pingen avec courrier A inclus. La demande de conciliation part aussi directement depuis l'app, en recommandé (+ CHF&nbsp;7.90), avec ta photo du bail et les lettres précédentes en annexe, ou tu peux la télécharger en <strong>fichier Word</strong> et la déposer toi-même.</p>
          <p>Si tu vas à la conciliation, l'app t'aide à trouver l'autorité cantonale de conciliation compétente (source : OFL).</p>
        </div>
      </details>

      <details>
        <summary>Sur quels appareils Baisse-loyer fonctionne ?</summary>
        <div class="faq__answer">
          <p>iPhone (iOS&nbsp;15+) et Android (9+). Fonctionne sur smartphone comme sur tablette, l'écran plus grand de la tablette laisse simplement plus de place pour la saisie.</p>
        </div>
      </details>
    </div>
  </div>
</section>

<section class="section sources" id="sources">
  <div class="section__inner">
    <span class="eyebrow" data-reveal>Sources et avertissement</span>
    <h2 class="section-title" data-reveal>Tout vient de sources officielles suisses.</h2>
    <p class="section-lead" data-reveal>Baisse-loyer renvoie directement aux données fédérales et aux bases légales sous-jacentes. Tu peux vérifier toi-même chaque valeur dans l'app.</p>

    <div class="sources__grid">
      <a class="source-row" href="https://www.bwo.admin.ch/fr/taux-de-reference" rel="noopener">
        <span class="source-row__abbr">OFL</span>
        <span class="source-row__body">
          <span class="source-row__title">Taux d'intérêt de référence hypothécaire</span>
          <span class="source-row__sub">Office fédéral du logement, source primaire</span>
        </span>
      </a>
      <a class="source-row" href="https://www.bfs.admin.ch/bfs/fr/home/statistiques/prix/indice-prix-consommation.html" rel="noopener">
        <span class="source-row__abbr">OFS</span>
        <span class="source-row__body">
          <span class="source-row__title">Indice national des prix à la consommation</span>
          <span class="source-row__sub">Office fédéral de la statistique, pour le renchérissement</span>
        </span>
      </a>
      <a class="source-row" href="https://www.fedlex.admin.ch/eli/cc/27/317_321_377/fr" rel="noopener">
        <span class="source-row__abbr">CO</span>
        <span class="source-row__body">
          <span class="source-row__title">Droit du bail : CO art. 269 ss, en particulier 270a</span>
          <span class="source-row__sub">Code des obligations (Fedlex)</span>
        </span>
      </a>
      <a class="source-row" href="https://www.fedlex.admin.ch/eli/cc/1990/835_835_835/fr" rel="noopener">
        <span class="source-row__abbr">OBLF</span>
        <span class="source-row__body">
          <span class="source-row__title">Ordonnance sur le bail à loyer</span>
          <span class="source-row__sub">OBLF art. 13, formule de calcul</span>
        </span>
      </a>
      <a class="source-row" href="https://www.bwo.admin.ch/fr/procedure-de-conciliation" rel="noopener">
        <span class="source-row__abbr">AC</span>
        <span class="source-row__body">
          <span class="source-row__title">Annuaire des autorités de conciliation</span>
          <span class="source-row__sub">OFL, adresses cantonales</span>
        </span>
      </a>
      <a class="source-row" href="https://www.gerichte-zh.ch/de/themen/miete" rel="noopener">
        <span class="source-row__abbr">ZH</span>
        <span class="source-row__body">
          <span class="source-row__title">Informations en matière de bail des Tribunaux zurichois</span>
          <span class="source-row__sub">Référence de vérification (en allemand)</span>
        </span>
      </a>
    </div>

    <div class="sources-disclaimer">
      <p style="margin: 0 0 8px;"><strong>Baisse-loyer est une application indépendante.</strong> Sans lien avec la Confédération, les cantons, une autorité ou un tribunal, non opérée par eux et ne représente aucune entité gouvernementale.</p>
      <p style="margin: 0;">L'app n'est <strong>pas un conseil juridique</strong> et ne remplace pas un·e avocat·e. Pour des questions juridiques, contacte une association cantonale de locataires ou un·e avocat·e.</p>
    </div>
  </div>
</section>

<section class="cta" id="download">
  <div class="cta__inner" data-reveal>
    <h2>Prêt·e à faire valoir ta prétention ?</h2>
    <p>La vérification est gratuite. La lettre part dès CHF&nbsp;9.90, impression et courrier A inclus. Si ton·a bailleur·esse reste silencieux·se ou refuse, Baisse-loyer t'accompagne jusqu'à l'autorité de conciliation.</p>
    <div class="hero__cta">
      <a class="store-button" href="#" data-coming-soon aria-label="Télécharger Baisse-loyer sur l'App Store">
        <svg class="store-button__icon" viewBox="0 0 384 512" fill="currentColor" aria-hidden="true"><path d="M318.7 268.7c-.2-36.7 16.4-64.4 50-84.8-18.8-26.9-47.2-41.7-84.7-44.6-35.5-2.8-74.3 20.7-88.5 20.7-15 0-49.4-19.7-76.4-19.7C63.3 141.2 4 184.8 4 273.5q0 39.3 14.4 81.2c12.8 36.7 59 126.7 107.2 125.2 25.2-.6 43-17.9 75.8-17.9 31.8 0 48.3 17.9 76.4 17.9 48.6-.7 90.4-82.5 102.6-119.3-65.2-30.7-61.7-90-61.7-91.9zm-56.6-164.2c27.3-32.4 24.8-61.9 24-72.5-24.1 1.4-52 16.4-67.9 34.9-17.5 19.8-27.8 44.3-25.6 71.9 26.1 2 49.9-11.4 69.5-34.3z"/></svg>
        <span class="store-button__text">
          <span class="store-button__small">Télécharger sur l'</span>
          <span class="store-button__big">App&nbsp;Store</span>
        </span>
      </a>
      <a class="store-button" href="#" data-coming-soon aria-label="Obtenir Baisse-loyer sur Google Play">
        <svg class="store-button__icon" viewBox="0 0 512 512" aria-hidden="true">
          <path fill="#34d399" d="M325.3 234.3 104.6 13l280.8 161.2-60.1 60.1z"/>
          <path fill="#fbbf24" d="M104.6 499 325.3 277.7l60.1 60.1L104.6 499z"/>
          <path fill="#60a5fa" d="m480.6 256.5-95.2 60.1-66.3-60.1 66.3-60.1 95.2 60.1z"/>
          <path fill="#f87171" d="m104.6 499 1.3-489.7 219.4 222 0 .3 0 .3z"/>
        </svg>
        <span class="store-button__text">
          <span class="store-button__small">Disponible sur</span>
          <span class="store-button__big">Google&nbsp;Play</span>
        </span>
      </a>
    </div>
    <p class="hero__pricing"><span class="hero__pricing-bit"><strong>Vérification + alerte taux gratuites</strong></span><span class="dot" aria-hidden="true">·</span><span class="hero__pricing-bit">Lettre dès <strong>CHF&nbsp;9.90</strong></span><span class="dot" aria-hidden="true">·</span><span class="hero__pricing-bit">Sans abonnement</span></p>
  </div>
</section>
