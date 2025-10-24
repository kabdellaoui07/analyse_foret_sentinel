# Forest Health Monitoring using Sentinel-2 and Machine Learning

##  Overview
This project analyzes the health of forest ecosystems using Sentinel-2 satellite imagery (2017–2023).  
The goal is to evaluate vegetation dynamics, identify stressed forest zones, and classify vegetation health using spectral indices and machine learning.

---

##  Objectives
- Monitor the temporal evolution of forest vegetation.
- Compute spectral indices: NDVI, SAVI, NDWI, and EVI.
- Classify forest health using Random Forest and SVM models.
- Visualize trends and produce classification maps.

---

##  Data Source
- Sentinel-2 (COPERNICUS/S2_SR_HARMONIZED) imagery.
- Processed via Google Earth Engine (GEE).
- Timeframe: May 2017 → May 2023

---

## ⚙️ Methodology
1. Data collection and preprocessing in GEE.
2. Computation of vegetation and water indices (NDVI, SAVI, NDWI, EVI).
3. Statistical analysis and visualization (trend analysis, confusion matrices).
4. Machine learning classification:
   - Random Forest
   - Support Vector Machine (SVM)

---

## Results
Results are stored in the [results/](./results) folder:
- maps/ → Final classification maps  
- indicators/ → Temporal NDVI, SAVI, NDWI, and EVI trends  
- matrices/ → Confusion matrices and accuracy reports  

---

##  Tools & Libraries
- Google Earth Engine (GEE)
- Python (Google Colab)
- ee, geemap, matplotlib, pandas, scikit-learn, ...

---

##  Conclusion
This study demonstrates how remote sensing and machine learning can be combined to monitor forest health efficiently.  
The approach provides a precise spatial diagnosis that supports sustainable forest management and long-term environmental monitoring.

---

## 👩‍💻 Author
Kheira Abdellaoui  
GIS & Remote Sensing Student  
 Algeria  
📧 khairaabdellaoui07@gmail.com 