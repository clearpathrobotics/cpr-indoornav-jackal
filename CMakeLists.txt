cmake_minimum_required(VERSION 3.0.2)
project(cpr_indoornav_jackal)

find_package(catkin REQUIRED)

catkin_package(
)

include_directories(
)

install(PROGRAMS
  scripts/environment
  scripts/install
  scripts/jackal_power_monitor
  scripts/setup_docking
  scripts/start_jackal_bridge

  DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION}
)

install(DIRECTORY config img launch urdf
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
