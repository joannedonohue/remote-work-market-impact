# Remote Work Market Impact

Data analysis of remote work's effects on office vacancy rates, commercial real estate pricing, and transit ridership across 24 major US metros (2019–2023).

---

## Overview

This project investigates how the shift to remote work reshaped urban commercial real estate and commuter behavior across 24 US metropolitan areas from 2019 to 2023. Drawing on Bureau of Labor Statistics employment data and commercial real estate reports, the analysis finds that outcomes diverged significantly by city based on industry composition, pre-pandemic office concentration, housing costs, and local return-to-office mandates.

---

## Key Findings

| Dimension | Finding |
|---|---|
| Office vacancies — tech hubs | Bay Area, Austin, Denver saw **steeper vacancy increases** than national average |
| Office vacancies — finance centers | Manhattan and Chicago showed **greater resilience** relative to tech metros |
| Rent trends | Cities with high pre-pandemic office concentration saw **rent declines**; Sun Belt metros showed **resilience** |
| Transit recovery driver | Strong correlation between **return-to-office mandates** and ridership recovery |
| City variation | Outcomes driven by **industry mix, housing costs, and local policy** |

---

## Geographic Scope

24 US metropolitan areas analyzed:

> Boston · Manhattan · New Jersey · Chicago · Philadelphia · Detroit · Washington DC · Atlanta · Miami · Tampa · Orlando · Charlotte · Nashville · Houston · Dallas · Austin · Denver · Phoenix · Los Angeles · Bay Area · Portland · Seattle · New York · Las Vegas

---

## Methodology

1. Compile BLS remote work and employment metrics across all 24 metros
2. Integrate commercial real estate vacancy and pricing data by city
3. Use transit ridership as an office attendance proxy
4. Cluster cities by recovery trajectory and structural resilience
5. Cross-reference return-to-office mandates with ridership recovery rates
6. Identify industry composition and local policy as key differentiating factors

---

## Tech Stack

| Component | Tool |
|---|---|
| Data analysis | pandas |
| Visualization | Matplotlib |
| Data sources | Bureau of Labor Statistics, commercial real estate reports |
| Notebook environment | Jupyter |
| Language | Python |

---

## Repository Structure

```
remote-work-market-impact/
├── remote_work_market_impact.ipynb              # Main analysis notebook
├── BLS Dataset/                                 # Employment data from BLS
├── Project 1 - Group 2 Presentation.pdf        # Project presentation slides
└── README.md
```

---

## Outcomes

- Documented diverging vacancy and rent trajectories across 24 metros, establishing that tech-heavy cities experienced disproportionately higher commercial vacancy increases
- Quantified the relationship between return-to-office mandates and transit ridership recovery as a proxy for office attendance
- Found Sun Belt metros resilient relative to coastal tech and finance hubs, driven by lower pre-pandemic office concentration and population inflows
- Produced a city-level clustering framework distinguishing recovery trajectories by industry composition and local policy environment

---

## Getting Started

```bash
pip install pandas matplotlib jupyter
jupyter notebook remote_work_market_impact.ipynb
```
