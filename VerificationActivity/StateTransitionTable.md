# Task 5 — Verification Activity

| Check | Transition | Result | Explanation |
| :--- | :--- | :--- | :--- |
| **Check 1 — Invalid Transition** | `IDLE` → `DELIVERING` | **Not Allowed** | The robot must first receive a delivery request and navigate to the destination. |
| **Check 2 — Missing Transition** | `AVOIDING_OBSTACLE` → `NAVIGATING` | **Required** | After avoiding the obstacle, the robot must continue navigating toward the destination. |
| **Check 3 — Obstacle During Delivery** | `AVOIDING_OBSTACLE` → `DELIVERING` | **Not Allowed** | The robot must return to `NAVIGATING` after the obstacle is avoided before it can reach the delivery state. |
