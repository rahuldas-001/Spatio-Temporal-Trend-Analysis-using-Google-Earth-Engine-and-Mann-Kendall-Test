# Spatio-Temporal-Trend-Analysis-using-Google-Earth-Engine-and-Mann-Kendall-Test


This project focuses on analyzing long-term environmental trends using Earth Observation datasets through Google Earth Engine (GEE) and the non-parametric **Mann-Kendall trend test**. The analysis integrates geospatial processing with Python-based statistical workflows.

## 📌 Project Goals

- 🔍 Detect monotonic trends in hydrometeorological variables (e.g., rainfall, NDVI, surface water extent).
- 🛰️ Use Google Earth Engine for efficient multi-temporal data access and ROI-based extraction.
- 📊 Apply the **Mann-Kendall trend test** using the `pymannkendall` package.
- 📍 Visualize spatial trends over user-defined regions with `geemap` and `geopandas`.

## 🛠️ Tools & Technologies

| Tool          | Purpose                             |
|---------------|-------------------------------------|
| Google Earth Engine | Remote sensing data access & processing |
| geemap        | Interactive map visualization in Jupyter |
| pymannkendall | Trend detection in time series      |
| xarray        | Handling multi-dimensional arrays   |
| geopandas     | Vector spatial data processing      |
| shapely       | Geometric operations on ROIs        |

## 🚀 How It Works

1. Authenticate and initialize GEE with `xee`.
2. Define an ROI interactively using `geemap`.
3. Fetch satellite-derived variables over time using GEE.
4. Convert the extracted data to `xarray` and apply the **Mann-Kendall test**.
5. Visualize spatial patterns and time series using `matplotlib` and `geemap`.
