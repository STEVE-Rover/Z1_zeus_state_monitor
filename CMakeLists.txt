cmake_minimum_required(VERSION 3.0.2)
project(zeus_data_logging)

find_package(catkin REQUIRED COMPONENTS
  rospy
)

catkin_package()

include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)
