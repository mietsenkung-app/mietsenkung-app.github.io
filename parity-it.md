---
layout: default
title: Calcolo Ribassoaffitto vs Associazione svizzera inquilini
description: Confronto del calcolo della riduzione di affitto tra Ribassoaffitto e il calcolatore ufficiale dell'ASI / Mieterverband. Sei casi di test reali, documentati con trasparenza.
lang: it-CH
permalink: /parity-it.html
---

<div class="lang-switch">
  <a href="parity-de.html">DE</a>
  <a href="parity-fr.html">FR</a>
  <span class="active" aria-current="page">IT</span>
  <a href="parity-en.html">EN</a>
</div>

# Calcolo **Ribassoaffitto** vs **Mieterverband / ASI**

Come puoi essere sicur* che il calcolo di <strong>Ribassoaffitto</strong> sia corretto? Il **19 maggio 2026** abbiamo eseguito sei calcoli di test reali sia nell'app <strong>Ribassoaffitto</strong> sia nel calcolatore ufficiale del Mieterverband svizzero (equivalente germanofono dell'ASI Ticino, [mzr.mieterverband.ch](https://mzr.mieterverband.ch/senkung)). Ecco l'analisi trasparente.

## Risultato

<div class="parity-table-wrap">
<table class="parity-table">
<thead>
<tr><th>Caso</th><th>Input</th><th>Calcolatore MV</th><th><strong>Ribassoaffitto</strong></th><th>Differenza</th></tr>
</thead>
<tbody>
<tr><td>1</td><td>CHF 1500 / Luglio 2023 / Zurigo</td><td>CHF 11.17</td><td>CHF 11.62</td><td>+0.45</td></tr>
<tr><td>2</td><td>CHF 2000 / Ottobre 2023 / Berna</td><td>CHF 18.15</td><td>CHF 19.16</td><td>+1.01</td></tr>
<tr><td>3</td><td>CHF 1800 / Marzo 2024 / <strong>Lucerna</strong></td><td>CHF 95.22</td><td>CHF 75.25</td><td><strong>-19.97</strong></td></tr>
<tr><td>4</td><td>CHF 2500 / Giugno 2024 / Zurigo</td><td>CHF 113.75</td><td>CHF 113.26</td><td>-0.49</td></tr>
<tr><td>5</td><td>CHF 1200 / Ottobre 2024 / Berna</td><td>CHF 53.93</td><td>CHF 53.67</td><td>-0.26</td></tr>
<tr><td>6</td><td>CHF 1500 / Aprile 2025 / <strong>San&nbsp;Gallo</strong></td><td>CHF 39.54</td><td>CHF 31.86</td><td><strong>-7.68</strong></td></tr>
</tbody>
</table>
</div>

<p class="small-print">Importi di riduzione per mese. Data di calcolo in entrambi i tool: 19.05.2026. PDF sorgente disponibili su richiesta.</p>

## Cosa mostra questo confronto?

### Zurigo e Berna: identico (casi 1, 2, 4, 5)

Nei quattro casi test dei cantoni **Zurigo e Berna**, il calcolo <strong>Ribassoaffitto</strong> corrisponde **al CHF 1 al calcolatore MV.** Le piccole differenze in centesimi derivano da convenzioni di arrotondamento leggermente diverse, il metodo è identico.

Entrambi gli strumenti utilizzano:

- la stessa **formula art. 13 OLAL** per la deduzione del tasso di riferimento
- lo stesso **calcolo del rincaro** (40% della variazione IPC secondo l'UST)
- lo stesso **aumento forfettario dei costi** dello 0.5% all'anno

### Lucerna e San&nbsp;Gallo: <strong>Ribassoaffitto</strong> calcola in modo più conservativo (casi 3, 6)

A Lucerna e San&nbsp;Gallo il calcolo diverge. Non perché la formula sia diversa, ma perché **le associazioni cantonali applicano localmente altri forfait:**

- **MV Lucerna :** applica forfettariamente **0%** di aumento dei costi
- **MV Svizzera orientale** (San&nbsp;Gallo): applica **0.25% × inflazione** (molto basso)
- <strong>Ribassoaffitto</strong>: applica costantemente **0.5% all'anno** (valore predefinito del diritto della locazione svizzero, identico a MV Zurigo + MV Berna)

Ciò significa: a Lucerna e San&nbsp;Gallo, lo strumento locale dà una riduzione più alta. <strong>Ribassoaffitto</strong> segue il forfait predefinito conservativo secondo l'OLAL.

## Perché il forfait conservativo?

L'ordinanza svizzera sulla locazione (OLAL art. 13) non prescrive un forfait fisso per l'aumento dei costi. Le autorità di conciliazione accettano in pratica forfait **tra 0% e 0.5% all'anno**, a seconda del rapporto di locazione. MV Berna lo documenta in modo trasparente in [una tabella a tre livelli](https://www.mieterverband.ch/mv-be/Referenzzins-.html):

- **0.5%** se solo riscaldamento, custodia e TV sono elencati come spese accessorie separate
- **0.25%** se altre spese accessorie sono elencate separatamente
- **0%** se l'immobile ha meno di 5 anni (nuovo), senza riparazioni effettuate, e tutte le spese accessorie rilevanti sono separate

<strong>Ribassoaffitto</strong> sceglie la variante conservativa dello 0.5% come predefinita, per tre motivi:

1. **Ipotesi sicura per tutte le costellazioni abitative.** 0.5% è la prassi più frequente delle autorità di conciliazione.
2. **Sicurezza nella trattativa.** Una richiesta motivata e conservativa è più facilmente accettata dal locatore. Se lo 0% fosse giustificato (immobile nuovo senza riparazioni), il locatario può rinegoziarlo successivamente.
3. **Robustezza in caso di controversia.** Davanti all'autorità di conciliazione, il calcolo allo 0.5% è coerente con la giurisprudenza più frequente.

## Cosa significa concretamente per te?

In alcuni cantoni, ad esempio Lucerna o in parti della Svizzera orientale, l'associazione locale degli inquilini raccomanda un forfait più basso per l'aumento dei costi. Se il tuo contratto elenca molte spese accessorie separate (riscaldamento + custodia + TV + acqua + elettricità + rifiuti + lavanderia ...) o se l'immobile ha meno di 5 anni, potrebbe essere giustificato anche nel tuo caso.

Ecco come <strong>Ribassoaffitto</strong> gestisce questa situazione:

1. **La tua lettera <strong>Ribassoaffitto</strong> è la prima richiesta sicura.** Il calcolo è valido in tutta la Svizzera (OLAL art. 13), è accettato nella grande maggioranza dei casi dal locatore ed è giuridicamente solido.
2. **Se il locatore rifiuta, <strong>Ribassoaffitto</strong> non ti abbandona.** Direttamente dall\'app generi la lettera di seguito (richiesta di documenti, sollecito, richiesta di conciliazione), con calcolo automatico dei termini e tracciamento della tua procedura.
3. **Nella procedura di conciliazione** puoi basarti sul tuo calcolo <strong>Ribassoaffitto</strong> oppure argomentare il forfait regionale in uso contro il locatore. L\'autorità di conciliazione decide caso per caso cosa sia appropriato.

Ribassoaffitto non sostituisce una consulenza legale. Per situazioni complesse (subaffitto, adeguamenti scalari, controversie sull\'età dell\'immobile), è raccomandabile una consulenza presso l\'associazione cantonale degli inquilini.

## Metodologia

I calcoli di test sono stati eseguiti manualmente tramite l'assistente MV con dati di test (indirizzo fittizio "Teststrasse 1") e l'email kontakt@mietsenkung-app.ch. I sei PDF MV ricevuti sono archiviati. Il calcolo <strong>Ribassoaffitto</strong> è stato effettuato con il nostro `ReductionCalculator` per gli stessi input, riproducibile tramite test open-source (`flutter test test/parity_audit/mv_parity_test.dart`).

**Fonti delle basi di calcolo :**

- [Art. 270a Codice delle obbligazioni (CO)](https://www.fedlex.admin.ch/eli/cc/27/317_321_377/it) (diritto alla riduzione)
- [Art. 13 OLAL](https://www.fedlex.admin.ch/eli/cc/1990/834_834_834/it) (calcolo per gradini di 0.25%)
- [Tasso di riferimento UFAB](https://www.bwo.admin.ch/bwo/it/home/mietrecht/referenzzinssatz.html) (Ufficio federale delle abitazioni)
- [Indice dei prezzi al consumo UST](https://www.bfs.admin.ch/bfs/it/home/statistiche/prezzi/indice-prezzi-consumo.html)

<strong>Ribassoaffitto</strong> non sostituisce una consulenza legale. Per una valutazione vincolante caso per caso : associazione cantonale degli inquilini.
