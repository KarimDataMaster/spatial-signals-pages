Week 39 · 2026-09-25

GeoAI is moving beyond the idea of “chat on top of a map.”

The more important shift is architectural: spatial data and geospatial operations are becoming callable infrastructure for AI agents.

2GIS released its own MCP server this week. An agent can now call POI search, geocoding, reverse geocoding, routing, isochrones and static maps through a standard MCP interface rather than through a custom integration for every assistant.
Source: https://docs.2gis.com/api/ai/mcp-server

Felt + Databricks showed the next layer. A user asked a wildfire-risk question in Slack; agents found the relevant datasets, ran spatial SQL in PostGIS and produced a live map of exposed energy infrastructure.
Source: https://felt.com/blog/gis-agent-databricks-felt-mcp-server

This is broader than two companies. Mapbox, TomTom, Google Maps, Esri and CARTO are all exposing parts of their spatial stacks to agents through MCP. The depth varies dramatically: some provide search and routing, while others expose SQL, data ingestion, map creation and spatial analysis.
Source: https://docs.mapbox.com/location-ai/mcp-servers/mcp-server/

At the same time, domain-specific GeoAI is becoming more visible. Niantic is testing a national Visual Positioning System in Singapore, GeoIntelX is organizing geoscience knowledge spatially, and Land id is building AI around property and land decisions.
Source: https://nianticspatial.com/blog/singapore-land-authority

The emerging stack looks like:

spatial data → tools → agent → domain model → decision

That changes the competitive question.

“Do you support MCP?” will likely stop being interesting very quickly.

The real differentiation is: what data, spatial operations and controlled actions can an agent actually use?

Sources:
2GIS — https://docs.2gis.com/api/ai/mcp-server
Felt — https://felt.com/blog/gis-agent-databricks-felt-mcp-server
Mapbox — https://docs.mapbox.com/location-ai/mcp-servers/mcp-server/
Niantic — https://nianticspatial.com/blog/singapore-land-authority

Full Spatial Signals issue:
https://karimdatamaster.github.io/spatial-signals-pages/2026/09/25/maps-to-agent-infrastructure/