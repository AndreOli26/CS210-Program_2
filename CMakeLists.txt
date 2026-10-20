cmake_minimum_required(VERSION 4.3)
project(Program_2)

set(CMAKE_CXX_STANDARD 20)

add_executable(Program_2 src/webserver.cpp
        src/request.h
        src/loadbalancer.h
        src/loadbalancer.cpp
        src/p2.cpp
)
