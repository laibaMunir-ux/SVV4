# Task 1 — Extract Requirements

| **Req. ID** | **Requirement**                                                                                                       |
| ----------- | --------------------------------------------------------------------------------------------------------------------- |
| **R1**      | The robot shall remain in **IDLE** until a delivery request is received.                                              |
| **R2**      | When a delivery request is received, the robot shall change to **NAVIGATING**.                                        |
| **R3**      | The robot shall continuously monitor its surroundings while navigating.                                               |
| **R4**      | When an obstacle is detected, the robot shall enter **AVOIDING_OBSTACLE**.                                            |
| **R5**      | After avoiding the obstacle, the robot shall return to **NAVIGATING**.                                                |
| **R6**      | When the destination is reached, the robot shall enter **DELIVERING**.                                                |
| **R7**      | After successful delivery, the robot shall enter **RETURNING**.                                                       |
| **R8**      | When the warehouse is reached, the robot shall return to **IDLE**.                                                    |
| **R9**      | If the battery becomes critically low during navigation, the robot shall enter **RETURNING**.                         |
| **R10**     | The robot shall not move directly from **IDLE** to **DELIVERING** or enter **DELIVERING** while avoiding an obstacle. |

