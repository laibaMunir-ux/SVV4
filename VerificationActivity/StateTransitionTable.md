Task 5 — Verification Activity
Check 1 — Invalid Transition
Transition	Result	Explanation
IDLE → DELIVERING	Not Allowed	The robot must first receive a delivery request and navigate to the destination.
Check 2 — Missing Transition
Transition	Result	Explanation
AVOIDING_OBSTACLE → NAVIGATING	Required	After avoiding the obstacle, the robot must continue navigating toward the destination.
Check 3 — Obstacle During Delivery
Transition	Result	Explanation
AVOIDING_OBSTACLE → DELIVERING	Not Allowed	The robot must return to NAVIGATING after the obstacle is avoided before it can reach the delivery state.
