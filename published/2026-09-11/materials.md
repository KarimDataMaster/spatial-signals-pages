# Materials - 2026-09-11

Status: draft research package under the expanded Spatial Signals flow.

Window: 2026-09-06 through 2026-09-11.

Issue candidate: Week 37, 2026.

Working thesis: GeoAI and spatial technology are moving from demos into operational systems. The strongest signals this week are about trusted data, controlled agent tools, field data capture, validation, and human oversight.

## 1. Main Signals

### NASA / IBM - Lunar Foundation Model

- Basket: global_geoai_signals / papers_preprints.
- Date: 2026-09-10.
- Source: https://d3ccyth396mz21.cloudfront.net/blog/nasa-ibm-lunar-foundation-model
- Verification: PASS, HTTP 200.
- What happened: IBM and NASA released an open multimodal Lunar Foundation Model for analysis of the Moon's surface.
- Why it matters: spatial foundation models are moving beyond Earth observation into planetary mapping, mission planning and resource search.
- Use in issue: strong main signal.

### PNNL - NEPA MCP v0.1.6

- Basket: global_geoai_signals / tools_plugins_releases.
- Date: 2026-09-06.
- Source: https://github.com/pnnl/nepa-mcp/releases/tag/v0.1.6
- Verification: PASS, HTTP 200.
- What happened: NEPA MCP added a read-only Permitting Dashboard server backed by public Federal Permitting Data Portal data.
- Why it matters: a good spatial/regulatory agent is bounded, source-aware and explicit about what it cannot decide.
- Use in issue: strong main signal.

### ICEYE / Sompo Japan - Flood Insights in Insurance Claims

- Basket: global_geoai_signals / commercial_spatial_applications.
- Date: 2026-09-07.
- Source: https://www.iceye.com/newsroom/press-releases/sompo-japan-and-iceye-partner-to-accelerate-flood-claims-response-using-satellite-intelligence
- Verification: PASS, HTTP 200.
- What happened: Sompo Japan will use ICEYE Flood Insights to speed flood response and claims handling.
- Why it matters: satellite intelligence is becoming part of operational insurance workflows, not only post-event reporting.
- Dedup note: adjacent 2026-08-30 issue used ICEYE / Water Institute predictive flood intelligence. This is a different date, partner and operational use case. Treat as follow-up if promoted.
- Use in issue: strong main signal, but phrase as new insurance-operations angle.

### QField 4.3 "Danube"

- Basket: tools_plugins_releases / user_pain_points.
- Date: 2026-09-08.
- Source: https://qfield.org/blog/2026/09/08/qfield-4.3-danube-summer-of-stability/
- Verification: PASS, HTTP 200.
- What happened: QField released a stability-focused field GIS update with bookmark export, camera improvements, QFieldCloud templates, clearer sync flows, local-change review and QR scanning from images.
- Why it matters: operational GeoAI depends on reliable field data before any model sees the data.
- Use in issue: strong main signal or practical stack lead.

### Arctic Eco-Navigation Agent

- Basket: papers_preprints / global_geoai_signals.
- Date: 2026-09-08.
- Source: https://arxiv.org/abs/2609.09374
- Verification: PASS, HTTP 200.
- What happened: new arXiv paper describes a human-in-the-loop multi-agent GeoAI system for Arctic route planning with operational, physical, ecological and community criteria.
- Why it matters: useful example of spatial agents where automation should expose alternatives and trade-offs, not replace human value judgments.
- Use in issue: strong research signal.

### Sentinel Online - CEOS-FRM / Cal/Val Guidelines

- Basket: global_geoai_signals / trusted_data_infrastructure.
- Date: 2026-09-10.
- Source: https://sentinels.copernicus.eu/web/sentinel/-/new-guidelines-for-ceos-frm-and-cal-val-for-copernicus-sentinel-missions
- Verification: PASS, HTTP 200.
- What happened: Sentinel Online published new guidance on Calibration/Validation and Fiducial Reference Measurements for Copernicus Sentinel missions.
- Why it matters: as AI scales satellite-data interpretation, data-quality chains become part of model trust.
- Use in issue: strong trust-layer signal.

## 2. Practical Stack

### CARTO - Agentic GIS in Gemini Enterprise, Claude, Microsoft Copilot and deck.gl

- Basket: global_geoai_signals / tools_plugins_releases / developer_infrastructure.
- Dates: 2026-09-07 to 2026-09-09.
- Sources:
  - https://carto.com/blog/all-of-carto-from-gemini-enterprise/
  - https://carto.com/blog/geospatial-analysis-claude-mcp-server/
  - https://carto.com/blog/agentic-gis-microsoft-copilot/
  - https://carto.com/blog/making-deckgl-ai-ready/
- Verification: PASS, HTTP 200 for promoted pages.
- What happened: CARTO showed how CARTO MCP Server connects to Gemini Enterprise, Claude and Microsoft Copilot Studio, and published a deck.gl AI-readiness analysis.
- Why it matters: spatial analysis is becoming a governed tool surface inside enterprise AI environments, with user-level permissions, warehouse-native execution, row-level security and activity logging.
- Dedup note: adjacent 2026-09-05 issue used CARTO SDI / Portolan. This week use CARTO only as a new agentic-GIS integration and developer-infrastructure signal.
- Use in issue: strong practical stack / main signal.

### QGIS AI / MCP Plugin Cluster

- Basket: tools_plugins_releases.
- Sources:
  - https://plugins.qgis.org/plugins/tags/ai/
  - https://plugins.qgis.org/plugins/tags/mcp/
- Verification: PASS, HTTP 200 for both.
- Current-week observations:
  - 02Agent Smart Modeler updated on 2026-09-06; QGIS 3.44+ and QGIS 4 visual Processing studio with typed graphs and validated AI planning.
  - AI Agent created/updated on 2026-09-01; explores a QGIS project and processes data from a plain-language request.
  - AI GIS AGENT created/updated 2026-09-03/04; multi-agent workflows, MCP connectivity, internet geodata and optional machine learning.
  - WAI QGIS MCP updated on 2026-09-07; lets trusted AI assistants inspect, map and automate QGIS.
- Why it matters: the agent layer is not only in cloud platforms; it is appearing inside desktop GIS and QGIS plugin workflows.
- Use in issue: compact `Практический стек недели` block. Do not overstate maturity; plugins vary in stability and trust model.

### Felt + Databricks GIS Agent

- Basket: tools_plugins_releases / global_geoai_signals.
- Date: 2026-09-01, still current enough as adjacent-week practical context.
- Source: https://felt.com/webinars/building-a-gis-agent-with-felt-and-databricks
- Verification: PASS, HTTP 200.
- What happened: Felt and Databricks showed an agent pattern where a prompt connects data, runs analysis and produces a map app. The stack mentions Lakebase, Postgres/PostGIS, MCP tools and Agent Bricks.
- Why it matters: reinforces the cloud-data-to-map agent pattern outside CARTO.
- Use in issue: practical stack or supporting context, not a main promoted signal if avoiding adjacent-week overlap.

### NextGIS Connect 4

- Basket: ru_cis_market_signals / tools_plugins_releases.
- Date: 2026-09-07.
- Source: https://nextgis.ru/blog/
- Verification: PASS via web open; local HTTP client timed out twice against nextgis.ru. The page opened through the web reader and shows the item.
- What happened: NextGIS blog index lists `NextGIS Connect 4: большое обновление для работы с QGIS и Веб ГИС`, with updated interface, attachments/descriptions and sync capabilities.
- Why it matters: local Russia/CIS market signal around QGIS-to-Web-GIS production workflows.
- Use in issue: `Локальный радар` block, not main signal unless the full article can be fetched and verified.

## 3. Research

### OpenEarthAgent

- Basket: papers_preprints.
- Date: IBM Research publication page dated 2026-09-08; arXiv originally earlier.
- Sources:
  - https://research.ibm.com/publications/openearthagent-a-unified-framework-for-tool-augmented-geospatial-agents
  - https://arxiv.org/abs/2602.17665
  - https://github.com/mbzuai-oryx/OpenEarthAgent
- Verification: search/web verified; use IBM or arXiv as primary if included.
- What happened: framework and dataset for tool-augmented geospatial agents over satellite imagery, GIS data and spectral indices.
- Why it matters: moves from "agent can talk about a map" to benchmarkable tool traces and structured EO reasoning.
- Use in issue: optional research block. Avoid making it look like a new September release if using the arXiv date; IBM page is the current hook.

### GeoNatureAgent Benchmark

- Basket: papers_preprints.
- Date: revised 2026-09-03.
- Source candidate: https://arxiv.org/abs/2606.12821
- Verification: search result surfaced arXiv mirror text; direct primary URL still needs fetch if included.
- What happened: benchmark for environmental geospatial agents using structured tool calls against a production-style geospatial API.
- Why it matters: complements GISAgentBench by measuring real API tool-calling capability and cost/capability trade-offs.
- Use in issue: candidate for research block after direct source verification.

### GISAgentBench

- Basket: papers_preprints.
- Date: 2026-08-03.
- Source: https://arxiv.org/abs/2608.01645
- Verification: public arXiv search result available; direct source should be fetched if included.
- What happened: 349 real-world GIS tasks from GIS Stack Exchange with executable reference trajectories and ground-truth outputs.
- Why it matters: best tested agent solves only 32.7% under strict scoring; useful counterweight to hype.
- Use in issue: optional research context, but likely not current-week unless the issue explicitly has a research-benchmark sidebar.

## 4. Events

### FOSS4G Hiroshima 2026

- Basket: events.
- Date: 2026-08-30 to 2026-09-05.
- Source: https://2026.foss4g.org/
- Verification: web open; event page confirms dates and academic track publication.
- Use in issue: event wrap-up / ecosystem context if needed.

### BUILD with Mapbox 2026

- Basket: events.
- Date: 2026-09-15 to 2026-09-17.
- Source: https://www.mapbox.com/build
- Verification: PASS, HTTP 200.
- Relevant sessions: AI search/local discovery, Atlas v3, Mapbox Location AI tools, Mapbox MCP Server and AI-native risk intelligence.
- Use in issue: event block.

### INTERGEO 2026

- Basket: events.
- Date: 2026-09-15 to 2026-09-17.
- Source: https://dvw.de/intergeo/en/
- Verification: PASS, HTTP 200.
- Relevant theme: geodata, AI and live experiences; world's leading geodesy/geoinformation/land-management event.
- Use in issue: event block.

### UK Earth Observation Conference 2026

- Basket: events.
- Date: 2026-09-15 to 2026-09-17.
- Sources:
  - https://ukeo.org/
  - https://dataspace.copernicus.eu/events
- Verification: PASS, HTTP 200.
- Use in issue: event block for EO community and applications.

### AI & GEO 2026

- Basket: events.
- Date: 2026-09-21 to 2026-09-22.
- Source: https://geoai.cic.ipn.mx/
- Verification: PASS, HTTP 200.
- Use in issue: event block if keeping GeoAI-specific international events.

## 5. User Pain Points / Practical Frictions

Validated from this week's sources rather than informal forums:

- Field data reliability: QField emphasizes crash reduction, camera stability, local-change review and synchronization clarity.
- Trust and validation: Sentinel Cal/Val and FRM guidance show that satellite AI products need observation-quality evidence, not just model metrics.
- Agent control boundaries: NEPA MCP and Arctic Eco-Navigation both keep consequential decisions under human/regulatory control.
- Plugin maturity: QGIS AI/MCP plugin growth is fast, but trust boundaries, permissions, local project access and write operations need careful review before business use.
- Source and sync continuity: NextGIS Connect 4 points to ordinary production needs: attachments, descriptions and synchronization between QGIS and Web GIS.

## 6. Recommended Issue Structure

1. Main thesis: operational trust in GeoAI.
2. Main signals:
   - NASA/IBM Lunar Foundation Model;
   - PNNL NEPA MCP;
   - ICEYE/Sompo Japan;
   - QField 4.3;
   - Arctic Eco-Navigation Agent;
   - Sentinel Cal/Val / FRM.
3. Practical stack week:
   - QGIS AI/MCP plugin cluster;
   - Felt + Databricks GIS agent;
   - QField 4.3, if not already main.
4. Local radar:
   - NextGIS Connect 4.
5. Research:
   - OpenEarthAgent;
   - optional GeoNatureAgent Benchmark after direct arXiv verification.
6. Events:
   - BUILD with Mapbox;
   - INTERGEO;
   - UK EO Conference;
   - AI & GEO.
7. Practical conclusion.
8. What to check for business / hypotheses.

## 7. Do Not Promote Unless User Approves

- PostGIS 3.7.0rc2: adjacent 2026-08-30 issue already promoted rc1; rc2 is a release-candidate follow-up.
- MapServer security/maintenance release: operationally important, but weaker than the current trust/agent thesis.
- General conference listings without product/research delta: keep in events only.
