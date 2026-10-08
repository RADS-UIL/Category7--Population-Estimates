# Population Estimates

Gridded and catchment-based population estimation for planning health and development programmes.

## Projects

| # | Project | File | Resolution |
|---|---------|------|------------|
| 1 | [Gridded Population Map, Lasbela](#1-gridded-population-map-lasbela-district) | `population_map_lasbela 100m.html` | 100 m |
| 2 | [Gridded Population Map, Pakistan](#2-gridded-population-map-pakistan) | `pakistan_population_map_1km.html` | 1 km |

Open either `.html` file in a web browser to explore the interactive map.

---

## 1. Gridded Population Map, Lasbela District

**Automated Population Estimation on a 100 m x 100 m Grid, Lasbela, Balochistan**

> Location: Lasbela, Balochistan, Pakistan · Year: 2023 estimates

An interactive map of Lasbela district built from an automated population-estimation workflow. Population is estimated for every 100 m grid cell, then summed for any block or area. Indicators include total population by sex, under-1, under-2, under-5 and women of reproductive age (MWRA).

**Key results**

- 641,021 people across 14,968 km2, about 43 people per km2.
- 1,463,040 grid cells at about 100 m resolution. The map merges cells for fast display, but every total is summed from the full-resolution cells.
- 99,547 children under 5, 30,205 under 2, 11,962 under 1 and 95,281 MWRA.
- Near-even sex split: 328,761 male and 312,260 female.

---

## 2. Gridded Population Map, Pakistan

**Population Estimates for Pakistan at 1 km Resolution**

> Location: Pakistan · Year: 2023
An interactive national population map produced with the same automated workflow, drawn at 1 km resolution so the whole country can be viewed in one file. Population figures are still summed from the full-resolution grid for each administrative area.

**Key results**

- Population total for Pakistan: _add here_
- Number of districts / administrative areas covered: _add here_ (area boundary: ADM3, 577 areas)
- Indicators included: _add here_

---

## About the workflow

The population-estimation tool takes any boundary (shapefile, GeoJSON, KML, zip or coordinate list), matches the population grid to each area, and produces area totals (CSV and Excel) and an interactive map. The map resolution can be coarsened for very wide areas, such as the whole country, without changing the population figures.
