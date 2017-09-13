cmake_minimum_required( VERSION 2.8 )
project( geometry )

# 添加Eigen头文件
#include_directories( "/usr/include/eigen3" )
include_directories( "c:/all_libs/eigen/include/eigen3" )

add_executable( eigenGeometry eigenGeometry.cpp )
