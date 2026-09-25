Неделя 39 · 25.09.2026

GeoAI уходит от идеи "чат поверх карты".

Главный сдвиг недели: пространственные данные и операции становятся инфраструктурой, которую AI-агент может вызывать напрямую, а поверх нее уже строятся отраслевые решения.

2ГИС выпустил собственный MCP-сервер. Агент получает поиск организаций, геокодирование, маршруты, изохроны и статические карты. Это не отдельный "AI API", а новый способ доступа к существующим геосервисам.
Источник: https://docs.2gis.com/api/ai/mcp-server

Felt вместе с Databricks показал следующий уровень: пользователь задает вопрос в Slack, агент сам находит данные, пишет пространственный SQL в PostGIS и собирает карту риска пожаров для энергетической инфраструктуры.
Источник: https://felt.com/blog/gis-agent-databricks-felt-mcp-server

Похожий MCP-слой уже есть у Mapbox, TomTom, Google Maps, Esri и CARTO. Но глубина разная: от поиска и маршрутизации до полноценного GIS с SQL, загрузкой данных и пространственным анализом.

Параллельно растут вертикальные сценарии: Niantic тестирует национальный VPS в Сингапуре, GeoIntelX связывает геологические данные с пространственным контекстом, Land id делает AI вокруг недвижимости.
Источник: https://nianticspatial.com/blog/singapore-land-authority

Итог:

карта → инструменты → агент → предметная модель → решение.

Вопрос "есть ли MCP?" быстро станет неинтересным. Важнее, какие данные и пространственные действия реально доступны агенту.

Источники:
2ГИС — https://docs.2gis.com/api/ai/mcp-server
Felt — https://felt.com/blog/gis-agent-databricks-felt-mcp-server
Mapbox — https://docs.mapbox.com/location-ai/mcp-servers/mcp-server/
Niantic — https://nianticspatial.com/blog/singapore-land-authority

Подробный выпуск:
https://karimdatamaster.github.io/spatial-signals-pages/2026/09/25/maps-to-agent-infrastructure/