# 🗾 Japan POI Map — the Nomad Spine

**Japan 2026 trip planner** — 96 points of interest plotted on an interactive map,
auto-generated from the Obsidian POI registry.

## 🔗 Live site
The map lives at the repo root (`index.html`) — visit **https://AnthonyAvram.github.io/japan-poi-map/** to see it.

## What's here
- `index.html` — the interactive map (Leaflet + Esri English-label basemap). Color-coded by region arc:
  - 🟡 **A** — Tokyo → Fuji
  - 🟣 **B** — Nagano → Gifu
  - 🟢 **C** — Kansai (Osaka/Kyoto/Nara)
  - 🔴 **D** — Chugoku (Hiroshima)
  - 🟠 **E** — North Kyushu
  - 🟥 **F** — South Kyushu
  - ⚪ **Z** (grey) — off-spine detours
- `poi-data.csv` — all 96 points (lat/lon), for importing into **Google My Maps**.
- `poi-data.kml` — all 96 as placemarks, for dropping straight into **Google Maps**.

## Regenerating
The map is generated from `Z:/First Vault/MarketT/Travel/POI Registry.json`.
Re-run the generator + re-push `index.html` whenever the registry changes.
