cmake_minimum_required(VERSION 3.20)

# Create an interface library for stb
add_library(stb INTERFACE)

# Include directory for stb headers
target_include_directories(stb INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})
