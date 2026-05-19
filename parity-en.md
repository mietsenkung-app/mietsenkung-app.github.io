---
layout: default
title: RentReducer calculation vs Swiss Tenants' Association
description: Comparison of the rent reduction calculation between RentReducer and the official calculator of the Mieterverband Schweiz / ASLOCA. Six real test cases, documented transparently.
lang: en
permalink: /parity-en.html
---

<div class="lang-switch">
  <a href="parity-de.html">DE</a>
  <a href="parity-fr.html">FR</a>
  <a href="parity-it.html">IT</a>
  <span class="active" aria-current="page">EN</span>
</div>

# **RentReducer** vs the Swiss Tenants' Association calculation

How can you be sure the <strong>RentReducer</strong> calculation is correct? On **19 May 2026** we ran six real test calculations both in the <strong>RentReducer</strong> app and in the official calculator of the Swiss Tenants' Association ([mzr.mieterverband.ch](https://mzr.mieterverband.ch/senkung)). Here is the transparent comparison.

## Result

<div class="parity-table-wrap">
<table class="parity-table">
<thead>
<tr><th>Case</th><th>Inputs</th><th>MV calculator</th><th><strong>RentReducer</strong></th><th>Difference</th></tr>
</thead>
<tbody>
<tr><td>1</td><td>CHF 1500 / July 2023 / Zurich</td><td>CHF 11.17</td><td>CHF 11.62</td><td>+0.45</td></tr>
<tr><td>2</td><td>CHF 2000 / October 2023 / Bern</td><td>CHF 18.15</td><td>CHF 19.16</td><td>+1.01</td></tr>
<tr><td>3</td><td>CHF 1800 / March 2024 / <strong>Lucerne</strong></td><td>CHF 95.22</td><td>CHF 75.25</td><td><strong>-19.97</strong></td></tr>
<tr><td>4</td><td>CHF 2500 / June 2024 / Zurich</td><td>CHF 113.75</td><td>CHF 113.26</td><td>-0.49</td></tr>
<tr><td>5</td><td>CHF 1200 / October 2024 / Bern</td><td>CHF 53.93</td><td>CHF 53.67</td><td>-0.26</td></tr>
<tr><td>6</td><td>CHF 1500 / April 2025 / <strong>St.&nbsp;Gallen</strong></td><td>CHF 39.54</td><td>CHF 31.86</td><td><strong>-7.68</strong></td></tr>
</tbody>
</table>
</div>

<p class="small-print">Monthly reduction amounts. Calculation date in both tools: 19.05.2026. Source PDFs available on request.</p>

## What this shows

### Zurich and Bern: identical (cases 1, 2, 4, 5)

In the four test cases from the cantons of **Zurich and Bern**, the <strong>RentReducer</strong> calculation matches the MV calculator **to within CHF 1.** The minor centime differences come from slightly different rounding conventions. The methodology is the same.

Both tools use:

- the same **VMWG art. 13 formula** for the reference-rate deduction
- the same **inflation calculation** (40% of CPI change as published by the Federal Statistical Office)
- the same **flat-rate cost increase** of 0.5% per year

### Lucerne and St.&nbsp;Gallen: <strong>RentReducer</strong> calculates more conservatively (cases 3, 6)

In Lucerne and St.&nbsp;Gallen the calculations diverge. Not because the formula is different, but because the **cantonal tenants' associations apply different flat rates locally:**

- **MV Lucerne :** applies a flat **0% cost increase**
- **MV Eastern Switzerland** (St.&nbsp;Gallen): applies **0.25% × inflation** (very low)
- <strong>RentReducer</strong>: consistently applies **0.5% per year** (Swiss tenancy-law default, same as MV Zurich + MV Bern)

This means: in Lucerne and St.&nbsp;Gallen the local MV tool yields a higher reduction demand. <strong>RentReducer</strong> follows the more conservative VMWG default.

## Why the conservative flat rate?

The Swiss tenancy ordinance (VMWG art. 13) does not prescribe a fixed cost-increase rate. In practice, conciliation authorities accept flat rates **between 0% and 0.5% per year**, depending on the lease conditions. MV Bern documents this transparently in [a three-tier table](https://www.mieterverband.ch/mv-be/Referenzzins-.html):

- **0.5%** if only heating, caretaking and TV are listed as separate ancillary costs
- **0.25%** if additional ancillary costs are listed separately
- **0%** if the property is less than 5 years old (new build) with no repairs and all relevant ancillary costs are billed separately

<strong>RentReducer</strong> chose the conservative 0.5% variant as the default. Three reasons:

1. **Safe assumption across all rental situations.** 0.5% is the most common conciliation-authority practice.
2. **Negotiation safety.** A justified, conservative claim is more readily accepted by the landlord. If 0% were justified (new build without repairs), the tenant can negotiate that afterwards.
3. **Robustness in disputes.** Before the conciliation authority, the 0.5% calculation aligns with the most common decision practice.

## What to do if you live in Lucerne or Eastern Switzerland?

If your lease lists many separate ancillary costs (heating + caretaking + TV + water + electricity + waste + laundry...), a lower flat rate could be justified. Proceed as follows:

1. **Use your <strong>RentReducer</strong> letter as your first demand.** The calculation is a safe lower bound and is rarely contested by the landlord.
2. **If the landlord refuses or you want a higher reduction:** contact the cantonal tenants' association (free advice for members):
   - **MV Lucerne :** [luzern@mieterverband.ch](mailto:luzern@mieterverband.ch) / 041 220 10 22
   - **MV Eastern Switzerland :** [ostschweiz@mieterverband.ch](mailto:ostschweiz@mieterverband.ch) / 071 222 50 29
3. **In conciliation proceedings** you can submit the cantonal calculation as an extension of your demand.

## Methodology

The test calculations were performed manually via the MV wizard using test data (fictional address "Teststrasse 1") and the email kontakt@mietsenkung-app.ch. The six MV PDFs received are archived. The <strong>RentReducer</strong> calculation was performed with our `ReductionCalculator` for the same inputs, reproducible via an open-source test (`flutter test test/parity_audit/mv_parity_test.dart`).

**Sources of the calculation basis :**

- [Art. 270a Code of Obligations (CO)](https://www.fedlex.admin.ch/eli/cc/27/317_321_377/de) (reduction claim)
- [Art. 13 VMWG](https://www.fedlex.admin.ch/eli/cc/1990/834_834_834/de) (calculation per 0.25% step)
- [Reference interest rate BWO](https://www.bwo.admin.ch/bwo/de/home/mietrecht/referenzzinssatz.html) (Federal Housing Office)
- [Consumer Price Index BFS](https://www.bfs.admin.ch/bfs/en/home/statistics/prices/consumer-price-index.html) (Federal Statistical Office)

<strong>RentReducer</strong> is not legal advice. For a binding case-by-case assessment, contact the cantonal Swiss Tenants' Association.
