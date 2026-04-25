# KNOWING Transferability Assessment Framework

> Deliverable D3.6 · KNOWING Project · Horizon Europe GA 101056841

One-sentence pitch + badges (license, DOI, project website).

---

## Overview
[The full description paragraph drafted earlier goes here]

## Framework Architecture
Brief description of the Four-Tier structure with weights (40–25–15–20)
and the Gower distance scoring approach. One diagram or table.

## Repository Structure
Directory tree of the repo with one-line descriptions per folder.

## Requirements
- PostgreSQL ≥ 14 + PostGIS ≥ 3.3
- GeoServer ≥ 2.24
- Python ≥ 3.10 (dependencies via requirements.txt / pyproject.toml)
- GDAL / ogr2ogr

## Installation & Setup
1. Clone the repo
2. Create the `knowing` schema (link to SQL script)
3. Load GeoPackage data via ogr2ogr (example command)
4. Configure GeoServer datastore and SQL View
5. Run the ingestion pipeline

## Data Sources
Table listing each indicator group, source (Eurostat, Copernicus, ERA5…),
and update frequency.

## Usage
### Running the similarity pipeline
### Querying via GeoServer WMS/WFS
### Reproducing D3.6 results

## Demonstrator Regions
Short table: South Westphalia · Granollers · Naples/Murcia · Tallinn
with their assigned Climate Impact Contexts.

## Citation
BibTeX block for the deliverable.

## Acknowledgements
Horizon Europe funding statement (mandatory for EU projects).

## License
[See below]
