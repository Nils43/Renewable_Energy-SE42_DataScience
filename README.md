
# Global Renewable Energy Build‑out 1971–2015
Trends, leaders, and turning points

Author: Nils Heck  
Course: SE_42 Data Science Basics (CODE University of Applied Sciences, Berlin)  
Date: 19.11.2025  
Contact: nils.heck@code.berlin

---

## Overview
### 1) How did global renewables develop from 1971–2015?
### 2) Which countries had the highest average annual growth rates (1990–2015)?
### 3) When was the largest absolute annual increase worldwide (the year with the
### biggest global delta)?
### 4) Who contributed most to global growth by period?
### 5) Which countries were the earliest to show a sustained turnaround in the
### build‑out of renewables — and how early was that compared to the global
### average?
## Key Questions & Answers

### 1) How did global renewables develop from 1971–2015?
<img width="1310" height="476" alt="image" src="https://github.com/user-attachments/assets/666071d8-8929-4d5f-9f5e-3f90d3d53d16" />

Between 1971 and 2015, the global amount of renewable energy (in KTOE) rose steadily: until around 2000 it increased fairly evenly from roughly 350–360k to about 600–650k KTOE. From the mid‑2000s onward, growth accelerated markedly, reaching around 950k KTOE by 2015, with the strongest year‑on‑year gains occurring between 2010 and 2015.

### 2) Which countries had the highest average annual growth rates (1990–2015)?
<img width="1182" height="940" alt="image" src="https://github.com/user-attachments/assets/0710fc0c-d057-4086-bf55-1a6e6bb147e2" />

From 1990 to 2015, the highest average annual growth rates concentrated in parts of Central/Eastern Europe, with countries like UK, Germany, and Belarus showing the largest
percentage increases. Several African and Asian economies (e.g., Kenya and Vietnam) also posted strong growth, while most OECD countries grew more moderately. Note: extremely high rates often reflect small 1990 baselines, so these leaders are percentage winners rather than the largest absolute contributors.

### 3) When was the largest absolute annual increase worldwide (the year with the
### biggest global delta)?
<img width="1340" height="798" alt="image" src="https://github.com/user-attachments/assets/88d6a2f7-86a2-4a8a-a229-5b1e4cfb8aee" />

The largest absolute year‑over‑year increase in global renewable energy occurred in 2012, when the worldwide total expanded by 72,234 ktoe versus 2011. This surge marks the peak of the acceleration phase visible since the mid‑2000s, reflecting broad, simultaneous scale‑up across multiple regions and technologies rather than a single outlier. It underscores the moment when renewables moved from steady growth to rapid deployment at global scale.

### 4) Who contributed most to global growth by period?
<img width="1212" height="1400" alt="image" src="https://github.com/user-attachments/assets/baa82b6b-537c-4139-9d25-c65028655fac" />

From 1990 to 2000, global growth was led by Nigeria, India, and China, with additional momentum from Indonesia, Ethiopia, and Canada, while Brazil and the United States contributed more moderately. In 2000–2010, China dominated contributions by a wide margin, followed by Brazil and India, with Nigeria and the United States adding substantial gains and countries like Germany, Italy, Indonesia, Ethiopia, and Spain providing smaller but notable increments. Over 2010–2015, leadership shifted toward OECD economies: the United States contributed the most, followed by Germany and the United Kingdom, with Canada, Sweden, and Italy also significant and Japan, Turkey, Chile, and South Korea rounding out the top contributors.

### 5) Which countries were the earliest to show a sustained turnaround in the
### build‑out of renewables — and how early was that compared to the global
### average?
<img width="988" height="1126" alt="image" src="https://github.com/user-attachments/assets/4866f8bf-f78e-45c5-a017-fdcc388c5b01" />


Earliest sustained turnarounds appear well before the global “new normal. ” A first wave of pioneers turned in the late 1950s–mid 1960s (e.g., CHE, ESP, GBR, GRC, ISL, AUS, AUT, DEU), followed by a second wave through the late 1960s. Compared with the global normal year around 1970–71 (vertical line), these pioneers were typically 5–15 years earlier; a long tail of countries only reached sustained expansion in the late 1970s–1990s.

## Methodology (Sustained Turnaround Detection)
How I determined the “new normal”: I reconstructed the global total (sum across ISO3 countries) and smoothed the annual series with a 3‑year window. The global “normal” year is the first year after which at least 4 of the next 5 annual changes are positive (K=5, M=4) a robustness rule that filters out one‑off spikes. We applied the same rule to each country’s
smoothed series to detect its first sustained turnaround, then measured lead/lag versus the global normal (positive lead = earlier than global).

Dataset: https://www.kaggle.com/datasets/imtkaggleteam/renewable-energy-1960-2023




