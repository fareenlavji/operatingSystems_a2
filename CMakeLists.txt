cmake_minimum_required(VERSION 4.0)
project(part3)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(part3
        build.sh
        device_table.txt
        external_files.txt
        interrupts.cpp
        interrupts.hpp
        vector_table.txt)
