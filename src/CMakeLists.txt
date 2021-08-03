cmake_minimum_required(VERSION 3.0)
project(main)

set(CMAKE_CXX_STANDARD 11)

add_executable(${PROJECT_NAME} main.cpp
        ../3rd/easyloggingpp/src/easylogging++.cc
        )

target_include_directories(${PROJECT_NAME} PRIVATE
        ../3rd/easyloggingpp/src
        )

target_link_libraries(${PROJECT_NAME}
        clipp
        )