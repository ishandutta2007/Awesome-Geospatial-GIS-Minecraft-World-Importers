# Awesome-Geospatial-GIS-Minecraft-World-Importers

<p align="center">
  <img src="./assets/banner.svg" alt="Top Geospatial GIS & Minecraft World Importers" width="100%" />
</p>

<p align="center">
  <a href="https://github.com"><img src="https://shields.io" alt="Awesome"/></a>
  <a href="https://discord.gg"><img src="https://shields.io" alt="Discord" /></a>
  <a href="https://github.com"><img src="https://shields.io" alt="GitHub stars" /></a>
  <a href="https://github.com"><img src="https://shields.io" alt="GitHub forks" /></a>
  <a href="https://github.com"><img alt="GitHub followers" src="https://shields.io" /></a>
</p>

# 🌍 Top Geospatial GIS & Minecraft World Importers

**Curated List of SaaS/Commercial Platforms & Open-Source GitHub Projects**  
*Focused on Real-World DEM/LiDAR/OSM-to-Minecraft World Generators (RealWorldMC, Arnis, TerraPlusPlus, GeoBox), Minecraft Region/NBT Editors (Amulet, WorldPainter) & Open GIS Data Engines (QGIS, GDAL, Overture Maps)*  
**Last updated: November 2026**

This repository tracks notable **SaaS/Commercial platforms** and **open-source projects** for **Geospatial GIS & Minecraft World Importers**. These tools power 1:1 real-world city, elevation DEM, LiDAR, and OpenStreetMap terrain generation inside Minecraft (`teddy563/realworldmc`, `Arnis`, `TerraPlusPlus`, `GeoBox`), programmatic Anvil `.mca` / NBT world manipulation (`Amulet-Map-Editor`, `anvil-parser`, `WorldPainter`), and global GIS/satellite data sourcing (`QGIS`, `GDAL`, `Overture Maps`, `OpenTopography`) for urban planners, educators, Build The Earth builders, and geospatial developers.

**Examples** include Google Earth Engine (Google), ArcGIS Online (Esri), Nearmap (Thoma Bravo), Mapbox, Planet Insights / Sentinel Hub (Planet Labs), CARTO, Felt, QGIS Cloud (Sourcepole), and Placemark (the category leaders).

**🚀 Open-source emphasis**: This section is heavily expanded with every major active project for real-world GIS-to-Minecraft importers (`teddy563/realworldmc`, `Arnis`, `TerraPlusPlus`, `GeoBox`, `minecraft-earth-map`), Minecraft world & Anvil `.mca` editors (`Amulet-Map-Editor`, `WorldPainter`, `Chunky`, `Bluemap`), and open-source GIS/DEM/LiDAR toolkits (`QGIS`, `GDAL`, `PDAL`, `Overture Maps`, `OpenStreetMap`) — ideal for transforming real-world cities, national parks, and bathymetry into playable 3D voxel worlds.

🤝 Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## 📑 Table of Contents
- [📊 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [☁️ SaaS/Hosted & Commercial Platforms](#️-saashosted--commercial-platforms)
- [💻 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ How to Contribute](#️-how-to-contribute)
- [⚠️ Disclaimer](#️-disclaimer)
- [💖 Support & Thank You](#-support--thank-you)

## 📊 Sector Overview & Market Dynamics

The global Geographic Information Systems (GIS), Digital Twin Visualization & Educational Sandbox Simulation market is valued at approximately **$16.5B–$20.8B+ in 2026**, expanding at a ~12%–16% CAGR alongside growing adoption of **gamified 3D urban planning, public-participation GIS (PPGIS), and real-world voxel digital twins** in Minecraft (such as Ordnance Survey's *OS OpenData* maps, Dutch Kadaster/AHN LiDAR worlds, and *Build The Earth*). While commercial geospatial data and cloud GIS platforms exhibit **strong consolidation** around Esri, Google Earth Engine, Mapbox, and Nearmap, the **GIS-to-Minecraft converter, Anvil region parser, and open elevation/LiDAR data ecosystems are 100% open-source driven** (`realworldmc`, `Arnis`, `TerraPlusPlus`, `Amulet`, `QGIS`, `GDAL`).

## ☁️ SaaS/Hosted & Commercial Platforms

*Sorted descending by company valuation / annual revenue scale.*

| Platform | Description | Company Scale (Valuation / Revenue) | Starting Paid Tier | Free Tier / Trial Limit |
| :--- | :--- | :--- | :--- | :--- |
| **[Google Earth Engine](https://google.com)** | Planetary-scale cloud geospatial analysis platform combining petabytes of DEM elevation, land-cover, and satellite imagery exportable for voxel terrain modeling. | **Part of Alphabet Inc.** (~$350B+ Alphabet revenue; ~$2T+ market cap) | **Pay-as-you-go / Google Cloud Billing** (Commercial EECU compute & storage tiers starting ~$50+/mo) | **Forever Free Non-Commercial & Research Tier** (100% free global SRTM/ALOS DEM and land-cover exports for educational & research use) |
| **[ArcGIS Online (Esri)](https://arcgis.com)** | Enterprise cloud GIS platform offering global elevation layers, 3D building footprints, and geoprocessing workflows used in municipal Minecraft urban planning. | **~$2.0B+ Annual Revenue** (Privately held GIS market leader) | **$100 / user / year** (Viewer) or **$700 / user / year** (Creator license for full web GIS & data export) | **Forever Free Public Account & Developer Tier** (Free public map viewing/basic creation + **2,000,000 free map tile/basemap requests/month**) |
| **[Nearmap (Thoma Bravo)](https://nearmap.com)** | Ultra-high-resolution aerial orthomosaic, DSM/DEM elevation, and 3D reality mesh SaaS used for detailed real-world building and terrain reconstruction. | **~$730M Take-Private Valuation** (~$150M+ ARR; backed by Thoma Bravo) | **~$5,000 – $15,000+ / year** indicative commercial area/seat subscription | **Guided Commercial Demo** (No public self-serve free tier; sample high-res aerial imagery and elevation evaluations via sales) |
| **[Mapbox](https://mapbox.com)** | Cloud location platform providing global Terrain-RGB elevation tiles, vector building heights, and Satellite APIs frequently ingested by Minecraft world generators. | **~$1.0B–$1.2B Valuation** (~$150M+ est. ARR; backed by SoftBank/Foundry) | **Pay-as-you-go API Usage** (Raster/Terrain-RGB tile loads from **$0.25–$5.00 per 1,000 requests** beyond free quota) | **Forever Free Developer Tier** (**50,000 free web map loads/month** and generous free raster/Terrain-RGB API requests for indie builders) |
| **[Planet Insights / Sentinel Hub (Planet Labs)](https://planet.com)** | Cloud Earth-observation platform and Sentinel Hub API providing global Copernicus DEM elevation, Sentinel-2 land cover, and NDVI vegetation indices. | **~$220M+ Annual Revenue** (~$1B+ public market cap on NYSE; acquired Sinergise / Sentinel Hub) | **€25 / month** billed annually (€30/mo monthly for Sentinel Hub Exploration plan, 30,000 processing units/mo) | **30-Day Full-Access Free Trial** (Includes Sentinel Hub EO Browser, Copernicus DEM/Sentinel APIs, and custom evalscripts) |
| **[CARTO](https://carto.com)** | Cloud-native spatial analytics platform running directly on Snowflake, BigQuery, and PostgreSQL for querying large-scale building and land-use datasets. | **~$100M–$200M Est. Valuation** ($61M+ Series C led by Insight Partners) | **$199 / month** billed annually ($299/mo monthly for Starter cloud workspace) | **14-Day Full-Access Free Trial** (Full cloud spatial SQL workflows and Builder maps for 14 days; free student/educator program) |
| **[Felt](https://felt.com)** | Collaborative browser-native GIS and internet mapping platform for outlining target real-world bounding boxes, styling GeoJSON layers, and sharing project maps. | **~$50M–$100M Est. Valuation** ($34M+ VC funding led by Footwork/Bain Capital Ventures) | **$200 / month** billed annually ($240/mo monthly for Team plan, 5 editors) | **Forever Free Starter Plan** (**Unlimited maps**, up to **3 editors**, 100 MB spatial data uploads, and GeoJSON export) |
| **[QGIS Cloud (Sourcepole)](https://qgiscloud.com)** | Hosted cloud Web-GIS publishing service letting users share and inspect desktop QGIS DEM/OSM preparation layers online with collaborators. | **Independent Swiss Open-Core GIS Vendor** (Sourcepole AG; core QGIS contributors) | **€65 / month** for QGIS Cloud Pro (unlimited databases, password protection, and custom domains) | **Forever Free Community Plan** (**Unlimited public web maps**, 1 PostGIS database, and **50 MB storage** free forever) |
| **[Placemark](https://placemark.com)** | Fast, browser-based GeoJSON, TopoJSON, KML, and Shapefile editor ideal for drawing and exporting exact polygon bounding boxes for Minecraft world importers. | **Open-Source / Community Hosted** (Created by Tom MacWright; MIT open-source) | **$0 / Free Open-Source** (Self-hosted or community browser instances at zero cost) | **100% Free Forever** (Unlimited browser-based vector boundary editing, coordinate inspection, and GeoJSON export) |

## 💻 Open-Source GitHub Projects

| Project | License / Hosting Cost | Free Tier / Self-Hosted Limit | Description |
| :--- | :--- | :--- | :--- |
| **[RealWorldMC (`teddy563/realworldmc`)](https://github.com)** | **Open-Source** ($0 local real-world GIS-to-Minecraft world generator) | **100% Free forever** (Unlimited real-world elevation, map data, and custom Minecraft world generation locally) | Open-source real-world GIS-to-Minecraft importer converting geographic elevation and spatial map datasets into playable Minecraft worlds. |
