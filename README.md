# Artisanal Mining Site Suitability Scanner — Ashanti Region, Ghana

An automated geospatial pipeline that scores land suitability for 
artisanal mining across the Ashanti Region using satellite data and 
terrain analysis.

## What it does
Combines three inputs to produce a 0–3 suitability score for every 
pixel in the Ashanti Region:
- Terrain slope (SRTM DEM) — flat terrain scores higher
- Vegetation cover (Landsat 9 NDVI) — low vegetation scores higher  
- Proximity to known mining footprints — within 5km scores higher

## Results
High-suitability zones concentrate in the Obuasi-Tarkwa corridor — 
consistent with Ghana's primary gold-producing belt.

## Live map
[View interactive map]((https://joshuaafenyo.github.io/artisanal-mining-suitability-ashanti/)

## Tools
Python · Google Earth Engine · geemap · GeoPandas · Landsat 9 · SRTM DEM
