---
layout: default
title: "Mietsenkung. Hol dir zurück was dir zusteht."
description: Schweizer App für Mieter*innen. In 2 Minuten prüft sie, ob dir eine Mietzinssenkung deiner Wohnung zusteht, und versendet das Senkungsbegehren mit einem Tap per Post. Ab CHF 9.90.
lang: de-CH
lang_short: de
permalink: /
---

<section class="hero">
  <div class="hero__bg-trend" aria-hidden="true">
    <!-- Echte BWO-Referenzzinssatz-Historie 2008–2025 (Quelle: bwo.admin.ch).
         3.50% (Sep 2008) bis 1.25% (heute), mit Anstieg 2023 von 1.25% → 1.75%
         und Rückgang 2025 zurück auf 1.25%. -->
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
      <a class="hero__brandmark" href="#download" aria-label="Mietsenkung App laden">
        <img src="{{ '/assets/app_icon.svg' | relative_url }}" alt="" class="hero__brandmark__icon" width="56" height="56">
        <span class="hero__brandmark__word">Mietsenkung</span>
      </a>
      <span class="eyebrow">Mietzinssenkung in 2 Minuten</span>
      <h1 class="hero__title">Hol dir zurück<br>was dir <em>zusteht</em>.</h1>
      <p class="hero__sub">Du zahlst womöglich seit Jahren zu viel Miete für deine Wohnung. <strong>Mietsenkung</strong> berechnet deinen Anspruch nach Bundesrecht und versendet den Brief per Post. Bei Schweigen oder Ablehnung deiner Vermieter*in begleitet dich die App weiter bis zur Schlichtungsbehörde.</p>

      <div class="hero__cta">
        <a class="store-button" href="#" data-coming-soon aria-label="Mietsenkung im App Store laden">
          <svg class="store-button__icon" viewBox="0 0 384 512" fill="currentColor" aria-hidden="true"><path d="M318.7 268.7c-.2-36.7 16.4-64.4 50-84.8-18.8-26.9-47.2-41.7-84.7-44.6-35.5-2.8-74.3 20.7-88.5 20.7-15 0-49.4-19.7-76.4-19.7C63.3 141.2 4 184.8 4 273.5q0 39.3 14.4 81.2c12.8 36.7 59 126.7 107.2 125.2 25.2-.6 43-17.9 75.8-17.9 31.8 0 48.3 17.9 76.4 17.9 48.6-.7 90.4-82.5 102.6-119.3-65.2-30.7-61.7-90-61.7-91.9zm-56.6-164.2c27.3-32.4 24.8-61.9 24-72.5-24.1 1.4-52 16.4-67.9 34.9-17.5 19.8-27.8 44.3-25.6 71.9 26.1 2 49.9-11.4 69.5-34.3z"/></svg>
          <span class="store-button__text">
            <span class="store-button__small">Laden im</span>
            <span class="store-button__big">App&nbsp;Store</span>
          </span>
        </a>
        <a class="store-button" href="#" data-coming-soon aria-label="Mietsenkung bei Google Play laden">
          <svg class="store-button__icon" viewBox="0 0 512 512" aria-hidden="true">
            <path fill="#34d399" d="M325.3 234.3 104.6 13l280.8 161.2-60.1 60.1z"/>
            <path fill="#fbbf24" d="M104.6 499 325.3 277.7l60.1 60.1L104.6 499z"/>
            <path fill="#60a5fa" d="m480.6 256.5-95.2 60.1-66.3-60.1 66.3-60.1 95.2 60.1z"/>
            <path fill="#f87171" d="m104.6 499 1.3-489.7 219.4 222 0 .3 0 .3z"/>
          </svg>
          <span class="store-button__text">
            <span class="store-button__small">Jetzt bei</span>
            <span class="store-button__big">Google&nbsp;Play</span>
          </span>
        </a>
      </div>

      <p class="hero__pricing"><span class="hero__pricing-bit"><strong>Anspruch prüfen + Zins-Alarm gratis</strong></span><span class="dot" aria-hidden="true">·</span><span class="hero__pricing-bit">Brief ab <strong>CHF&nbsp;9.90</strong></span><span class="dot" aria-hidden="true">·</span><span class="hero__pricing-bit">Brief-Versand inklusive</span><span class="dot" aria-hidden="true">·</span><span class="hero__pricing-bit">Kein Abo</span></p>

      <div class="qr-install" aria-label="QR-Codes zum Installieren der App">
        <p class="qr-install__hint">Am Laptop? Mit Smartphone scannen:</p>
        <div class="qr-install__row">
          <span class="qr-card">
            <img src="{{ '/assets/qr-app-store.svg' | relative_url }}" alt="QR-Code App Store" width="84" height="84">
            <span class="qr-card__label">App&nbsp;Store</span>
          </span>
          <span class="qr-card">
            <img src="{{ '/assets/qr-google-play.svg' | relative_url }}" alt="QR-Code Google Play" width="84" height="84">
            <span class="qr-card__label">Google&nbsp;Play</span>
          </span>
        </div>
      </div>

      <div class="hero__trust">
        <span class="trust-pill">
          <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/></svg>
          nDSG-konform
        </span>
        <span class="trust-pill">
          <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="3" y="11" width="18" height="11" rx="2"/><path d="M7 11V7a5 5 0 0 1 10 0v4"/></svg>
          Daten bleiben auf deinem Gerät
        </span>
        <span class="trust-pill">
          <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M3 12h18M12 3v18"/></svg>
          Swiss made
        </span>
      </div>
    </div>

    <div class="hero__visual" data-reveal>
      <div class="phone" role="img" aria-label="Beispiel-Bildschirm der App Mietsenkung: aktueller Anspruch CHF 73 pro Monat, ein Tap zum Brief erstellen.">
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
            <span class="phone__appbar-title">Mietsenkung</span>
            <span class="phone__appbar-action" aria-hidden="true">
              <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="3"/><path d="M19.4 15a1.65 1.65 0 0 0 .33 1.82l.06.06a2 2 0 0 1-2.83 2.83l-.06-.06a1.65 1.65 0 0 0-1.82-.33 1.65 1.65 0 0 0-1 1.51V21a2 2 0 0 1-4 0v-.09a1.65 1.65 0 0 0-1-1.51 1.65 1.65 0 0 0-1.82.33l-.06.06a2 2 0 0 1-2.83-2.83l.06-.06a1.65 1.65 0 0 0 .33-1.82 1.65 1.65 0 0 0-1.51-1H3a2 2 0 0 1 0-4h.09a1.65 1.65 0 0 0 1.51-1 1.65 1.65 0 0 0-.33-1.82l-.06-.06a2 2 0 0 1 2.83-2.83l.06.06a1.65 1.65 0 0 0 1.82.33h0a1.65 1.65 0 0 0 1-1.51V3a2 2 0 0 1 4 0v.09a1.65 1.65 0 0 0 1 1.51h0a1.65 1.65 0 0 0 1.82-.33l.06-.06a2 2 0 0 1 2.83 2.83l-.06.06a1.65 1.65 0 0 0-.33 1.82v0a1.65 1.65 0 0 0 1.51 1H21a2 2 0 0 1 0 4h-.09a1.65 1.65 0 0 0-1.51 1z"/></svg>
            </span>
          </div>
          <div class="phone__body">
            <div class="phone__card">
              <p class="phone__claim-label">Dein Anspruch</p>
              <div class="phone__claim-row">
                <span class="phone__claim-value">CHF&nbsp;73</span>
                <span class="phone__claim-unit">pro Monat</span>
              </div>
              <p class="phone__claim-sub">CHF&nbsp;876 pro Jahr · ab 1.&nbsp;Juni</p>
              <a class="phone__cta" href="#download">Brief erstellen →</a>
              <p class="phone__recalc">Neu berechnen</p>
            </div>
            <div class="phone__card">
              <p class="phone__history-title">
                <svg width="11" height="11" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M3 3v18h18"/><polyline points="7 14 11 10 15 14 21 8"/></svg>
                Mietverlauf
              </p>
              <div class="phone__history-row">
                <span>Aktuell</span>
                <strong>CHF 1'920</strong>
              </div>
              <div class="phone__history-row">
                <span>Neu (ab 1. Juni)</span>
                <strong class="is-new">CHF 1'847</strong>
              </div>
              <div class="phone__history-row">
                <span>Referenzzins</span>
                <strong>1.25&nbsp;%</strong>
              </div>
            </div>
          </div>
          <div class="phone__tabbar" aria-hidden="true">
            <span class="phone__tab phone__tab--active">
              <span class="phone__tab-icon-wrap">
                <svg viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2.5l9.5 8.2v10.3a1 1 0 0 1-1 1h-5.5v-7h-6v7H4.5a1 1 0 0 1-1-1V10.7L12 2.5z"/></svg>
              </span>
              <span>Home</span>
            </span>
            <span class="phone__tab">
              <span class="phone__tab-icon-wrap">
                <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M22 19a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h5l2 3h9a2 2 0 0 1 2 2z"/></svg>
              </span>
              <span>Daten</span>
            </span>
            <span class="phone__tab">
              <span class="phone__tab-icon-wrap">
                <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="3" y="5" width="18" height="14" rx="2"/><path d="M3 7l9 6 9-6"/></svg>
              </span>
              <span>Briefe</span>
            </span>
            <span class="phone__tab">
              <span class="phone__tab-icon-wrap">
                <svg viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><circle cx="5" cy="12" r="1.7"/><circle cx="12" cy="12" r="1.7"/><circle cx="19" cy="12" r="1.7"/></svg>
              </span>
              <span>Mehr</span>
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
    <span class="trust-strip__label">Daten und Recht aus offiziellen&nbsp;Schweizer Quellen</span>
    <div class="trust-strip__sources">
      <span>Bundesamt für Wohnungswesen</span>
      <span>Bundesamt für Statistik</span>
      <span>Mietrecht (OR + VMWG)</span>
      <span>Zürcher Mietzinsrechner</span>
    </div>
  </div>
</section>

<section class="section steps" id="how">
  <div class="section__inner">
    <span class="eyebrow" data-reveal>Ablauf</span>
    <h2 class="section-title" data-reveal>Drei Schritte vom Anspruch bis zum versandfertigen Brief.</h2>
    <p class="section-lead" data-reveal>Du gibst deinen aktuellen Mietzins und das Datum der letzten Anpassung ein. Die App berechnet den Anspruch, generiert das Senkungsbegehren mit deiner Unterschrift und übergibt es der Schweizer Post. Reagiert dein*e Vermieter*in nicht oder lehnt ab, übernimmt die App auch den nächsten Schritt.</p>

    <div class="steps__grid">
      <article class="step" data-reveal>
        <span class="step__num">01</span>
        <span class="step__icon">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="3" y="3" width="18" height="18" rx="3"/><path d="M9 9h6M9 13h6M9 17h4"/></svg>
        </span>
        <h3>Anspruch prüfen</h3>
        <p>Mietzins und Datum der letzten Anpassung eingeben. Die App rechnet nach Bundesrecht (Art.&nbsp;270a&nbsp;OR + VMWG&nbsp;Art.&nbsp;13) inkl. Teuerung und Kostensteigerung. Resultat 1:1 mit dem Mietzinsrechner der Zürcher&nbsp;Gerichte.</p>
        <span class="step__time">≈ 2&nbsp;min · gratis</span>
      </article>

      <article class="step" data-reveal>
        <span class="step__num">02</span>
        <span class="step__icon">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="2" y="5" width="20" height="14" rx="2"/><path d="M2 7l10 7 10-7"/></svg>
        </span>
        <h3>Ein Tap auf Senden</h3>
        <p>Die App generiert dein Senkungsbegehren mit deiner Unterschrift, übergibt es verschlüsselt an unseren Schweizer Post-Partner und der versendet als Standardbrief oder Einschreiben. Du erhältst eine Push-Bestätigung.</p>
        <span class="step__time">≈ 3&nbsp;sek · ab CHF&nbsp;9.90</span>
      </article>

      <article class="step" data-reveal>
        <span class="step__num">03</span>
        <span class="step__icon">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M18 8a6 6 0 0 0-12 0c0 7-3 9-3 9h18s-3-2-3-9"/><path d="M13.73 21a2 2 0 0 1-3.46 0"/></svg>
        </span>
        <h3>Auto-Reminder und Folgebriefe</h3>
        <p>Reagiert dein*e Vermieter*in nicht, erinnert die App dich nach 30 und 60 Tagen. Je nach Antwort schlägt sie den passenden Folgebrief vor: Erinnerungsschreiben bei Schweigen, Aufforderung zur Begründung bei Ablehnung, oder die Schlichtungsklage als letzten Schritt.</p>
        <span class="step__time">automatisch</span>
      </article>
    </div>
  </div>
</section>

<section class="stats">
  <div class="stats__inner">
    <span class="eyebrow" data-reveal>Warum gibt's das</span>
    <h2 class="stats__title" data-reveal>Schweizer Mieter*innen verschenken jährlich Millionen.</h2>
    <p class="stats__lead" data-reveal>Nur ein Bruchteil der Berechtigten fordert die Senkung tatsächlich ein. Der Aufwand schreckt ab: Anspruch berechnen, Brief formulieren, Termine setzen, bei Schweigen oder Ablehnung den nächsten Schritt einleiten. <strong>Mietsenkung</strong> übernimmt diese Schritte vollständig, vom Anspruchs-Check bis zur Schlichtungsbehörde.</p>

    <div class="stats__grid">
      <div class="stat" data-reveal>
        <p class="stat__num"><span class="stat__num--accent">9&nbsp;von&nbsp;10</span></p>
        <p class="stat__label">Mieter*innen fordern nichts ein</p>
        <p class="stat__desc">Nur 12 % verlangen aktiv eine Senkung, obwohl rund die Hälfte Anspruch hätte. Quelle: ZKB-Studie&nbsp;2026.</p>
      </div>
      <div class="stat" data-reveal>
        <p class="stat__num">CHF&nbsp;73</p>
        <p class="stat__label">durchschnittliche Monatsersparnis</p>
        <p class="stat__desc">Bei einer typischen 2.5-Zimmer-Wohnung à CHF&nbsp;1'920. Ein Brief amortisiert sich in der ersten Woche.</p>
      </div>
      <div class="stat" data-reveal>
        <p class="stat__num">2&nbsp;min</p>
        <p class="stat__label">vom Öffnen zum versandfertigen Brief</p>
        <p class="stat__desc">Du gibst deinen Mietzins und das Anpassungs-Datum ein, die App übernimmt alles Weitere bis zur Push-Benachrichtigung über den Briefversand.</p>
      </div>
    </div>
  </div>
</section>

<section class="section">
  <div class="section__inner">
    <span class="eyebrow" data-reveal>Was Mietsenkung anders macht</span>
    <h2 class="section-title" data-reveal>Privat. Präzise. Mit einem Tap.</h2>
    <p class="section-lead" data-reveal>Was <strong>Mietsenkung</strong> von einer Word-Vorlage unterscheidet.</p>

    <div class="bento">
      <article class="bento__card bento__a bento__card--accent" data-reveal>
        <span class="bento__icon">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M13 2L3 14h9l-1 8 10-12h-9l1-8z"/></svg>
        </span>
        <h3>Berechnung mit Gerichts-Parität</h3>
        <p><strong>Mietsenkung</strong> verwendet Bundesrechts-Quelldaten (BWO Referenzzinssatz, BFS Landesindex der Konsumentenpreise) und reproduziert die Berechnung des amtlichen Mietzinsrechners der Zürcher Gerichte auf Rappen-Genauigkeit. Inklusive Teuerung, Kostensteigerung, Tragbarkeits-Check.</p>
      </article>

      <article class="bento__card bento__b" data-reveal>
        <span class="bento__icon">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="3" y="11" width="18" height="11" rx="2"/><path d="M7 11V7a5 5 0 0 1 10 0v4"/></svg>
        </span>
        <h3>Privacy-first</h3>
        <p>Deine Daten bleiben verschlüsselt auf deinem Gerät. Kein Konto, keine Cloud-DB. Nur das fertige PDF wird verschlüsselt an unseren Schweizer Versand-Partner übergeben.</p>
      </article>

      <article class="bento__card bento__c" data-reveal>
        <span class="bento__icon">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><circle cx="12" cy="12" r="10"/><path d="M12 6v6l4 2"/></svg>
        </span>
        <h3>Zins-Alarm gratis</h3>
        <p>Push-Benachrichtigung sobald der Referenzzinssatz sinkt. Keine Anmeldung, kein Abo. Du kannst die App auch nur als Frühwarn-System nutzen, das ist absolut okay.</p>
      </article>

      <article class="bento__card bento__d" data-reveal>
        <span class="bento__icon">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M9 12l2 2 4-4"/><path d="M21 12c0 5-4 9-9 9s-9-4-9-9 4-9 9-9c2 0 4 1 5 2"/></svg>
        </span>
        <h3>Verfahrens-Begleitung</h3>
        <p>Pro Wohnung führt die App ein eigenes Verfahren: aktueller Anspruch, alle versendeten Briefe, Status pro Reaktion deiner Vermieter*in (akzeptiert, teilweise, abgelehnt). Erinnerungen nach 30 und 60 Tagen, konkrete Vorschläge für den nächsten Schritt. Abgeschlossene Verfahren wandern ins Archiv, ein neues startet jederzeit.</p>
      </article>

      <article class="bento__card bento__e" data-reveal>
        <span class="bento__icon">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M3 3h18v18H3z"/><path d="M10 8h4M10 12h4M10 16h4M8 8v8M16 8v8"/></svg>
        </span>
        <h3>Vom Begehren bis zur Schlichtung</h3>
        <p>Vier Brief-Arten in der App: Senkungsbegehren, Erinnerungsschreiben, Begründung &amp; Belege verlangen, Schlichtungsklage. Jeder Folgebrief wird im Verfahrens-Kontext vorbereitet, mit allen bisherigen Brief-Kopien als Beilage. Beim Schlichtungsbrief lädst du den Mietvertrag direkt aus der App hoch, per Foto, Datei oder integriertem Dokument-Scanner.</p>
      </article>

      <article class="bento__card" data-reveal>
        <span class="bento__icon">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"/><circle cx="9" cy="7" r="4"/><path d="M23 21v-2a4 4 0 0 0-3-3.87"/><path d="M16 3.13a4 4 0 0 1 0 7.75"/></svg>
        </span>
        <h3>Genau für deine Situation</h3>
        <p>Wohnst du allein, mit Partner*in oder in einer WG? Jede Mietpartei unterschreibt einzeln auf dem Gerät, der Brief wird automatisch in der richtigen Form formuliert. Verwaltet eine Firma deine Wohnung, findet die App die Adresse via Schweizer Firmen-Register. Privat-Vermieter*innen tippst du einfach ein.</p>
      </article>

    </div>
  </div>
</section>

<section class="journey" id="journey">
  <div class="journey__inner">
    <div class="journey__visual" data-reveal>
      <div class="phone phone--journey" role="img" aria-label="Dashboard nach erstem Brief-Versand mit Antwort-eingegangen-Chip und Empfehlung für den nächsten Schritt">
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
            <span class="phone__appbar-title">Mietsenkung</span>
            <span class="phone__appbar-action" aria-hidden="true">
              <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="3"/><path d="M19.4 15a1.65 1.65 0 0 0 .33 1.82l.06.06a2 2 0 0 1-2.83 2.83l-.06-.06a1.65 1.65 0 0 0-1.82-.33 1.65 1.65 0 0 0-1 1.51V21a2 2 0 0 1-4 0v-.09a1.65 1.65 0 0 0-1-1.51 1.65 1.65 0 0 0-1.82.33l-.06.06a2 2 0 0 1-2.83-2.83l.06-.06a1.65 1.65 0 0 0 .33-1.82 1.65 1.65 0 0 0-1.51-1H3a2 2 0 0 1 0-4h.09a1.65 1.65 0 0 0 1.51-1 1.65 1.65 0 0 0-.33-1.82l-.06-.06a2 2 0 0 1 2.83-2.83l.06.06a1.65 1.65 0 0 0 1.82.33h0a1.65 1.65 0 0 0 1-1.51V3a2 2 0 0 1 4 0v.09a1.65 1.65 0 0 0 1 1.51h0a1.65 1.65 0 0 0 1.82-.33l.06-.06a2 2 0 0 1 2.83 2.83l-.06.06a1.65 1.65 0 0 0-.33 1.82v0a1.65 1.65 0 0 0 1.51 1H21a2 2 0 0 1 0 4h-.09a1.65 1.65 0 0 0-1.51 1z"/></svg>
            </span>
          </div>
          <div class="phone__body">
            <div class="phone__journey-hero">
              <p class="phone__journey-eyebrow">Aktuelles Verfahren</p>
              <p class="phone__journey-title">Senkungsbegehren versendet</p>
              <p class="phone__journey-sub">Versendet · 5.5.2026 · Tag 12</p>
            </div>
            <div class="phone__letter-card">
              <div class="phone__letter-icon">✉</div>
              <div class="phone__letter-body">
                <p class="phone__letter-title">Senkungsbegehren</p>
                <p class="phone__letter-meta">Versendet am 5.5.2026</p>
                <span class="phone__chip">Antwort eingegangen?</span>
              </div>
            </div>
            <div class="phone__rec-card">
              <p class="phone__rec-label">Empfohlen</p>
              <p class="phone__rec-title">Erinnerungsschreiben in 18 Tagen</p>
              <p class="phone__rec-sub">Wir melden uns automatisch.</p>
            </div>
          </div>
          <div class="phone__tabbar" aria-hidden="true">
            <span class="phone__tab phone__tab--active">
              <span class="phone__tab-icon-wrap">
                <svg viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 2.5l9.5 8.2v10.3a1 1 0 0 1-1 1h-5.5v-7h-6v7H4.5a1 1 0 0 1-1-1V10.7L12 2.5z"/></svg>
              </span>
              <span>Home</span>
            </span>
            <span class="phone__tab">
              <span class="phone__tab-icon-wrap">
                <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M22 19a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h5l2 3h9a2 2 0 0 1 2 2z"/></svg>
              </span>
              <span>Daten</span>
            </span>
            <span class="phone__tab">
              <span class="phone__tab-icon-wrap">
                <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="3" y="5" width="18" height="14" rx="2"/><path d="M3 7l9 6 9-6"/></svg>
              </span>
              <span>Briefe</span>
            </span>
            <span class="phone__tab">
              <span class="phone__tab-icon-wrap">
                <svg viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><circle cx="5" cy="12" r="1.7"/><circle cx="12" cy="12" r="1.7"/><circle cx="19" cy="12" r="1.7"/></svg>
              </span>
              <span>Mehr</span>
            </span>
          </div>
          <div class="phone__home"></div>
        </div>
      </div>
    </div>
    <div class="journey__copy" data-reveal>
      <span class="eyebrow">Verfahrens-Tracking</span>
      <h2>Mietsenkung denkt mit.</h2>
      <p>Nach dem Versand zeigt dir die App den Status deines Verfahrens. Du markierst die Antwort deiner Vermieter*in mit einem Tap, und die App schlägt dir den nächsten Schritt vor: <strong>Erinnerungsschreiben</strong> bei Schweigen, <strong>Begründung &amp; Belege verlangen</strong> bei Ablehnung, <strong>Schlichtungsklage</strong> als letzter Schritt.</p>
      <p>Wenn nichts passiert, meldet sich die App selbst nach 30 und 60 Tagen. Du musst dir keine Termine merken und keine Vorlagen recherchieren. Abgeschlossene Verfahren wandern ins Archiv, ein neues startest du jederzeit.</p>
    </div>
  </div>
</section>

<section class="section pricing" id="price">
  <div class="section__inner">
    <span class="eyebrow" data-reveal>Preis</span>
    <h2 class="section-title" data-reveal>Kein Abo. Du zahlst weniger als 1/3 deiner ersten Monatsersparnis.</h2>
    <p class="section-lead" data-reveal>Anspruch prüfen ist gratis. Bezahlen tust du erst, wenn du den Brief abschickst, und auch dann nur einmal pro Brief.</p>

    <div class="pricing__grid">
      <article class="price-card" data-reveal>
        <p class="price-card__name">Gratis</p>
        <p class="price-card__price">CHF&nbsp;0</p>
        <p class="price-card__price-sub">unbegrenzt nutzbar</p>
        <ul class="price-card__list">
          <li>
            <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><polyline points="20 6 9 17 4 12"/></svg>
            Anspruch in 2 Minuten prüfen
          </li>
          <li>
            <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><polyline points="20 6 9 17 4 12"/></svg>
            Zins-Alarm bei Referenzzinssatz-Senkung
          </li>
          <li>
            <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><polyline points="20 6 9 17 4 12"/></svg>
            Mietverlauf + Ersparnis-Counter
          </li>
          <li>
            <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><polyline points="20 6 9 17 4 12"/></svg>
            Daten lokal verschlüsselt, kein Konto nötig
          </li>
        </ul>
        <div class="price-card__addons">
          <strong>Perfekt zum Reinschnuppern.</strong> Wenn du keinen Anspruch auf eine Mietsenkung hast, musst du auch nichts bezahlen.
        </div>
      </article>

      <article class="price-card price-card--featured" data-reveal>
        <span class="price-card__tag">Beliebt</span>
        <p class="price-card__name">Brief-Versand</p>
        <p class="price-card__price">CHF&nbsp;9.90<span style="font-size: 0.4em; color: var(--ink-soft); font-weight: 500;">&nbsp;bis 29.90</span></p>
        <p class="price-card__price-sub">einmalig pro Brief · Brief-Versand inklusive</p>
        <ul class="price-card__list">
          <li>
            <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><polyline points="20 6 9 17 4 12"/></svg>
            Senkungsbegehren als rechtssicheres&nbsp;PDF
          </li>
          <li>
            <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><polyline points="20 6 9 17 4 12"/></svg>
            Druck + Versand durch Schweizer Post-Partner
          </li>
          <li>
            <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><polyline points="20 6 9 17 4 12"/></svg>
            Eigene Unterschrift, im Wizard erfasst
          </li>
          <li>
            <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><polyline points="20 6 9 17 4 12"/></svg>
            Auto-Reminder + Folgebriefe verfügbar
          </li>
        </ul>
        <div class="price-card__addons">
          <strong>Add-Ons (optional, einzeln):</strong>
          <div class="price-card__addons-grid">
            <div class="price-card__addons-row"><span>Einschreiben optional (mit Tracking)</span><strong>+ CHF 7.90</strong></div>
            <div class="price-card__addons-row"><span>Folgebrief Erinnerung / Unterlagen (via Pingen, beliebig oft buchbar)</span><strong>CHF 6.90</strong></div>
            <div class="price-card__addons-row"><span>Folgebrief Schlichtungsklage als Einschreiben mit Mietvertrag-Foto und Brief-Historie als Beilage (oder Word-Download)</span><strong>CHF 6.90 + 7.90</strong></div>
          </div>
        </div>
      </article>
    </div>

    <p class="pricing-note">Der Brief-Preis richtet sich nach deiner monatlichen Ersparnis, rund ein Drittel davon.</p>
    <p class="pricing-note">Wer wenig spart, zahlt wenig. Wer viel spart, zahlt etwas mehr, aber nie mehr als CHF&nbsp;29.90.</p>
    <p class="pricing-note">CHF&nbsp;9.90 / 14.90 / 19.90 / 24.90 / 27.90 / 29.90, je nachdem, wie viel du sparst.</p>
  </div>
</section>

<section class="section" id="faq">
  <div class="section__inner">
    <span class="eyebrow" data-reveal>Häufige Fragen</span>
    <h2 class="section-title" data-reveal>Was du wissen willst, bevor du loslegst.</h2>

    <div class="faq__list" data-reveal>
      <details>
        <summary>Habe ich überhaupt Anspruch auf eine Mietsenkung?</summary>
        <div class="faq__answer">
          <p>Wenn deine letzte Mietzins-Anpassung auf einem höheren Referenzzinssatz basiert als heute gültig, dann ja, sehr wahrscheinlich. <strong>Mietsenkung</strong> berechnet das automatisch nach Art.&nbsp;270a&nbsp;OR und VMWG&nbsp;Art.&nbsp;13. Du gibst nur deinen aktuellen Mietzins und das Datum der letzten Anpassung ein.</p>
          <p>Der Anspruchs-Check selbst kostet nichts. Wenn dein Anspruch null ist, musst du auch nichts bezahlen, die Berechnung bleibt gratis.</p>
        </div>
      </details>

      <details>
        <summary>Was kostet mich die App wirklich?</summary>
        <div class="faq__answer">
          <p>Die App selbst ist gratis. Der Anspruchs-Check und der Zins-Alarm sind dauerhaft kostenlos. Bezahlt wird nur der Brief-Versand: einmalig CHF&nbsp;9.90 bis 29.90, je nach deiner monatlichen Ersparnis. Im Preis enthalten: Brief-Generierung, Druck und Zustellung durch unseren Schweizer Post-Partner.</p>
          <p>Optional: Einschreiben optional (+ CHF&nbsp;7.90, mit Sendungsverfolgung). Folgebriefe je CHF&nbsp;6.90, <strong>Erinnerungsschreiben</strong> und <strong>Begründung &amp; Belege verlangen</strong> gehen automatisch via Pingen. Die <strong>Schlichtungsklage</strong> geht ebenfalls aus der App, als Einschreiben (+ CHF&nbsp;7.90) mit Mietvertrag-Foto und allen vorherigen Brief-Kopien als Beilagen. Wer lieber selbst zur Post will, kann sie auch als <strong>Word-Datei</strong> herunterladen.</p>
        </div>
      </details>

      <details>
        <summary>Ist Mietsenkung eine offizielle App vom Bund?</summary>
        <div class="faq__answer">
          <p>Nein. <strong>Mietsenkung</strong> ist eine unabhängige App und nicht mit dem Bund, einem Kanton, einer Behörde oder einem Gericht verbunden. Sämtliche genutzten amtlichen Daten und Rechtsgrundlagen stammen aus offiziellen Schweizer Quellen. Siehe Quellen-Block weiter unten.</p>
          <p><strong>Mietsenkung</strong> ersetzt keine Rechtsberatung. Bei rechtlichen Fragen wende dich an einen kantonalen Mieterverband oder ein*e Anwält*in.</p>
        </div>
      </details>

      <details>
        <summary>Kann mich mein*e Vermieter*in kündigen weil ich ein Senkungsbegehren stelle?</summary>
        <div class="faq__answer">
          <p><strong>Nein, du bist gesetzlich geschützt.</strong> Eine Kündigung als Reaktion auf ein Senkungsbegehren ist nach <strong>Art. 271a Abs. 1 lit. a Obligationenrecht (OR)</strong> anfechtbar (sog. Rachekündigung). Die Beweislast liegt beim Vermieter: er muss zeigen können dass die Kündigung NICHT wegen deines Senkungsbegehrens erfolgt. In der Praxis schaffen Vermieter*innen das fast nie. Die Schlichtungsbehörde erklärt eine solche Kündigung dann für ungültig.</p>
          <p><strong>Zusätzlicher Schutz:</strong> Während <strong>drei Jahren</strong> ab Abschluss eines Schlichtungs- oder Gerichtsverfahrens kann dein Vermieter dich nicht ordentlich kündigen (Art. 271a Abs. 1 lit. e OR). Auch eine Kündigung zur Unzeit (während laufendem Verfahren oder kurz danach) ist ungültig (Art. 271a Abs. 1 lit. d OR).</p>
          <p>Senkungsbegehren sind ein gesetzlich vorgesehenes, normales Verfahren und ein alltäglicher Teil des Schweizer Mietverhältnisses. Falls du trotzdem eine Kündigung erhältst: du hast <strong>30 Tage Frist</strong> ab Erhalt um sie bei der Schlichtungsbehörde anzufechten (Art. 273 OR). Wende dich sofort an den <strong>Mieterinnen- und Mieterverband</strong> (mieterverband.ch). Die App-FAQ enthält eine detaillierte Schritt-für-Schritt-Anleitung.</p>
        </div>
      </details>

      <details>
        <summary>Was passiert mit meinen Daten?</summary>
        <div class="faq__answer">
          <p>Deine Mietzins- und Vertragsdaten bleiben verschlüsselt auf deinem Gerät. Wir betreiben keine Cloud-Datenbank und du brauchst kein Konto. Nur das fertige PDF deines Briefes wird verschlüsselt an unseren Schweizer Post-Partner übergeben, damit er gedruckt und zugestellt werden kann.</p>
          <p><strong>Mietsenkung</strong> ist nDSG-konform. Details findest du in der <a href="{{ '/privacy-de.html' | relative_url }}">Datenschutzerklärung</a>.</p>
        </div>
      </details>

      <details>
        <summary>Wie genau ist die Berechnung?</summary>
        <div class="faq__answer">
          <p>Auf den Rappen genau gegenüber dem Mietzinsrechner der Zürcher Gerichte. Wir verwenden direkt die offiziellen Datenquellen (BWO Referenzzinssatz, BFS Landesindex der Konsumentenpreise) und reproduzieren die Formel aus VMWG&nbsp;Art.&nbsp;13 inklusive Teuerung, Kostensteigerung und Tragbarkeits-Check.</p>
          <p>Wenn die Bundesdaten upstream aktualisiert werden, registriert das die App automatisch und rechnet beim nächsten Öffnen mit den neuen Werten.</p>
        </div>
      </details>

      <details>
        <summary>Was, wenn mein*e Vermieter*in nicht antwortet?</summary>
        <div class="faq__answer">
          <p><strong>Mietsenkung</strong> erinnert dich automatisch nach <strong>30 und 60 Tagen</strong>. Bei jeder Erinnerung kannst du mit einem Tap den passenden Folgebrief auslösen, je nach Status: <strong>Erinnerungsschreiben</strong>, <strong>Begründung &amp; Belege verlangen</strong> oder <strong>Schlichtungsklage</strong>. Jeder Folgebrief kostet CHF&nbsp;6.90. Erinnerungsschreiben und Begründung &amp; Belege gehen via Pingen mit Brief-Versand inklusive. Die Schlichtungsklage geht direkt aus der App als Einschreiben (+ CHF&nbsp;7.90), mit deinem hochgeladenen Mietvertrag-Foto und allen vorherigen Brief-Kopien als Beilagen, alternativ kannst du sie als <strong>Word-Datei</strong> herunterladen und selber einreichen.</p>
          <p>Wenn du in die Schlichtung gehst, hilft dir die App mit der Verzeichnis-Suche der zuständigen kantonalen Schlichtungsbehörde (Quelle: BWO).</p>
        </div>
      </details>

      <details>
        <summary>Auf welchen Geräten läuft Mietsenkung?</summary>
        <div class="faq__answer">
          <p>iPhone (iOS&nbsp;15+) und Android (9+). Funktioniert auf Smartphone und Tablet, auf dem grösseren Tablet-Display hast du einfach mehr Platz für die Eingabe.</p>
        </div>
      </details>
    </div>
  </div>
</section>

<section class="section sources" id="sources">
  <div class="section__inner">
    <span class="eyebrow" data-reveal>Quellen und Haftungsausschluss</span>
    <h2 class="section-title" data-reveal>Alles aus offiziellen Schweizer Quellen.</h2>
    <p class="section-lead" data-reveal><strong>Mietsenkung</strong> verlinkt direkt auf die zugrundeliegenden Bundes-Daten und Rechtsgrundlagen. Du kannst jeden Wert in der App selbst überprüfen.</p>

    <div class="sources__grid">
      <a class="source-row" href="https://www.bwo.admin.ch/de/entwicklung-referenzzinssatz-und-durchschnittszinssatz" rel="noopener">
        <span class="source-row__abbr">BWO</span>
        <span class="source-row__body">
          <span class="source-row__title">Hypothekarischer Referenzzinssatz</span>
          <span class="source-row__sub">Bundesamt für Wohnungswesen, primäre Datenquelle</span>
        </span>
      </a>
      <a class="source-row" href="https://www.bfs.admin.ch/bfs/de/home/statistiken/preise/landesindex-konsumentenpreise.html" rel="noopener">
        <span class="source-row__abbr">BFS</span>
        <span class="source-row__body">
          <span class="source-row__title">Landesindex der Konsumentenpreise</span>
          <span class="source-row__sub">Bundesamt für Statistik, für die Teuerungs-Komponente</span>
        </span>
      </a>
      <a class="source-row" href="https://www.fedlex.admin.ch/eli/cc/27/317_321_377/de" rel="noopener">
        <span class="source-row__abbr">OR</span>
        <span class="source-row__body">
          <span class="source-row__title">Mietrecht: OR Art. 269 ff., insb. 270a</span>
          <span class="source-row__sub">Schweizerisches Obligationenrecht (Fedlex)</span>
        </span>
      </a>
      <a class="source-row" href="https://www.fedlex.admin.ch/eli/cc/1990/835_835_835/de" rel="noopener">
        <span class="source-row__abbr">VMWG</span>
        <span class="source-row__body">
          <span class="source-row__title">Verordnung über Wohn- und Geschäftsräume</span>
          <span class="source-row__sub">VMWG Art. 13, Berechnungsformel</span>
        </span>
      </a>
      <a class="source-row" href="https://www.bwo.admin.ch/de/schlichtungsverfahren" rel="noopener">
        <span class="source-row__abbr">SB</span>
        <span class="source-row__body">
          <span class="source-row__title">Schlichtungsbehörden-Verzeichnis</span>
          <span class="source-row__sub">BWO, kantonale Adressen</span>
        </span>
      </a>
      <a class="source-row" href="https://www.gerichte-zh.ch/de/themen/miete" rel="noopener">
        <span class="source-row__abbr">ZH</span>
        <span class="source-row__body">
          <span class="source-row__title">Mietzinsrechner der Zürcher Gerichte</span>
          <span class="source-row__sub">Verifikations-Referenz für die Berechnung</span>
        </span>
      </a>
    </div>

    <div class="sources-disclaimer">
      <p style="margin: 0 0 8px;"><strong>Mietsenkung ist eine unabhängige App.</strong> Sie ist nicht mit dem Bund, einem Kanton, einer Behörde oder einem Gericht verbunden, wird von diesen nicht betrieben und vertritt keine staatliche Stelle.</p>
      <p style="margin: 0;">Die App ist <strong>keine Rechtsberatung</strong> und ersetzt keine anwaltliche Vertretung. Bei rechtlichen Fragen wende dich an einen kantonalen Mieterverband oder ein*e Anwält*in.</p>
    </div>
  </div>
</section>

<section class="cta" id="download">
  <div class="cta__inner" data-reveal>
    <h2>Bereit, deinen Anspruch durchzusetzen?</h2>
    <p>Anspruch prüfen ist gratis. Der Brief geht ab CHF&nbsp;9.90 inklusive Druck und Versand. Bei Schweigen oder Ablehnung deiner Vermieter*in begleitet dich <strong>Mietsenkung</strong> bis zur Schlichtungsbehörde.</p>
    <div class="hero__cta">
      <a class="store-button" href="#" data-coming-soon aria-label="Mietsenkung im App Store laden">
        <svg class="store-button__icon" viewBox="0 0 384 512" fill="currentColor" aria-hidden="true"><path d="M318.7 268.7c-.2-36.7 16.4-64.4 50-84.8-18.8-26.9-47.2-41.7-84.7-44.6-35.5-2.8-74.3 20.7-88.5 20.7-15 0-49.4-19.7-76.4-19.7C63.3 141.2 4 184.8 4 273.5q0 39.3 14.4 81.2c12.8 36.7 59 126.7 107.2 125.2 25.2-.6 43-17.9 75.8-17.9 31.8 0 48.3 17.9 76.4 17.9 48.6-.7 90.4-82.5 102.6-119.3-65.2-30.7-61.7-90-61.7-91.9zm-56.6-164.2c27.3-32.4 24.8-61.9 24-72.5-24.1 1.4-52 16.4-67.9 34.9-17.5 19.8-27.8 44.3-25.6 71.9 26.1 2 49.9-11.4 69.5-34.3z"/></svg>
        <span class="store-button__text">
          <span class="store-button__small">Laden im</span>
          <span class="store-button__big">App&nbsp;Store</span>
        </span>
      </a>
      <a class="store-button" href="#" data-coming-soon aria-label="Mietsenkung bei Google Play laden">
        <svg class="store-button__icon" viewBox="0 0 512 512" aria-hidden="true">
          <path fill="#34d399" d="M325.3 234.3 104.6 13l280.8 161.2-60.1 60.1z"/>
          <path fill="#fbbf24" d="M104.6 499 325.3 277.7l60.1 60.1L104.6 499z"/>
          <path fill="#60a5fa" d="m480.6 256.5-95.2 60.1-66.3-60.1 66.3-60.1 95.2 60.1z"/>
          <path fill="#f87171" d="m104.6 499 1.3-489.7 219.4 222 0 .3 0 .3z"/>
        </svg>
        <span class="store-button__text">
          <span class="store-button__small">Jetzt bei</span>
          <span class="store-button__big">Google&nbsp;Play</span>
        </span>
      </a>
    </div>
    <p class="hero__pricing"><span class="hero__pricing-bit"><strong>Anspruch prüfen + Zins-Alarm gratis</strong></span><span class="dot" aria-hidden="true">·</span><span class="hero__pricing-bit">Brief ab <strong>CHF&nbsp;9.90</strong></span><span class="dot" aria-hidden="true">·</span><span class="hero__pricing-bit">Kein Abo</span></p>
  </div>
</section>
