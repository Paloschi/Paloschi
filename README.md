<h1 align="center">Hi, I'm Rennan Paloschi</h1>
<h3 align="center">Senior Geospatial Engineer</h3>

<p align="center">
  <a href="https://github.com/Paloschi">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&center=true&vCenter=true&width=560&lines=Senior+Geospatial+Engineer;Earth+observation+and+GIS;Production+geospatial+systems" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/Paloschi?tab=followers">
    <img src="https://img.shields.io/github/followers/Paloschi?label=Followers&style=for-the-badge" />
  </a>
  <a href="https://github.com/Paloschi">
    <img src="https://img.shields.io/github/stars/Paloschi?affiliations=OWNER%2CCOLLABORATOR&style=for-the-badge" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=Paloschi&style=for-the-badge&color=blue" alt="Profile views" />
</p>

---

## About Me

- Senior Geospatial Engineer with a PhD in Remote Sensing from INPE (Caatinga water use, phenology, and sap flow)
- Co-founder of Picsel: I own the geospatial stack for agricultural insurance
- I turn satellite, climate, and soil data into risk and yield products
- Also design field instrumentation (ESP32 / ATmega loggers) for ecohydrology campaigns
- From raster pipelines and Earth Engine to PostGIS, APIs, and maps in production

---

## Tech Stack

<p>
  <img src="https://img.shields.io/badge/Python-black?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/Numba-black?style=for-the-badge" />
  <img src="https://img.shields.io/badge/CUDA-black?style=for-the-badge&logo=nvidia&logoColor=white" />
  <img src="https://img.shields.io/badge/xarray-black?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Zarr-black?style=for-the-badge" />
  <img src="https://img.shields.io/badge/GDAL-black?style=for-the-badge" />
  <img src="https://img.shields.io/badge/GeoPandas-black?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/Rasterio-black?style=for-the-badge" />
  <img src="https://img.shields.io/badge/PostGIS-black?style=for-the-badge&logo=postgresql" />
  <img src="https://img.shields.io/badge/Google%20Earth%20Engine-black?style=for-the-badge&logo=googleearth&logoColor=white" />
  <img src="https://img.shields.io/badge/Sentinel%20%2F%20HLS-black?style=for-the-badge" />
  <img src="https://img.shields.io/badge/TensorFlow-black?style=for-the-badge&logo=tensorflow" />
  <img src="https://img.shields.io/badge/GeoTIFF%20%2F%20COG-black?style=for-the-badge" />
  <img src="https://img.shields.io/badge/GeoParquet-black?style=for-the-badge" />
  <img src="https://img.shields.io/badge/DuckDB-black?style=for-the-badge&logo=duckdb" />
  <img src="https://img.shields.io/badge/Leaflet-black?style=for-the-badge&logo=leaflet" />
  <img src="https://img.shields.io/badge/AWS-black?style=for-the-badge&logo=amazonwebservices&logoColor=white" />
  <img src="https://img.shields.io/badge/Step%20Functions-black?style=for-the-badge&logo=amazonwebservices&logoColor=white" />
</p>

---

## Featured Projects

### 1. AquaCrop-Grid <sub>[Repository](https://github.com/Paloschi/aquacrop-grid)</sub>

Open-source **pixel-wise AquaCrop** on rasters: zarr climate and sowing in, yield and biomass grids out. Daily kernels compiled with Numba (CPU + CUDA GPU), bit-exact against AquaCrop-OSPy. Per-pixel soil from HiHydroSoil hydraulics or sand/silt/clay texture.

*Early stage — we are just getting this project started.*

**Tech:** Python, Numba, CUDA, xarray, zarr, AquaCrop  

### 2. TabGeo <sub>[Repository](https://github.com/Paloschi/tabgeo.com.br) · [Live](https://tabgeo.com.br)</sub>

Content platform for geospatial professionals who need practical, high-value material.

*Early stage — we are just getting this project started.*

**Tech:** Next.js, React, Node.js, PostgreSQL, Jest  

### 3. Picsel <sub>[Website](https://picsel.com.br)</sub>

Co-founded geospatial platform for agricultural insurance. I own the stack end to end — remote crop inspection, cotton stand-count, and Vision Suite, where insurers inspect satellite evidence on the map. Rural quotations went from several days to about 3 minutes.

**Publications**

- Paloschi, R. A.; Ozaki, V. A.; Miquelluti, D. L. *Plataforma Picsel*. Computer program registration **INPI BR 51 2023 000705-6** (titular: Picsel Soluções em Gerenciamento de Risco Ltda; issued 21/03/2023). — https://www.gov.br/inpi/pt-br

**Tech:** Python, GDAL, GeoPandas, Rasterio, PostGIS, Google Earth Engine, Sentinel/HLS, NDVI, GeoTIFF/COG, TensorFlow, AWS Step Functions, Metaflow, Leaflet  

### 4. Eco Grade <sub>[Website](https://eco-grade.com)</sub>

B2B sustainability marketplace for the EU (eco grade GmbH) — from compliance-gated seller onboarding to Stripe subscriptions with EU VAT.  
**Tech:** Next.js, React, PostgreSQL, Stripe, Vitest  

### 5. SapFlow Logger <sub>[Repository](https://github.com/Paloschi/sapflow-logger)</sub>

Open-source **Granier-style sap-flow field logger** (ESP32, microSD, Bluetooth Low Energy, phone download). Hardware 6.0 is open in this repo; earlier thesis-era units supported Caatinga work at INPE.

**Publications**

- Paloschi, R. A., et al. (2021). Environmental Drivers of Water Use for Caatinga Woody Plant Species: Combining Remote Sensing Phenology and Sap Flow Measurements. *Remote Sensing*, 13(1), 75. — https://doi.org/10.3390/rs13010075
- Ventura, D. J., et al. (2024). Seasonal dynamics of water sources for woody plants in the Caatinga. Authorea preprint. — https://doi.org/10.22541/au.173397840.03126234/v1
- Paloschi, R. A. (2020/2021). *Seasonality of water availability, plant phenology, and plant transpiration in a Brazilian Caatinga environment investigated by in situ and remote sensing data*. Ph.D. thesis, INPE. — http://urlib.net/sid.inpe.br/mtc-m21c/2021/01.13.15.06
- Medeiros, M., et al. (2025). Seasonal shifts in tree water use and non-structural carbohydrate storage in a tropical dry forest. *Plant, Cell & Environment*, 48(6), 4518–4532. — https://doi.org/10.1111/pce.15449
- Jesus, A. L. N., et al. (2025). Semiarid woody plant functional groups contribute differently to canopy conductance. *Journal of Arid Environments*. — https://doi.org/10.1016/j.jaridenv.2025.105318

**Tech:** ESP32, Arduino, BLE, SD, RTClib / INA219 / thermocouple  

### 6. CyMP <sub>[Repository](https://github.com/Paloschi/CyMP)</sub>

Open-source **Crop-yield Modeling Platform** for spatial agricultural yield estimation (FAO water balance on MODIS / ECMWF rasters), developed at UNIOESTE–LEA. AquaCrop-Grid started from this lineage. Software registration **INPI BR 51 2017 000623-7**.

**Publications**

- Paloschi, R. A. (2016). *Software aplicado a modelos de estimativa de produtividade agrícola*. M.Sc. dissertation (Agricultural Engineering), UNIOESTE, Cascavel. — https://tede.unioeste.br/handle/tede/2726
- Paloschi, R. A.; Johann, J. A.; Santa Catarina, A. Crop-yield Modeling Platform (CyMP). Computer program registration **INPI BR 51 2017 000623-7**. — https://www.gov.br/inpi/pt-br
- Biasotto, G.; Johann, J. A.; Richetti, J.; Becker, W. R. (2017). Determinação da série histórica mensal do balanço hídrico para o estado do Paraná utilizando o modelo ECMWF. In: *Anais do XVIII SBSR*. (uses CyMP). — http://urlib.net/sid.inpe.br/marte2/2017/10.27.15.27.59
- Successor / evolution: AquaCrop-Grid (pixel-wise AquaCrop on rasters). — https://github.com/Paloschi/aquacrop-grid

**Tech:** Python, Remote Sensing, GIS  

---

## Connect with Me

<p>
  <a href="https://www.linkedin.com/in/rennan-paloschi">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:rennanandrespaloschi@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>
