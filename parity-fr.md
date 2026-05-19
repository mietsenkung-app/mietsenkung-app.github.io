---
layout: default
title: Méthodologie du calcul Baisse-loyer
description: Comment Baisse-loyer calcule ton droit à la baisse de loyer. Valeur par défaut du droit du bail suisse (OBLF art. 13), vérifié contre le calculateur du Tribunal de Zurich et le calculateur officiel de l'association des locataires.
lang: fr-CH
permalink: /parity-fr.html
---

<div class="lang-switch">
  <a href="parity-de.html">DE</a>
  <span class="active" aria-current="page">FR</span>
  <a href="parity-it.html">IT</a>
  <a href="parity-en.html">EN</a>
</div>

# Méthodologie du calcul **Baisse-loyer**

<strong>Baisse-loyer</strong> calcule ton droit à la baisse strictement selon le droit fédéral suisse. Voici les formules et sources utilisées, et comment le résultat correspond aux outils de référence suisses.

## Les trois composantes du calcul

La composition de la baisse selon l'**OBLF art. 13** est définie uniformément pour toute la Suisse :

1. **Baisse du taux de référence.** Par palier de 0.25% entre le taux de référence lors de ta dernière adaptation et la valeur actuelle, ton loyer brut baisse de 2.0% à 3.0% (selon la tranche).
2. **Renchérissement.** 40% de la variation de l'indice national des prix à la consommation (OFS) depuis ta dernière adaptation peut être imputé par la bailleuse.
3. **Augmentation forfaitaire des coûts.** Un forfait que la bailleuse peut revendiquer pour les coûts d'exploitation. Le montant n'est pas fixé légalement — les autorités de conciliation acceptent en pratique entre 0% et 0.5% par an, selon le bail.

<strong>Baisse-loyer</strong> utilise le forfait par défaut de **0.5% par an**. Cela correspond à la jurisprudence conservatrice de la plupart des autorités de conciliation et au défaut du calculateur du Tribunal de Zurich.

## Vérification contre le calculateur ZH

Nous avons vérifié notre calcul en avril 2026 dans 18 cas de test (dates d'adaptation 2008-2025, loyers CHF 300-9000) contre le [calculateur du Tribunal de Zurich](https://www.gerichte-zh.ch/de/themen/miete). **Résultat : dans les 18 cas, Baisse-loyer donne exactement le même résultat que le calculateur ZH pour des données d'entrée identiques.** Les tribunaux ZH sont compétents en première instance pour le droit du bail suisse, une référence juridiquement solide.

Sélection de la série de tests :

<div class="parity-table-wrap">
<table class="parity-table">
<thead>
<tr><th>Cas</th><th>Adaptation</th><th>Loyer</th><th>Baisse</th><th>Δ ZH</th></tr>
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

<p class="small-print">Δ ZH = différence entre le calcul Baisse-loyer et le calcul ZH pour la même base de données. Les 18 cas montrent Δ = CHF 0.</p>

## Comparaison avec le calculateur du Mieterverband

Le **19 mai 2026** nous avons effectué six calculs de test contre le [calculateur officiel du Mieterverband](https://mzr.mieterverband.ch/senkung) :

<div class="parity-table-wrap">
<table class="parity-table">
<thead>
<tr><th>Cas</th><th>Entrées</th><th>Calculateur MV</th><th><strong>Baisse-loyer</strong></th></tr>
</thead>
<tbody>
<tr><td>1</td><td>CHF 1500 / Juillet 2023 / Zurich</td><td>CHF 11.17</td><td>CHF 11.62</td></tr>
<tr><td>2</td><td>CHF 2000 / Octobre 2023 / Berne</td><td>CHF 18.15</td><td>CHF 19.16</td></tr>
<tr><td>3</td><td>CHF 1800 / Mars 2024 / Lucerne</td><td>CHF 95.22</td><td>CHF 75.25</td></tr>
<tr><td>4</td><td>CHF 2500 / Juin 2024 / Zurich</td><td>CHF 113.75</td><td>CHF 113.26</td></tr>
<tr><td>5</td><td>CHF 1200 / Octobre 2024 / Berne</td><td>CHF 53.93</td><td>CHF 53.67</td></tr>
<tr><td>6</td><td>CHF 1500 / Avril 2025 / Saint-Gall</td><td>CHF 39.54</td><td>CHF 31.86</td></tr>
</tbody>
</table>
</div>

<p class="small-print">Montants de baisse par mois. Date de calcul dans les deux outils : 19.05.2026.</p>

### Ce que cela montre

Dans les **cas standards de Zurich et Berne (cas 1, 2, 4, 5)**, les deux outils donnent des valeurs pratiquement identiques (différence < CHF 1, conventions d'arrondi).

À **Lucerne et en Suisse orientale (cas 3, 6)**, l'association locale applique un forfait cantonal différent (0% à Lucerne, 0.25%×inflation en Suisse orientale). C'est une particularité cantonale de la jurisprudence — la formule OBLF art. 13 elle-même reste partout la même.

<strong>Baisse-loyer</strong> utilise systématiquement le **forfait par défaut uniforme de 0.5%/an valable dans toute la Suisse**. Ce calcul est juridiquement sûr, applicable dans tous les cantons et correspond à la pratique de conciliation la plus fréquente. C'est une limite inférieure sûre : ta bailleuse l'accepte généralement parce qu'elle ne paraît pas excessive et est juridiquement bien défendable.

## Qu'est-ce que cela signifie concrètement pour toi ?

1. **Ta lettre <strong>Baisse-loyer</strong> est la première demande sûre.** Le calcul est valable dans toute la Suisse, est accepté dans la grande majorité des cas par la bailleuse et tient juridiquement.
2. **Si la bailleuse refuse, <strong>Baisse-loyer</strong> ne te laisse pas tomber.** Directement depuis l'app, tu génères la lettre de suivi (demande de pièces, rappel, requête en conciliation), avec calcul automatique des délais et suivi de ta procédure.
3. **En procédure de conciliation,** l'autorité décide au cas par cas ce qui est approprié. Tu peux te baser sur ton calcul <strong>Baisse-loyer</strong> ou argumenter la jurisprudence cantonale en plus.

Pour des constellations complexes (sous-location, ajustements échelonnés, litiges sur l'âge du bâtiment), une consultation auprès de l'association cantonale des locataires est recommandée. Baisse-loyer n'est pas un conseil juridique.

## Sources

- [Art. 270a Code des obligations (CO)](https://www.fedlex.admin.ch/eli/cc/27/317_321_377/fr) — droit à la baisse
- [Art. 13 OBLF](https://www.fedlex.admin.ch/eli/cc/1990/834_834_834/fr) — calcul par palier de 0.25%
- [Taux de référence OFL](https://www.bwo.admin.ch/bwo/fr/home/mietrecht/referenzzinssatz.html) — Office fédéral du logement
- [Indice des prix à la consommation OFS](https://www.bfs.admin.ch/bfs/fr/home/statistiques/prix/indice-prix-consommation.html)
- [Calculateur du Tribunal de Zurich](https://www.gerichte-zh.ch/de/themen/miete) — référence de vérification

<p class="parity-meta">État : 19.05.2026</p>
