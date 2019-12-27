cmake_minimum_required(VERSION 2.8.3)
project(handcart_bringup)

find_package(catkin REQUIRED)

#############
## Install ##
#############

install(DIRECTORY launch/
    DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}/launch
)
