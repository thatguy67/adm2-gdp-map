# World ADM-2 GDP Explorer

Interactive choropleth of **48,009 second-level administrative regions** (GADM 4.1),
shaded by **GDP per capita (PPP, 2022)**, with per-region GDP totals and
provenance on hover.

- **Boundaries:** GADM 4.1 (free for non-commercial use)
- **GDP:** Kummu, M. et al. (2025), *Downscaled gridded global dataset for GDP
  per capita (PPP) over 1990–2022*, **Scientific Data** 12:567 (CC-BY-4.0) —
  compiled admin-2 statistics where available, modelled grid estimates elsewhere;
  every value is tagged with its source on hover.
- **Rendering:** MapLibre GL (WebGL) + PMTiles vector tiles, generated with
  tippecanoe.

## Run locally

Any static file server works (PMTiles needs HTTP, not `file://`):

```bash
python3 -m http.server 8000
# open http://localhost:8000
```
