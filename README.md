## Johan Fernandez
### Urban data scientist · GeoAI for housing, land use and infrastructure

I build **location-aware machine learning and spatial analysis** around one question: **who gets what in cities?** My work combines GIS, spatial statistics and predictive modeling with California and New York planning policy.

🎓 B.A. Urban Studies & Planning, UC San Diego · preparing for doctoral study in urban data science
📍 San Diego, CA · 📫 jhoven.jan98@gmail.com

---

### 🧭 Research focus

- **GeoAI for housing policy:** predicting where zoned capacity actually becomes housing, and auditing those predictions for equity
- **Spatially honest machine learning:** spatial cross-validation, calibration and explainability, so models hold up in places they have never seen
- **Ranking and fairness:** how the rule a city uses to rank neighborhoods decides who benefits first
- **Responsible AI in city government:** transparency and resident voice in AI-assisted decisions (3rd place, UCSD Urban Expo)

---

### 🗺️ GeoAI for Cities: research projects

| Project | Question | Methods |
|---|---|---|
| **[Will It Get Built?](https://github.com/JohanArisato/housing-site-realization)** | Which of San Diego's 2021 Housing Element sites actually got housing approvals, and can a model predict it better than the city's capacity assumptions? | Spatial CV, LightGBM, calibration, SHAP, equity audit |
| **[Who Gets the Shade?](https://github.com/JohanArisato/who-gets-the-shade)** | When NYC ranks neighborhoods for tree planting, how much does the ranking rule change who benefits? | Moran's I/LISA, spatial lag & error models, leave-one-borough-out CV, 5,000 random weightings |
| **[CurbCall](https://github.com/JohanArisato/curbcall)** | If residents report and vote on what to fix first, whose problems get heard? | Product prototype, PostGIS data model, per-area ranking |
| **[GeoAI for Cities](https://github.com/JohanArisato/geoai-for-cities)** | What is GeoAI, and who benefits when cities use it to decide? | Research website and article series |
| **[geoai-cities-db](https://github.com/JohanArisato/geoai-cities-db)** | One spatial database behind every project | GeoPackage + PostGIS, data catalog with synthetic-data flags, cross-project spatial views |

**Who Gets the Shade? in one line:** tree canopy cools surfaces (−0.17 °F per point), but heat illness follows poverty (r = 0.59), and switching the ranking rule moves the poorest neighborhoods from 4 to 9 of the first 10 planted.

---

### 🛠️ Applied GIS work

| Project | What I did |
|---|---|
| Municipal stormwater priority mapping | Geodatabases ranking Capital Improvement Plan sites across four San Diego cities under MS4/NPDES permits |
| UCSD campus CAD-to-GIS & UAV mapping | Georeferenced 1,788 AutoCAD drawings into an ArcGIS Pro basemap; drone orthomosaics with Drone2Map |
| Community health equity mapping | Census/ACS data joined with infrastructure layers to find service gaps in underserved neighborhoods |

---

### 🧰 Toolkit

**GeoAI & ML:** Python · GeoPandas · PySAL (esda, spreg) · scikit-learn · LightGBM · SHAP
**Spatial data:** PostgreSQL/PostGIS · GeoPackage · GDAL/OGR · SQL · ArcGIS Pro · ArcPy · QGIS · Drone2Map
**Web & viz:** Folium/Leaflet · D3 · Power BI · Tableau
**Planning:** Housing Element & RHNA · land use & zoning · CEQA · MS4/NPDES · equity mapping
