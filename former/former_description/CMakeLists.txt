cmake_minimum_required(VERSION 2.8.3)
project(former_description)

find_package(catkin REQUIRED)

catkin_package()

install(
  DIRECTORY launch meshes rviz urdf
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)