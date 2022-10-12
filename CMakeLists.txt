cmake_minimum_required(VERSION 3.5)

project(ament_hardware_acceleration NONE)

find_package(ament_cmake_core REQUIRED)

ament_package(
  CONFIG_EXTRAS "ament_hardware_acceleration-extras.cmake"
)

install(
  DIRECTORY cmake
  DESTINATION share/${PROJECT_NAME}
)
