# Presentation of Results in Reflex3D and Calibration in QGIS

## Table of Contents
1. [Objective](#objective)
2. [3D Cube](#3d-cube)
3. [Individual Cut](#individual-cut)
4. [Cuts](#cuts)
5. [Export to QGIS](#export-to-qgis)
6. [Result in QGIS](#result-in-qgis)

---

## Objective
The purpose of these exercises is to demonstrate various methods of interpolating Ground Penetrating Radar (GPR) data in ReflexW to create a 3D representation that provides a quasi-continuous view of subsurface conditions. Interpolation is conducted on pre-processed echograms (filtered and georeferenced), producing a data cube that allows further analysis through suitable visualization and filtering of 3D data. This data cube enables the generation of horizontal cross-sections, known as C-scans, which may be georeferenced and used as raster layers in geospatial software.

> *Note: This exercise follows guidelines provided in class. Some screenshots may differ due to multiple iterations.*

## 3D Cube
The imported data was visualized in ReflexW as a **3D Cube**, representing subsurface conditions in three dimensions.

![image](https://github.com/user-attachments/assets/8b87ded0-7dfb-4204-9deb-3e628386d99d)

*Source: Own work*

## Individual Cut
Following the instructions, an **individual cut** was performed on the data to focus on specific areas of interest.

![image](https://github.com/user-attachments/assets/ac85b6fc-3fec-4af6-97d4-b8690d54a4d1)

*Source: Own work*

## Cuts
Next, parameter adjustments were made to identify values corresponding to vertical alignments in the data, focusing on the vertical continuity of detected structures.

![image](https://github.com/user-attachments/assets/b8a5fe5c-057d-442a-9a07-6d5b72522a0e)

*Source: Own work*

## Export to QGIS
The selected and processed data was exported as a **TIFF** file for integration into **QGIS**, allowing for further spatial analysis and visualization with geospatial tools.

![image](https://github.com/user-attachments/assets/607c1694-bcc5-49c0-a22f-9cf017bda6ce)

*Source: Own work*

## Result in QGIS
The final result of importing the TIFF file into QGIS is displayed below, showing the processed data aligned with geospatial references for further analysis.

![image](https://github.com/user-attachments/assets/2e9a8fde-70b0-4214-b101-bb9279f28cb3)

*Source: Own work*

---
