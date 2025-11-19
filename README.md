
# Global Renewable Energy Build‑out 1971–2015
Trends, leaders, and turning points

Author: Nils Heck  
Course: SE_42 Data Science Basics (CODE University of Applied Sciences, Berlin)  
Date: 27.11.2025  
Contact: nils.heck@code.berlin

---

## Overview
Between 1971 and 2015, global renewable energy (ktoe) grew steadily, with a clear acceleration from the mid‑2000s onward. By 2015, the global total reached ~950k ktoe, and the strongest year‑on‑year gains occurred between 2010 and 2015.

- 1971–2000: Moderate, steady increases (≈350–360k to ≈600–650k ktoe).
- Mid‑2000s–2015: Marked acceleration phase.
- Peak annual jump: 2012 recorded the largest absolute increase.

> Note: Percentage growth leaders often stem from small 1990 baselines and aren’t necessarily the largest absolute contributors.

---

## Key Questions & Answers

### 1) How did global renewables develop from 1971–2015?
- Steady growth up to ~2000, followed by a pronounced acceleration from mid‑2000s.
- By 2015, levels ≈950k ktoe.
- Strongest YoY gains in 2010–2015 window.

### 2) Which countries had the highest average annual growth rates (1990–2015)?
- Top percentage growth concentrated in Central/Eastern Europe (incl. UK, Germany, Belarus).
- Strong growth also in several African and Asian economies (e.g., Kenya, Vietnam).
- Most OECD countries: moderate percentage growth.
- Caution: High percentage rates can reflect small 1990 baselines.

### 3) When was the largest absolute annual increase (global)?
- Year: 2012  
- Absolute delta: 72,234 ktoe vs. 2011  
- Interpretation: Broad, simultaneous scale‑up across regions/technologies; inflection from “steady” to “rapid” deployment.

### 4) Who contributed most to global growth by period?
- 1990–2000:
  - Leaders: Nigeria, India, China
  - Additional momentum: Indonesia, Ethiopia, Canada
  - Moderate: Brazil, United States
- 2000–2010:
  - Dominant: China (by a wide margin)
  - Next: Brazil, India
  - Substantial: Nigeria, United States
  - Notable: Germany, Italy, Indonesia, Ethiopia, Spain
- 2010–2015:
  - Shift to OECD economies
  - Leaders: United States, Germany, United Kingdom
  - Also significant: Canada, Sweden, Italy
  - Rounding out: Japan, Turkey, Chile, South Korea

### 5) Earliest sustained turnaround vs. global average
- First wave (≈late 1950s–mid 1960s): CHE, ESP, GBR, GRC, ISL, AUS, AUT, DEU
- Second wave: late 1960s
- Relative to global “normal” (≈1970–71): pioneers were typically 5–15 years earlier
- Long tail: many countries only achieved sustained expansion in late 1970s–1990s

---

## Methodology (Sustained Turnaround Detection)
- Construct global total by summing ISO3 country series.
- Smooth annual series with a 3‑year moving window.
- Define “new normal” year using a robustness rule K=5, M=4:
  - First year after which at least 4 of the next 5 annual changes are positive.
- Apply the same rule per country on smoothed series.
- Lead/Lag = country’s first sustained turnaround year minus global “normal.”
  - Positive lead = earlier than global.

Dataset: https://www.kaggle.com/datasets/imtkaggleteam/renewable-energy-1960-2023

---

## Visuals (placeholders)
> Replace with your charts/figures once exported.

- Global Renewables (ktoe) 1971–2015: `fig_global_trend.png`
- YoY Change with peak (2012): `fig_yoy_peak_2012.png`
- Growth Rate Leaders (1990–2015): `fig_growth_rate_leaders_map.png`
- Contributors by Period:
  - `fig_contrib_1990_2000.png`
  - `fig_contrib_2000_2010.png`
  - `fig_contrib_2010_2015.png`
- Lead/Lag vs. Global “Normal”: `fig_lead_lag_turnaround.png`

Suggested structure:
