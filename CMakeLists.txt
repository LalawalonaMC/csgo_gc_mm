cmake_minimum_required(VERSION 3.10)
project(csgo_gc_mm)

set(CMAKE_CXX_STANDARD 17)

# Include directories
include_directories(include)

# Add your source files
add_library(csgo_gc SHARED src/main.cpp src/utils.cpp)
