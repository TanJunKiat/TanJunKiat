- 👋 Hi, I’m Tan Jun Kiat (@TanJunKiat)
- 👀 I’m interested in Robotics (design, control development and implementation) 
- 💞️ I’m looking to collaborate on any robotics project
- 📫 Reach me via my email (tanjunkiat@outlook.sg)

<!---
TanJunKiat/TanJunKiat is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

```mermaid
flowchart LR


H("rmf_task_sequence")
M("rmf_task")
O("rmf_traffic_examples")
P("rmf_robot_sim_gz_plugins")
Q("rmf_robot_sim_gz_classic_plugins")
R("rmf_battery")
Y("rmf_traffic")
AA("rmf_robot_sim_common")
AF("rmf_building_sim_gz_plugins")
AG("rmf_building_sim_gz_classic_plugins")
AL("rmf_utils")
AO("rmf_building_sim_common")
AR("rmf_visualization_msgs")
AY("rmf_gz_ros2_bridge")
BF("rmf_building_map_msgs")
BG("rmf_api_msgs")
BH("pybind11_json_vendor")
BI("nlohmann_json_schema_validator_vendor")
BJ("menge_vendor")
BK("ament_cmake_catch2")

subgraph "rmf_internal_msgs repository"
BE("rmf_charger_msgs")
BB("rmf_dispenser_msgs")
AZ("rmf_fleet_msgs")
BA("rmf_door_msgs")
AX("rmf_lift_msgs")
AN("rmf_ingestor_msgs")
AV("rmf_scheduler_msgs")
AW("rmf_obstacle_msgs")
AU("rmf_site_map_msgs")
AM("rmf_task_msgs")
AQ("rmf_workcell_msgs")
AS("rmf_traffic_msgs")
end


subgraph "rmf_demos repository"
A("rmf_demos_gz_classic")
B("rmf_demos_gz")
C("rmf_demos")
BD("rmf_demos_assets")
AB("rmf_demos_tasks")
AC("rmf_demos_panel")
AD("rmf_demos_maps")
AE("rmf_demos_bridges")
BC("rmf_demos_dashboard_resources")
D("rmf_demos_fleet_adapter")
end

subgraph "rmf_traffic_editor repository"
AP("rmf_building_map_tools")
AT("rmf_traffic_editor_assets")
W("rmf_traffic_editor_test_maps")
T("rmf_traffic_editor")
end


subgraph "rmf_visualisation repository"
G("rmf_visualization")
I("rmf_visualization_schedule")
J("rmf_visualization_rviz2_plugins")
K("rmf_visualization_navgraphs")
T("rmf_visualization_obstacles")
U("rmf_visualization_floorplans")
V("rmf_visualization_fleet_states")
AH("rmf_visualization_walls")
AI("rmf_visualization_sensors")
AJ("rmf_visualization_sensor_range")
AK("rmf_visualization_building_systems")
end

subgraph "rmf_ros2 repository"
E("rmf_fleet_adapter_python")
F("rmf_fleet_adapter")
Z("rmf_sensor_manager")
N("rmf_traffic_ros2")
L("rmf_task_ros2")
S("rmf_websocket")
end

A --> C
A --> AG
A --> Q
B --> C
B --> P
B --> AF
C --> N
C --> BD
C --> AB
C --> D
C --> AC
C --> L
C --> F
C --> AD
C --> AP
C --> G
D --> AZ
D --> AM
D --> E
E --> BH
E --> F
F --> S
F --> BA
F --> H
F --> BB
F --> Y
F --> BF
F --> L
F --> BG
F --> R
F --> M
F --> AL
F --> AN
F --> N
F --> AM
F --> AX
F --> AZ
F --> BI
F --> AW
F --> BK
G --> U
G --> I
G --> AK
G --> J
G --> AH
G --> AJ
G --> K
G --> AI
G --> V
G --> T
H --> M
H --> BI
H --> BG
H --> BK
I --> N
I --> Y
I --> AS
I --> AR
I --> AL
J --> N
J --> AX
J --> BA
J --> AR
J --> AL
K --> N
K --> Y
K --> AZ
K --> BF
K --> AR
K --> AL
L --> N
L --> AM
L --> Y
L --> S
L --> BI
L --> AL
L --> BG
L --> BK
M --> AL
M --> R
M --> BK
N --> Y
N --> AS
N --> AZ
N --> BF
N --> AL
N --> AU
N --> BK
O --> Y
P --> AZ
P --> BF
P --> AA
Q --> AZ
Q --> BF
Q --> AA
R --> Y
R --> AL
R --> BK
S --> BI
S --> AL
S --> BK
T --> AW
T --> AR
T --> AL
U --> BF
U --> AR
U --> AL
V --> AZ
V --> AR
V --> AL
W --> AP
T --> AL
Y --> AL
Y --> BK
Z --> BF
Z --> AW
Z --> AL
AA --> BB
AA --> AZ
AA --> BF
AA --> AN
AB --> AM
AB --> AZ
AB --> BB
AB --> AX
AC --> AM
AC --> AZ
AC --> BC
AD --> AP
AE --> AS
AE --> AZ
AE --> AP
AE --> AU
AF --> BJ
AF --> AO
AF --> AZ
AG --> BJ
AG --> AO
AG --> AZ
AH --> AX
AH --> BA
AH --> BF
AH --> AR
AI --> BF
AI --> AR
AJ --> BF
AJ --> AR
AK --> AX
AK --> BA
AK --> BF
AK --> AR
AL --> BK
AM --> BB
AN --> BB
AO --> AX
AO --> BJ
AO --> BA
AO --> BF
AP --> BF
AP --> AU

```




