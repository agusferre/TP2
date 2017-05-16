cmake_minimum_required(VERSION 3.6)
project(TP_2)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    map.h)

add_executable(TP_2 ${SOURCE_FILES})