cmake_minimum_required(VERSION 2.8)
project( ChamDiem )
find_package( OpenCV REQUIRED )
add_executable( ChamDiem sample.cpp teacher.cpp )
target_link_libraries( ChamDiem ${OpenCV_LIBS} )