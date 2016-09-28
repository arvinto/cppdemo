cmake_minimum_required(VERSION 3.6)
project(cpp_practice)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES src/main.cpp src/add.cpp src/add.h)
add_executable(cpp_practice ${SOURCE_FILES})