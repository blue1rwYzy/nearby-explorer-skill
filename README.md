# nearby-explorer-skill

An Agent Skill that recommends nearby places for a user in one turn. It uses the
Amap (高德) MCP Server for place search and walking-route planning, filters by the
user's walking-time limit, ranks by walking time, returns at most three places,
and says "未核实" (unverified) for anything the tools did not return.

- Skill file: [`nearby-explorer/SKILL.md`](nearby-explorer/SKILL.md)
- Tools used: `maps_geo`, `maps_around_search`, `maps_text_search`, `maps_direction_walking`
- No API key is stored in this repository; configure the Amap MCP Server in your agent.
