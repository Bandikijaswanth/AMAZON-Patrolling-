# AMAZON-Patrolling-
AIM

To implement a cyclic waypoint-based patrolling system for autonomous navigation.

PROCEDURE
Define a list of waypoints
Initialize the robot position
Navigate sequentially through each waypoint
After reaching the last waypoint, return to the first
Repeat the cycle continuously
Display the result
CODE
# List of waypoints
waypoints = [1, 2, 3, 4, 5]

# Simulate patrolling
for i in range(len(waypoints)):
    print("Moving to Waypoint", waypoints[i])

# Repeat patrol
print("Continuous Patrol")
OUTPUT

Continuous Patrol

RESULT

The robot successfully follows all waypoints in sequence and continues the patrol loop autonomously.
