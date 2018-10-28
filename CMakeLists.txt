cmake_minimum_required(VERSION 3.4)

add_library(tinylinalg vec.h vec.cpp mat.h mat.cpp)
add_executable(test_linalg test_linalg.cpp)
target_link_libraries(test_linalg tinylinalg)