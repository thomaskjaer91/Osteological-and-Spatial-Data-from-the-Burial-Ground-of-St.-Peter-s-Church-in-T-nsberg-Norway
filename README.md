# Osteological and Spatial Data from the Burial Ground of St. Peter’s Church in Tønsberg, Norway

## Description
This dataset contains **vectorized and georeferenced osteological data** from the medieval burial ground of **St. Peter’s Church (Peterskirken)** in Tønsberg, Norway.  
A total of **407 individuals** are represented, each linked to spatial coordinates (ETRS89 / UTM zone 32N).  
Attributes include estimated sex, age category, age range, stature, and distance to the nearest point of the church.  

The dataset was digitized and georeferenced in **QGIS**, based on excavation drawings and osteological records from the **1983 and 1985 excavations**, originally analyzed at the **Anatomical Institute, University of Oslo**.

## Contents
- `Osteological_and_Spatial_Data_Peterskirken.csv` – Main dataset of 407 individuals  
- `metadata.csv` – Variable definitions, coordinate system, and methodological notes  
- `README.md` – Project description and citation information  

## Spatial Reference
- **Coordinate system:** ETRS89 / UTM zone 32N (EPSG:25832)  
- **Spatial accuracy:** ±2 m (manual georeferencing in QGIS)  

## Methodological Notes
The dataset was produced by vectorizing original excavation drawings and linking each burial to its corresponding osteological record.  
Sex and age estimations are morphological assessments following **Holck (1989)**.  
Distance to church was calculated in QGIS using the “Distance to Nearest Hub” algorithm.  

## How to cite
Kjær, Thomas (2025). *Osteological and Spatial Data from the Burial Ground of St. Peter’s Church in Tønsberg, Norway.* Zenodo. DOI:[insert DOI]

## License
This dataset is published under the **Creative Commons Attribution 4.0 International License (CC BY 4.0)**.  
You are free to use, share, and adapt the material with appropriate attribution.

## Contact
**Author:** Thomas Kjær  
**Institution:** Independent researcher
**Email:** tkarlbergkjaer@gmail.com

---
