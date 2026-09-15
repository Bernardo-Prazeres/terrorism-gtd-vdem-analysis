# Between Violence and Politics: An Analysis of Global Terrorism

Academic project for Visual Analytics and Data Visualization (VAD), NOVA FCT, 2026.

## Objective

Explore the dynamics of global terrorism through a data-driven approach, combining the **Global Terrorism Database (GTD)** with political indicators from the **Varieties of Democracy Project (V-Dem)**, to answer three research questions:

1. What is the lifecycle of a terrorist group (emergence, activity peaks, decline)?
2. How do attack type, target type, and region jointly influence the lethality and success of terrorist attacks?
3. How do political regimes shape the frequency, lethality, and success of terrorist attacks?

## Datasets

- **GTD** (1970–2017, excluding 1993) — 181,692 global terrorism events
- **V-Dem Core v16** — country-year political and institutional indicators (democracy, civil liberties, government violence, corruption, etc.)

## Methodology

- Cleaning and harmonization of both datasets (country name standardization, spatial and temporal hierarchies)
- Exploratory data analysis (EDA)
- Construction of **8 interactive dashboards in Tableau**, covering:
  1. Lifecycle of terrorist groups
  2. Tactical profile (weapons and attack types)
  3. Global landscape (scale, distribution, mortality)
  4. Attack dynamics and impact (lethality, success, victims)
  5–8. Relationship between political regimes and attack frequency, lethality, and success

## Key findings

- The post-2010 period is dominated by a small number of extraordinarily lethal groups (ISIL, Boko Haram, the Taliban)
- Bombing/Explosion is consistently the most frequent attack method
- Attack success rates are uniformly high (>84%) across all regions
- **Electoral autocracies** are associated with the highest attack frequencies; **closed autocracies**, despite fewer events, produce the most lethal individual incidents
- The relationship between political regime and terrorism is non-linear: the greatest risk is concentrated in states undergoing political transition

## Authors

Bernardo Prazeres, Inês Pinto, Leonor Afonso — NOVA FCT

## Files

- `paper.pdf` — full project report, with all figures and dashboards described
