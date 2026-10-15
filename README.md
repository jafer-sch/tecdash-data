# Saudi Arabia offline data

Data-only distribution. Version: saudi-2026-10-15. OSM data timestamp: 2026-10-14T20:21:12Z.
Source: Geofabrik OpenStreetMap GCC extract, cropped to the Saudi admin_level=2 boundary; complete border ways are retained. © OpenStreetMap contributors · OpenMapTiles. See LICENSE.md and ATTRIBUTION.md.

Download the versioned assets from Releases. The stable discovery URL is releases/latest/download/manifest.json. Downloads are public and require no authentication. The manifest pins the versioned downloadBase, source date, engine compatibility, byte sizes and SHA256 hashes.
Logical files: map.pmtiles (OpenMapTiles schema), places.sqlite (Arabic search/POIs/limits/cameras), resources.zip (local styles/fonts/sprites/licenses/config), routing.zip (Valhalla graph).
Every uploaded asset is smaller than 2GiB. A logical file at or above 2GiB is split into 1GiB parts (last part may be smaller). Its manifest parts array is ordered and includes each part's name, bytes and SHA256. Verify every part, concatenate in that exact order, then verify the resulting logical file's bytes and SHA256. Do not unzip or activate it before verification. Unsplit files are verified directly. Example: sha256sum map.pmtiles.part0001; cat map.pmtiles.part0001 map.pmtiles.part0002 > map.pmtiles; sha256sum map.pmtiles. Use all parts listed, including a shorter final part.

The geographic data is ODbL 1.0; supporting fonts/styles have their own bundled licenses. Package generation happens separately; only explicitly listed, verified data assets and these public documents are published. No application code, key, token or private build log belongs in this repository.
