cmake_minimum_required(VERSION 3.6)
project(TP_2)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")
include_directories(usr/lib/googletest-master)
include_directories(usr/lib/googletest-master/googletest/include)
include_directories(usr/lib/googletest-master/googlemock/include)

set(SOURCE_FILES
        test.cpp)

add_executable(TP_2 ${SOURCE_FILES})
target_link_libraries(TP_2 gtest gtest_main pthread)