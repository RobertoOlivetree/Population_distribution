# Population Distribution and Building Analysis in BGRI2021_1312

This repository contains geospatial and demographic data analyses focused on a specific region identified by the BGRI code `BGRI2021_1312`. The analysis integrates building information with population distribution to support spatial planning, urban development, or demographic studies.

## Repository Contents

- **BGRI2021_1312.gpkg**: A GeoPackage file containing the geographic boundaries and relevant spatial data for the area of interest.
- **edificios.csv**: A CSV file listing building-related information such as location, height, usage type, or other attributes (depending on available data).
- **population_distribution.ipynb**: A Jupyter Notebook with the main analysis workflow. This includes:
  - Loading and preprocessing spatial and tabular data.
  - Mapping population density.
  - Visualizing building distribution.
  - Generating summary statistics and visual representations.

## Requirements

To run the notebook, you will need Python and the following libraries:
- `geopandas`
- `pandas`
- `matplotlib`
- `seaborn`
- `jupyter`

You can install them with:

```bash
pip install geopandas pandas matplotlib seaborn notebook
