cmake_minimum_required (VERSION 2.8.3)
project(mavlink_v2)

find_package(catkin REQUIRED)
set(KOBI_CXX_COMPILE_OPTIONS -std=c++11)

catkin_package(
  INCLUDE_DIRS include
)

install(DIRECTORY include/${PROJECT_NAME}/
        DESTINATION ${CATKIN_PACKAGE_INCLUDE_DESTINATION})

