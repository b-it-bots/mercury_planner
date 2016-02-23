cmake_minimum_required(VERSION 2.8.3)
project(mercury_planner)
find_package(catkin REQUIRED COMPONENTS
    mk
)

add_custom_target(
  mercury_planner ALL
  COMMAND cmake -E chdir ${PROJECT_SOURCE_DIR} make -f Makefile.tarball
)

catkin_package()
