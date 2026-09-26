# ⚡ Project VoltMatrix: EV Swapping Network Diagnostic & Capital Allocation Roadmap

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Hackathon](https://img.shields.io/badge/Gradient%20Learnings-Data%20Analytics%20Hackathon-orange.svg)](#)

An end-to-end diagnostic analytics framework investigating the operational "growth trap" of **VoltRelay**, an urban electric vehicle (EV) battery-swapping network operating 152 stations across 6 Indian metropolitan hubs.

---

## 📌 Executive Summary

Over an 18-month operational window, VoltRelay expanded its physical footprint by **65.2% (92 → 152 stations)**, facilitating over **3.8M+ battery swap events**[cite: 1]. Despite aggressive top-line growth, net margin per swap collapsed into negative territory, and monthly customer support escalations surged **8.6x (from 665 to 5,723 tickets/month)**[cite: 1, 3].

Leadership initially prepared to deploy capital toward constructing 60 additional stations, presuming an infrastructure shortage[cite: 1]. **Project VoltMatrix** refutes this premise: through multi-table telemetry diagnostics, we proved that network failure was driven by **cell-level battery degradation**, **ambient thermal throttling**, and **unhedged B2B commercial discounting**[cite: 1].

---

## 🔍 Core Analytical Discoveries

### 1. The Primary Defect: Catastrophic Hardware Failure (Kyron Supplier)
* Evaluated 6,500 battery packs across three suppliers (Cellora, Amptek, Kyron)[cite: 1, 3].
* **Cellora & Amptek** maintained high asset integrity (~81% State of Health [SoH]) with **0 premature retirements**[cite: 1, 3].
* **Kyron** suffered an **87.8% catastrophic failure rate (1,438 premature pack retirements)**, erasing **22.1% of network battery capacity** and driving severe station stock-outs[cite: 1, 3].

### 2. Environmental Thermal Throttling
* In high-heat northern corridors (Jaipur & Delhi NCR, experiencing 72 and 62 heat alert days >40°C), legacy Gen1 chargers suffered severe thermal lockouts[cite: 1, 2, 7].
* Battery pack turnaround times doubled from **45 to 90+ minutes**, starving stations precisely during evening commercial peak hours.

### 3. Commercial Margin Leakage
* A November 2024 contract amendment granted delivery fleet partner **ZipDrop** an unhedged 28% volume discount while completely waiving peak demand surcharges[cite: 1].
* Fleet drivers concentrated swaps during high-tariff grid hours, turning every completed swap into a subsidized operational loss[cite: 1].

---

## 📊 Visual Exhibits

| Exhibit | Title | Key Insight |
| :--- | :--- | :--- |
| **Exhibit 1** | Battery Degradation & Supplier Audit | Proves Kyron's 1,438 premature failures vs. 0 failures for Cellora/Amptek[cite: 3]. |
| **Exhibit 2** | Customer Support Escalations Timeline | Documents the 860% explosion in monthly tickets (665 → 5,723)[cite: 6, 7]. |
| **Exhibit 3** | Thermal Stress & Grid Outage Profile | Correlates extreme heat days (>40°C) with charger lockout bottlenecks in Jaipur & Delhi[cite: 1, 7]. |

---

## 🛠️ Strategic Capital Reallocation Roadmap

We provide a definitive capital reallocation verdict: **Reject physical station deployment** and redistribute available capital into unit-level asset restoration[cite: 1].

```text
┌────────────────────────────────────────────────────────────────────────┐
│               CAPITAL REALLOCATION FRAMEWORK (100%)                    │
├────────────────────────────────┬───────────────────────────────────────┤
│ 55% Capital Allocation         │ Procure 2,000 Grade-A battery packs   │
│                                │ from Cellora & Amptek (target 1.8 SDR)│
├────────────────────────────────┼───────────────────────────────────────┤
│ 25% Capital Allocation         │ Retrofit active cooling & BMS firmware│
│                                │ on 51 Gen1 stations in Jaipur & Delhi │
├────────────────────────────────┼───────────────────────────────────────┤
│ 20% Capital Allocation         │ Restructure B2B contracts: reinstate  │
│                                │ peak surcharges & cap discounts at 14%│
└────────────────────────────────┴───────────────────────────────────────┘
