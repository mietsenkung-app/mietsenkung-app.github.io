---
layout: default
title: "RentReducer. Get back what you're owed."
description: Swiss app for tenants. In 2 minutes it checks whether you have a right to a lower rent on your apartment and mails the reduction request to your landlord with one tap. From CHF 9.90.
lang: en
lang_short: en
permalink: /en/
---

<section class="hero">
  <div class="hero__bg-trend" aria-hidden="true">
    <!-- Real BWO Swiss reference-rate history 2008–2025 (source: bwo.admin.ch).
         3.50% (Sep 2008) down to 1.25% (today), with a 2023 bump up to 1.75%
         and 2025 drop back to 1.25%. -->
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
      <a class="hero__brandmark" href="#download" aria-label="Get the RentReducer app">
        <img src="{{ '/assets/app_icon.svg' | relative_url }}" alt="" class="hero__brandmark__icon" width="56" height="56">
        <span class="hero__brandmark__word">RentReducer</span>
      </a>
      <span class="eyebrow">Lower rent in 2 minutes</span>
      <h1 class="hero__title">Get back<br>what you're <em>owed</em>.</h1>
      <p class="hero__sub">You may have been overpaying rent on your apartment for years. <strong>RentReducer</strong> calculates your claim under Swiss federal law and mails the letter for you. If your landlord stays silent or refuses, the app guides you all the way to the conciliation authority.</p>

      <div class="hero__cta">
        <a class="store-button" href="#" data-coming-soon aria-label="Download RentReducer on the App Store">
          <svg class="store-button__icon" viewBox="0 0 384 512" fill="currentColor" aria-hidden="true"><path d="M318.7 268.7c-.2-36.7 16.4-64.4 50-84.8-18.8-26.9-47.2-41.7-84.7-44.6-35.5-2.8-74.3 20.7-88.5 20.7-15 0-49.4-19.7-76.4-19.7C63.3 141.2 4 184.8 4 273.5q0 39.3 14.4 81.2c12.8 36.7 59 126.7 107.2 125.2 25.2-.6 43-17.9 75.8-17.9 31.8 0 48.3 17.9 76.4 17.9 48.6-.7 90.4-82.5 102.6-119.3-65.2-30.7-61.7-90-61.7-91.9zm-56.6-164.2c27.3-32.4 24.8-61.9 24-72.5-24.1 1.4-52 16.4-67.9 34.9-17.5 19.8-27.8 44.3-25.6 71.9 26.1 2 49.9-11.4 69.5-34.3z"/></svg>
          <span class="store-button__text">
            <span class="store-button__small">Download on the</span>
            <span class="store-button__big">App&nbsp;Store</span>
          </span>
        </a>
        <a class="store-button" href="#" data-coming-soon aria-label="Get RentReducer on Google Play">
          <svg class="store-button__icon" viewBox="0 0 512 512" aria-hidden="true">
            <path fill="#34d399" d="M325.3 234.3 104.6 13l280.8 161.2-60.1 60.1z"/>
            <path fill="#fbbf24" d="M104.6 499 325.3 277.7l60.1 60.1L104.6 499z"/>
            <path fill="#60a5fa" d="m480.6 256.5-95.2 60.1-66.3-60.1 66.3-60.1 95.2 60.1z"/>
            <path fill="#f87171" d="m104.6 499 1.3-489.7 219.4 222 0 .3 0 .3z"/>
          </svg>
          <span class="store-button__text">
            <span class="store-button__small">Get it on</span>
            <span class="store-button__big">Google&nbsp;Play</span>
          </span>
        </a>
      </div>

      <p class="hero__pricing"><span class="hero__pricing-bit"><strong>Claim check + rate alert free</strong></span><span class="dot" aria-hidden="true">·</span><span class="hero__pricing-bit">Letter from <strong>CHF&nbsp;9.90</strong></span><span class="dot" aria-hidden="true">·</span><span class="hero__pricing-bit">A-Mail included</span><span class="dot" aria-hidden="true">·</span><span class="hero__pricing-bit">No subscription</span></p>

      <div class="qr-install" aria-label="QR codes to install the app">
        <p class="qr-install__hint">On a laptop? Scan with your phone:</p>
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
          GDPR-aware
        </span>
        <span class="trust-pill">
          <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="3" y="11" width="18" height="11" rx="2"/><path d="M7 11V7a5 5 0 0 1 10 0v4"/></svg>
          Data stays on your device
        </span>
        <span class="trust-pill">
          <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M3 12h18M12 3v18"/></svg>
          Swiss made
        </span>
      </div>
    </div>

    <div class="hero__visual" data-reveal>
      <div class="phone" role="img" aria-label="Sample app screen of RentReducer: current claim CHF 73 per month, one tap to create the letter.">
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
            <span class="phone__appbar-title">RentReducer</span>
            <span class="phone__appbar-action" aria-hidden="true">
              <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="3"/><path d="M19.4 15a1.65 1.65 0 0 0 .33 1.82l.06.06a2 2 0 0 1-2.83 2.83l-.06-.06a1.65 1.65 0 0 0-1.82-.33 1.65 1.65 0 0 0-1 1.51V21a2 2 0 0 1-4 0v-.09a1.65 1.65 0 0 0-1-1.51 1.65 1.65 0 0 0-1.82.33l-.06.06a2 2 0 0 1-2.83-2.83l.06-.06a1.65 1.65 0 0 0 .33-1.82 1.65 1.65 0 0 0-1.51-1H3a2 2 0 0 1 0-4h.09a1.65 1.65 0 0 0 1.51-1 1.65 1.65 0 0 0-.33-1.82l-.06-.06a2 2 0 0 1 2.83-2.83l.06.06a1.65 1.65 0 0 0 1.82.33h0a1.65 1.65 0 0 0 1-1.51V3a2 2 0 0 1 4 0v.09a1.65 1.65 0 0 0 1 1.51h0a1.65 1.65 0 0 0 1.82-.33l.06-.06a2 2 0 0 1 2.83 2.83l-.06.06a1.65 1.65 0 0 0-.33 1.82v0a1.65 1.65 0 0 0 1.51 1H21a2 2 0 0 1 0 4h-.09a1.65 1.65 0 0 0-1.51 1z"/></svg>
            </span>
          </div>
          <div class="phone__body">
            <div class="phone__card">
              <p class="phone__claim-label">Your claim</p>
              <div class="phone__claim-row">
                <span class="phone__claim-value">CHF&nbsp;73</span>
                <span class="phone__claim-unit">per month</span>
              </div>
              <p class="phone__claim-sub">CHF&nbsp;876 per year · from June&nbsp;1</p>
              <a class="phone__cta" href="#download">Create letter →</a>
              <p class="phone__recalc">Recalculate</p>
            </div>
            <div class="phone__card">
              <p class="phone__history-title">
                <svg width="11" height="11" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M3 3v18h18"/><polyline points="7 14 11 10 15 14 21 8"/></svg>
                Rent history
              </p>
              <div class="phone__history-row">
                <span>Current</span>
                <strong>CHF 1'920</strong>
              </div>
              <div class="phone__history-row">
                <span>New (from Jun 1)</span>
                <strong class="is-new">CHF 1'847</strong>
              </div>
              <div class="phone__history-row">
                <span>Reference rate</span>
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
              <span>Data</span>
            </span>
            <span class="phone__tab">
              <span class="phone__tab-icon-wrap">
                <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="3" y="5" width="18" height="14" rx="2"/><path d="M3 7l9 6 9-6"/></svg>
              </span>
              <span>Letters</span>
            </span>
            <span class="phone__tab">
              <span class="phone__tab-icon-wrap">
                <svg viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><circle cx="5" cy="12" r="1.7"/><circle cx="12" cy="12" r="1.7"/><circle cx="19" cy="12" r="1.7"/></svg>
              </span>
              <span>More</span>
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
    <span class="trust-strip__label">Data and law from official Swiss&nbsp;sources</span>
    <div class="trust-strip__sources">
      <span>Federal Office for Housing</span>
      <span>Federal Statistical Office</span>
      <span>Tenancy law (CO + VMWG)</span>
      <span>Zurich rent calculator</span>
    </div>
  </div>
</section>

<section class="section steps" id="how">
  <div class="section__inner">
    <span class="eyebrow" data-reveal>How it works</span>
    <h2 class="section-title" data-reveal>Three steps from claim to ready-to-mail letter.</h2>
    <p class="section-lead" data-reveal>Enter your current rent and the date of the last adjustment. The app calculates the claim, generates the reduction request with your signature and hands it to Swiss Post. If your landlord stays silent or refuses, the app handles the next step too.</p>

    <div class="steps__grid">
      <article class="step" data-reveal>
        <span class="step__num">01</span>
        <span class="step__icon">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="3" y="3" width="18" height="18" rx="3"/><path d="M9 9h6M9 13h6M9 17h4"/></svg>
        </span>
        <h3>Check your claim</h3>
        <p>Enter your rent and the date of the last adjustment. The app calculates under federal law (Art.&nbsp;270a&nbsp;CO + VMWG&nbsp;art.&nbsp;13) including inflation and cost increases. 1:1 with the rent calculator of the Zurich&nbsp;courts.</p>
        <span class="step__time">≈ 2&nbsp;min · free</span>
      </article>

      <article class="step" data-reveal>
        <span class="step__num">02</span>
        <span class="step__icon">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="2" y="5" width="20" height="14" rx="2"/><path d="M2 7l10 7 10-7"/></svg>
        </span>
        <h3>One tap to send</h3>
        <p>The app generates your reduction request with your finger-signature, hands it off encrypted to our Swiss postal partner, and mails it as A-Mail or registered. You get a push confirmation.</p>
        <span class="step__time">≈ 3&nbsp;sec · from CHF&nbsp;9.90</span>
      </article>

      <article class="step" data-reveal>
        <span class="step__num">03</span>
        <span class="step__icon">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M18 8a6 6 0 0 0-12 0c0 7-3 9-3 9h18s-3-2-3-9"/><path d="M13.73 21a2 2 0 0 1-3.46 0"/></svg>
        </span>
        <h3>Auto-reminders and follow-ups</h3>
        <p>If your landlord doesn't reply, the app reminds you after 30 and 60 days. Depending on their answer it suggests the right follow-up letter: a reminder letter for silence, a request for explanation and evidence for refusal, or a conciliation petition as the last step.</p>
        <span class="step__time">automatic</span>
      </article>
    </div>
  </div>
</section>

<section class="stats">
  <div class="stats__inner">
    <span class="eyebrow" data-reveal>Why we built this</span>
    <h2 class="stats__title" data-reveal>Swiss tenants miss out on millions every year.</h2>
    <p class="stats__lead" data-reveal>Only a fraction of those entitled actually claim. The effort puts people off: calculating the claim, drafting the letter, scheduling reminders, chasing silence or refusal with the next step. <strong>RentReducer</strong> takes those steps over completely, from the initial claim to the conciliation authority.</p>

    <div class="stats__grid">
      <div class="stat" data-reveal>
        <p class="stat__num"><span class="stat__num--accent">9&nbsp;in&nbsp;10</span></p>
        <p class="stat__label">tenants don't claim</p>
        <p class="stat__desc">Only 12 % actively ask for a reduction, even though about half are entitled. Source: ZKB study&nbsp;2026.</p>
      </div>
      <div class="stat" data-reveal>
        <p class="stat__num">CHF&nbsp;73</p>
        <p class="stat__label">average monthly saving</p>
        <p class="stat__desc">For a typical 2.5-room flat at CHF&nbsp;1'920. The letter pays for itself in the first week.</p>
      </div>
      <div class="stat" data-reveal>
        <p class="stat__num">2&nbsp;min</p>
        <p class="stat__label">from open to ready-to-send</p>
        <p class="stat__desc">You enter your rent and the adjustment date, the app handles everything else through to the push confirmation that the letter is in the mail.</p>
      </div>
    </div>
  </div>
</section>

<section class="section">
  <div class="section__inner">
    <span class="eyebrow" data-reveal>What sets RentReducer apart</span>
    <h2 class="section-title" data-reveal>Private. Precise. With one tap.</h2>
    <p class="section-lead" data-reveal><strong>RentReducer</strong>... wait wrongdifferent from a Word template.</p>

    <div class="bento">
      <article class="bento__card bento__a bento__card--accent" data-reveal>
        <span class="bento__icon">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M13 2L3 14h9l-1 8 10-12h-9l1-8z"/></svg>
        </span>
        <h3>Court-grade calculation</h3>
        <p><strong>RentReducer</strong> uses federal source data (BWO reference rate, BFS national CPI) and reproduces the official Zurich-courts rent calculator down to the cent. Including inflation, cost increases and an affordability check.</p>
      </article>

      <article class="bento__card bento__b" data-reveal>
        <span class="bento__icon">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="3" y="11" width="18" height="11" rx="2"/><path d="M7 11V7a5 5 0 0 1 10 0v4"/></svg>
        </span>
        <h3>Privacy-first</h3>
        <p>Your data stays encrypted on your device. No account, no cloud DB. Only the finished PDF is handed encrypted to our Swiss postal partner.</p>
      </article>

      <article class="bento__card bento__c" data-reveal>
        <span class="bento__icon">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><circle cx="12" cy="12" r="10"/><path d="M12 6v6l4 2"/></svg>
        </span>
        <h3>Free rate alert</h3>
        <p>Push notification when the Swiss reference rate drops. No sign-up, no subscription. You can use the app purely as an early-warning system, that's perfectly fine too.</p>
      </article>

      <article class="bento__card bento__d" data-reveal>
        <span class="bento__icon">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M9 12l2 2 4-4"/><path d="M21 12c0 5-4 9-9 9s-9-4-9-9 4-9 9-9c2 0 4 1 5 2"/></svg>
        </span>
        <h3>Case-by-case guidance</h3>
        <p>Each apartment gets its own case: current claim, every letter sent, status per landlord response (accepted, partial, refused). Reminders at 30 and 60 days, concrete suggestions for the next step. Closed cases move to the archive, a new one starts any time.</p>
      </article>

      <article class="bento__card bento__e" data-reveal>
        <span class="bento__icon">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M3 3h18v18H3z"/><path d="M10 8h4M10 12h4M10 16h4M8 8v8M16 8v8"/></svg>
        </span>
        <h3>From request to conciliation</h3>
        <p>Four letter types in the app: reduction request, reminder letter, request for explanation and evidence, conciliation petition. Each follow-up is prepared in the case context, with all prior letter copies attached. For the conciliation letter you upload the lease directly from the app, by photo, file or built-in document scanner.</p>
      </article>

      <article class="bento__card" data-reveal>
        <span class="bento__icon">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"/><circle cx="9" cy="7" r="4"/><path d="M23 21v-2a4 4 0 0 0-3-3.87"/><path d="M16 3.13a4 4 0 0 1 0 7.75"/></svg>
        </span>
        <h3>Built for your situation</h3>
        <p>Living alone, with a partner, or in a shared flat? Each tenant signs on the device, the letter is worded in the right form automatically. If a company manages your flat, the app pulls the address from the Swiss commercial register. For private landlords you just type the name.</p>
      </article>

    </div>
  </div>
</section>

<section class="journey" id="journey">
  <div class="journey__inner">
    <div class="journey__visual" data-reveal>
      <div class="phone phone--journey" role="img" aria-label="Dashboard after first letter dispatch with got-a-reply chip and recommendation for next step">
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
            <span class="phone__appbar-title">RentReducer</span>
            <span class="phone__appbar-action" aria-hidden="true">
              <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="3"/><path d="M19.4 15a1.65 1.65 0 0 0 .33 1.82l.06.06a2 2 0 0 1-2.83 2.83l-.06-.06a1.65 1.65 0 0 0-1.82-.33 1.65 1.65 0 0 0-1 1.51V21a2 2 0 0 1-4 0v-.09a1.65 1.65 0 0 0-1-1.51 1.65 1.65 0 0 0-1.82.33l-.06.06a2 2 0 0 1-2.83-2.83l.06-.06a1.65 1.65 0 0 0 .33-1.82 1.65 1.65 0 0 0-1.51-1H3a2 2 0 0 1 0-4h.09a1.65 1.65 0 0 0 1.51-1 1.65 1.65 0 0 0-.33-1.82l-.06-.06a2 2 0 0 1 2.83-2.83l.06.06a1.65 1.65 0 0 0 1.82.33h0a1.65 1.65 0 0 0 1-1.51V3a2 2 0 0 1 4 0v.09a1.65 1.65 0 0 0 1 1.51h0a1.65 1.65 0 0 0 1.82-.33l.06-.06a2 2 0 0 1 2.83 2.83l-.06.06a1.65 1.65 0 0 0-.33 1.82v0a1.65 1.65 0 0 0 1.51 1H21a2 2 0 0 1 0 4h-.09a1.65 1.65 0 0 0-1.51 1z"/></svg>
            </span>
          </div>
          <div class="phone__body">
            <div class="phone__journey-hero">
              <p class="phone__journey-eyebrow">Active case</p>
              <p class="phone__journey-title">Reduction request mailed</p>
              <p class="phone__journey-sub">A-Mail · May 5, 2026 · Day 12</p>
            </div>
            <div class="phone__letter-card">
              <div class="phone__letter-icon">✉</div>
              <div class="phone__letter-body">
                <p class="phone__letter-title">Reduction request</p>
                <p class="phone__letter-meta">Sent on May 5, 2026</p>
                <span class="phone__chip">Got a reply?</span>
              </div>
            </div>
            <div class="phone__rec-card">
              <p class="phone__rec-label">Suggested</p>
              <p class="phone__rec-title">Reminder letter in 18 days</p>
              <p class="phone__rec-sub">We'll ping you automatically.</p>
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
              <span>Data</span>
            </span>
            <span class="phone__tab">
              <span class="phone__tab-icon-wrap">
                <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="3" y="5" width="18" height="14" rx="2"/><path d="M3 7l9 6 9-6"/></svg>
              </span>
              <span>Letters</span>
            </span>
            <span class="phone__tab">
              <span class="phone__tab-icon-wrap">
                <svg viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><circle cx="5" cy="12" r="1.7"/><circle cx="12" cy="12" r="1.7"/><circle cx="19" cy="12" r="1.7"/></svg>
              </span>
              <span>More</span>
            </span>
          </div>
          <div class="phone__home"></div>
        </div>
      </div>
    </div>
    <div class="journey__copy" data-reveal>
      <span class="eyebrow">Case tracking</span>
      <h2>RentReducer thinks ahead.</h2>
      <p>After the letter goes out, the app shows you the case status. Mark your landlord's response with one tap, and the app suggests the next step: <strong>reminder letter</strong> for silence, <strong>request for explanation and evidence</strong> on refusal, <strong>conciliation petition</strong> as last resort.</p>
      <p>If nothing happens, the app pings you on day 30 and 60. No calendar reminders to set, no templates to research. Closed cases move to the archive, a new one starts whenever you want.</p>
    </div>
  </div>
</section>

<section class="section pricing" id="price">
  <div class="section__inner">
    <span class="eyebrow" data-reveal>Price</span>
    <h2 class="section-title" data-reveal>No subscription. Less than 1/3 of your first month's saving.</h2>
    <p class="section-lead" data-reveal>The claim check is free. You pay only when you mail the letter, and even then only once per letter.</p>

    <div class="pricing__grid">
      <article class="price-card" data-reveal>
        <p class="price-card__name">Free</p>
        <p class="price-card__price">CHF&nbsp;0</p>
        <p class="price-card__price-sub">unlimited use</p>
        <ul class="price-card__list">
          <li><svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><polyline points="20 6 9 17 4 12"/></svg>Check your claim in 2 minutes</li>
          <li><svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><polyline points="20 6 9 17 4 12"/></svg>Rate alert when the reference rate drops</li>
          <li><svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><polyline points="20 6 9 17 4 12"/></svg>Rent history + savings counter</li>
          <li><svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><polyline points="20 6 9 17 4 12"/></svg>Data locally encrypted, no account needed</li>
        </ul>
        <div class="price-card__addons">
          <strong>Perfect to dip in.</strong> If you have no claim to a rent reduction, you don't pay anything.
        </div>
      </article>

      <article class="price-card price-card--featured" data-reveal>
        <span class="price-card__tag">Popular</span>
        <p class="price-card__name">Letter mailing</p>
        <p class="price-card__price">CHF&nbsp;9.90<span style="font-size: 0.4em; color: var(--ink-soft); font-weight: 500;">&nbsp;to 29.90</span></p>
        <p class="price-card__price-sub">once per letter · A-Mail included</p>
        <ul class="price-card__list">
          <li><svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><polyline points="20 6 9 17 4 12"/></svg>Reduction request as a legally compliant&nbsp;PDF</li>
          <li><svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><polyline points="20 6 9 17 4 12"/></svg>Print + delivery by Swiss postal partner</li>
          <li><svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><polyline points="20 6 9 17 4 12"/></svg>Your own finger-signature, captured in the wizard</li>
          <li><svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><polyline points="20 6 9 17 4 12"/></svg>Auto-reminders + follow-up letters available</li>
        </ul>
        <div class="price-card__addons">
          <strong>Add-ons (optional, à la carte):</strong>
          <div class="price-card__addons-grid">
            <div class="price-card__addons-row"><span>Registered with tracking</span><strong>+ CHF 7.90</strong></div>
            <div class="price-card__addons-row"><span>Follow-up reminder / document request (via Pingen)</span><strong>CHF 6.90</strong></div>
            <div class="price-card__addons-row"><span>Follow-up conciliation petition as registered mail with lease photo and prior letters attached (or Word download)</span><strong>CHF 6.90 + 7.90</strong></div>
          </div>
        </div>
      </article>
    </div>

    <p class="pricing-note">The letter price scales with your monthly saving, about a third.</p>
    <p class="pricing-note">Save little, pay little. Save more, pay a touch more, but never above CHF&nbsp;29.90.</p>
    <p class="pricing-note">CHF&nbsp;9.90 / 14.90 / 19.90 / 24.90 / 27.90 / 29.90, depending on how much you save.</p>
  </div>
</section>

<section class="section" id="faq">
  <div class="section__inner">
    <span class="eyebrow" data-reveal>Frequently asked</span>
    <h2 class="section-title" data-reveal>What you'd want to know before you start.</h2>

    <div class="faq__list" data-reveal>
      <details>
        <summary>Do I even have a claim?</summary>
        <div class="faq__answer">
          <p>If your last rent adjustment was based on a higher reference rate than today's, then yes, most likely. <strong>RentReducer</strong> calculates this automatically under Art.&nbsp;270a&nbsp;CO and VMWG art.&nbsp;13. You just enter your current rent and the date of the last adjustment.</p>
          <p>The claim check itself is free. If your claim is zero, you don't pay anything, the calculation stays free.</p>
        </div>
      </details>

      <details>
        <summary>What does the app actually cost?</summary>
        <div class="faq__answer">
          <p>The app is free. Claim check and rate alert stay free. You only pay for mailing the letter: a one-time CHF&nbsp;9.90 to 29.90 depending on your monthly saving. Included: letter generation, A-Mail print and delivery by our Swiss postal partner.</p>
          <p>Optional: Registered with tracking (+ CHF&nbsp;7.90). Follow-up letters at CHF&nbsp;6.90 each, the <strong>reminder letter</strong> and <strong>request for explanation and evidence</strong> go out automatically via Pingen. The <strong>conciliation petition</strong> also goes from the app, as registered mail (+ CHF&nbsp;7.90) with your uploaded lease photo and all prior letter copies attached. Prefer to mail it yourself? You can also download it as a <strong>Word file</strong>.</p>
        </div>
      </details>

      <details>
        <summary>Is RentReducer an official government app?</summary>
        <div class="faq__answer">
          <p>No. <strong>RentReducer</strong> is an independent app and is not affiliated with, operated by, or endorsed by the Swiss Confederation, any canton, public authority or court. All official data and legal references come from official Swiss sources. See the Sources block below.</p>
          <p><strong>RentReducer</strong> does not replace legal advice. For legal questions, contact a cantonal tenants' association or a lawyer.</p>
        </div>
      </details>

      <details>
        <summary>What happens with my data?</summary>
        <div class="faq__answer">
          <p>Your rent and contract data stays encrypted on your device. We operate no cloud database and you don't need an account. Only the finished PDF of your letter is handed encrypted to our Swiss postal partner so it can be printed and delivered.</p>
          <p>Details are in the <a href="{{ '/privacy-en.html' | relative_url }}">Privacy Policy</a>.</p>
        </div>
      </details>

      <details>
        <summary>How accurate is the calculation?</summary>
        <div class="faq__answer">
          <p>Cent-accurate against the rent calculator of the Zurich courts. We use the official data sources (BWO reference rate, BFS CPI) and reproduce the formula from VMWG art.&nbsp;13 including inflation, cost increases and an affordability check.</p>
          <p>When the federal data is updated upstream, the app picks it up automatically and recalculates with the new values on next open.</p>
        </div>
      </details>

      <details>
        <summary>What if my landlord doesn't reply?</summary>
        <div class="faq__answer">
          <p><strong>RentReducer</strong> reminds you automatically after <strong>30 and 60 days</strong>. At every reminder you can fire the right follow-up letter with one tap, by status: <strong>reminder letter</strong>, <strong>request for explanation and evidence</strong>, or <strong>conciliation petition</strong>. Each follow-up letter costs CHF&nbsp;6.90. The reminder letter and request for explanation go via Pingen with A-Mail included. The conciliation petition also goes straight from the app as registered mail (+ CHF&nbsp;7.90) with your uploaded lease photo and prior letter copies attached, or you can download it as a <strong>Word file</strong> and mail it yourself.</p>
          <p>If you go to conciliation, the app helps you with the directory of the cantonal conciliation authority (source: BWO).</p>
        </div>
      </details>

      <details>
        <summary>What devices does RentReducer run on?</summary>
        <div class="faq__answer">
          <p>iPhone (iOS&nbsp;15+) and Android (9+). Works on phones and tablets, the larger tablet screen just gives you more room to type.</p>
        </div>
      </details>
    </div>
  </div>
</section>

<section class="section sources" id="sources">
  <div class="section__inner">
    <span class="eyebrow" data-reveal>Sources and disclaimer</span>
    <h2 class="section-title" data-reveal>All from official Swiss sources.</h2>
    <p class="section-lead" data-reveal><strong>RentReducer</strong> links directly to the underlying federal data and legal references. You can verify every value in the app yourself.</p>

    <div class="sources__grid">
      <a class="source-row" href="https://www.bwo.admin.ch/de/entwicklung-referenzzinssatz-und-durchschnittszinssatz" rel="noopener">
        <span class="source-row__abbr">BWO</span>
        <span class="source-row__body">
          <span class="source-row__title">Mortgage reference interest rate</span>
          <span class="source-row__sub">Federal Office for Housing, primary data source (German)</span>
        </span>
      </a>
      <a class="source-row" href="https://www.bfs.admin.ch/bfs/en/home/statistiken/preise/landesindex-konsumentenpreise.html" rel="noopener">
        <span class="source-row__abbr">BFS</span>
        <span class="source-row__body">
          <span class="source-row__title">National Consumer Price Index</span>
          <span class="source-row__sub">Federal Statistical Office, for the inflation component</span>
        </span>
      </a>
      <a class="source-row" href="https://www.fedlex.admin.ch/eli/cc/27/317_321_377/en" rel="noopener">
        <span class="source-row__abbr">CO</span>
        <span class="source-row__body">
          <span class="source-row__title">Tenancy law: CO art. 269 ff., esp. 270a</span>
          <span class="source-row__sub">Swiss Code of Obligations (Fedlex)</span>
        </span>
      </a>
      <a class="source-row" href="https://www.fedlex.admin.ch/eli/cc/1990/835_835_835/de" rel="noopener">
        <span class="source-row__abbr">VMWG</span>
        <span class="source-row__body">
          <span class="source-row__title">Ordinance on residential and commercial premises</span>
          <span class="source-row__sub">VMWG art. 13, calculation formula</span>
        </span>
      </a>
      <a class="source-row" href="https://www.bwo.admin.ch/de/schlichtungsverfahren" rel="noopener">
        <span class="source-row__abbr">SB</span>
        <span class="source-row__body">
          <span class="source-row__title">Conciliation authorities directory</span>
          <span class="source-row__sub">BWO, cantonal addresses (German)</span>
        </span>
      </a>
      <a class="source-row" href="https://www.gerichte-zh.ch/de/themen/miete" rel="noopener">
        <span class="source-row__abbr">ZH</span>
        <span class="source-row__body">
          <span class="source-row__title">Tenancy law information from the Zurich courts</span>
          <span class="source-row__sub">Verification reference (in German)</span>
        </span>
      </a>
    </div>

    <div class="sources-disclaimer">
      <p style="margin: 0 0 8px;"><strong>RentReducer is an independent app.</strong> It is not affiliated with, operated by, or endorsed by the Swiss Confederation, any canton, public authority or court, and it does not represent any government entity.</p>
      <p style="margin: 0;">The app is <strong>not legal advice</strong> and does not replace an attorney. For legal questions, contact a cantonal tenants' association or a lawyer.</p>
    </div>
  </div>
</section>

<section class="cta" id="download">
  <div class="cta__inner" data-reveal>
    <h2>Ready to claim what's yours?</h2>
    <p>The claim check is free. The letter starts at CHF&nbsp;9.90 including print and A-Mail. If your landlord stays silent or refuses, <strong>RentReducer</strong> guides you all the way to the conciliation authority.</p>
    <div class="hero__cta">
      <a class="store-button" href="#" data-coming-soon aria-label="Download RentReducer on the App Store">
        <svg class="store-button__icon" viewBox="0 0 384 512" fill="currentColor" aria-hidden="true"><path d="M318.7 268.7c-.2-36.7 16.4-64.4 50-84.8-18.8-26.9-47.2-41.7-84.7-44.6-35.5-2.8-74.3 20.7-88.5 20.7-15 0-49.4-19.7-76.4-19.7C63.3 141.2 4 184.8 4 273.5q0 39.3 14.4 81.2c12.8 36.7 59 126.7 107.2 125.2 25.2-.6 43-17.9 75.8-17.9 31.8 0 48.3 17.9 76.4 17.9 48.6-.7 90.4-82.5 102.6-119.3-65.2-30.7-61.7-90-61.7-91.9zm-56.6-164.2c27.3-32.4 24.8-61.9 24-72.5-24.1 1.4-52 16.4-67.9 34.9-17.5 19.8-27.8 44.3-25.6 71.9 26.1 2 49.9-11.4 69.5-34.3z"/></svg>
        <span class="store-button__text">
          <span class="store-button__small">Download on the</span>
          <span class="store-button__big">App&nbsp;Store</span>
        </span>
      </a>
      <a class="store-button" href="#" data-coming-soon aria-label="Get RentReducer on Google Play">
        <svg class="store-button__icon" viewBox="0 0 512 512" aria-hidden="true">
          <path fill="#34d399" d="M325.3 234.3 104.6 13l280.8 161.2-60.1 60.1z"/>
          <path fill="#fbbf24" d="M104.6 499 325.3 277.7l60.1 60.1L104.6 499z"/>
          <path fill="#60a5fa" d="m480.6 256.5-95.2 60.1-66.3-60.1 66.3-60.1 95.2 60.1z"/>
          <path fill="#f87171" d="m104.6 499 1.3-489.7 219.4 222 0 .3 0 .3z"/>
        </svg>
        <span class="store-button__text">
          <span class="store-button__small">Get it on</span>
          <span class="store-button__big">Google&nbsp;Play</span>
        </span>
      </a>
    </div>
    <p class="hero__pricing"><span class="hero__pricing-bit"><strong>Claim check + rate alert free</strong></span><span class="dot" aria-hidden="true">·</span><span class="hero__pricing-bit">Letter from <strong>CHF&nbsp;9.90</strong></span><span class="dot" aria-hidden="true">·</span><span class="hero__pricing-bit">No subscription</span></p>
  </div>
</section>
