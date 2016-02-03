cmake_minimum_required(VERSION 3.3)
project(HW4)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.c reverse_sort.c sort.c sort.h golden_main.out golden_reverse.out)
add_executable(HW4 ${SOURCE_FILES})