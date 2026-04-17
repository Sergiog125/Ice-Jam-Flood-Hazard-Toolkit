# Operational Toolkit for Flood Hazard Mapping

**Roadmap to empirically formulated, reach-based extrapolated, ice-jam flood hazard assessment**

This repository contains the operational toolkit, datasets, and manual for rapid flood mapping using an empirical proxy method. It was developed to overcome the computational overhead of full 2D hydrodynamic models while maintaining high spatial fidelity for economic risk assessment.

## Authors
* **Karl-Erich Lindenschmidt** (Global Institute for Water Security, School of Environment and Sustainability, University of Saskatchewan)
* **Sergio Gomez Munoz** (Global Institute for Water Security, School of Environment and Sustainability, University of Saskatchewan)

*Developed for the Water Monitoring and Stewardship Division, Environment and Climate Change, Government of the Northwest Territories.*

## Repository Structure

* **`/rating curves prep`**: Contains Excel workbooks, BestFit configurations, and ADCP measurements for staging calibration and extrapolation (Fort Simpson & Jean Marie River).
* **`/10GC001 adcp MACKENZIE RIVER AT FORT SIMPSON`**: Acoustic Doppler Current Profiler (ADCP) data and survey results.
* **`/GUI (Mackenzie River at Fort Simpson)`**: The executable tool (`RiverFloodAnalysis.exe`), MathCad scripts, and template input/output files for point and reach-based Monte-Carlo simulations.
* **`/QGIS_transects (class)`**: Spatial data (LiDAR DTMs, Transect Shapefiles) used for the Geographic Information System mapping steps.

## Documentation & Tutorials
Please refer to the `Lindenschmidt_user manual.pdf` included in this repository for a comprehensive, step-by-step guide.

### Video Tutorials & Slide Decks
The step-by-step video tutorials and accompanying slide decks for this toolkit are hosted on Zenodo due to file size limits. They have been assigned a formal DOI for academic reference.

(https://doi.org/10.5281/zenodo.19636626)

**Contents included in the Zenodo repository:**
* [1] Rating curves (conceptual)
* [2] Site description (Fort Simpson)
* [3] Rating curves (Fort Simpson gauge data)
* [4] Flow and stage frequency distributions (using BestFit)
* [5] (Point) backwater staging of the 2021 ice-jam event (empirical approach)
* [6] Monte-Carlo Analysis (Manning's equation example)
* [7] (Point) ice-jam flood hazard (MOCA approach)
* [8] (Reach) ice-jam flood hazard (Fort Simpson)
* [9] Ice-jam flood mapping of the 2021 event
* [10] Extrapolation of ice-jam flood hazard (to Jean Marie River)

## Disclaimer
Please note, this user manual and its associated videos, data sets and coding scripts, are the product of an applied science endeavour. The methodologies used in generating the research results contained herein are novel, and further testing is required to verify the methodology’s robustness. While every effort has been made to ensure the accuracy and completeness of the information contained herein, neither the authors nor the University of Saskatchewan make any guarantee, nor do they assume any liability for any errors or omissions. The information provided is on an 'as is' basis and the authors and University of Saskatchewan disclaim all warranties, express or implied, including but not limited to, implied warranties of merchantability or fitness for a particular purpose.

