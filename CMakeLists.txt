cmake_minimum_required(VERSION 2.8)
project(parsimonious)

find_package(catkin REQUIRED COMPONENTS
)

catkin_package()

catkin_python_setup()

#install(DIRECTORY data/
#  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}/data
#  )

#install(DIRECTORY launch/
#  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}/launch
#  )

#catkin_install_python(PROGRAMS
#    scripts/hello_world
#    DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION})

#install(DIRECTORY include/${PROJECT_NAME}/
#  DESTINATION ${CATKIN_PACKAGE_INCLUDE_DESTINATION}
#)
