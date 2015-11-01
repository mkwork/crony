cmake_minimum_required(VERSION 2.8)
project (crony)

message(${PROJECT_NAME})

set(CMAKE_MODULE_PATH ${CMAKE_MODULE_PATH} "${CMAKE_SOURCE_DIR}/cmake/Modules")
include_directories(${CMAKE_SOURCE_DIR}/include/)

add_subdirectory(include)
add_subdirectory(src)
add_subdirectory(test)
