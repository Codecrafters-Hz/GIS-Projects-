# Budapest GIS Analysis

This project presents an interactive Geographic Information System (GIS) analysis of **Budapest, Hungary**, using **OpenStreetMap (OSM)** data.  
The goal is to demonstrate how urban spatial data can be extracted, processed, and visualized using Python-based GIS tools.

The project focuses on administrative boundaries and selected points of interest (POIs), displayed on an interactive web map.

---

## 📌 Project Overview

The analysis includes:
- Extraction of Budapest’s administrative boundary
- Retrieval of OpenStreetMap-based spatial data
- Visualization of multiple POI layers on an interactive map
- Layer controls for exploratory spatial analysis

The final output is an **interactive HTML map** suitable for reports, presentations, or further GIS analysis.

---

## 🗺️ Features

- **Administrative Boundary Mapping**
  - Accurate city-level boundary of Budapest

- **Interactive Folium Map**
  - Dark-themed basemap
  - Zoom, pan, and scale control

- **Points of Interest (POIs)**
  - Pubs
  - Gyms & sports facilities
  - Healthcare facilities

- **Layer Control**
  - Toggle individual layers on/off
  - Dynamic map exploration

---

## 🧰 Technologies Used

- **Python 3.9**
- **OSMnx** – OpenStreetMap data extraction and geocoding
- **GeoPandas** – Spatial data handling and analysis
- **Folium** – Interactive web-based maps
- **Matplotlib** – Static spatial visualization
- **OpenStreetMap** – Data source

---

## 📁 Project Structure

```text
budapest-gis-analysis/
│
├── notebooks/
│   └── budapest_analysis.ipynb
│
├── outputs/
│   └── budapest_pubs.html
│
├── data/
│   └── README.md
│
├── requirements.txt
└── README.md
