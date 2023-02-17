cmake_minimum_required(VERSION 3.0.2)
project(robomobo_controller)


find_package(catkin REQUIRED COMPONENTS
  actionlib
  actionlib_msgs
  cv_bridge
  genmsg
  image_transport
  message_generation
  roscpp
  rospy
  sensor_msgs
  std_msgs
)


## Generate messages in the 'msg' folder
# add_message_files(
#   FILES
#   Message1.msg
#   Message2.msg
# )

## Generate services in the 'srv' folder
# add_service_files(
#   FILES
#   Service1.srv
#   Service2.srv
# )

## Generate actions in the 'action' folder
# add_action_files(
#   FILES
#   Action1.action
#   Action2.action
# )

## Generate added messages and services with any dependencies listed here
# generate_messages(
#   DEPENDENCIES
#   actionlib_msgs#   sensor_msgs#   std_msgs
# )


catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES robomobo_controller
#  CATKIN_DEPENDS actionlib actionlib_msgs cv_bridge genmsg image_transport message_generation roscpp rospy sensor_msgs std_msgs
#  DEPENDS system_lib
)


include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)
