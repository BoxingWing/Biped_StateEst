cmake_minimum_required(VERSION 3.23)
project(Biped_StateEst)

set(CMAKE_CXX_STANDARD 14)
include_directories("/usr/include/eigen3")
add_executable(Biped_StateEst main.cpp StateEst.cpp StateEst.h)
