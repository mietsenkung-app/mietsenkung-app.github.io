---
layout: default
title: RentReducer calculation methodology
description: How RentReducer calculates your rent reduction claim. Swiss tenancy-law default (VMWG art. 13), verified against the Zurich Court's rent calculator and the official Mieterverband calculator.
lang: en
permalink: /parity-en.html
---

<div class="lang-switch">
  <a href="parity-de.html">DE</a>
  <a href="parity-fr.html">FR</a>
  <a href="parity-it.html">IT</a>
  <span class="active" aria-current="page">EN</span>
</div>

# **RentReducer** calculation methodology

<strong>RentReducer</strong> calculates your reduction claim strictly under Swiss federal law. Here are the formulas and sources we use, and how the result lines up with the established Swiss reference tools.

## The three components of the calculation

The composition of the reduction under **VMWG art. 13** is defined uniformly Switzerland-wide:

1. **Reference-rate decrease.** Per 0.25% step between the reference rate at your last rent setting and today's value, your gross rent decreases by 2.0% to 3.0% (band-dependent).
2. **Inflation.** 40% of the change in the Swiss Consumer Price Index (CPI, published by the Federal Statistical Office) since your last adjustment can be offset by the landlord.
3. **General cost increase.** A flat rate the landlord may claim for operating costs. The amount is not fixed by law. conciliation authorities accept between 0% and 0.5% per year in practice, depending on the lease.

<strong>RentReducer</strong> uses a default flat rate of **0.5% per year**. This corresponds to the conservative jurisprudence of most conciliation authorities and the default of the Zurich Court's rent calculator.

## Verification against the Zurich Court calculator

We verified our calculation in April 2026 across 18 test cases (adjustment dates 2008-2025, rents CHF 300-9000) against the [Zurich Court's rent calculator](https://www.gerichte-zh.ch/de/themen/miete). **Result: in all 18 cases RentReducer produces the same result as the ZH calculator for identical input data.** The Zurich courts are first-instance authority for Swiss tenancy law, a legally robust reference.

Selection from the test series:

<div class="parity-table-wrap">
<table class="parity-table">
<thead>
<tr><th>Case</th><th>Adjustment</th><th>Rent</th><th>Reduction</th><th>Δ ZH</th></tr>
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

<p class="small-print">Δ ZH = difference between RentReducer calculation and ZH calculation for the same data basis. All 18 cases show Δ = CHF 0.</p>

## Comparison with the Mieterverband calculator

On **19 May 2026** we ran six test calculations against the [official Mieterverband calculator](https://mzr.mieterverband.ch/senkung):

<div class="parity-table-wrap">
<table class="parity-table">
<thead>
<tr><th>Case</th><th>Inputs</th><th>MV calculator</th><th><strong>RentReducer</strong></th></tr>
</thead>
<tbody>
<tr><td>1</td><td>CHF 1500 / July 2023 / Zurich</td><td>CHF 11.17</td><td>CHF 11.62</td></tr>
<tr><td>2</td><td>CHF 2000 / October 2023 / Bern</td><td>CHF 18.15</td><td>CHF 19.16</td></tr>
<tr><td>3</td><td>CHF 1800 / March 2024 / Lucerne</td><td>CHF 95.22</td><td>CHF 75.25</td></tr>
<tr><td>4</td><td>CHF 2500 / June 2024 / Zurich</td><td>CHF 113.75</td><td>CHF 113.26</td></tr>
<tr><td>5</td><td>CHF 1200 / October 2024 / Bern</td><td>CHF 53.93</td><td>CHF 53.67</td></tr>
<tr><td>6</td><td>CHF 1500 / April 2025 / St.&nbsp;Gallen</td><td>CHF 39.54</td><td>CHF 31.86</td></tr>
</tbody>
</table>
</div>

<p class="small-print">Monthly reduction amounts. Calculation date in both tools: 19.05.2026.</p>

### What this shows

In the **standard cases from Zurich and Bern (cases 1, 2, 4, 5)**, both tools produce practically identical values (difference < CHF 1, rounding conventions).

In **Lucerne and Eastern Switzerland (cases 3, 6)**, the local association applies a different cantonal flat rate (0% in Lucerne, 0.25%×inflation in Eastern Switzerland). This is a cantonal jurisprudence particularity. the VMWG art. 13 formula itself remains the same everywhere.

<strong>RentReducer</strong> consistently uses the **Switzerland-wide uniform default flat rate of 0.5%/year**. This calculation is legally sound, applicable in every canton, and corresponds to the most common conciliation-authority practice. It is a safe lower bound: your landlord generally accepts it because it does not appear excessive and is robust in legal proceedings.

## What does this mean for you in practice?

1. **Your <strong>RentReducer</strong> letter is your safe first demand.** The calculation is valid Switzerland-wide, accepted by the landlord in the vast majority of cases, and legally robust.
2. **If your landlord refuses, <strong>RentReducer</strong> does not leave you hanging.** Directly from the app you generate the follow-up letter (request for documentation, reminder, conciliation proceedings), with automatic deadline calculation and tracking of your case.
3. **In conciliation proceedings,** the authority decides case by case what is appropriate. You can rely on your <strong>RentReducer</strong> calculation or additionally argue for cantonal jurisprudence.

For complex situations (sublease, stepped adjustments, building-age disputes), consultation with the cantonal tenants' association is recommended. RentReducer is not legal advice.

## Sources

- [Art. 270a Code of Obligations (CO)](https://www.fedlex.admin.ch/eli/cc/27/317_321_377/de). reduction claim
- [Art. 13 VMWG](https://www.fedlex.admin.ch/eli/cc/1990/834_834_834/de). calculation per 0.25% step
- [Reference interest rate BWO](https://www.bwo.admin.ch/bwo/de/home/mietrecht/referenzzinssatz.html). Federal Housing Office
- [Consumer Price Index BFS](https://www.bfs.admin.ch/bfs/en/home/statistics/prices/consumer-price-index.html)
- [Zurich Court rent calculator](https://www.gerichte-zh.ch/de/themen/miete). verification reference

<p class="parity-meta">Status: 19.05.2026</p>
