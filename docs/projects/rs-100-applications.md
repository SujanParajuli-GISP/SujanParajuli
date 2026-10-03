---
hide:
  - toc
---

# 100 Remote Sensing Applications

*A code-first tutorial series: one working application for each of 100 remote sensing use cases.*

`Python` `PostGIS` `FastAPI` `Docker` `Jupyter` `Google Colab`

!!! info "Overview only"
    This page is a public overview. The full specifications, notebooks and source code are
    used for tutorial and teaching purposes and are **shared on request** —
    [get in touch](../contact.md).

## Overview

Each of the 100 applications on GIS Geography's well-known
[list of remote sensing applications](https://gisgeography.com/remote-sensing-applications/)
becomes one self-contained tutorial that **builds a small, working application** rather than
only describing the idea.

Every application follows the same spec-driven structure:

| Document | Purpose |
|----------|---------|
| `README` | Plain-language tutorial description |
| `requirements` | User stories written in EARS style |
| `design` | Architecture, spatial-database schema, processing pipeline, API, notebook outline, tests and deployment |
| `tasks` | A phased, requirement-linked build checklist |

Applications are built from seven reusable reference architecture patterns — for example
time-series zonal raster analysis, object detection, scheduled monitoring, cloud-native
STAC/COG access, and DEM terrain analysis — so learners see the same ideas applied across
very different domains.

## Coverage — 22 application areas

| Area | Apps | Area | Apps |
|------|:---:|------|:---:|
| Society | 12 | Oceanography | 6 |
| Military | 7 | Weather | 6 |
| Transportation | 7 | Business | 5 |
| Disasters | 5 | Ecology | 5 |
| Government | 5 | Navigation | 5 |
| Agriculture | 4 | Climate change | 4 |
| Environment | 4 | Mining | 4 |
| Arctic / Antarctica | 3 | Crime | 3 |
| Elevation | 3 | Forestry | 3 |
| Hydrology | 3 | Archaeology | 2 |
| Engineering / construction | 2 | Insurance | 2 |

## Status

Specifications are drafted for all 100 applications. Implementation is in progress, starting
with five pilot apps chosen to exercise five different architecture patterns: NDVI crop
condition, parking-lot car counting, volcano thermal monitoring, Copernicus STAC monitoring,
and DEM watershed delineation.

[Request the full materials :material-email:](../contact.md){ .md-button .md-button--primary }
