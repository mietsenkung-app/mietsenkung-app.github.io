---
layout: default
title: Calcul Baisse-loyer vs Association de défense des locataires
description: Comparaison du calcul de réduction de loyer entre Baisse-loyer et le calculateur officiel de l'ASLOCA / Mieterverband. Six cas de test réels, documentés en toute transparence.
lang: fr-CH
permalink: /parity-fr.html
---

<div class="lang-switch">
  <a href="parity-de.html">DE</a>
  <span class="active" aria-current="page">FR</span>
  <a href="parity-it.html">IT</a>
  <a href="parity-en.html">EN</a>
</div>

# Calcul **Baisse-loyer** vs **Mieterverband / ASLOCA**

Comment être sûr·e que le calcul de <strong>Baisse-loyer</strong> est correct ? Le **19 mai 2026**, nous avons effectué six calculs de test réels à la fois dans l'app <strong>Baisse-loyer</strong> et dans le calculateur officiel du Mieterverband suisse (équivalent germanophone de l'ASLOCA, [mzr.mieterverband.ch](https://mzr.mieterverband.ch/senkung)). Voici l'évaluation transparente.

## Résultat

<div class="parity-table-wrap">
<table class="parity-table">
<thead>
<tr><th>Cas</th><th>Entrées</th><th>Calculateur MV</th><th><strong>Baisse-loyer</strong></th><th>Différence</th></tr>
</thead>
<tbody>
<tr><td>1</td><td>CHF 1500 / Juillet 2023 / Zurich</td><td>CHF 11.17</td><td>CHF 11.62</td><td>+0.45</td></tr>
<tr><td>2</td><td>CHF 2000 / Octobre 2023 / Berne</td><td>CHF 18.15</td><td>CHF 19.16</td><td>+1.01</td></tr>
<tr><td>3</td><td>CHF 1800 / Mars 2024 / <strong>Lucerne</strong></td><td>CHF 95.22</td><td>CHF 75.25</td><td><strong>-19.97</strong></td></tr>
<tr><td>4</td><td>CHF 2500 / Juin 2024 / Zurich</td><td>CHF 113.75</td><td>CHF 113.26</td><td>-0.49</td></tr>
<tr><td>5</td><td>CHF 1200 / Octobre 2024 / Berne</td><td>CHF 53.93</td><td>CHF 53.67</td><td>-0.26</td></tr>
<tr><td>6</td><td>CHF 1500 / Avril 2025 / <strong>Saint-Gall</strong></td><td>CHF 39.54</td><td>CHF 31.86</td><td><strong>-7.68</strong></td></tr>
</tbody>
</table>
</div>

<p class="small-print">Montants de réduction par mois. Date de calcul dans les deux outils : 19.05.2026. PDFs source disponibles sur demande.</p>

## Ce que cela montre

### Zurich et Berne : identique (cas 1, 2, 4, 5)

Dans les quatre cas test des cantons de **Zurich et Berne**, le calcul <strong>Baisse-loyer</strong> correspond **au CHF 1 près au calculateur MV.** Les petites différences en centimes proviennent de conventions d'arrondi légèrement différentes, la méthode est identique.

Les deux outils utilisent :

- la même **formule VMWG art. 13** pour la déduction du taux de référence
- le même **calcul du renchérissement** (40% de la variation IPC selon l'OFS)
- la même **augmentation forfaitaire des coûts** de 0.5% par an

### Lucerne et Saint-Gall : <strong>Baisse-loyer</strong> calcule de manière plus conservatrice (cas 3, 6)

À Lucerne et à Saint-Gall, le calcul diverge. Pas parce que la formule serait différente, mais parce que **les associations cantonales appliquent localement d'autres forfaits :**

- **MV Lucerne** : applique forfaitairement **0%** d'augmentation des coûts
- **MV Suisse orientale** (Saint-Gall) : applique **0.25% × inflation** (très faible)
- <strong>Baisse-loyer</strong> : applique systématiquement **0.5% par an** (valeur par défaut du droit du bail suisse, identique à MV Zurich + MV Berne)

Cela signifie : à Lucerne et Saint-Gall, l'outil local donne une réduction plus élevée. <strong>Baisse-loyer</strong> suit le forfait par défaut conservateur selon l'OBLF.

## Pourquoi le forfait conservateur ?

L'ordonnance suisse sur le bail (OBLF art. 13) ne prescrit pas de forfait fixe pour l'augmentation des coûts. Les autorités de conciliation acceptent en pratique des forfaits **entre 0% et 0.5% par an**, selon le contrat de bail. MV Berne le documente de manière transparente dans [un tableau à trois niveaux](https://www.mieterverband.ch/mv-be/Referenzzins-.html) :

- **0.5%** si seuls le chauffage, la conciergerie et la TV figurent comme frais accessoires séparés
- **0.25%** si d'autres frais accessoires figurent en plus
- **0%** si l'immeuble a moins de 5 ans (neuf), sans réparations effectuées, et tous les frais accessoires sont séparés

<strong>Baisse-loyer</strong> choisit la variante conservative de 0.5% par défaut, pour trois raisons :

1. **Hypothèse sûre pour toutes les constellations.** 0.5% est la pratique la plus fréquente des autorités de conciliation.
2. **Sécurité de négociation.** Une demande motivée et conservatrice est plus facilement acceptée par la bailleuse. Si 0% se justifie (immeuble neuf sans réparations), le locataire peut le négocier ensuite.
3. **Robustesse en cas de litige.** Devant l'autorité de conciliation, le calcul à 0.5% est congruent avec la jurisprudence la plus fréquente.

## Qu'est-ce que cela signifie concrètement pour toi ?

Dans certains cantons, par exemple à Lucerne ou dans des parties de la Suisse orientale, l'association locale des locataires recommande un forfait inférieur pour l'augmentation des coûts. Si ton bail liste de nombreux frais accessoires séparés (chauffage + conciergerie + TV + eau + électricité + ordures + buanderie ...) ou si l'immeuble a moins de 5 ans, cela pourrait aussi se justifier dans ton cas.

Voici comment <strong>Baisse-loyer</strong> gère cela :

1. **Ta lettre <strong>Baisse-loyer</strong> est la première demande sûre.** Le calcul est valable dans toute la Suisse (OBLF art. 13), est accepté dans la grande majorité des cas par la bailleuse et tient juridiquement.
2. **Si la bailleuse refuse, <strong>Baisse-loyer</strong> ne te laisse pas tomber.** Directement depuis l'app, tu génères la lettre de suivi (demande de pièces justificatives, rappel, requête en conciliation), avec calcul automatique des délais et suivi de ta procédure.
3. **En procédure de conciliation,** tu peux te baser sur ton calcul <strong>Baisse-loyer</strong> ou argumenter le forfait régional en vigueur contre la bailleuse. L'autorité de conciliation décide au cas par cas ce qui est approprié.

Baisse-loyer n'est pas un conseil juridique. Pour des constellations complexes (sous-location, ajustements échelonnés, litiges sur l'âge du bâtiment), une consultation auprès de l'association cantonale des locataires est recommandée.

## Méthodologie

Les calculs test ont été effectués manuellement via l'assistant MV avec des données de test (adresse fictive "Teststrasse 1") et l'email kontakt@mietsenkung-app.ch. Les six PDFs MV reçus sont archivés. Le calcul <strong>Baisse-loyer</strong> a été réalisé avec notre `ReductionCalculator` pour les mêmes entrées, reproductible via un test open-source (`flutter test test/parity_audit/mv_parity_test.dart`).

**Sources des bases de calcul :**

- [Art. 270a Code des obligations (CO)](https://www.fedlex.admin.ch/eli/cc/27/317_321_377/fr) (droit à la baisse)
- [Art. 13 OBLF](https://www.fedlex.admin.ch/eli/cc/1990/834_834_834/fr) (calcul par tranche de 0.25%)
- [Taux de référence OFL](https://www.bwo.admin.ch/bwo/fr/home/mietrecht/referenzzinssatz.html) (Office fédéral du logement)
- [Indice des prix à la consommation OFS](https://www.bfs.admin.ch/bfs/fr/home/statistiques/prix/indice-prix-consommation.html)

<strong>Baisse-loyer</strong> n'est pas un conseil juridique. Pour une évaluation contraignante au cas par cas : association cantonale des locataires.
