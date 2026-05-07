# mietsenkung-app.github.io

Statische Site mit Datenschutzerklärung, Privacy Policy und Impressum zur App **Mietsenkung**. Wird über GitHub Pages aus diesem Repo gerendert.

Live unter: [https://mietsenkung-app.ch/](https://mietsenkung-app.ch/) (Custom Domain via Infomaniak DNS, GitHub-Pages-Backend bleibt `mietsenkung-app.github.io`).

## Struktur

- `index.md` — Landing mit Links zu den Rechtsdokumenten
- `privacy-de.md` / `privacy-en.md` — Datenschutzerklärung (DE / EN)
- `impressum.md` — Impressum (DE)
- `_layouts/default.html` — gemeinsames Layout (Header, Footer, Sprachumschalter)
- `assets/style.css` — Styling (Emerald-Akzent passend zur App)
- `_config.yml` — Jekyll-Konfiguration

## Quelle der Inhalte

Die Privacy-Policy-Inhalte sind eine Kopie aus dem Haupt-Repo der App: `mietsenkung-app/mietsenkung` → `docs/legal/privacy-policy-de.md` und `privacy-policy-en.md`. Bei inhaltlichen Änderungen zuerst dort editieren, dann hierher synchronisieren.

## Lokal bauen

```bash
bundle install
bundle exec jekyll serve
```

Voraussetzung: Ruby + Jekyll. Für GitHub Pages ist der lokale Build nicht zwingend nötig — Pages baut automatisch bei jedem Push.
