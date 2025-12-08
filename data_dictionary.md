# Data Dictionary

## Climate Disaster Events Dataset

**File:** `global_climate_events_economic_impact_2020_2025.csv`  
**Records:** 3,000 disaster events  
**Time Period:** 2020-2025  
**SHA-256:** `27eb23bf938ea866120068dae9ccd3f0539bab39b02cd475f42511950f48328e`

| Variable | Type | Description | Range |
|----------|------|-------------|-------|
| event_id | VARCHAR | Unique disaster identifier | EVXXXXX |
| date | DATE | Date of disaster | 2020-01-01 to 2025 |
| year | INTEGER | Year | 2020-2025 |
| month | INTEGER | Month | 1-12 |
| country | VARCHAR | Country where disaster occurred | Various |
| event_type | VARCHAR | Type of disaster | Tsunami, Hurricane, Drought, Heatwave, Wildfire, etc. |
| severity | INTEGER | Severity rating | 1-10 (1=minor, 10=catastrophic) |
| duration_days | INTEGER | Duration of event | 0-115 days |
| affected_population | INTEGER | Number of people affected | 622 - 56,248,320 |
| deaths | INTEGER | Fatalities | 0-117 |
| injuries | INTEGER | Injuries | 0-734 |
| economic_impact_million_usd | DOUBLE | Direct economic damage | 0 - 718.21 million USD |
| infrastructure_damage_score | DOUBLE | Infrastructure damage | 0-100 |
| response_time_hours | INTEGER | Time to emergency response | Hours |
| international_aid_million_usd | DOUBLE | Aid received | 0+ million USD |
| latitude | DOUBLE | Latitude | -90 to 90 |
| longitude | DOUBLE | Longitude | -180 to 180 |
| total_casualties | INTEGER | Deaths + injuries | Computed |
| impact_per_capita | DOUBLE | Impact per affected person | Computed |
| aid_percentage | DOUBLE | Aid as % of economic impact | Computed |

---

## World GDP and CO2 Emissions Dataset

**File:** `World_GDP_Population_CO2_Emissions_Dataset.csv`  
**Records:** 46 years  
**Time Period:** 1977-2022  
**SHA-256:** `1d5b4ae7c57914b02df77a37fcf8201c1c9179d46c1c7af3cf4e17ed8e3527ca`

| Variable | Type | Description | Range |
|----------|------|-------------|-------|
| year | INTEGER | Year | 1977-2022 |
| gdp_real_usd | DOUBLE | Global GDP (constant USD) | 24-90.8 trillion |
| gdp_growth_pct | DOUBLE | GDP growth rate | -2.88% to 6.35% |
| gdp_per_capita_usd | INTEGER | GDP per person | 5,685 - 11,317 USD |
| world_population | BIGINT | Total world population | 4.2 - 8.0 billion |
| net_change | BIGINT | Annual population change | Persons |
| population_change_pct | DOUBLE | Population growth rate | 0.84% - 1.85% |
| co2_tons | BIGINT | Total CO2 emissions | 19-38.5 billion tons |
| co2_change | DOUBLE | CO2 change rate | -4.97% to 6.12% |
| co2_per_capita | DOUBLE | CO2 per person | 4.03 - 4.95 tons |
| population_density_p_km2 | INTEGER | Population density | 28-54 persons/km² |

---

## Integrated Dataset

**File:** `integrated_yearly.csv`  
**Created by:** Joining disaster and GDP data on year

| Variable | Source | Description |
|----------|--------|-------------|
| year | Both | Year |
| n_events | Disasters | Number of events in year |
| total_econ_impact_musd | Disasters | Total economic impact |
| avg_severity | Disasters | Average severity |
| total_deaths | Disasters | Total deaths |
| total_injuries | Disasters | Total injuries |
| total_affected | Disasters | Total people affected |
| gdp_real_usd | GDP | Global GDP |
| gdp_growth_pct | GDP | GDP growth rate |
| gdp_per_capita_usd | GDP | GDP per capita |
| world_population | GDP | World population |
| population_change_pct | GDP | Population growth |
| co2_tons | GDP | CO2 emissions |
| co2_change | GDP | CO2 change rate |
| co2_per_capita | GDP | CO2 per capita |
| population_density_p_km2 | GDP | Population density |

---

## Data Quality Notes

- **Missing Values:** Deaths, injuries, and aid filled with 0 when unreported
- **Integration:** Only 2020-2022 has both disaster and GDP data
- **Derived Variables:** `impact_per_person_usd` calculated as economic impact / affected population
- **Validation:** Severity constrained to 1-10, economic values non-negative

---

**Last Updated:** 2025-12-07
