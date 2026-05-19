---
layout: default
title: Berechnung Mietsenkung vs Mieterverband
description: Vergleich der Mietzinssenkungs-Berechnung von Mietsenkung mit dem offiziellen Mieterverband-Mietzinsrechner. Sechs reale Test-Fälle, ehrlich dokumentiert.
lang: de-CH
permalink: /parity-de.html
---

<div class="lang-switch">
  <span class="active" aria-current="page">DE</span>
  <a href="parity-fr.html">FR</a>
  <a href="parity-it.html">IT</a>
  <a href="parity-en.html">EN</a>
</div>

# Berechnung **Mietsenkung** vs **Mieterverband**

Wie kannst du sicher sein, dass die <strong>Mietsenkung</strong>-Berechnung stimmt? Wir haben am **19. Mai 2026** sechs reale Test-Berechnungen sowohl in der <strong>Mietsenkung</strong>-App als auch im offiziellen Mieterverbands-Mietzinsrechner ([mzr.mieterverband.ch](https://mzr.mieterverband.ch/senkung)) durchgeführt. Hier die transparente Auswertung.

## Resultat

<div class="parity-table-wrap">
<table class="parity-table">
<thead>
<tr><th>Fall</th><th>Inputs</th><th>MV-Rechner</th><th><strong>Mietsenkung</strong></th><th>Differenz</th></tr>
</thead>
<tbody>
<tr><td>1</td><td>CHF 1500 / Juli 2023 / Zürich</td><td>CHF 11.17</td><td>CHF 11.62</td><td>+0.45</td></tr>
<tr><td>2</td><td>CHF 2000 / Oktober 2023 / Bern</td><td>CHF 18.15</td><td>CHF 19.16</td><td>+1.01</td></tr>
<tr><td>3</td><td>CHF 1800 / März 2024 / <strong>Luzern</strong></td><td>CHF 95.22</td><td>CHF 75.25</td><td><strong>-19.97</strong></td></tr>
<tr><td>4</td><td>CHF 2500 / Juni 2024 / Zürich</td><td>CHF 113.75</td><td>CHF 113.26</td><td>-0.49</td></tr>
<tr><td>5</td><td>CHF 1200 / Oktober 2024 / Bern</td><td>CHF 53.93</td><td>CHF 53.67</td><td>-0.26</td></tr>
<tr><td>6</td><td>CHF 1500 / April 2025 / <strong>St.&nbsp;Gallen</strong></td><td>CHF 39.54</td><td>CHF 31.86</td><td><strong>-7.68</strong></td></tr>
</tbody>
</table>
</div>

<p class="small-print">Senkungs-Beträge pro Monat. Berechnungs-Tag in beiden Tools: 19.05.2026. Quell-PDFs auf Anfrage einsehbar.</p>

## Was zeigt das?

### Zürich + Bern: identisch (Fälle 1, 2, 4, 5)

In den vier Test-Fällen aus den Kantonen **Zürich und Bern** stimmt die <strong>Mietsenkung</strong>-Berechnung **bis auf maximal CHF 1 mit dem MV-Mietzinsrechner überein.** Die kleinen Cents-Differenzen kommen von minimal unterschiedlichen Rundungs-Konventionen, die Methodik ist gleich.

Beide Tools nutzen:

- die gleiche **VMWG-Art-13-Formel** für den Referenzzins-Abzug
- die gleiche **Teuerungs-Berechnung** (40% der LIK-Veränderung gemäss Bundesamt für Statistik)
- die gleiche **Kostensteigerungs-Pauschale** von 0.5% pro Jahr

### Luzern + St.&nbsp;Gallen: <strong>Mietsenkung</strong> rechnet konservativer (Fälle 3, 6)

In Luzern und St.&nbsp;Gallen weicht die Berechnung ab. Nicht weil die Formel anders wäre, sondern weil die kantonalen Mieterverbände **lokal andere Kostensteigerungs-Pauschalen anwenden:**

- **MV Luzern Nidwalden Obwalden Uri:** rechnet pauschal mit **0% Kostensteigerung**
- **MV Ostschweiz** (St.&nbsp;Gallen): rechnet mit **0.25% × Inflation** (sehr klein)
- <strong>Mietsenkung</strong>: rechnet konsequent mit **0.5% pro Jahr** (Schweizer-Mietrechts-Default, gleich wie MV Zürich + MV Bern)

Das heisst: In Luzern und St.&nbsp;Gallen gibt der lokale MV-Tool eine höhere Senkungs-Forderung an. <strong>Mietsenkung</strong> folgt der konservativeren Default-Pauschale gemäss Schweizer Mietverordnung.

## Warum die konservative Pauschale?

Die Schweizer Mietverordnung (VMWG Art. 13) gibt keine fixe Kostensteigerungs-Pauschale vor. Schlichtungsbehörden akzeptieren in der Praxis Pauschalen **zwischen 0% und 0.5% pro Jahr**, je nach Mietverhältnis. Der MV Bern dokumentiert das transparent in [einer Drei-Stufen-Tabelle](https://www.mieterverband.ch/mv-be/Referenzzins-.html):

- **0.5%** wenn nur Heizung, Hauswartung und TV-Gebühren als separate Nebenkosten aufgeführt sind
- **0.25%** wenn weitere Nebenkosten separat aufgeführt sind
- **0%** wenn die Liegenschaft unter 5 Jahre alt ist (Neubau), keine Reparaturen vorgenommen wurden und alle massgeblichen Nebenkosten separat aufgeführt sind

<strong>Mietsenkung</strong> wählt die konservative 0.5%-Variante als Default. Drei Gründe:

1. **Sichere Anwendung über alle Wohn-Konstellationen.** 0.5% ist die häufigste Schlichtungsbehörden-Praxis.
2. **Verhandlungs-Sicherheit.** Eine begründete, konservative Forderung wird vom Vermieter eher akzeptiert. Falls 0% gerechtfertigt wäre (z.B. Neubau ohne Reparaturen), kann der Mieter das in der Beantwortung der Vermieterschaft nachverhandeln.
3. **Streitfall-Robustheit.** Falls es zur Schlichtungsbehörde geht, ist die 0.5%-Berechnung mit der häufigsten Spruchpraxis kongruent.

## Was bedeutet das für dich konkret?

In gewissen Kantonen, beispielsweise Luzern oder Teilen der Ostschweiz, empfiehlt der lokale Mieterverband eine niedrigere Kostensteigerungs-Pauschale. Wenn dein Mietvertrag eine umfassende Nebenkosten-Liste enthält (Heizung + Hauswartung + TV + Wasser + Strom + Kehricht + Wäsche ...) oder die Liegenschaft jünger als 5 Jahre ist, könnte das auch in deinem Fall gerechtfertigt sein.

So geht <strong>Mietsenkung</strong> damit um:

1. **Dein <strong>Mietsenkung</strong>-Brief ist die sichere Erstforderung.** Die Berechnung gilt schweizweit (VMWG Art. 13), wird in der grössten Mehrheit der Fälle vom Vermieter akzeptiert und ist juristisch belastbar.
2. **Lehnt deine Vermieterschaft ab, schickt <strong>Mietsenkung</strong> dich nicht weg.** Direkt aus der App heraus erstellst du den Folgebrief (Unterlagen anfordern, Erinnerung, Schlichtungs-Klage), inklusive automatischer Frist-Berechnung und Tracking deines Verfahrens.
3. **Im Schlichtungs-Verfahren** kannst du dich auf deine <strong>Mietsenkung</strong>-Berechnung stützen oder die regional übliche Pauschale gegen den Vermieter argumentieren. Die Schlichtungsbehörde entscheidet im Einzelfall, was angemessen ist.

Mietsenkung ist keine Rechtsberatung. Bei komplexen Konstellationen (z.B. Mitvertrag mit Untermiete, gestaffelte Anpassungen, Streitigkeiten ums Gebäudealter) ist eine Beratung beim kantonalen Mieterinnen- und Mieterverband empfehlenswert.

## Methodik

Die Test-Berechnungen wurden manuell über den MV-Wizard durchgeklickt mit Test-Daten (Fake-Adresse "Teststrasse 1") und der Email kontakt@mietsenkung-app.ch. Die sechs erhaltenen MV-PDFs sind archiviert. Die <strong>Mietsenkung</strong>-Berechnung wurde mit unserem `ReductionCalculator` für die identischen Inputs berechnet, reproduzierbar via Open-Source-Test (`flutter test test/parity_audit/mv_parity_test.dart`).

**Quellen der Berechnungsgrundlagen:**

- [Art. 270a Obligationenrecht (OR)](https://www.fedlex.admin.ch/eli/cc/27/317_321_377/de) (Senkungsanspruch)
- [Art. 13 Mietverordnung (VMWG)](https://www.fedlex.admin.ch/eli/cc/1990/834_834_834/de) (Berechnung pro 0.25%-Schritt)
- [Referenzzinssatz BWO](https://www.bwo.admin.ch/bwo/de/home/mietrecht/referenzzinssatz.html) (Bundesamt für Wohnungswesen)
- [Landesindex der Konsumentenpreise BFS](https://www.bfs.admin.ch/bfs/de/home/statistiken/preise/landesindex-konsumentenpreise.html) (Bundesamt für Statistik)
- [Drei-Stufen-Tabelle MV Bern](https://www.mieterverband.ch/mv-be/Referenzzins-.html)

<strong>Mietsenkung</strong> ist keine Rechtsberatung. Für eine verbindliche Einschätzung im Einzelfall: kantonaler Mieterinnen- und Mieterverband.

<p class="parity-meta">Erstellt: 19.05.2026 | Datenstand: BWO Referenzzinssatz Stand 2025-09-02 (1.25%), BFS LIK Stand April 2026 (108.1)</p>
