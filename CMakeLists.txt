cmake_minimum_required(VERSION 3.24)
project(hw0 LANGUAGES CXX)
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED TRUE)

# add Eigen to include path
include_directories("${CMAKE_SOURCE_DIR}")

add_subdirectory(Part1)
add_subdirectory(Part2)
