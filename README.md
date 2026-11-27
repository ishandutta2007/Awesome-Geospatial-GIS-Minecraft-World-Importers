# 🌍 Awesome-Geospatial-GIS-Minecraft-World-Importers

<p align="center">
  <img src="./assets/banner.svg" alt="Awesome Geospatial GIS and Minecraft World Importers" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Geospatial-GIS-Minecraft-World-Importers/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Geospatial-GIS-Minecraft-World-Importers?style=flat-square&logo=github" alt="GitHub_Stars" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Geospatial-GIS-Minecraft-World-Importers/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Geospatial-GIS-Minecraft-World-Importers?style=flat-square&logo=github" alt="GitHub forks" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Geospatial-GIS-Minecraft-World-Importers/issues"><img src="https://img.shields.io/github/issues/ishandutta2007/Awesome-Geospatial-GIS-Minecraft-World-Importers?style=flat-square" alt="GitHub issues" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Geospatial-GIS-Minecraft-World-Importers/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-green.svg?style=flat-square" alt="License" /></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🧭 Search-Engine & Keywords Overview (SEO)

> **Geospatial GIS & Minecraft World Importers** | *Curated resources for converting real-world Geographic Information Systems (GIS), Digital Elevation Models (DEM), LiDAR point clouds, satellite remote sensing imagery, and OpenStreetMap (OSM) vector data into 1:1 scale Minecraft worlds, Anvil `.mca` chunk regions, and interactive 3D digital twins.*

**Target Ecosystems & Tech Stack:**
`Minecraft Java Edition` • `Bedrock Edition` • `OpenStreetMap (OSM)` • `QGIS` • `GDAL / OGR` • `PDAL LiDAR` • `Copernicus DEM / SRTM` • `Google Earth Engine` • `ArcGIS Online` • `Mapbox Terrain-RGB` • `BlueMap 3D Web Viewer` • `Amulet Map Editor` • `WorldPainter` • `Build The Earth (BTE)` • `Arnis GIS Generator` • `RealWorldMC` • `Anvil MCA Parser`

---

## 📑 Table of Contents

- [📊 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [☁️ SaaS / Hosted & Commercial Geospatial Platforms](#️-saas--hosted--commercial-geospatial-platforms)
- [💻 Open-Source GitHub Projects & GIS-to-Minecraft Importers](#-open-source-github-projects--gis-to-minecraft-importers)
- [📈 Star History](#-star-history)
- [🛠️ How to Contribute](#️-how-to-contribute)
- [💖 Support & Thank You](#-support--thank-you)
- [⚠️ Disclaimer](#️-disclaimer)

---

## 📊 Sector Overview & Market Dynamics

The global Geographic Information Systems (GIS) and spatial analytics market is estimated at approximately **$12.8B to $16.6B in 2026** (scaling toward $30B+ by the early 2030s at an ~11%–14% CAGR). Market dynamics reflect a **bifurcated structure**: the enterprise platform and foundational cloud spatial layer is **moderately concentrated** around entrenched giants (notably Esri and Alphabet/Google Earth Engine), whereas downstream data sourcing, drone/aerial capture, GeoAI processing, and 3D voxel/Minecraft world-generation tooling remain **highly fragmented** across specialized niche SaaS providers, independent data vendors, and open-source developer communities.

---

## ☁️ SaaS / Hosted & Commercial Geospatial Platforms

*Sorted descending by company scale (valuation / annual revenue).*

| Platform | Description | Company Scale (Valuation / Revenue) | Starting Paid Tier | Free Tier / Trial Limit |
| :--- | :--- | :--- | :--- | :--- |
| **[Google Earth Engine](https://earthengine.google.com)** | 🛰️ Planetary-scale cloud geospatial analysis platform combining petabytes of DEM elevation, land-cover, and satellite imagery exportable for voxel terrain modeling. | **Alphabet Inc. subsidiary** (~$350B+ annual revenue; ~$2T+ market cap) | **$500 / month** (Basic commercial tier; on-demand EECU batch compute at $0.40/EECU-hr and online compute at $1.33/EECU-hr) | **Forever Free Non-Commercial Tier** (Community tier with 150 EECU-hours/month; Contributor tier with 1,000 EECU-hours/month for research/education) |
| **[ArcGIS Online (Esri)](https://www.esri.com/en-us/arcgis/products/arcgis-online/overview)** | 🗺️ Enterprise cloud GIS platform offering global elevation layers, 3D building footprints, and geoprocessing workflows used in municipal Minecraft urban planning. | **~$2.0B+ Annual Revenue** (Privately held market leader) | **$125 / user / year** (Viewer user type; full GIS Creator plan at $700 / user / year) | **21-Day Free Trial** (Full-access organizational account with up to 5 named users and 200 service credits; plus free public non-commercial developer account with 2,000,000 basemap tiles/month) |
| **[Mapbox](https://www.mapbox.com)** | 🌐 Cloud location platform providing global Terrain-RGB elevation tiles, vector building heights, and Satellite APIs frequently ingested by Minecraft world generators. | **~$1.0B–$1.2B Valuation** (~$150M+ ARR; backed by SoftBank) | **$0.25 per 1,000 requests** (Pay-as-you-go billing above free threshold for raster/elevation tiles; vector tiles at $0.25–$0.50/1k loads) | **Forever Free Tier** (**50,000 free web map loads/month**, up to 200,000 tile requests, and generous free API requests every month) |
| **[Planet Insights / Sentinel Hub (Planet Labs)](https://www.planet.com)** | 🛰️ Cloud Earth-observation platform and Sentinel Hub API providing global Copernicus DEM elevation, Sentinel-2 land cover, and NDVI vegetation indices. | **~$1.0B Market Cap** (~$220M+ annual revenue; NYSE: PL) | **€25 / month** (€30/month billed monthly for Sentinel Hub Exploration plan with 30,000 processing units) | **30-Day Free Trial** (Full Sentinel Hub API and EO Browser access with Copernicus DEM, Sentinel-2 processing, and custom evalscripts) |
| **[Nearmap (Thoma Bravo)](https://www.nearmap.com)** | 📐 Ultra-high-resolution aerial orthomosaic, DSM/DEM elevation, and 3D reality mesh SaaS used for detailed real-world building and terrain reconstruction. | **~$730M Valuation** (Acquired by Thoma Bravo; ~$150M+ ARR) | **~$3,000 / year** (Starting annual subscription package for single-user/small geographic coverage; enterprise tiers scale above $10,000+/year) | **7 to 14-Day Sales-Assisted Evaluation Trial** (Custom proof-of-concept trial granted by sales upon demo request with bounded tile/download limits; no self-serve free tier) |
| **[CARTO](https://carto.com)** | 📊 Cloud-native spatial analytics platform running directly on Snowflake, BigQuery, and PostgreSQL for querying large-scale building and land-use datasets. | **~$150M–$200M Valuation** ($61M+ Series C led by Insight Partners) | **$199 / month** ($299/month billed monthly for Starter cloud workspace with 1 editor and 10 viewers) | **14-Day Free Trial** (Full-featured access to CARTO Builder, spatial SQL workflows, and cloud data warehouse connectors; no credit card required) |
| **[Felt](https://felt.com)** | ✏️ Collaborative browser-native GIS and internet mapping platform for outlining target real-world bounding boxes, styling GeoJSON layers, and sharing project maps. | **~$50M–$100M Valuation** ($34M+ VC funding led by Bain Capital & Footwork) | **$200 / month** ($240/month billed monthly for Team tier including 5 editor seats) | **Forever Free Starter Tier** (**Unlimited maps**, up to **3 editors**, 100 MB file upload limit per dataset, and full GeoJSON export capabilities) |
| **[QGIS Cloud (Sourcepole)](https://qgiscloud.com)** | ☁️ Hosted cloud Web-GIS publishing service letting users share and inspect desktop QGIS DEM/OSM preparation layers online with collaborators. | **~$1M–$5M Bootstrapped Scale** (Sourcepole AG; boutique core QGIS contributor firm with ~9 engineers) | **€65 / month** (QGIS Cloud Pro with unlimited private databases, custom domain, and Web-GIS map services) | **Forever Free Community Tier** (**Unlimited public maps**, 1 PostGIS database, and up to **50 MB data storage**) |

---

## 💻 Open-Source GitHub Projects & GIS-to-Minecraft Importers

*Sorted descending by repository GitHub Stars_Count.*

| Project | GitHub_Stars | Category / Tech Stack | License | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Arnis (`louis-e/arnis`)](https://github.com/louis-e/arnis)** | <a href="https://github.com/louis-e/arnis/stargazers"><img src="https://img.shields.io/github/stars/louis-e/arnis?style=social&color=white" alt="Stars" /></a> | 🏙️ Real-World 3D City Generator (Rust) | AGPL-3.0 | Generates detailed real-world locations in Minecraft using OpenStreetMap and digital elevation data with high fidelity. |
| **[QGIS (`qgis/QGIS`)](https://github.com/qgis/QGIS)** | <a href="https://github.com/qgis/QGIS/stargazers"><img src="https://img.shields.io/github/stars/qgis/QGIS?style=social&color=white" alt="Stars" /></a> | 🗺️ Desktop GIS Workstation (C++ / Python) | GPL-2.0 | Flagship open-source geographical information system used for preprocessing DEM rasters, LiDAR point clouds, and OSM vectors for Minecraft import. |
| **[GDAL (`OSGeo/gdal`)](https://github.com/OSGeo/gdal)** | <a href="https://github.com/OSGeo/gdal/stargazers"><img src="https://img.shields.io/github/stars/OSGeo/gdal?style=social&color=white" alt="Stars" /></a> | ⚙️ Raster & Vector Geospatial Translator (C++) | MIT / X11 | Universal translator and processing library for reading, reprojecting, and converting raster DEMs and vector GIS boundaries. |
| **[Cuberite (`cuberite/cuberite`)](https://github.com/cuberite/cuberite)** | <a href="https://github.com/cuberite/cuberite/stargazers"><img src="https://img.shields.io/github/stars/cuberite/cuberite?style=social&color=white" alt="Stars" /></a> | ⚡ Fast Custom Minecraft Server (C++) | Apache-2.0 | High-performance C++ Minecraft server engine frequently used in programmatic automated real-world world generation pipelines. |
| **[Minecraft-Overviewer (`overviewer/Minecraft-Overviewer`)](https://github.com/overviewer/Minecraft-Overviewer)** | <a href="https://github.com/overviewer/Minecraft-Overviewer/stargazers"><img src="https://img.shields.io/github/stars/overviewer/Minecraft-Overviewer?style=social&color=white" alt="Stars" /></a> | 🔍 Isometric Web Map Renderer (Python / C) | GPL-3.0 | Generates high-resolution Google Maps-style isometric web maps from Minecraft Anvil worlds. |
| **[BlueMap (`BlueMap-Minecraft/BlueMap`)](https://github.com/BlueMap-Minecraft/BlueMap)** | <a href="https://github.com/BlueMap-Minecraft/BlueMap/stargazers"><img src="https://img.shields.io/github/stars/BlueMap-Minecraft/BlueMap?style=social&color=white" alt="Stars" /></a> | 🌐 3D Browser Voxel Map Viewer (Java) | MIT | Real-time 3D web viewer converting Minecraft chunks into interactive three.js browser digital twins. |
| **[Amulet Map Editor (`Amulet-Team/Amulet-Map-Editor`)](https://github.com/Amulet-Team/Amulet-Map-Editor)** | <a href="https://github.com/Amulet-Team/Amulet-Map-Editor/stargazers"><img src="https://img.shields.io/github/stars/Amulet-Team/Amulet-Map-Editor?style=social&color=white" alt="Stars" /></a> | 🧱 Universal World & Anvil Editor (Python) | GPL-3.0 | Cross-platform Minecraft world editor and converter supporting Java and Bedrock formats for pasting real-world geospatial structures. |
| **[Placemark (`Placemark/placemark`)](https://github.com/Placemark/placemark)** | <a href="https://github.com/Placemark/placemark/stargazers"><img src="https://img.shields.io/github/stars/Placemark/placemark?style=social&color=white" alt="Stars" /></a> | ✏️ Browser Geospatial Data Editor (TypeScript) | MIT | Powerful web-based geospatial editor and converter for inspecting, editing, and exporting GeoJSON, KML, and TopoJSON bounding boxes. |
| **[PDAL (`PDAL/PDAL`)](https://github.com/PDAL/PDAL)** | <a href="https://github.com/PDAL/PDAL/stargazers"><img src="https://img.shields.io/github/stars/PDAL/PDAL?style=social&color=white" alt="Stars" /></a> | 🛰️ Point Cloud Data Abstraction Library (C++) | BSD-3-Clause | Point cloud processing library for filtering, rasterizing, and translating airborne LiDAR data into elevation DEM grids. |
| **[Overture Maps Data Tools (`OvertureMaps/data`)](https://github.com/OvertureMaps/data)** | <a href="https://github.com/OvertureMaps/data/stargazers"><img src="https://img.shields.io/github/stars/OvertureMaps/data?style=social&color=white" alt="Stars" /></a> | 🌍 Open Global Map Data (Python) | CDLA-Permissive-2.0 | Open map datasets and query tools providing building footprints, elevations, transportation, and base layers for voxel world builders. |
| **[Chunky (`chunky-dev/chunky`)](https://github.com/chunky-dev/chunky)** | <a href="https://github.com/chunky-dev/chunky/stargazers"><img src="https://img.shields.io/github/stars/chunky-dev/chunky?style=social&color=white" alt="Stars" /></a> | 📸 Photorealistic Path Tracer (Java) | GPL-3.0 | Renders high-resolution, photorealistic ray-traced scenes and aerial vistas of Minecraft worlds created from GIS data. |
| **[WorldPainter (`Captain-Chaos/WorldPainter`)](https://github.com/Captain-Chaos/WorldPainter)** | <a href="https://github.com/Captain-Chaos/WorldPainter/stargazers"><img src="https://img.shields.io/github/stars/Captain-Chaos/WorldPainter?style=social&color=white" alt="Stars" /></a> | 🎨 Interactive Terrain Painter (Java) | GPL-3.0 | Interactive map generator that imports heightmaps (DEMs) and exports customized Minecraft worlds with custom biomes and terrain layers. |
| **[Terra121 (`orangeadam3/terra121`)](https://github.com/orangeadam3/terra121)** | <a href="https://github.com/orangeadam3/terra121/stargazers"><img src="https://img.shields.io/github/stars/orangeadam3/terra121?style=social&color=white" alt="Stars" /></a> | 🌍 1:1 Earth World Generator (Java) | MIT | Original 1:1 scale Earth world generation mod utilizing global elevation heightmaps and OpenStreetMap street networks. |
| **[RealWorldMC (`teddy563/realworldmc`)](https://github.com/teddy563/realworldmc)** | <a href="https://github.com/teddy563/realworldmc/stargazers"><img src="https://img.shields.io/github/stars/teddy563/realworldmc?style=social&color=white" alt="Stars" /></a> | 🏙️ Google 3D & Street View to MC (Java) | MIT | Fabric mod bringing Google 3D photogrammetry maps and real-world elevation terrain directly into Minecraft Java Edition. |
| **[TerraPlusPlus (`BuildTheEarth/terraplusplus`)](https://github.com/BuildTheEarth/terraplusplus)** | <a href="https://github.com/BuildTheEarth/terraplusplus/stargazers"><img src="https://img.shields.io/github/stars/BuildTheEarth/terraplusplus?style=social&color=white" alt="Stars" /></a> | 🌐 High-Performance 1:1 Earth Mod (Java) | MIT | High-performance fork of Terra121 powering the Build The Earth project with multi-threaded terrain ingestion and custom projections. |
| **[Anvil Parser (`matcool/anvil-parser`)](https://github.com/matcool/anvil-parser)** | <a href="https://github.com/matcool/anvil-parser/stargazers"><img src="https://img.shields.io/github/stars/matcool/anvil-parser?style=social&color=white" alt="Stars" /></a> | 🧱 Anvil `.mca` Chunk Parser (Python) | MIT | Lightweight Python library for reading, modifying, and programmatically writing Minecraft Anvil chunk region files. |

---

## 📈 Star History

[![Star History Chart](https://www.star-history.com/svg?repos=ishandutta2007/Awesome-Geospatial-GIS-Minecraft-World-Importers&type=date&legend=top-left)](https://www.star-history.com/#ishandutta2007/Awesome-Geospatial-GIS-Minecraft-World-Importers&type=date&legend=top-left)

---

## 🛠️ How to Contribute

Contributions are warmly welcomed! 🌟 To add or update an entry:

1. **Fork** the repository on GitHub.
2. **Create a branch** for your feature or project update (`git checkout -b feature/add-new-gis-tool`).
3. **Add the tool** to either the SaaS or Open-Source table, maintaining alphabetical or sorted order.
4. **Include factual data**: Official URL, Stars_Badge (for open-source), clear license, specific starting price, and exact free tier limits.
5. **Open a Pull Request** with a concise description of why the tool is valuable for geospatial GIS and Minecraft builders.

---

## 💖 Support & Thank You

Thank you for visiting and supporting **Awesome-Geospatial-GIS-Minecraft-World-Importers**! 💙

If you find this repository helpful for your geospatial research, urban planning digital twins, or Build The Earth creations:
- ⭐ **Star** this repository to show your appreciation and help others discover it!
- 🍴 **Fork** it to build your own custom pipelines and collections.
- 📢 **Share** it with your fellow GIS analysts, Minecraft modders, and cartography enthusiasts.
- ☕ **Support the maintainer**: If you would like to buy me a coffee or support ongoing development, please visit the [GitHub Sponsors Dashboard](https://github.com/sponsors/ishandutta2007).

---

## ⚠️ Disclaimer

*Minecraft is a registered trademark of Mojang Synergies AB / Microsoft Corporation. This repository is an independent open-source curation and is not affiliated with, endorsed by, or associated with Mojang Studios or Microsoft.*
