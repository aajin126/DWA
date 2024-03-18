cmake_minimum_required(VERSION 2.8.3)
project(former_gazebo)

find_package(catkin REQUIRED)

catkin_package()

install(
  DIRECTORY config launch worlds models
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)