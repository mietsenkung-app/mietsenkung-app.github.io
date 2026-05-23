---
layout: default
title: Methodik der Mietsenkungs-Berechnung
description: Wie Mietsenkung den Senkungsanspruch berechnet. Schweizer Mietrechts-Default (VMWG Art. 13), verifiziert gegen den Mietzinsrechner der Zürcher Gerichte und den offiziellen Mieterverbands-Rechner.
lang: de-CH
permalink: /parity-de.html
---

<div class="lang-switch">
  <span class="active" aria-current="page">DE</span>
  <a href="parity-fr.html">FR</a>
  <a href="parity-it.html">IT</a>
  <a href="parity-en.html">EN</a>
</div>

# Methodik der **Mietsenkung**-Berechnung

<strong>Mietsenkung</strong> berechnet deinen Senkungsanspruch strikt nach Schweizer Bundesrecht. Hier zeigen wir, welche Formeln und Quellen wir nutzen, und wie das Resultat mit den etablierten Schweizer Vergleichs-Tools übereinstimmt.

## Die drei Komponenten der Berechnung

Wie die Mietzinssenkung gemäss **VMWG Art. 13** zusammengesetzt wird, ist schweizweit einheitlich vorgegeben:

1. **Referenzzinssatz-Senkung.** Pro 0.25%-Schritt zwischen dem Referenzzinssatz bei deiner letzten Mietzinsfestsetzung und dem heutigen Wert reduziert sich dein Bruttomietzins um 2.0% bis 3.0% (band-abhängig).
2. **Teuerung.** 40% der Veränderung des Landesindex der Konsumentenpreise (BFS) seit deiner letzten Anpassung darf die Vermieterschaft gegenverrechnen.
3. **Allgemeine Kostensteigerung.** Eine Pauschale, die die Vermieterschaft für betriebliche Mehrkosten beanspruchen darf. Die Höhe ist nicht gesetzlich fixiert. Schlichtungsbehörden akzeptieren in der Praxis zwischen 0% und 0.5% pro Jahr, je nach Mietverhältnis.

<strong>Mietsenkung</strong> verwendet als Default-Pauschale **0.5% pro Jahr**. Das entspricht der konservativen Spruchpraxis der häufigsten Schlichtungsbehörden und dem Default des Mietzinsrechners der Zürcher Gerichte.

## Verifikation gegen den ZH-Mietzinsrechner

Wir haben unsere Berechnung im April 2026 in 18 Test-Fällen (Mietanpassungs-Daten 2008-2025, Mietzinse CHF 300-9000) gegen den [Mietzinsrechner der Zürcher Gerichte](https://www.gerichte-zh.ch/de/themen/miete) verifiziert. **Resultat: in allen 18 Fällen liefert die Mietsenkung-Berechnung bei identischen Eingabe-Daten exakt das gleiche Ergebnis wie der ZH-Rechner.** Die ZH-Gerichte sind erstinstanzlich für Schweizer Mietrecht zuständig, ein juristisch belastbarer Referenz-Wert.

Auswahl aus der Test-Reihe (vollständige Tabelle siehe Methodik-Repository):

<div class="parity-table-wrap">
<table class="parity-table">
<thead>
<tr><th>Fall</th><th>Anpassung</th><th>Mietzins</th><th>Senkung</th><th>Δ ZH-Rechner</th></tr>
</thead>
<tbody>
<tr><td>C1</td><td>25.06.2008</td><td>CHF 4981</td><td>CHF 507.47</td><td>± CHF 0</td></tr>
<tr><td>C3</td><td>02.10.2010</td><td>CHF 5532</td><td>CHF 277.10</td><td>± CHF 0</td></tr>
<tr><td>C4</td><td>25.03.2011</td><td>CHF 6944</td><td>CHF 393.83</td><td>± CHF 0</td></tr>
<tr><td>C6</td><td>22.05.2013</td><td>CHF 1560</td><td>CHF 24.84</td><td>± CHF 0</td></tr>
<tr><td>C17</td><td>21.10.2024</td><td>CHF 7418</td><td>CHF 342.41</td><td>± CHF 0</td></tr>
<tr><td>C18</td><td>20.07.2025</td><td>CHF 5878</td><td>CHF 148.03</td><td>± CHF 0</td></tr>
</tbody>
</table>
</div>

<p class="small-print">Δ ZH-Rechner = Differenz Mietsenkung-Berechnung zur ZH-Berechnung bei identischer Daten-Basis. Alle 18 Fälle zeigen Δ = 0 CHF.</p>

## Vergleich mit dem MV-Mietzinsrechner

Zusätzlich haben wir am **19. Mai 2026** sechs Test-Berechnungen gegen den offiziellen [Mietzinsrechner des Mieterverbands](https://mzr.mieterverband.ch/senkung) durchgeführt:

<div class="parity-table-wrap">
<table class="parity-table">
<thead>
<tr><th>Fall</th><th>Inputs</th><th>MV-Rechner</th><th><strong>Mietsenkung</strong></th></tr>
</thead>
<tbody>
<tr><td>1</td><td>CHF 1500 / Juli 2023 / Zürich</td><td>CHF 11.17</td><td>CHF 11.62</td></tr>
<tr><td>2</td><td>CHF 2000 / Oktober 2023 / Bern</td><td>CHF 18.15</td><td>CHF 19.16</td></tr>
<tr><td>3</td><td>CHF 1800 / März 2024 / Luzern</td><td>CHF 95.22</td><td>CHF 75.25</td></tr>
<tr><td>4</td><td>CHF 2500 / Juni 2024 / Zürich</td><td>CHF 113.75</td><td>CHF 113.26</td></tr>
<tr><td>5</td><td>CHF 1200 / Oktober 2024 / Bern</td><td>CHF 53.93</td><td>CHF 53.67</td></tr>
<tr><td>6</td><td>CHF 1500 / April 2025 / St.&nbsp;Gallen</td><td>CHF 39.54</td><td>CHF 31.86</td></tr>
</tbody>
</table>
</div>

<p class="small-print">Senkungs-Beträge pro Monat. Berechnungs-Tag in beiden Tools: 19.05.2026.</p>

### Was zeigt das?

In den **Standardfällen aus Zürich und Bern (Fälle 1, 2, 4, 5)** liefern beide Tools praktisch identische Werte (Differenz < CHF 1, Rundungs-Konventionen).

In **Luzern und der Ostschweiz (Fälle 3, 6)** wendet der lokale Mieterverband eine eigene, kantonal abweichende Pauschale an (0% in Luzern, 0.25%×Inflation in der Ostschweiz). Das ist eine kantonale Spruchpraxis-Besonderheit, nicht eine Abweichung in der gesetzlichen Berechnungsformel. VMWG Art. 13 selbst bleibt überall gleich.

<strong>Mietsenkung</strong> verwendet konsequent die **schweizweit einheitliche Default-Pauschale 0.5%/Jahr**. Diese Berechnung ist juristisch sauber, in jedem Kanton anwendbar und entspricht der häufigsten Schlichtungsbehörden-Praxis. Sie ist eine sichere Untergrenze: dein Vermieter akzeptiert sie in der Regel, weil sie nicht überzogen wirkt und gerichtlich gut belastbar ist.

## Was bedeutet das für dich konkret?

1. **Dein <strong>Mietsenkung</strong>-Brief ist die sichere Erstforderung.** Die Berechnung gilt schweizweit, wird in der grossen Mehrheit der Fälle vom Vermieter akzeptiert und ist juristisch belastbar.
2. **Lehnt deine Vermieterschaft ab, schickt <strong>Mietsenkung</strong> dich nicht weg.** Direkt aus der App heraus erstellst du den Folgebrief (Unterlagen anfordern, Erinnerung, Schlichtungs-Klage), inklusive automatischer Frist-Berechnung und Tracking deines Verfahrens.
3. **Im Schlichtungs-Verfahren** entscheidet die Behörde im Einzelfall, was angemessen ist. Hier kannst du dich auf deine <strong>Mietsenkung</strong>-Berechnung stützen oder zusätzlich kantonale Spruchpraxis argumentieren.

Bei komplexen Konstellationen (z.B. Untermiete, gestaffelte Anpassungen, Streitigkeiten ums Gebäudealter) ist eine Beratung beim kantonalen Mieterinnen- und Mieterverband empfehlenswert. <strong>Mietsenkung</strong> ist keine Rechtsberatung.

## Quellen

- [Art. 270a Obligationenrecht (OR)](https://www.fedlex.admin.ch/eli/cc/27/317_321_377/de). Senkungsanspruch
- [Art. 13 Verordnung über die Miete (VMWG)](https://www.fedlex.admin.ch/eli/cc/1990/834_834_834/de). Berechnung pro 0.25%-Schritt
- [Referenzzinssatz BWO](https://www.bwo.admin.ch/bwo/de/home/mietrecht/referenzzinssatz.html). Bundesamt für Wohnungswesen
- [Landesindex der Konsumentenpreise BFS](https://www.bfs.admin.ch/bfs/de/home/statistiken/preise/landesindex-konsumentenpreise.html). Bundesamt für Statistik
- [Mietzinsrechner Zürcher Gerichte](https://www.gerichte-zh.ch/de/themen/miete). Verifikations-Referenz

<p class="parity-meta">Stand: 19.05.2026</p>
