# Markov regime report

Updated 2026-11-04 16:10 UTC · 10 years of daily data · 20-day window · ±2% threshold

Each day is labelled **Bull**, **Bear** or **Sideways** from the trailing return. *Long-run mix* is the share of time the model expects in each regime. *Stays* is the chance a regime continues the next day. *Strategy* goes long in Bull-leaning states and short in Bear-leaning ones, re-fitted every day with no lookahead; *B&H* is simply holding the asset over the same days. Backtests are historical, not forward-looking, and exclude trading costs.

![Long-run regime mix](charts/_comparison_long_run_mix.png)

## Table

| Ticker | Now | Bear | Sideways | Bull | Bear stays | Bull stays | Sharpe: strategy | Sharpe: B&H | Max DD: strategy | Max DD: B&H | Data from |
|---|---|---|---|---|---|---|---|---|---|---|---|
| [VOO](#voo) | Bear | 17.9% | 34.9% | 47.2% | 86.0% | 89.0% | 0.24 | 0.81 | -33% | -34% | 2016-11-04 |
| [VTI](#vti) | Bear | 18.6% | 34.9% | 46.5% | 86.6% | 87.9% | 0.31 | 0.78 | -38% | -35% | 2016-11-04 |
| [EWT](#ewt) | Bear | 24.7% | 27.4% | 47.9% | 85.0% | 89.8% | 0.37 | 0.81 | -53% | -39% | 2016-11-04 |
| [SHY](#shy) | Sideways | 0.0% | 99.8% | 0.2% | 0.0% | 40.0% | 0.72 | 1.11 | -6% | -6% | 2016-11-04 |
| [SGOV](#sgov) | Sideways | 0.0% | 100.0% | 0.0% | 0.0% | 0.0% | – | 11.38 | 0% | -0% | 2020-06-01 |
| [SCHP](#schp) | Sideways | 5.3% | 88.8% | 5.9% | 72.9% | 69.1% | -0.13 | 0.46 | -25% | -14% | 2016-11-04 |
| [IEF](#ief) | Bull | 11.7% | 76.2% | 12.2% | 80.3% | 79.4% | -0.14 | 0.13 | -23% | -24% | 2016-11-04 |
| [VXUS](#vxus) | Bear | 21.1% | 38.6% | 40.4% | 86.4% | 87.1% | 0.30 | 0.50 | -35% | -36% | 2016-11-04 |
| [QQQM](#qqqm) | Bear | 25.3% | 26.7% | 48.0% | 86.5% | 88.7% | 0.45 | 0.69 | -27% | -35% | 2020-10-13 |
| [AAPL](#aapl) | Sideways | 26.6% | 19.2% | 54.3% | 88.9% | 91.7% | 0.57 | 0.93 | -39% | -39% | 2016-11-04 |
| [GOOG](#goog) | Bear | 27.1% | 21.4% | 51.5% | 86.1% | 90.7% | 0.31 | 0.77 | -64% | -45% | 2016-11-04 |
| [AAAU](#aaau) | Bear | 21.7% | 38.3% | 40.0% | 80.0% | 87.7% | 0.10 | 0.82 | -47% | -28% | 2018-08-15 |
| [MSFT](#msft) | Sideways | 23.2% | 24.9% | 51.9% | 81.6% | 89.5% | -0.38 | 0.88 | -82% | -37% | 2016-11-04 |
| [NVDA](#nvda) | Bear | 29.0% | 13.5% | 57.5% | 84.8% | 91.3% | 0.23 | 1.07 | -75% | -66% | 2016-11-04 |
| [TSLA](#tsla) | Bull | 39.1% | 11.0% | 49.9% | 88.7% | 90.0% | 0.37 | 0.84 | -83% | -74% | 2016-11-04 |
| [SPOT](#spot) | Bull | 37.8% | 13.5% | 48.7% | 88.0% | 90.3% | -0.11 | 0.64 | -91% | -81% | 2018-04-03 |
| [SNDK](#sndk) | Bear | 25.9% | 7.0% | 67.1% | 90.5% | 95.6% | 1.92 | 1.35 | -43% | -56% | 2025-02-13 |
| [NKE](#nke) | Bull | 36.4% | 21.6% | 42.0% | 86.6% | 87.3% | -0.06 | 0.09 | -69% | -79% | 2016-11-04 |
| [MA](#ma) | Bull | 24.1% | 26.0% | 49.9% | 82.9% | 90.2% | -0.33 | 0.74 | -80% | -41% | 2016-11-04 |
| [XLE](#xle) | Bull | 30.6% | 25.7% | 43.7% | 86.0% | 89.6% | 0.06 | 0.52 | -68% | -67% | 2016-11-04 |
| [RSP](#rsp) | Bull | 19.8% | 36.4% | 43.8% | 88.4% | 87.9% | 0.35 | 0.66 | -37% | -39% | 2016-11-04 |
| [VTV](#vtv) | Bull | 17.5% | 38.6% | 44.0% | 84.1% | 89.3% | 0.31 | 0.75 | -31% | -37% | 2016-11-04 |
| [SCHD](#schd) | Bull | 18.8% | 37.6% | 43.6% | 84.6% | 88.8% | 0.21 | 0.78 | -35% | -33% | 2016-11-04 |
| [HYG](#hyg) | Sideways | 7.9% | 81.2% | 10.8% | 78.4% | 80.5% | -0.01 | 0.49 | -31% | -22% | 2016-11-04 |
| [TLT](#tlt) | Bull | 28.3% | 44.2% | 27.5% | 85.3% | 84.7% | -0.13 | -0.06 | -42% | -48% | 2016-11-04 |
| [VGIT](#vgit) | Sideways | 4.7% | 89.4% | 5.9% | 78.0% | 78.4% | 0.35 | 0.30 | -14% | -16% | 2016-11-04 |
| [XLU](#xlu) | Bull | 24.5% | 33.2% | 42.2% | 84.3% | 88.1% | 0.04 | 0.51 | -57% | -36% | 2016-11-04 |
| [EQAL](#eqal) | Sideways | 21.3% | 35.8% | 42.8% | 88.4% | 87.7% | 0.44 | 0.58 | -27% | -40% | 2016-11-04 |
| [KSA](#ksa) | Bear | 27.9% | 33.3% | 38.8% | 87.3% | 87.5% | 0.26 | 0.40 | -37% | -41% | 2016-11-04 |
| [2222.SR](#2222.sr) | Sideways | 26.1% | 45.7% | 28.2% | 87.8% | 87.0% | 0.33 | 0.25 | -23% | -29% | 2019-12-11 |

## Charts

### VOO

![VOO](charts/VOO.png)

### VTI

![VTI](charts/VTI.png)

### EWT

![EWT](charts/EWT.png)

### SHY

![SHY](charts/SHY.png)

### SGOV

![SGOV](charts/SGOV.png)

### SCHP

![SCHP](charts/SCHP.png)

### IEF

![IEF](charts/IEF.png)

### VXUS

![VXUS](charts/VXUS.png)

### QQQM

![QQQM](charts/QQQM.png)

### AAPL

![AAPL](charts/AAPL.png)

### GOOG

![GOOG](charts/GOOG.png)

### AAAU

![AAAU](charts/AAAU.png)

### MSFT

![MSFT](charts/MSFT.png)

### NVDA

![NVDA](charts/NVDA.png)

### TSLA

![TSLA](charts/TSLA.png)

### SPOT

![SPOT](charts/SPOT.png)

### SNDK

![SNDK](charts/SNDK.png)

### NKE

![NKE](charts/NKE.png)

### MA

![MA](charts/MA.png)

### XLE

![XLE](charts/XLE.png)

### RSP

![RSP](charts/RSP.png)

### VTV

![VTV](charts/VTV.png)

### SCHD

![SCHD](charts/SCHD.png)

### HYG

![HYG](charts/HYG.png)

### TLT

![TLT](charts/TLT.png)

### VGIT

![VGIT](charts/VGIT.png)

### XLU

![XLU](charts/XLU.png)

### EQAL

![EQAL](charts/EQAL.png)

### KSA

![KSA](charts/KSA.png)

### 2222.SR

![2222.SR](charts/2222.SR.png)
