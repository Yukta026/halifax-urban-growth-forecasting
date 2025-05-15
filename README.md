**Halifax Urban Expansion Forecast & Hotspot Mapping**

📍 **Project Title:**
Urban Growth Forecasting and Hotspot Detection in Halifax (2014–2034)
Using Landsat Satellite Imagery, NDBI, Python & Folium

🧠 **About the Project**
This project analyzes and forecasts urban expansion in the Greater Halifax Region using satellite-derived NDBI (Normalized Difference Built-up Index) from Landsat imagery between 2014 and 2024, and projects future growth to 2034. It also identifies top spatial hotspots of rapid urbanization using pixel-wise intensity change.

**Built with:**

🛰️ Landsat 8 C2 Level-1 data

🧪 Python (rasterio, numpy, matplotlib, Prophet, geopandas, folium)

🗺️ Interactive web map (Netlify-deployable via Folium)

🎯 **Objectives**
Track changes in urban development across Halifax from 2014–2024

Forecast urban growth through 2034 using time series modeling

Identify top 5 geographic hotspots of urban intensity increase

Visualize insights on an interactive map for planning and policy applications

🔧** Methodology**
Data Collection
Landsat 8 images (Path 008 / Row 029) from 2014, 2016, 2018, 2020, 2022, and 2024 were downloaded from USGS EarthExplorer.

NDBI Calculation
For each year, NDBI was computed:

𝑁𝐷𝐵𝐼 =  (SWIR − NIR) / (SWIR + NIR)

​ 
**Time Series Forecasting**
Mean NDBI values per year were fed into Prophet to forecast urban growth to 2034.

Hotspot Mapping

NDBI change map: NDBI_2024 - NDBI_2014


🗺️ **Live Map**
🚀 View the urban growth map here:
https://halifax-urban-growth-map.netlify.app/

🚀 View the interactive hotspot map here:
https://urban-growth-hotspots.netlify.app/

📈 Sample Output
Time series plot of mean NDBI growth

Urban intensity change map (2014–2024)

Interactive map showing urban hotspots

