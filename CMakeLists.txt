cmake_minimum_required(VERSION 3.6)
project(AP_Project)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    .gitignore
    README.md River_Raid/main.cpp)

add_executable(AP_Project ${SOURCE_FILES})