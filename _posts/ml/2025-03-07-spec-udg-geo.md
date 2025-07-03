---
layout: post
title: "Optimal Location of EV Charging Stations"
subtitle: "Spatial Data"
category: machine-learning
tags: ml-projects
---

This project proposes a lightweight, scalable method to locate optimal EV fast-charging stations using Voronoi geometry and a greedy algorithm. It maximizes coverage while avoiding overlap with current infrastructure.

The approach is inspired by *Carlvo-Jurado et al.* (2024), *"Optimal location of electric vehicle charging stations using proximity diagrams"*, published in *Sustainable Cities and Society*.  
[Read the paper](https://www.sciencedirect.com/science/article/pii/S2210670724005444)

Data sources include OpenChargeMap, OpenStreetMap, and city population stats. The pipeline—built in Python with `geopandas`, `shapely`, and `scipy`—identifies high-potential points through spatial filtering and iterative selection.

Preliminary results show promising coverage improvements along strategic transport routes.

## Presentation

<embed src="../../assets/pdf/2025/07/spatial_data_presentation.pdf" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true" type="application/pdf" width="100%" height="600px">


