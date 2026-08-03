# GLOF Hazard Risk Assessment · Kargil, Ladakh 

Interactive HTML Dashboard for the Academic Mini Project **"GLOF Hazard Risk Assessment using Remote Sensing-Derived Cryospheric & Topographic Indicators with Random Forest"** — Kargil, Ladakh, India (2000–2024).

##  Research Objective

This study investigates Glacial Retreat and Glacial Lake Proliferation in Kargil, Ladakh using multi-temporal Landsat 8/9 imagery (2000–2024), ALOS PALSAR DEM (12.5m) 
and remote sensing-derived Cryospheric and Topographic indicators. A Random Forest Machine Learning Classifier generates a spatially explicit GLOF Hazard Risk Map 
integrating NDSI, NDWI, SWI, Slope, TRI, TWI, Aspect and Stream Orders providing a reproducible framework for disaster preparedness in high-mountain communities.

##  Key Findings

| Metric | 2000 | 2024 | Change |
|---|---|---|---|
| Glacier Extent | 1584.82 km² | 996.37 km² | −37.1% (−588.45 km²) |
| Glacial Lakes (count) | 455 | 579 | +27.3% |
| Glacial Lake Water Area | 14.97 km² | 18.65 km² | +24.6% |

- Accelerating Retreat: The 2016–2024 period alone recorded −370.10 km² (−27.1%) of glacier loss, the sharpest decline of any period studied.
- Inverse Correlation Confirmed: Glacier Retreat directly drives glacial lake expansion with Proglacial Lakes posing the highest individual GLOF hazard.
- Lake classification (2024): Periglacial — 253 lakes (43.7%); Proglacial — 213 lakes (Highest Hazard Potential); Supraglacial — 113 lakes.

##  Dashboard Sections

1. Overview — Key Statistics and Summary Findings
2. Study Area — Location, LULC and Strahler Stream Order Drainage Network
3. Terrain Analysis — DEM, Slope, Aspect, TRI, TWI Derivatives
4. Spectral Indices — NDSI, NDWI, SWI Interpretation
5. Glacial Extent — Multi-Temporal Glacier Mapping (2000/2008/2016/2024)
6. Glacial Lakes — Temporal Lake Inventory and Classification
7. Findings & Interpretation — Random Forest GLOF Hazard Risk Map with Validation Points

##  Methodology Pipeline

Landsat 8/9 Imagery → ALOS PALSAR DEM (10m) → NDSI · NDWI · SWI → Glacier Extent Mapping → Glacial Lake Inventory → Terrain Derivatives → Random Forest Classifier → GLOF Hazard Risk Map

Model inputs (10+ features): ALOS PALSAR DEM, Slope, TRI, TWI, Aspect, NDSI, NDWI, SWI, Stream Order, Lake Proximity.

Output: Three-class validated GLOF Susceptibility Map: High / Moderate / Low Risk Zones, concentrated along the Suru Valley axis and southern Kargil sector.

##  Data Sources

- Landsat 8/9 Satellite Imagery (2000–2024)
- ALOS PALSAR DEM, 12.5m resolution
- Validation Points for Random Forest Model Accuracy Assessment

##  Conclusion

The integrated Remote Sensing and Machine Learning approach successfully delineates GLOF hazard susceptibility across Kargil, Ladakh. Accelerating glacial retreat is directly driving glacial lake expansion, with proglacial and periglacial lakes as primary GLOF sources. These findings can directly inform infrastructure planning, 
early warning systems and disaster risk reduction strategies for downstream communities in the region.

Author: Swapnanil Saha · M.Sc. Geoinformatics, Symbiosis Institute of Geoinformatics
Keywords: GLOF, Remote Sensing, GIS, Random Forest, Glacial Lakes, Cryosphere, Ladakh, Machine Learning
