cmake_minimum_required(VERSION 3.0)
project(stdcxx11template)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_VERBOSE_MAKEFILE ON)

add_subdirectory(3rd)
add_subdirectory(libs)
add_subdirectory(src)