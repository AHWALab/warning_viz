# warning_viz

Interactive visualization of the UQ flood potential prototype for Guatemala, developed under the WMO supported early warning activities (University of Iowa and Guatemalan partners, AHWA Lab).

**Live site:** https://ahwalab.github.io/warning_viz/

The page is a single self contained file (`index.html`, about 8 MB). It needs an internet connection only for the basemap tiles.

## What it shows

Uncertainty quantified flood potential from the TITO EF5 CREST ensemble for the hydrometeorological event of 20 to 22 June 2023, at two scales with the same classes and colors:

- 90 m, Villalobos basin (metropolitan pilot)
- 900 m, national domain

Flood potential classes on maximum unit streamflow in m3/s per km2, FLASH style Low to High: under 0.5 no signal, 0.5 to 1 Low, 1 to 2 Moderate, 2 to 4 High, 4 and up Very high. Two views: A, hazard and layers; B, impact adjusted through a likelihood by impact matrix using municipal vulnerability and exposure. Additional layers: ensemble probability, EF5 maximum unit streamflow percentiles (p5, median, p95, forecast and QPE), QPE verification, INE communities, flood prone settlements, municipal data, roads, and the official CONRED reports of the event.

This product shows flood potential. Issuing official warnings remains the mandate of the national institutions. Prototype, not operational.

## Data and credits

TITO EF5 hindcast (StormLab 50 member forecast ensemble, STREAM-Sat 10 member QPE ensemble). Thematic layers: INE 2018 census, SEGEPLAN MARN flood prone settlements and vulnerability index, INFORM components, IGN boundaries, CONRED event reports. Basemaps: OpenStreetMap, CARTO, Esri.
