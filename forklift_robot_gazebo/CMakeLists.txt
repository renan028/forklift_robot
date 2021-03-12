cmake_minimum_required(VERSION 3.10)
project(forklift_robot_gazebo)
find_package(catkin REQUIRED)
catkin_package()

install(DIRECTORY launch worlds DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
