cmake_minimum_required(VERSION 2.8.3)
project(master_ble)

find_package(catkin REQUIRED)

###################################
## catkin specific configuration ##
###################################
catkin_package()

#############
## Install ##
#############

install(PROGRAMS
   scripts/talker.js
   scripts/listener.js
   DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION}
)

