cmake_minimum_required(VERSION 3.15)
project(os_lab_3)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -pthread")
add_executable(os_lab_3 main.cpp)