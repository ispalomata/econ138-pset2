# Problem Set 2: Geospatial Mapping in Development Economics

This repository contains replication code and output maps for **Problem Set 2**, focused on recreating geospatial figures from four published development economics papers. Each figure has been reproduced using open-source spatial data and Python-based geospatial tools.

> **Goal:** Accurately visualize and interpret key spatial patterns in infrastructure, population, and survey data across South Africa, Ethiopia, Vietnam, and Brazil.

---

## Project Structure


---

## Replicated Figures

| Country        | Figure | Source Citation                                                                 | Description                                                  |
|----------------|--------|----------------------------------------------------------------------------------|--------------------------------------------------------------|
| South Africa   | Fig. 2 | Mettetal (2019), *JDE*                                                           | Hydrodams over population density (raster substitute)        |
| Ethiopia       | Fig. 4 | Fried & Lagakos (2021), *Regional Science & Urban Economics*                     | ERSS villages + WorldPop raster                              |
| Vietnam        | Fig. 10| Balboni (2025), *American Economic Review*                                       | Road classes by type + major coastal cities                  |
| Brazil         | Fig. 1 | Morten & Oliveira (2024), *AEJ: Applied Economics*                               | Major roads + cities in Centro-Oeste, focused on Brasília    |

---

## 🛠 Tools & Technologies

- Python 3.x  
- JupyterLab  
- **Geo-processing:** `geopandas`, `shapely`, `rasterio`, `rasterstats`  
- **Visualization:** `matplotlib`, `contextily`  
- **Data handling:** `pandas`, `numpy`

---

## Code & Style Guidelines

- Written in clean, modular Python with comments and markdown cells
- Paths follow global, absolute structure (`D:/Problem Set 2/...`)
- Style conforms to **PEP8** with logical section headers
- All figures clipped, reprojected, and layered with CRS alignment

---

## Outputs

- Final plots match (or closely resemble) original published figures
- Enhanced visual clarity with legends, colormaps, and clipped rasters
- Uses 2020 population density data from **WorldPop** (UN-adjusted)

---

## Data Sources

- [WorldPop](https://www.worldpop.org/)
- [Geofabrik (OSM Roads)](https://download.geofabrik.de/)
- [HDX / World Bank / ERSS](https://data.humdata.org/)
- Instructor’s shared [Google Drive folder](https://drive.google.com/)

---

## Academic Context

This project was completed as part of the course **Econ 138 WZQ: Data Science for Economists**.  
All maps and data are used strictly for academic and non-commercial purposes.

---

## Acknowledgments

Special thanks to the course instructor for data access, and to the open-source community for the tools that made this replication possible.

---

