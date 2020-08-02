cmake_minimum_required(VERSION 3.10.2)
project(docker-clion)

set(CMAKE_CXX_STANDARD 11)

include_directories(.)

add_executable(docker-clion main.cpp)
