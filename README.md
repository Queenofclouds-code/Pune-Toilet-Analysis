# Pune Public Toilet Accessibility & Highway Coverage Analysis

This project analyzes the accessibility of public toilets in Pune, India, with a special focus on their proximity to highways. It identifies underserved regions using buffer, network, and difference analysis, and proposes new toilet locations to support urban sanitation goals under initiatives like Swachh Bharat Mission.

## 📍 Project Objective

To improve public sanitation planning by identifying areas where highways are not adequately served by public toilets. This analysis can guide authorities in strategic infrastructure placement.

## 🧰 Tools & Technologies

- **GIS Software:** QGIS (Desktop)
- **Web Map Publishing:** QGIS Cloud
- **Database:** PostgreSQL + PostGIS
- **Data Sources:**
  - Public Toilets: Open City Urban Data Portal (Pune)
  - Highways: OpenStreetMap via QuickOSM Plugin

## 🔍 Geospatial Analysis Performed

- **Buffer Analysis:**
  - Created 500m buffers around public toilets and highways
  - Reprojected layers to EPSG:32643 for accurate distance in meters

- **Network Analysis:**
  - Assessed walking accessibility from highways to toilets

- **Difference Analysis:**
  - Identified highway segments without nearby toilets
  - Red dash-dotted lines: highways lacking access
  - Green dotted lines: highways within 500m of a toilet

- **Heatmap (KDE):**
  - Toilet density map with radius 500m in EPSG:32643
  - Grayscale styling to highlight low-to-high density zones

## 🗺️ Map Layers (Styled in QGIS)

- **Pune_toilets:** 547 point features, dark purple icons
- **Highways_with_toilets:** Green dotted lines
- **No_highways_with_toilets:** Red dash-dotted lines
- **500m Buffers:** Yellow (highways), Green (toilets)
- **Heatmap:** Grayscale (light to dark)

## 🖼️ Map Layout & Publishing

- Created a professional QGIS layout with:
  - Title: *“Pune Public Toilet Accessibility: Highway Coverage Analysis”*
  - Legend, scale bar, north arrow, and grouped layer names
  - Added a text box citing data sources
- 📤 Published as an interactive map using **QGIS Cloud**

## 🚫 Deployment Status

> ✅ Published successfully on QGIS Cloud.  
> ❌ No standalone backend or web app developed for this project.

## 📄 Report

This project is documented in a detailed PDF titled **“Analysis Of Pune Toilets.pdf”** (layout export from QGIS).

## 👩‍💻 Author

**Meghaj Kamble**  
📍 Pune, Maharashtra  
📧 meghaj9096@gmail.com  
🔗 [GitHub](https://github.com/Queenofclouds-code)

## 📌 Credits

- Open City Urban Data Portal (Pune)  
- OpenStreetMap (via QuickOSM)  
- QGIS & QGIS Cloud

## 📜 License

For academic and demonstration purposes.
