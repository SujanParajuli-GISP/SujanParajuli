---
hide:
  - toc
---

# Geodatabase Management for Backend GIS Developers

*A code-first PostgreSQL / PostGIS course, rebuilt from scratch as runnable notebooks.*

`PostgreSQL` `PostGIS` `SQL` `FastAPI` `GeoAlchemy2` `Folium` `Google Colab`

## Overview

A redesign of a graduate-level spatial-database course for people who want **backend and
database skills rather than desktop GIS skills**. It keeps a 12-week concept sequence but
replaces GUI loaders and static teaching databases with notebooks that install their own
PostgreSQL + PostGIS, pull live open data (no manual downloads, no API keys), and finish with
a capstone that wraps the finished geodatabase in a REST API.

Every notebook runs top-to-bottom in Google Colab, creates and tears down its own database,
and combines theory, fully commented SQL and Python, and an interactive `folium` map wherever
geometry is involved.

## Curriculum

| # | Module | What it covers |
|---|--------|----------------|
| 00 | Setup & spatial databases | Why a spatial RDBMS beats shapefiles; PostGIS architecture; installing Postgres in Colab |
| 01 | SQL foundations | SELECT / WHERE, boolean logic, string functions, aggregates |
| 02 | Spatial data types | Geometry vs. geography, WKT / WKB, constructors, buffering |
| 03 | Schema design & migration | Normalising a legacy schema, type mapping, parameterised inserts |
| 04 | Coordinate reference systems | SRIDs, `ST_Transform`, planar vs. spheroidal measurement |
| 05 | Spatial database design | ER modelling and cardinality on real national-park data |
| 06 | Spatial queries & DE-9IM | Named spatial predicates, `ST_Relate`, ranking |
| 07 | Spatial joins & processing | Spatial vs. attribute joins, GeoJSON / KML output |
| 08 | Geocoding | Batch and reverse geocoding, PostGIS caching, rate-limit-aware clients |
| 09 | Proximity & KNN | `ST_DWithin`, KNN operators, window functions |
| 10 | Topology | `postgis_topology`, shared edges and faces, validation |
| 11 | Views, triggers & inheritance | Updatable views, audit triggers, table inheritance |
| 12 | Spatial indexing & performance | GiST indexes, `EXPLAIN ANALYZE`, VACUUM / ANALYZE |
| — | **Capstone: backend API** | FastAPI + GeoAlchemy2 service with GeoJSON endpoints, KNN search and cache-first geocoding |

## Highlights

- **Fully reproducible** — no module depends on another's database.
- **Open data throughout** — e.g. NYC Open Data subway stations and neighbourhoods.
- **Production-flavoured** — Docker Compose, tests and a deployable API in the capstone.

[Ask about access :material-email:](../contact.md){ .md-button }
