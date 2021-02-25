cmake_minimum_required(VERSION 3.10)
project(forklift_robot_description)
find_package(catkin REQUIRED)
catkin_package()

install(DIRECTORY launch urdf DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
