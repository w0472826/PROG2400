cmake_minimum_required(VERSION 3.27)
project(PROG2400)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_FLAGS "-static")

add_executable(echo echo/main.cpp)
add_executable(command_line command_line/main.cpp)
add_executable(stringstreams stringstreams/main.cpp)
add_executable(pointers pointers/main.cpp)
add_executable(vector vector/main.cpp)