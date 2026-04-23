# Water Quality Assessment Tool

An interactive browser-based tool to assess **freshwater pond health** and **eutrophication risk** using 13 physicochemical parameters and a peer-reviewed weighted scoring model.

🌊 **Live tool → [ybaah-biotech.github.io/yb-water-quality-tool](https://ybaah-biotech.github.io/yb-water-quality-tool)**

---

## What it does

- Accepts 13 measured parameters (DO, phosphate, nitrate, chlorophyll A, ammonia, total nitrogen, pH, temperature, EC, TDS, salinity, ORP)
- Classifies each parameter as Good / Moderate / Poor against peer-reviewed thresholds
- Calculates a **Water Quality Score (WQS) from 0–100** using a weighted model
- Outputs an independent **Eutrophication Risk rating** (Low / Moderate / High)
- Displays results as an animated arc gauge + colour-coded parameter breakdown

## Scoring model

| Classification | Score |
|---|---|
| 80–100 | Excellent |
| 60–80  | Good |
| 40–60  | Moderate |
| <40    | Poor |

## Files

| File | Description |
|---|---|
| `index.html` | Self-contained web tool (HTML/CSS/JS, no dependencies) |
| `water_quality_data.xlsx` | Parameter thresholds, scoring model & 3 example scenarios |
| `linkedin_summary.pptx` | 6-slide project summary deck |
| `linkedin_posts.txt` | Draft LinkedIn posts for project dissemination |
| `notion_content.txt` | Ready-to-paste Notion content (Sections 3, 5, 6) |

## Thresholds & sources

Boyd (2019) · Carlson TSI (1977) · Elser et al. (2022) · US EPA · WHO · MSc experimental data

---

*MSc Environmental Monitoring Project · 2025*
