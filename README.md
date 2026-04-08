# Cruise industry data: ecological and economic analysis

Supporting data repository for the essay Rethinking Vacations in an Era of Immobility — submitted as part of the Master's programme in Degrowth, Ecology, Economics and Policy at Universitat Autònoma de Barcelona.

---

## What this repository contains

This repository compiles, processes and visualizes data on the global cruise industry to support a critical political economy argument: that cruise tourism is one of capitalism most concentrated expressions — oligopolistic, ecologically extractive, and structurally dependent on continuous growth.

The analysis draws on frameworks from:

- Fletcher, Murray, Blanco-Romero & Blázquez-Salom (2019). Tourism and degrowth: an emerging agenda for research and praxis. *Journal of Sustainable Tourism*.
- Blanco-Romero, Blázquez-Salom & Fletcher (2023). Fair vs. fake touristic degrowth. *Tourism Recreation Research*.
- Murray et al. (2023). Tourism and degrowth. *Tourism Geographies*.
- Bianchi & Milano (2024). Polycrisis and the metamorphosis of tourism capitalism. *Annals of Tourism Research*.

---

## Repository structure

```
cruise_degrowth/
├── data/
│   ├── passengers.csv              # Global cruise passengers 1990–2025 (CLIA)
│   ├── emissions_per_line.csv      # CO₂/nmi by cruise line (EU MRV 2023)
│   ├── emissions_comparative.csv   # Corporate totals & comparative daily footprints
│   └── market_concentration.csv    # Market share by parent corporation
│
├── notebooks/
│   ├── 01_growth.ipynb             # Passenger growth visualization
│   ├── 02_emissions.ipynb          # Emissions per line + comparative harm
│   └── 03_market.ipynb             # Market concentration (donut + bar)
│
├── figures/
│   ├── fig_growth.png / .html
│   ├── fig_emissions_per_line.png / .html
│   ├── fig_emissions_comparison.png
│   └── fig_market_concentration.png / .html
│
└── README.md
```

---

## Key findings

| Indicator | Value | Source |
|---|---|---|
| Cruise passengers 1990 | 3.8 million | CLIA |
| Cruise passengers 2024 | 34.6 million | CLIA |
| Growth 1990–2024 | +810% | Calculated |
| Carnival Corp CO₂ (2023) | 9.5 million tonnes | Transport & Environment |
| Glasgow city CO₂ (2021) | 2.43 million tonnes | Glasgow City Council |
| Cruise passenger daily CO₂ | 421 kg | Friends of the Earth |
| Average European daily CO₂ | ~30 kg | Eurostat |
| Top 4 corps' market share | 78.9% of capacity | Port Economics 2026 |
| Energy: cruise vs hotel night | 12× more | ScienceDaily 2024 |

---

## Data sources

- **CLIA** (2025). *State of the Cruise Industry Report 2025*. Cruise Lines International Association.
- **Notteboom, T., Pallis, A. & Rodrigue, J-P.** (2026). *Port Economics, Management and Policy* (2nd ed.). Routledge.
- **Transport & Environment** (2025). Cruise ship pollution exceeds urban emission levels.
- **EU MRV** (2024). EU MRV verified emissions data for cruise lines in European waters.
- **ICCT** (2025). Cruise the seas or cruise down the road? International Council on Clean Transportation.
- **Friends of the Earth** (2024). Cruise ship report card.
- **ScienceDaily** (2024). Cruise ships must be effectively regulated.
- **Cornell Hotel Sustainability Benchmarking Tool** (2024).
- **Eurostat** (2023). Greenhouse gas emissions per capita.

---

## How to run

Open each notebook in order. Each notebook is self-contained and exports both static `.png` (for PDF embedding) and interactive `.html` (for web linking).

---

## License

Data compiled from public sources for academic research purposes. Visualizations and analysis by Laura Rojas Olarte, 2025–2026.
