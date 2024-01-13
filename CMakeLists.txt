cmake_minimum_required(VERSION 3.27)
project(PROG2400)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_FLAGS "-static")

add_executable(echo echo/main.cpp
        echo/echo_application.cpp)
