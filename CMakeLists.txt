cmake_minimum_required(VERSION 3.5)
project(wolf_gazebo_resources)

# ROS
find_package(catkin QUIET)
find_package(ament_cmake QUIET)

if(${catkin_FOUND})
    catkin_package()
elseif(${ament_cmake_FOUND})
    ament_package()
endif()

install(DIRECTORY models/
  DESTINATION ${CMAKE_INSTALL_PREFIX}/share/${PROJECT_NAME}/models)

install(DIRECTORY worlds/
  DESTINATION ${CMAKE_INSTALL_PREFIX}/share/${PROJECT_NAME}/worlds)
