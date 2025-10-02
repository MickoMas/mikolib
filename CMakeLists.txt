cmake_minimum_required(VERSION 3.31.1)

project(
    mikl
    VERSION 0.01.0
    LANGUAGES CXX)

add_library(${PROJECT_NAME} INTERFACE)
target_include_directories(
    ${PROJECT_NAME} INTERFACE 
    "${CMAKE_CURRENT_SOURCE_DIR}/include")


