# https://maapoto.github.io/Bluto_Agriculture_Monitoring/

# Timor-Leste Agriculture Monitoring Map

A web-based map application for visualizing various vegetation and color indices for Timor-Leste using Sentinel Hub satellite imagery. This tool is designed for monitoring agricultural and environmental conditions.

![Screenshot of the application interface showing the map of Timor-Leste with layer controls, a date picker, and a cloud cover slider.]()
*Note: You can replace the line above with a real screenshot of your application.*

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [How to Use](#how-to-use)
- [Credits](#credits)

## Description

This project provides an interactive map interface to monitor agricultural and environmental conditions in Timor-Leste. It leverages Sentinel Hub's WMS (Web Map Service) to display up-to-date satellite imagery with different spectral indices. These indices are useful for assessing vegetation health, water content, and land use.

The application is built as a single, self-contained HTML file, making it lightweight and easy to deploy or use locally without any complex setup.

## Features

- **Interactive Map:** Pan and zoom functionality centered on Timor-Leste, Manatuto, Bluto Agriculcural Field, built with Leaflet.js.
- **Multiple Data Layers:**
    - **Base Map:** OpenStreetMap.
    - **Overlay Layers from Sentinel Hub:**
        - **NDWI (Normalized Difference Water Index):** Highlights water bodies.
        - **NDVI (Normalized Difference Vegetation Index):** Indicates vegetation health.
        - **Moisture Index:** Shows the moisture content in vegetation.
        - **True Color:** Displays natural colors as seen by the human eye.
        - **False Color:** Emphasizes differences in vegetation and land use.
- **Date Selection:** A date picker allows users to view satellite imagery for a specific day.
- **Cloud Cover Filter:** A slider filters out images with high cloud coverage, ensuring clearer views.
- **Drawing & Measurement Tools:**
    - Measure distances using polylines.
    - Calculate areas using polygons.
    - Edit or delete created drawings.
- **User-Friendly Controls:** All controls (layer selection, date picker, cloud cover) are integrated directly into the map interface for easy access.

## Technologies Used

- **Frontend:** HTML5, CSS3, JavaScript
- **Mapping Library:** [Leaflet.js](https://leafletjs.com/)
- **Plugins:** [Leaflet.draw](https://github.com/Leaflet/Leaflet.draw)
- **Data Source:** [Sentinel Hub WMS](https://www.sentinel-hub.com/)

## How to Use

No installation or build process is required.

1.  Clone or download this repository.
2.  Open the `index.html` file in a modern web browser (like Google Chrome, Mozilla Firefox, or Microsoft Edge).

That's it! The application will load, and you can start exploring the map and its features.

## Credits

- **Map Data:** © OpenStreetMap contributors.
- **Satellite Imagery:** Provided by Sentinel Hub.
- **Mapping Library:** Leaflet - an open-source JavaScript library for interactive maps.

---

This project was created to provide an accessible tool for agricultural monitoring in Timor-Leste.