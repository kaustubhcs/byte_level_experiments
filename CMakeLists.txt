cmake_minimum_required(VERSION 3.8)
project(byte_level_experiments)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        LICENSE
        README.md
        main.cpp)

add_executable(byte_level_experiments ${SOURCE_FILES})