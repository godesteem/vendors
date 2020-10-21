cmake_minimum_required(VERSION 3.14)

add_library(noise SHARED
    ${CMAKE_CURRENT_SOURCE_DIR}/OpenSimplexNoise.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/OpenSimplexNoise.h
)

target_include_directories(noise PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})