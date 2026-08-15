# warning_viz

Warning Products Portal for the UQ flood potential prototype, Guatemala. Developed under the WMO supported early warning activities (University of Iowa and Guatemalan partners, AHWA Lab).

**Live site:** https://ahwalab.github.io/warning_viz/

## Files

- `index.html` bilingual landing page, Warning Products Portal | Portal de Productos de Aviso
- `en.html` flood potential application, English
- `es.html` aplicacion de potencial de inundacion, Spanish

The two applications are self contained (about 8 MB each) and include a language switch in the header, so visitors can change language at any time. Internet is needed only for the basemap tiles.

## What it shows

Uncertainty quantified flood potential from the TITO EF5 CREST ensemble for the event of 20 to 22 June 2023, at 90 m (Villalobos basin) and 900 m (national domain). Flood potential classes on maximum unit streamflow in m3/s per km2, FLASH style Low to High: under 0.5 no signal, 0.5 to 1 Low, 1 to 2 Moderate, 2 to 4 High, 4 and up Very high. Views: A, hazard and layers; B, impact adjusted (likelihood by impact matrix with municipal vulnerability and exposure). Additional layers: ensemble probability, EF5 maximum unit streamflow percentiles (p5, median, p95, forecast and QPE), QPE verification, INE communities, flood prone settlements, municipal data, roads, and the official CONRED reports of the event.

This product shows flood potential. Issuing official warnings remains the mandate of the national institutions. Prototype, not operational.

## Data and credits

TITO EF5 hindcast (StormLab 50 member forecast ensemble, STREAM-Sat 10 member QPE ensemble). Thematic layers: INE 2018 census, SEGEPLAN MARN flood prone settlements and vulnerability index, INFORM components, IGN boundaries, CONRED event reports. Basemaps: OpenStreetMap, CARTO, Esri.
