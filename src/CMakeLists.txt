cmake_minimum_required(VERSION 3.15)
project(OS_lab3_new)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -pthread")
add_executable(OS_lab3_new main.cpp)