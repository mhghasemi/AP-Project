cmake_minimum_required(VERSION 3.6)
project(AP_Project)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    .gitignore
    README.md)

add_executable(AP_Project ${SOURCE_FILES})