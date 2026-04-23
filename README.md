# yb-water-quality-tool
Web-based tool for assessing pond water quality using a weighted scoring algorithm across 13 physicochemical parameters. Evaluates eutrophication risk based on peer-reviewed thresholds (US EPA, WHO, Boyd 2019). Built with HTML, CSS and JavaScript. Live at water-quality-tool.netlify.app
# Water Quality Assessment Tool

A science-backed, client-side web application for assessing pond water ecosystem 
health — built to translate environmental monitoring knowledge into an accessible 
analytical tool.

🔗 **Live tool:** [water-quality-tool.netlify.app](https://water-quality-tool.netlify.app)

---

## What It Does

Users input measurements for 13 physicochemical parameters and the tool returns:

- A **Water Quality Score (0–100)** calculated using a weighted algorithm
- A classification: Excellent / Good / Moderate / Poor
- An independent **Eutrophication Risk Assessment** (Low / Moderate / High)
- A per-parameter breakdown showing each score contribution

## Parameters Assessed

| Category | Parameters |
|---|---|
| Nutrients | Phosphate, Nitrate, Total Nitrogen, Ammonia |
| Oxygen & Biology | Dissolved Oxygen, Chlorophyll A |
| Physical | pH, Temperature, Conductivity, TDS, Salinity, ORP |

## Scientific Basis

Thresholds grounded in peer-reviewed standards:
- Boyd (2019) — aquaculture and pond water quality
- Carlson Trophic State Index (1977)
- US EPA water quality criteria
- WHO drinking water guidelines

## Built With

- HTML5, CSS3, Vanilla JavaScript
- Client-side only — no backend or data storage
- Deployed via Netlify

## Background

Built independently following an MSc Biotechnology research project 
(Nottingham Trent University) investigating eutrophication risk in pond 
systems through a 12-week physicochemical monitoring programme.

---

*Developed by Yaw Baah — [LinkedIn](https://linkedin.com/in/yaw-baah-92600b22a)*
