# Data notes

## GRID3 Nigeria LGA Boundary v3.0
- Source: https://data.grid3.org
- Downloaded: [04/09/2026]
- 774 Features, Polygons
- Columns: FID (Integer), uniq_id (UniqueID), timestamp (time), editor (text), lganame (text),statename (text), statecode (text) , source(text), amapcode (text)
- No nulls in all the column
- Covers my LGA

## OSM roads, extracted via QuickOSM
- Query : roads layer extent in Alimosho LGA
- Extracted: [08/09/2026]
- 22,378 features, lines
- Spatial scope: clipped precisely to Alimosho LGA extent
- Columns: osm_id (integer), full_id (UniqueID), highway (text), name (text), surface (text), maxspeed (null), ref (null)
- No nulls in highway
- Coverage look good in the built-up area and sparse at the edge.

## OSM roads, extracted via QuickOSM
- Query : buildings layer extent in Alimosho LGA
- Extracted: [08/09/2026]
- 564,007 features, Polygon
- Spatial scope: clipped precisely to Alimosho LGA extent
- Columns: osm_id (integer), full_id (UniqueID), osm_type (text), building (text), name (null), amenity (null), brand (null), wheelchair (null)
- No nulls in osm_type
- Coverage look good in the built-up area and sparse at the edge.
