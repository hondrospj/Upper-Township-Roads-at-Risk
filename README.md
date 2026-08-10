# Upper Township Roads at Risk

Static GitHub Pages app for drawing road and cross-section profiles through the Upper Township municipal DEM.

The interface follows the North Wildwood Roads at Risk reference: threshold presets, NAVD88/MLLW conversion, terrain and hillshade views, saved multi-line cross sections, flood-history and future-frequency charts, and CSV/Shapefile exports.

Municipal constants:

- Observations: USGS 01411320, Ocean City
- PETSS / NOAA station: 8534975
- NAVD88 thresholds: 4.07 ft minor, 5.07 ft moderate, 6.07 ft major
- MLLW thresholds: 6.1 ft minor, 7.1 ft moderate, 8.1 ft major
- MLLW = NAVD88 + 2.03 ft

Terrain source: USGS 3DEP Bare Earth DEM Dynamic ImageServer, clipped to the Upper Township boundary at 8.5-foot adaptive resolution.
