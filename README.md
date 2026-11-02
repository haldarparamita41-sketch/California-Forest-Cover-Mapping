# California Forest Cover Mapping Using Google Earth Engine

## Project Overview
This project focuses on identifying and mapping forest cover in California, USA, using satellite imagery and geospatial analysis in Google Earth Engine (GEE).

The project uses Sentinel-2 satellite data to study vegetation conditions and distinguish forest-covered areas from non-forest areas.

## Objectives
- To analyse satellite imagery for forest cover identification.
- To calculate vegetation indices using Sentinel-2 data.
- To distinguish forest and non-forest areas.
- To create a thematic forest cover map of California.

## Data and Tools
- **Satellite Data:** Sentinel-2
- **Platform:** Google Earth Engine
- **Programming Language:** JavaScript
- **Techniques:** Vegetation Index Analysis and Threshold-Based Classification

## Methodology
1. Selected the study area in California, USA.
2. Accessed Sentinel-2 satellite imagery for 2025.
3. Applied cloud filtering and image processing.
4. Used spectral bands to calculate vegetation indices.
5. Applied an NDVI threshold of 0.5 to identify forest and non-forest areas.
6. Analysed and visualised the classified results.

## Results
The NDVI-based classification produced the following results:

- **Forest pixels:** 3,228
- **Non-forest pixels:** 179,211

The classification results were also evaluated using test data. The reported test accuracy was 100%.

*Note: The accuracy value should be interpreted in the context of the available test samples and validation method.*

## Skills Demonstrated
- Google Earth Engine
- Sentinel-2 Satellite Data Analysis
- NDVI Calculation
- Forest Cover Mapping
- Geospatial Data Processing
- Thematic Map Preparation

## Repository Contents
- `California.ipynb` — Project notebook containing the analysis workflow.

## Project Purpose
This project helped develop practical skills in satellite image analysis, vegetation mapping, and geospatial data interpretation using Google Earth Engine.
