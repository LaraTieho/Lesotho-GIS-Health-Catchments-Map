# Lesotho Health Facilities Catchments Map

WebGIS portal for the Lesotho National GIS Catchments Mapping initiative.

This portal supports primary health care planning, EPI microplanning, outreach prioritization, supportive supervision, service access analysis, and equitable service delivery across all 10 districts of Lesotho. It presents district catchments together with villages, schools, roads, settlement extents, and health facilities in a single operational geospatial reference.

## Overview

The Lesotho GIS Catchments Mapping project provides a national planning framework that links villages and settlements to health facilities through validated catchments and documented access constraints. The WebGIS is intended for use by the Ministry of Health, district health teams, and approved partners as a common reference for planning, review, and update workflows.

The portal was generated from a QGIS/qgis2web export and uses Leaflet for interactive web mapping. It includes an OpenStreetMap basemap and a labels overlay for contextual reference.

## Objectives

- Provide a validated WebGIS reference for health catchments in Lesotho.
- Support EPI outreach planning, supervision, stock planning, and microplanning.
- Improve catchment accountability by linking settlements to health facilities.
- Document access constraints such as poor roads, bridges, terrain, and transport limitations.
- Maintain a single operational geospatial reference layer for planning and review.

## Scope

The portal covers all 10 districts of Lesotho and reflects the national catchment mapping exercise. It includes district boundaries, catchment polygons, settlement extents, roads, schools, health facilities, and villages.

## Data Layers

The portal currently organizes the following layers:

- **District boundaries**
- **Health facility catchments**
- **Settlement extents**
- **Roads**
- **Schools**
- **Health facilities**
- **Villages**

Layer visibility and styling are controlled through the map layer tree.

## Data Sources

The portal is based on the following source datasets:

- HMIS-collected village, school, road, and facility data
- Lesotho Survey and Physical Planning Department, Ministry of Local Government, Chieftainship, Home Affairs and Police
- Ministry of Education and Training
- Roads Directorate, Ministry of Public Works and Transport
- GRID3 Lesotho Settlement Extents Version 02
- Geospatial catchments developed during the national mapping initiative

## How the Data Was Developed

The catchment framework was produced through:

- desk-based spatial analysis
- satellite imagery review
- district-level validation
- field mapping and QA/QC
- reconciliation of village and settlement records
- review of road connectivity and geographic barriers

The workflow was designed to produce operational outputs that are suitable for PHC and immunization planning, not only map display.

## Intended Use

This portal is designed to support:

- PHC planning
- EPI microplanning
- outreach planning
- defaulter tracing
- supportive supervision
- commodity and stock planning
- hard-to-reach prioritization
- district and partner coordination

## Important Notes

- This is an **operational planning** tool, not a legal boundary dataset.
- Users should rely on the **latest validated version** of each layer.
- District and facility-level validation remains important for keeping the data current and credible.
- Changes to source datasets should follow the project’s stewardship and approval workflow.

## Metadata and Version Control

Each published layer should include:

- Title
- Abstract
- Credits
- Use constraints
- Contact
- Version number
- Update date
- CRS
- Source lineage

A changelog should be maintained for all updates to the portal or underlying GeoPackage files.

## Getting Started

To run the portal locally:

1. Download or clone the repository.
2. Open `index.html` in a browser, or serve the folder through a local web server.
3. Ensure the `css/`, `js/`, `data/`, and `markers/` folders remain in place.
4. Open the map and use the layer tree to toggle districts and thematic layers.
5. Review the metadata and legend before using the map for decision-making.

## Repository Structure

```text
.
├── index.html
├── css/
├── data/
├── js/
├── markers/
├── legend/
├── docs/
└── README.md
