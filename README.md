# nav-bez-gps maps

Offline map data for the nav-bez-gps Android app, one download per region of Ukraine (25 regions), in GitHub Releases:

- `<region>.mbtiles` - vector tiles, OpenMapTiles schema, zoom 0-14, built with planetiler from Geofabrik `ukraine-latest.osm.pbf`
- `<region>.roads` - road graph pack (cells of 0.25 x 0.375 degrees) for the app's map matching
- `<region>.places` (from release `maps-2026-10-31`) - places, house numbers and streets with their old and Russian
  names for the map's labels and the offline address search (gzip text, format in the app's `tools/build_places.py`);
  Dnipro street renames of the city council (2015, 2016, 2022) merged in where OpenStreetMap lacked them
- `manifest.json` - sizes, SHA-256 and URLs of every file; from `maps-2026-10-31` on it lists the tiles and roads of
  `maps-2026-10-23` (`tiles_release`: tiles of two releases must not be merged) and the places of its own release

Licences: map data (c) OpenStreetMap contributors, ODbL 1.0 (https://www.openstreetmap.org/copyright);
tiles (c) OpenMapTiles, CC-BY 4.0 (https://github.com/openmaptiles/openmaptiles#license).
Maps made with these tiles must show: (c) OpenMapTiles (c) OpenStreetMap contributors
Places packs: a derived database of OpenStreetMap, offered under ODbL 1.0 like the rest.
