cmake_minimum_required(VERSION 3.15)
project(PankeyEngineWindows)

# Header-only library
add_library(PankeyEngineWindows INTERFACE)

# Expose the folder with headers
target_include_directories(PankeyEngineWindows INTERFACE
    ${CMAKE_CURRENT_SOURCE_DIR}   # headers are in the root of ThePankeyEngine-Windows
)

