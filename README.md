# catkin_ws_rtabmap
## document
This is SLAM code using rtabmap.The loop closure can localize robot.After a map is generated, the localization.launch can localize the robot using the map.
## run
After catkin_make,you still need run:
`roslaunch my_robot world.launch`
`rosrun my_robot teleop.launch`
`roslaunch my_robot mapping.launch`
