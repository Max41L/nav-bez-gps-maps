# nav-bez-gps maps

Offline map data for the nav-bez-gps Android app, one download per region of Ukraine (25 regions), in GitHub Releases:

- `<region>.mbtiles` - vector tiles, OpenMapTiles schema, zoom 0-14, built with planetiler from Geofabrik `ukraine-latest.osm.pbf`
- `<region>.roads` - road graph pack (cells of 0.5 x 0.75 degrees) for the app's map matching
- `manifest.json` - sizes, SHA-256 and URLs of every file

Licences: map data (c) OpenStreetMap contributors, ODbL 1.0 (https://www.openstreetmap.org/copyright);
tiles (c) OpenMapTiles, CC-BY 4.0 (https://github.com/openmaptiles/openmaptiles#license).
Maps made with these tiles must show: (c) OpenMapTiles (c) OpenStreetMap contributors
