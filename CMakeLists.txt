cmake_minimum_required(VERSION 3.10)
project(cheapBlender VERSION 1.0.0)
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)
include_directories(include)

add_executable(cheapBlender src/main.cpp src/glad.c)

target_link_libraries(cheapBlender glfw)
