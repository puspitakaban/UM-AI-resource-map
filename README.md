# Introduction
This project maps AI resources across the three campuses of the University of Michigan — Ann Arbor, Dearborn, and Flint. The goal is to provide an interactive, spatial overview of organizations, labs, and facilities that offer AI-related services and research support across the university.



# Framework
The map is built using Leaflet.js, a lightweight open-source JavaScript library for interactive maps. The interface includes a left sidebar for filtering and navigation, and a right sidebar that displays detailed information when a resource building is selected.

# Features
- Interactive map centered on the University of Michigan campuses
- Building footprints color-coded by AI resource availability
- Hover tooltip showing building names
- Click on an AI resource building to view organization details on right sidebar
- Filter buildings by service category using a multi-select accordion 
- Campus extent buttons to quickly navigate between campuses

# Data
- **Building footprints** — Shapefile provided by the University of Michigan Facilities & Operations Information Services, accessed via ArcGIS Online ([link](https://www.arcgis.com/home/item.html?id=ba25642ae276429b8664dda39ba261e3)). Last updated July 8, 2025.
- 


## Project Structure
```
um-ai-resource-map/
├── index.html
├── README.md
└── map-data/
    └── um-building-footprint-edited.geojson
```