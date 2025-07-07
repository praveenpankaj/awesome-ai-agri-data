# 🗺️ Crop Extent Datasets

This page collects global and regional datasets that map the **spatial extent** of croplands, either annually or in near real time. These datasets are useful for land use classification, agricultural monitoring, policy planning, and training machine learning models.

---

## 🌍 Global Crop Extent Datasets

| Dataset | Resolution | Year(s) | Description | Source |
|--------|------------|---------|-------------|--------|
| **ESA WorldCereal Cropland Extent** | 10 m | 2021 | Global cropland probability layer from Sentinel-1/2 | [ESA WorldCereal](https://worldcereal.esa.int/) |
| **GFSAD30** | 30 m | 2015 | Global Food Security-support Analysis Data cropland extent map | [USGS GFSAD](https://lpdaac.usgs.gov/products/gfsad30afde001/) |
| **Global Cropland Area Database (GCAD)** | 30 m | 2000–2015 | Harmonized multi-year cropland masks | [NASA Harvest](https://nasaharvest.org/) |
| **GLC-FCS30** | 30 m | 2020 | Global Land Cover based on fine classification system; includes cropland class | [GLC-FCS30](https://data.essdc.sinica.edu.tw/glcfcs30/) |
| **ESRI Land Use Land Cover (LULC)** | 10 m | 2017–2023 | Annual global LULC map derived from Sentinel-2 using deep learning; includes cropland class | [ESRI Living Atlas](https://livingatlas.arcgis.com/landcover/) |
| **Google Dynamic World** | 10 m | Near real-time | Near real-time, globally available land use classification using Sentinel-2 and AI models; includes cropland probability | [Dynamic World](https://dynamicworld.app/) |

---

## 🇮🇳 India-Specific Crop Extent Datasets

| Dataset | Resolution | Description | Source |
|---------|------------|-------------|--------|
| **Bhuvan LULC** | 56 m | National-level land use/land cover map including cropland | [Bhuvan Portal](https://bhuvan.nrsc.gov.in/) |
| **Mahalanobis-NDMA Rabi-Kharif Masks** | 10–30 m | Seasonal crop extent masks generated from remote sensing for disaster and crop monitoring | [MNCFC](https://www.ncfc.gov.in/) |
| **ICAR-NRSC Crop Area Layers** | 10 m | Seasonal crop extent from Sentinel-2 for pilot districts | [ICAR-NRSC](https://nrsc.gov.in/) |

---

## 📦 Format & Licensing

- Formats: GeoTIFF raster layers, probability maps, or class labels
- Access: Most datasets are open under CC-BY or similar licenses
- Interoperability: Can be visualized and processed using GEE, QGIS, or Python geospatial tools

---

## 🧠 Use Cases

- Training and validating cropland segmentation models
- Estimating agricultural land use change over time
- Providing cropland masks for yield modeling, irrigation planning, or food security analysis


---

## 📥 Contribute

Know a dataset we missed? Add it via a pull request using this format:

```markdown
| Dataset Name | Resolution | Year(s) | Description | [Source](http://...) |
