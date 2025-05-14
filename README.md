# High-Resolution Seismic Depth Sections of the 2024 Noto Peninsula Earthquake

## Overview

This repository presents high-resolution seismic depth sections of the rupture zone associated with the **Mw 7.6 Noto Peninsula earthquake**, which struck Japan on **January 1, 2024, at 07:10:22.5 UTC**. The earthquake caused intense ground shaking, triggered a tsunami, and was identified as a **reverse-fault rupture** consistent with a northwest–southeast-oriented compressional stress regime.

While the rupture mechanism and seismic impacts have been extensively studied, detailed seismic imaging of the **shallow crustal structure** within the rupture zone remained limited. This project addresses that gap by providing the first high-resolution seismic images of the affected region.

## Data Acquisition

- **Organization**: Atmosphere and Ocean Research Institute (AORI), University of Tokyo
- **Survey Vessel**: R/V Hakuho-Maru
- **Survey Period**: March 4–16, 2024
- **Method**: Multichannel Seismic (MCS) Reflection Survey
- **Coverage**: 14 seismic profiles (~45 km each), extending from the western coast of the Noto Peninsula to the northeastern offshore area

## Data Processing Workflow

The acquired MCS data underwent an advanced depth imaging workflow that included:

- **Grid-Based Tomography**: Iterative refinement of the P-wave velocity model
- **Automated Continuity Attributes**: Enhancing reflection coherency
- **Structural Attributes Extraction**: Dip, continuity, and seismic pencil construction
- **Automated Horizon Picking**: Using extracted attributes for horizon tracking
- **Residual Moveout (RMO) Correction**: Optimizing migrated common image gathers

## Results

- High-resolution **2D seismic sections** of the shallow rupture zone
- **3D visualizations** of fault geometry and crustal structures
- Improved understanding of fault segmentation, rupture dynamics, and regional seismotectonics

## Repository Contents

- `/data/`: Processed seismic depth sections (SEG-Y, PNG, XYZ formats)
- `/visualizations/`: 3D rendered images and interactive visualizations
- `/scripts/`: Processing and visualization scripts (Python, MATLAB)
- `/docs/`: Technical report and detailed methodology
- `/notebooks/`: Jupyter notebooks for data exploration and plotting

## Applications

This dataset provides a critical foundation for:

- Fault geometry analysis
- Rupture dynamics modeling
- Seismotectonic framework studies of the Noto Peninsula region
- Tsunami source characterization

## Citation

If you use this dataset or methodology, please cite:

> Mohammadigheymasi, H. et al. (2024). High-Resolution Seismic Imaging of the 2024 Noto Peninsula Earthquake Rupture Zone. Atmosphere and Ocean Research Institute, University of Tokyo.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

This work was supported by the Atmosphere and Ocean Research Institute (AORI) at the University of Tokyo, with data acquisition aboard R/V Hakuho-Maru. We thank the Japan Meteorological Agency (JMA) for providing preliminary seismic analyses and aftershock distributions.
