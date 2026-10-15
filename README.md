# California Camp Finder

A free web map for finding dispersed camping on public land in California.

## Layers

- **Base maps:** USGS Topo, USGS satellite imagery, OpenTopoMap
- **Terrain:** 3D terrain, hillshade, contour lines (feet)
- **Land ownership:** BLM Surface Management Agency (BLM, Forest Service, NPS, state, military, tribal), California Protected Areas Database parks, federal wilderness areas
- **Roads and trails:** Forest Service Motor Vehicle Use Maps (MVUM), BLM roads and trails, Forest Service trails
- **Camping:** Forest Service campgrounds and dispersed camping areas, BLM campgrounds, OpenStreetMap campsites
- **Hazards:** active fire perimeters (NIFC)

Click anywhere on the map for a **"Can I camp here?"** check: land manager, wilderness, parks, active fire, elevation, ground slope and the nearest legal Forest Service road.

## Run locally

```
powershell -NoProfile -ExecutionPolicy Bypass -File serve.ps1
```

Then open http://localhost:8642.

## Data sources

USGS The National Map and 3DEP, BLM, USDA Forest Service, NIFC, GreenInfo Network (CPAD), Wilderness Connect, © OpenStreetMap contributors. All data loads live from public services.

Boundaries and rules shown are approximate. Always follow posted signs, current fire restrictions and the forest's printed MVUM.
