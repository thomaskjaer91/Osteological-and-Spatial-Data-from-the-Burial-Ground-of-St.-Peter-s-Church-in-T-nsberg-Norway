# Osteological and Spatial Data from the Burial Ground of St. Peter’s Church in Tønsberg, Norway

## Description
This dataset contains **vectorized and georeferenced osteological data** from the medieval burial ground of **St. Peter’s Church (Peterskirken)** in Tønsberg, Norway.

A total of **407 individuals** are represented, each linked to spatial coordinates (ETRS89 / UTM zone 32N). Attributes include estimated sex, age category, age range, stature, and distance to the nearest point of the church.

The dataset was digitized and georeferenced in **QGIS**, based on excavation drawings and osteological records from the **1983 and 1985 excavations**, originally analyzed at the **Anatomical Institute, University of Oslo**.

## Contents
- `Osteological_and_Spatial_Data_Peterskirken.csv` – Main dataset of 407 individuals  
- `metadata.csv` – Machine-readable metadata (duplicated in the README for human readability)  
- `README.md` – Project description, human-readable metadata, and citation information

## Metadata

| **Variable** | **Description** |
|---------------|-----------------|
| **Title** | Osteological and Spatial Data from the Burial Ground of St. Peter’s Church in Tønsberg, Norway |
| **Creator** | Thomas Kjær |
| **Creator_ORCID** | [https://orcid.org/0009-0001-5858-4112](https://orcid.org/0009-0001-5858-4112) |
| **Institution** | Independent |
| **Contact_Email** | tkarlbergkjaer@gmail.com |
| **License** | CC BY 4.0 |
| **Coordinate_System** | ETRS89 / UTM zone 32N (EPSG:25832) |
| **Spatial_Accuracy** | ±2 m |
| **Measurement_Methods** | Manually georeferenced and vectorized in QGIS from original excavation drawings. |
| **Sex_Determination** | Based on Holck (1989) and Sælebakke (1986). Morphological assessment of sex following criteria defined by the Anatomical Institute, University of Oslo. |
| **Age_Estimation** | Based on Holck (1989) and Sælebakke (1986). Age categories follow Sjøvold (1978). |
| **Stature_Estimation** | Based on Holck (1989) and Sælebakke (1986). Stature estimated from long bone measurements using Manouvrier’s (1893) method. |
| **Church_distance_m** | Calculated distance in meters from each burial to the nearest point of the church wall (in QGIS). |
| **Age_category** | After Sjøvold (1978) and Holck (1989): Infant = 0–1, Infans I = 1–7, Infans II = 5–14, Juvenis = 10–24, Adultus = 18–44, Maturus = 35–64, Senilis = 50–70. Adult* = Individuals identified as adults without group assignment. |
| **Data_Version** | 1.0 |
| **Date_of_Publication** | 2025-10-09 |
| **HS** | Human skeleton (HS) is defined as a minimum of two skeletal elements uncovered *in situ* and assessed during excavation as belonging to the same individual. |
| **HS_nr** | Sequential numbering system used during fieldwork to identify human skeletal remains. |
| **Data_Collection** | All data were originally collected during excavations by Flodin, Germer and Lind (1982) and Blohmè and Runeby (1985). This dataset provides a compiled and digitized version of their work. |

## Spatial Reference
- **Coordinate system:** ETRS89 / UTM zone 32N (EPSG:25832)  
- **Spatial accuracy:** ±2 m (manual georeferencing in QGIS)  

## Methodological Notes
The dataset was produced by vectorizing original excavation drawings and linking each burial to its corresponding osteological record.  
Sex and age estimations are morphological assessments following **Holck (1989)**.  
Distance to church was calculated in QGIS using the “Distance to Nearest Hub” algorithm.  

## How to cite
Kjær, Thomas (2025). *Osteological and Spatial Data from the Burial Ground of St. Peter’s Church in Tønsberg, Norway.* Zenodo. DOI: 

## License
This dataset is published under the **Creative Commons Attribution 4.0 International License (CC BY 4.0)**.  
You are free to use, share, and adapt the material with appropriate attribution.

## Contact
**Author:** Thomas Kjær  
**Institution:** Independent researcher
**Email:** tkarlbergkjaer@gmail.com

---
