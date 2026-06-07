# Snow-variation-analysis
This project investigates seasonal snow cover dynamics and snow melt rates across three climatically distinct mountainous regions:

Himachal Pradesh, India (Himalayan Region)
Valais, Switzerland (Alpine Region)
Alaska, USA (High-Latitude Snow Region)

Using NASA's MODIS Terra Snow Cover Daily Global 500m dataset (MOD10A1 Version 6.1) within Google Earth Engine, the study analyzes changes in snow cover during winter, spring, and early summer and estimates regional snow melt rates.

Methodology

Collected MODIS Terra Snow Cover Daily Global 500m (MOD10A1 Version 6.1) data from Google Earth Engine.

Selected three study regions:
Himachal Pradesh (India)
Valais (Switzerland)
Alaska (USA)

Filtered satellite imagery for January, March, and June 2025.

Applied quality masks using the NDSI_Snow_Cover_Basic_QA band to remove low-quality observations.

Generated monthly average snow-cover composites for each region.

Calculated mean snow-cover percentage using regional statistics.

Compared seasonal snow-cover variation across all three regions.

Computed snow melt rates for:
January → March
March → June

Analyzed differences in snow persistence and melting behavior between the Himalayas, Alps, and Alaska.

Technologies Used

Google Earth Engine
JavaScript
MODIS MOD10A1 Dataset
Remote Sensing
Geospatial Analysis
