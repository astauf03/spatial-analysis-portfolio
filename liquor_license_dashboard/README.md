# East Passyunk License Dashboard (Philadelphia)

This project summarizes **active business licenses** and **active PLCB liquor licenses** within the East Passyunk study area to describe corridor-scale dining and nightlife activity.

## View the dashboard
- **Dashboard report (HTML):** `licensingstuff.html`
- **1-page memo (PDF):** `memo2.pdf`

## Data
The business license dataset (`business_licenses.geojson`) is too large to store in this repository.  
To reproduce the analysis, place the file in the local `data/` folder (same structure as the Rmd expects) or update the Rmd to read the dataset from a hosted URL.

**Other included inputs:**
- `data/PHL_PLCB_geocoded.csv`
- `data/study_areas_2025_1.*` (East Passyunk boundary)

## Tools
R (`sf`, `dplyr`, `ggplot2`, `tigris`) + OpenDataPhilly + PLCB licensing data

