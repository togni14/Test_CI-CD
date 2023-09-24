# Specify the minimum version of CMake required (3.0 or higher is recommended)
cmake_minimum_required(VERSION 3.0)

# Project name
project(r-type_server)

# Define a variable to hold the source files
set(SOURCE_FILES main.cpp)

# Add the executable target
add_executable(${PROJECT_NAME} ${SOURCE_FILES})
