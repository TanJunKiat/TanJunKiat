- 👋 Hi, I’m Tan Jun Kiat (@TanJunKiat)
- 👀 I’m interested in Robotics (design, control development and implementation) 
- 💞️ I’m looking to collaborate on any robotics project
- 📫 Reach me via my email (tanjunkiat@outlook.sg)

<!---
TanJunKiat/TanJunKiat is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

## RMF Dependencies path
```mermaid
flowchart LR
A(level panel) -->|/level_param| B["update_level()"]
B -->C["update_map()"]
D[(RMF)] -->|/map| E["get_map()"]
E -->C["update_map()"]
subgraph "update_map() function"
C -->F["get_walls()"]
C -->G["get_nav_graphs()"]
C -->H["get_floors()"]
C -->I["get_lift()"]

F -->J["get_vertices()"]
F -->K["get_edges()"]

G -->L["get_nav_graph_markers()"]
L -->J
L -->K

G -->M["create_lane_marker()"]
G -->N["create_vertex_marker()"]
N -->O["create_text_marker()"]

I -->P["rotate_vertex()"]
I -->Q["get_lift_wall_marker()"]
end
C--> |/rmf_dd_building| Z[("Digital Twin")]
```
