
## Project Overview

This smart dashboard visualizes earthquake activity in Japan during September 2017. The application integrates an interactive Mapbox web map with coordinated dynamic charts built using C3.js.

The dashboard demonstrates how spatial data and interactive visual analytics can be combined to enhance geographic understanding and user exploration.

Users can:
- View earthquake locations on an interactive map
- See magnitude represented using proportional symbols
- Click earthquakes to view magnitude values
- Filter map features by selecting magnitude classes in the chart
- Observe dynamic updates based on map extent

---

## Cartographic Design

### Map Type: Proportional Symbol Map

This project uses a **proportional symbol map** to represent earthquake magnitudes.

### Why Proportional Symbols?

A proportional symbol map is appropriate because:

- Earthquakes are **point-based spatial events**
- Magnitude is a **continuous numerical variable**
- Symbol size effectively communicates intensity differences
- It avoids misleading aggregation that could occur with a choropleth map

Circle size and color both scale according to magnitude values, reinforcing visual interpretation.

---

## Dashboard Components

### Interactive Web Map (Mapbox GL JS)

- Displays earthquake locations
- Circle radius and color scaled by magnitude
- Interactive popups display magnitude values
- Map filtering triggered by chart interaction

---

### Coordinated Bar Chart (C3.js)

- Displays earthquake counts by magnitude class
- Dynamically updates based on map extent
- Clicking a bar filters the map to the selected magnitude range

---

### Additional Bar Chart

- Demonstrates categorical comparison
- Built using C3.js
- Enhances the analytical dashboard layout

---

### Stacked Area Chart

- Demonstrates grouped comparative trends
- Built using C3.js area-spline configuration
- Provides additional multi-series visualization within the dashboard

---

## Data Sources

**Earthquake Data:**  
United States Geological Survey (USGS)  
https://earthquake.usgs.gov/earthquakes/

**Basemap:**  
Mapbox Dark Style  
https://www.mapbox.com/

---

## Technologies Used

- Mapbox GL JS
- C3.js
- D3.js
- HTML5
- CSS3
- JavaScript
- GitHub Pages (Deployment)

---

## 📁 Repository Structure
